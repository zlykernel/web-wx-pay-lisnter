# web-wx-pay-lisnter

## 我本地环境

4.14.79-1-MANJARO
## 下载安装 mitmproxy

注意使用pip3 install mitmproxy
## 操作说明

### 启动服务

mitmweb -p 8888 -s addons.py
mitmweb -p 8888 -s test.py
### 浏览器设置代理
google浏览器
使用SwitchyOmega插件设置

代理服务器
网址协议	代理协议	代理服务器	   代理端口	
(默认)		http    127.0.0.1    8888

### 登录网页版微信即可

## 提示

脚本中涉及到的 mitmproxy 相关api可以在 [mitmproxy官方文档查看](https://docs.mitmproxy.org/stable/)
## 如果觉得该项目对你有帮助，请帮忙star！
