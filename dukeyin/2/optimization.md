# 优化

请注意，本页的所有内容都不是必须的。

## SEO优化

考虑到目前Wordpress针对SEO的插件非常多，在制作主题的时候SEO部分只做了最基本的处理。

强烈建议安装一个SEO插件以弥补SEO的弱势。

较为著名的SEO插件： [Yoast SEO](http://localhost/dk/wp-admin/plugin-install.php?tab=plugin-information&plugin=wordpress-seo&TB_iframe=true&width=600&height=550) [All in One SEO](https://cn.wordpress.org/plugins/all-in-one-seo-pack/)

直接在Wordpress后台搜索插件名称，即可安装。

## 精简代码

为了保持主题代码的可读性，我在写主题的时候通常会有规律的换行，并且加入必要的注释以便于日后修改完善，有这样一类插件可以在服务器将代码精简，删除换行和注释，合并CSS和JS，推荐安装并启用：

[Fast Velocity Minify](https://wordpress.org/plugins/fast-velocity-minify/)

类似的插件有很多，可以选择熟悉的使用。

## 设置CDN

把图片、CSS、JS这些固定的东西交给以速度优化为主的第三方网络公司去处理，是人人都知道的优化网站打开速度的秘诀，推荐安装：

[CDN Enabler – WordPress CDN Plugin](https://wordpress.org/plugins/cdn-enabler/)

不论你用的是七牛、又拍云还是阿里腾讯的CDN，都能很好的支持。

## 缓存页面

WordPress页面和文章都避免不了查询数据库，这是拖慢网站打开速度的一大原因。推荐安装缓存插件，将所有页面缓存为固定的html或Gzip格式，访问速度将大大提升。

推荐安装

[WP Super Cache](https://wordpress.org/plugins/hyper-cache/)

使用[WP Super Cache](https://wordpress.org/plugins/hyper-cache/)后，所有动态页面将被缓存为静态文档，大大提升网站打开速度。

[WP Super Cache](https://wordpress.org/plugins/hyper-cache/)也包含设置CDN功能，如果使用其内置的CDN设置，就无需安装 CDN Enabler。

## 动态提交评论

安装[WP Ajaxify Comments](https://wordpress.org/plugins/wp-ajaxify-comments/)插件之后，读者提交评论的时候不用再刷新页面。

## 延迟加载

如果一个页面的图片非常多，打开速度回很慢，安装延迟加载插件之后，图片会随着浏览器视口加载，没有看到的部分，暂时不加载，从而提高打开速度。

推荐： [a3 Lazy Load](https://wordpress.org/plugins/a3-lazy-load/)

自版本1.2.7后，主题适配了WordPress新版内置的延迟加载，已经不需要安装任何插件自带延迟加载功能。



## 总结

所有的 “优化” 都或多或少会带来一些负面影响，请根据自身服务器情况决定采用哪些插件，这个主题除了依赖的两个插件为必须安装，其他都是可选的。