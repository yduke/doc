# 安装更新

本主题可以自动更新，也可选择手动更新。

## 1 自动更新

- 在仪表盘左侧菜单找到“更新”菜单。
- 如果主题有更新，在此处会显示出更新选项。
- 勾选主题，点击更新。

## 2 手动更新

### 2.1 更新前准备

主题更新期间，会造成网站不能访问，请选择流量少的时候进行更新操作。

- 备份你的旧主题文件（可通过FTP下载，或者命令行打包下载，将原有themes文件夹下的主题全部备份到本地）
- 建议停止网站（通常可以在空间管理面板进行此操作）
- 如果你之前修改过主题文件，请将修改的文件记录下来方便日后操作。

### 2.2 进行更新

- 将空间里的旧主题文件删除。
- 将新的主题文件上传到网站空间，保证和之前的目录结构一致。
- 开启网站，如果运气好的话，您什么也不用做，更新完成

### 2.3 需要注意的地方

- 如果之前使用任何CDN，建议在更新完成后刷新CDN中的所有css、js文件。
- 之前做过修改的主题文件，需要一一进行再次修改。
- 文件的上传建议使用FTP工具，不建议在wordpress后台用zip文件上传主题。