# 更新

主题为了适应新的系统环境，新的软件运行环境会不时更新。

## 自动更新

当主题有新的版本时，在WordPress后台更新页面会提示进行更新。

- 进入更新页面，勾选主题
- 点击更新
- 更新完成

主题更新会覆盖原有主题，所以建议使用子主题进行自定义样式和功能。

------

有时候自动更新不能满足需求，可以和作者索取最新的更新包进行手动更新。

## 手动更新

### 安装更新

#### 1 更新前准备

主题更新期间，会造成网站不能访问，请选择流量少的时候进行更新操作。

1. 备份你的旧主题文件（可通过FTP下载，或者命令行打包下载，将原有themes文件夹下的主题全部备份到本地）
2. 建议停止网站（通常可以在空间管理面板进行此操作）
3. 如果你之前修改过主题文件，请将修改的文件记录下来方便日后操作。

#### 2 进行更新

1. 将空间里的旧主题文件删除，如果更新内容不含“dukeyin-helper”文件夹，则只需删除“dukeyin”文件夹即可
2. 将新的主题文件上传到网站空间，保证和之前的目录结构一致。
3. 开启网站，如果运气好的话，您什么也不用做，更新完成

#### 3 需要注意的地方

1. 如果之前使用七牛作为CDN，建议在更新完成后删除七牛空间中的所有css、js文件。
2. 之前做过修改的主题文件，需要一一进行再次修改。
3. 文件的上传建议使用FTP工具，不建议在wordpress后台用zip文件上传主题。