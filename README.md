# 1.说明
> GT-AC5300.koolshare版本固件自用工具集

# 2.功能说明

| 脚本名称             | 功能                                                         | 位置                                  |
| -------------------- | ------------------------------------------------------------ | ------------------------------------- |
| vacuum_skipd         | 1.备份skipd使用的数据库表log_1<br/>2.遍历所有有key，删除重复k记录，只保留最后一条<br/>3.`vacuum /jffs/db/log`文件, 减小log文件大小 | `/koolshare/bin/vacuum_skipd`         |
| reinit-koolshare-env | 1.优化bash环境<br/>2.解锁插件离线安装关键词屏蔽<br/>3.解锁usb2jffs,swap插件的usb写入速度限制 | `/koolshare/bin/reinit-koolshare-env` |
| vacuum_nc            | 清理`/jffs/.sys/nc/nc_center.db`                             | `/koolshare/bin/vacuum_nc`            |

