![Image text](https://raw.githubusercontent.com/Seicing/aoe4legion/master/assets/mod.jpg)
Age of Empire IV Legion and Legion Commander MOD
https://www.ageofempires.com/mods/details/170837/

Detailed mod content can be found at https://seicing.com/html/aoe2/index-aoe4legioneng.html

This git is used to collect crash information(and try to solve it) and study communicate.

350pop version: https://www.ageofempires.com/mods/details/516664/



维护两个mod(将现有mod做成新的mod)的方式：

新建调整包，然后将工程里的mod.jpg、attrib、ui复制过去

用vscode打开调整包文件夹，查找替换掉attrib的调整包guid，它在attrib的xml里面，替换掉后，删掉复制进去的原工程的24blastNoB.xml

原版军团长mod的guid是67987bbc33214c57b0617d9356614825，350人口版本是ccd8d0622fc2497f80bb16537cdc0f8a

本地化文件也用vscode打开手动将工程里的内容复制到新的调整包里面去

