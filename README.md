<img src="https://github.com/Yuanbanba/DeepSea/blob/master/bootlogo.jpg" align="center" width="90%" />

深海Deepsea替换包（Deepsea4.5.0）

深海Deepsea整合包是只有FSS0引导的大气层整合包，和其它的各种大气层整合包一样可以随意搭积木，添加插件包和软件包，没任何区别。

这个替换包可以覆盖到任何Atmospher+Hekate为内核的大气层整合包中，像换皮肤一样。

注意fss0引导的Sigpatch签名补丁，官方Deepsea的bootloader/Hekate_ipl.ini中少kip1patch=nosigchk，不能玩破解游戏。还有对应最新SW系统的fs插件和最新大气层package3的loader插件，在bootloader/patches.ini里面。

深海Deepsea替换包文件

1，atmosphere/exefs_patches/bootlogo，开机logo，最高支持SW16.0.0系统

2，bootloader/bootlogo.bmp和bootloader/res/background.bmp，Hekate的图片，忽略SW系统

3，config/nx-hbmenu，相册nro软件菜单的背景图，hbmenu的图片，忽略SW系统

那个switch/deepsea-toolbox/DeepSeaToolbox.nro，深海工具箱，是管理插件的软件，建议替换hekate工具箱。
