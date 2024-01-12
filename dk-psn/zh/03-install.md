# 安装

## 推荐事项

### 站点健康

在安装DK Games之前，请先检查WordPress的站点健康（后台->工具->站点健康）并解决所有 问题和推荐事项。

最为重要的，确保WP-CRON正常，因为本插件依赖WordPress的Cron Job定时执行以获取游戏和奖杯的数据。

### 独立站点

DK Games可以在任意健康的WordPress站点正常工作，但是，由于DK Games会从PSN和Steam下载大量图片和数据，且随着你玩的游戏越来越多，奖杯越来越多，数据量会越加庞大。

为了方便管理和备份，推荐将 DK Games安装到一个独立的WordPress站点且预留出足够的存储空间，不推荐与有其他功能的站点合用。

### 域名

使用子域名建立DK Games站点是个好主意。

例如：`game.yoursite.com`

站点的域名决定了你的API接入点。



## 安装步骤

浏览器进入Wordpress后台(例如: https://www.mysite.com/wp-admin )

1. 插件 -> 安装插件 -> 上传插件 -> 选择插件dk-games.zip，上传。
1. 插件 -> 已安装的插件 中找到“DK Games”
1. 点击“启用”
1. 在后台 “DK PSN” -> 授权 输入授权码，点击激活。

安装完成。



