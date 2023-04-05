# 关于Cron Job

WordPress的Cron Job是一套按计划执行任务的系统，本插件利用此系统定时检查、获取PSN和Steam游戏、奖杯、成就。

在安装本插件并激活后，会给站点自动添加三个计划任务，如下：

`update_psn_info` 执行PlayStation PSN同步，每日两次

`update_steam_info` 执行Steam 同步，每日两次

`update_steam_game_detail` 执行Steam详细游戏数据的获取，每半小时更新一个游戏



这三个任务是本插件能够同步你的游戏账号的的关键所在，借助Cron Job系统，只要按时执行，你的所有游戏信息就会保持最新。

但是，WordPress 的Corn Job系统有一个较大的缺陷，那就是只有站点被外部访问了，Cron Job才会执行。对于访问量极低的站点来说，有可能会造成计划任务不能按时执行，导致不能及时获取游戏信息。



## 更好地执行Cron Job

我们通过Linux服务器自带的 Cron系统去定时访问WordPress的Cron页面，就可以解决Cron错过计划的问题。

Linux系统的Cron Tab并不存在访问量的局限性，我们可以在Linux中定义半小时访问本机的WordPress站点来触发WordPress执行计划任务。

例如：

```
0,30 * * * * wget --delete-after https://站点域名/wp-cron.php
```

上述命令表示 每30分钟执行一次，访问站点的wp-cron.php，触发WordPress检查 Cron Job的情况，如果有未执行的，就执行。

如果你的服务器有GUI界面编辑Cron任务，只需要将后半部分：

`wget --delete-after https://站点域名/wp-cron.php`

填入“命令”，并设定每 30分钟执行即可。



如此一来，我们就不需要依赖WordPress站点的访问数量，也可以按计划定时获取游戏数据了