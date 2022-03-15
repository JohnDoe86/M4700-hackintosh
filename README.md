# M4700-Hackintosh
只是记录一下

- 在windows平台下编辑config文件，使用OCAuxiliaryTools工具，好用，且还可以帮忙检查某些错误，编辑完之后还以去opencore.slowgeek.com在线检查部分项目，错位的选项会特意标红。

遇到的问题

- 引导界面需要开key support才能用键盘选择
- scan policy开0才能看到U盘上面的base system.dmg
- 有时候需要resetnvm才会让启动参数生效，声卡的alcid修改了没有生效卡了好久。
- 大佬的背光亮度范围参数可能会引起问题，注释掉就可用全部亮度了。
- 触摸板和电池直接用smc*** 和 VoodooPS2Controller.kext

参考链接：https://github.com/1Revenger1/Dell-M4700-MacOS-Resources





  

