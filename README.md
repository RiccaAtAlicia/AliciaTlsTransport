# About
Alicia Tls Transport is a tunnel program that obfuscates itself into a normal TLS connection (other obfuscations are coming).
Unlike SSR's SSL obfs,ATTr will use a cert and a domain. It even shares TCP port 443 with normal HTTPS web servers, in order to make it more difficult to be identified. Those who access your server without a proper key will get a normal page (or a 403 for non-existing pages)

# 关于
Alicia Tls Transport 是一个把自己伪装成正常 TLS 连接的隧道应用（其他混淆方式将在将来出现）
ATTr 使用确实存在的证书，并和普通网页服务器共享 TCP 443 端口，以使它更难被发现。当用户没有使用正确的 key 访问时，他们会得到正常的 Web 页面或者 403 错误。

# Warning
Please Read [Security Tips](https://github.com/RiccaAtAlicia/AliciaTlsTransport/blob/master/Docs/Meta/Security.md)

# 警告
请先读 [Security Tips](https://github.com/RiccaAtAlicia/AliciaTlsTransport/blob/master/Docs/Meta/Security.md)

# TODO
Make cross-platform clients (for Windows, GNU+Linux, Android and macOS. Sorry that we won't support iOS).
Use Django or bottle as frontend.
Resigter a domain for it

# TODO
制作跨平台客户端（Windows, GNU+Linux, Android 和 macOS。不支持也不会支持 iOS，抱歉）
用 Python 的 Django 或 bottle 做前端
为它注册域名

# Licence
This program is licensed under [GNU General Public Licence version 2](LICENSE.GPLv2.txt)

The server-side program is licensed under [GNU Affero General Public Licence version 3](LICENSE.AGPLv3.txt)


# 许可
客户端以 GNU GPLv2 许可。
服务器端以 GNU AGPLv3 许可。

# Disclaimer
This project has nothing to do with Shadowsocks.

# 免责声明
本项目与 Shadowsocks 及其相关软件项目没有任何关系。
