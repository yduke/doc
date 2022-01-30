# 安装步骤

## 包含文件

主题包含两个文件：

- dukeyin.zip *主题打包文件*
- duke-yin-helper.zip *辅助插件打包文件*

** 为了严格遵照WordPress主题开发标准，一些必要的功能并不直接写进主题，而是包含在 duke-yin-helper 这个独立插件中。这样一来不仅符合标准，更方便日后更换其他主题。*

## 上传主题及插件

主题和插件会以 .zip 格式打包，有两种安装方法：

### 方法1

- 进入 WordPress后台，外观，主题，添加，上传主题。直接选dukeyin.zip压缩包上传。
- 进入 WordPress后台，外观，插件，添加 ，上传插件。选择dukeyin-helper.zip压缩包上传。

### 方法2

- 解压dukeyin.zip压缩包，用FTP把主题的根目录“dukeyin”及所有文件上传至网站的主题目录：

```
/wp-content/themes/
```

- 解压duke-yin-helper.zip压缩包，用FTP把所有文件及根目录“duke-yin-helper”上传到网站的插件目录

```
 /wp-content/plugins/
```

注意：如果采用第二种方式，一定要看清解压出来的目录结构，有一些压缩软件解压后，会在顶部添加一个文件夹，主题上传后的结构应该类似如下：

```
/wp-content/themes/dukeyin/css/
/wp-content/plugins/duke-yin-helper/
```

主题和插件安装完成后，在后台，外观，主题处激活dukeyin主题；后台插件处激活插件即可。

另所需Wordpress库中的插件，会收到提示请求安装2个插件，参见下一章节。

新增内容参见[使用章节](../使用.md)