# 代理和中继

Steam和PSN网络在国内的访问速度不是很理想，偶尔会间歇性出现无法访问的情况，造成我们无法获取PSN或Steam的信息。

这种情况我们可以使用主题自带的代理和中继服务器功能。

二者根据情况选一即可，不可都开

## 代理

在WordPress后台-> DK游戏设置 -> 代理

1. 勾选“使用代理”
2. “代理主机”处填写主机的IP地址。
3. “代理端口”处填写主机的端口。
4. 如果有鉴权，需要在接下来的地方填写登录名和密码
5. 如果希望代理图像下载，勾选最后一个“代理图像下载”
6. 点击保存更改。

以后访问API会绕道你设置的http代理，从而提升同步速度。

## 中继服务器

中继服务器仅提升Steam API 的访问速度。

任何安装了WordPress的国外VPS都可以作为中继服务器使用；

1. 首先需要保证你所持有的国外VPS服务WordPress健康运行，特别是REST API，如果REST API不正常请先解决使REST API能正常被外网访问；
2. 在此VPS安装WP Router插件，激活（此插件可与作者询问获取）；
3. 回到DK Games站点，在WP网站后台 -> DK游戏设置 -> 中继服务 ->中继服务器中填写您国外VPS的访问地址，如"https://router.domain.com"
4. 点击保存更改。

此后所有Steam API的请求都会通过中继服务器发起，速度将得到改善。

## 存在的问题

使用代理或中继服务器后，Steam愿望单页面和Steam促销页面的货币汇率会变为当地汇率。

例如，如果你的Steam原本是国区，货币为人民币，当你使用港区代理或中继服务器后，Steam愿望单和促销页面获取的信息会变为港币。

不使用代理或中继可解决此问题。
