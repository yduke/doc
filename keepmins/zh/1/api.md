# 应用接口 API

时光捕手从V 2.9.6.4开始提供应用接口 API，以帮助更快捷方便地创建、分享、发布内容。

假设，你的时光捕手主题运行网址是：https://keepmins.com/

**API接入点：** https://keepmins.com/ （与站点网址相同）

**API参数：**

`kmtitle` 标题

示范： `https://keepmins.com/?kmtitle=你所想要的标题文字`

 

`kmcontent` 内容

示范： `https://keepmins.com/?kmcontent=你所想要的内容文字`

 

`kmimage` 图片

示范： `https://keepmins.com/?kmimage=图片地址URL`

 

`kmtag` 标签

示范：`https://keepmins.com/?kmtag=标签1,标签2,标签3`

 

当然，也可以多个参数组合在一起：

示范：

```
https://keepmins.com/?kmtitle=你所想要的标题文字&kmcontent=你所想要的内容文字&kmtag=标签1,标签2,标签3
```

 

直接访问带有参数的URL，如果你有目标站点的发布权限的话，所有参数将会自动填充到发布表格中。

此API仅提供快捷输入内容，需要手动发布。