# 无法上传图片

时光捕手基于WordPress内核，在上传图片过程中使用多个WordPress推荐的PHP扩展进行图片的格式转换和裁切工作，缺失必要PHP扩展将会导致图片上传失败。

WordPress运行必须安装的扩展 参见： https://make.wordpress.org/hosting/handbook/server-environment/#php-extensions

在宝塔面板中推荐安装PHP 7.4后，还需安装如下扩展才能达到WordPress运行的基本要求：

- fileinfo
- imagemagick
- exif

另外，基于优化PHP速率的考虑，推荐同时安装如下扩展：

- opcache

根据服务器自身配置，如下数据库缓存扩展选择其一安装：

Redis

- redis

Memocache

- memcache
- memcached

安装好必须的PHP扩展后，即可保证图片上传正常。

当前WordPress缺失的PHP扩展，可在网站后台 -> 工具 -> 站点健康 处查看，可通过服务器控制面板或联系服务器提供商补全缺失的必要扩展。