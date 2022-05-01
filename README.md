<img src="https://github.com/Yuanbanba/DeepSea/blob/master/bootlogo.jpg" align="center" width="100%" />
---

深海迷你包-YuanBanban

【说明】

原版DeepSea整合包https://github.com/Team-Neptune/DeepSea/releases

深海是只有FSS0引导的大气层整合包，和大气层迷你包一样可以搭积木，添加插件包和软件包，没任何区别。

深海终极包=深海迷你包+特斯拉插件包+相册NRO软件包，

更新方法，删除原TF卡上atmosphere，bootloader，config，sept和switch五个文件夹，之后再将压缩包中的文件全选复制到TF卡覆盖（推荐）。注意：TF卡上switch/checkpoint/saves/是存档备份，不要删掉。

（3）软破机，大气层的注入器内置Payload需Hekate4.2以上，SX的注入器直接可以用。

短接+注入开机，点击launch，根据选择进入

cfw sysnand：真实系统破解状态（fss0引导）

cfw eumnand：虚拟系统破解状态（fss0引导）

ofw sysnand：真实系统不破解状态（fss0引导）

硬破机直接点击电源键开机，之后与软破机操作一样。

（4）默认启动90dns与隐藏序号，如需联机进ofw sysnand正版系统。

如需cfw sysnand破解系统联机，删除atmosphere/hosts/sysmmc.txt和修改exosphere.ini中blank_prodinfo_sysmmc=0
