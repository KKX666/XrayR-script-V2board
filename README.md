# XRayR
A Xray backend framework that can easily support many panels.

一个基于Xray的后端框架，支持V2ay,Trojan,Shadowsocks协议，极易扩展，支持多面板对接

如对脚本不放心，可使用此沙箱先测一遍再使用：https://killercoda.com/playgrounds/scenario/ubuntu

# 官方文档
**[XrayR-project](https://crackair.gitbook.io/xrayr-project/)**

# 特点
- 永久开源且免费。
- 支持V2ray，Trojan， Shadowsocks多种协议。
- 支持Vless和XTLS等新特性。
- 支持单实例对接多面板、多节点，无需重复启动。
- 支持限制在线IP
- 支持节点端口级别、用户级别限速。
- 配置简单明了。
- 修改配置自动重启实例。
- 方便编译和升级，可以快速更新核心版本， 支持Xray-core新特性。

## 功能介绍
| 功能            | v2ray | trojan | shadowsocks |
| --------------- | ----- | ------ | ----------- |
| 获取节点信息    | √     | √      | √           |
| 获取用户信息    | √     | √      | √           |
| 用户流量统计    | √     | √      | √           |
| 服务器信息上报  | √     | √      | √           |
| 自动申请tls证书 | √     | √      | √           |
| 自动续签tls证书 | √     | √      | √           |
| 在线人数统计    | √     | √      | √           |
| 在线用户限制    | √     | √      | √           |
| 审计规则        | TODO  | TODO   | TODO        |
| 节点端口限速    | √     | √      | √           |
| 按照用户限速    | √     | √      | √           |
## 支持前端
| 前端        | v2ray | trojan | shadowsocks                    |
| ----------- | ----- | ------ | ------------------------------ |
| sspanel-uim | √     | √      | √ (Shadowsocks - V2Ray-Plugin) |
| ProxyPanel  | TODO  | TODO   | TODO                           |
| v2board     | TODO  | TODO   | TODO                           |

# 一键安装

```
wget -N https://raw.githubusercontents.com/KKX666/XrayR-script-V2board/master/install.sh && bash install.sh
```

＆
```
bash <(curl -Ls https://raw.githubusercontents.com/KKX666/XrayR-script-V2board/master/install.sh)
```
