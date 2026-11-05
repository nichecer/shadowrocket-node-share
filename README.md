# 小火箭 Shadowrocket 免费节点

这里整理 Shadowrocket 客户端可导入的节点 URI 和订阅，提供固定入口、导入说明和更新信息。

## 本次更新

- 最近成功整理：2026-11-05 08:05:09
- 节点数量：16
- 最低 TCP 延迟：35 ms（香港）
- 国家/地区：IR、俄罗斯、意大利、日本、美国、荷兰、香港
- 定时更新：**08:00、20:00**
- 节点协议：VMess、VLESS、Trojan、Shadowsocks。

## 订阅入口

| 文件 | 地址 | 用途 |
| --- | --- | --- |
| Base64 订阅 | [sub.txt](https://raw.githubusercontent.com/nichecer/shadowrocket-node-share/main/sub.txt) | 在兼容的 Shadowrocket 客户端中添加订阅 |
| 明文节点 | [nodes.txt](https://raw.githubusercontent.com/nichecer/shadowrocket-node-share/main/nodes.txt) | 按需复制单条节点并导入 |

### 订阅二维码

![Shadowrocket 订阅二维码](sub.svg)

## 节点延迟

延迟信息最多显示25个，订阅后查看全部节点

| 节点名称 | 国家/地区 | 协议 | TCP 延迟 |
| --- | --- | --- | ---: |
| 🇭🇰 香港_01 | 香港 | VMESS | 35 ms |
| 🇯🇵 日本_01 | 日本 | SS | 80 ms |
| 🇮🇹 意大利_04 | 意大利 | SS | 219 ms |
| 🇮🇹 意大利_07 | 意大利 | SS | 233 ms |
| 🇮🇹 意大利_03 | 意大利 | SS | 238 ms |
| 🇮🇹 意大利_06 | 意大利 | SS | 247 ms |
| 🇮🇹 意大利_02 | 意大利 | SS | 252 ms |
| 🇮🇹 意大利_09 | 意大利 | SS | 255 ms |
| 🇮🇹 意大利_10 | 意大利 | SS | 261 ms |
| 🇮🇹 意大利_05 | 意大利 | SS | 264 ms |
| 🇮🇷 伊朗_01 | IR | VLESS | 276 ms |
| 🇷🇺 俄罗斯_01 | 俄罗斯 | SS | 280 ms |
| 🇮🇹 意大利_08 | 意大利 | SS | 285 ms |
| 🇳🇱 荷兰_01 | 荷兰 | VLESS | 290 ms |
| 🇮🇹 意大利_01 | 意大利 | SS | 306 ms |
| 🇺🇸 美国_01 | 美国 | VLESS | 620 ms |

[查看完整延迟数据](latency.json)

## 免费节点列表

节点列表最多显示25个，订阅后查看全部节点

```text
vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7Ag6aaZ5rivXzAxIiwiYWRkIjoiNDcuMjQ0LjEyMC4xOTciLCJwb3J0IjoiNDQ4NjciLCJ0eXBlIjoibm9uZSIsImlkIjoiODQ1ZTZiMDgtMjkxOS00MjkwLWFkZTAtNWRjN2RjZWE1OWNhIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9hcmtpIiwiaG9zdCI6IiIsInRscyI6IiJ9
ss://YWVzLTI1Ni1nY206QmVhVWY5YzBBRVdINDBQdQ==@154.36.158.197:8388#%F0%9F%87%AF%F0%9F%87%B5%20%E6%97%A5%E6%9C%AC_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.90:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_04
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.81:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_07
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.18:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_03
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.45:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_06
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.72:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.63:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_09
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0@202.50.253.54:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_10
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.99:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_05
vless://f47057d5-120d-4b42-b6d6-30469aef6813@tunell2027.crackerbinam.org:48312?encryption=none&security=reality&sni=www.cloudflare.com&fp=chrome&pbk=d9eM_jy8ztZrOf3DMq1m55VQSo7bnKcG1dRnO9ktJ2Y&sid=902c315efc&type=tcp&headerType=http#%F0%9F%87%AE%F0%9F%87%B7%20%E4%BC%8A%E6%9C%97_01
ss://YWVzLTI1Ni1nY206Y0NNSmdKVEEzQkE0ODlZVVlyRnE3WEhYU2lTcFdsTGE@46.17.46.27:18443#%F0%9F%87%B7%F0%9F%87%BA%20%E4%BF%84%E7%BD%97%E6%96%AF_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.27:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_08
vless://b2847c3b-5278-4b06-9c66-bc919d2dfec7@186.246.9.29:443?encryption=none&security=reality&sni=wordpress.com&fp=firefox&pbk=MPNMomAMn_lu9YMYjD2jAQWrI-rTM4hj9Jgg9d6qzTA&sid=50ad5564&type=tcp&headerType=none#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0@202.50.253.36:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_01
vless://7ad63b26-bf70-4872-8fab-ebaf73a1e19d@201.51.4.89:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=cache-89.topp-con.xyz&fp=chrome&pbk=LEziyH-E4k9hehGRJkVi1FadVObB_NZJy8U7oUCVWXU&sid=b9120cd53ffd7bba&type=tcp&headerType=none#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_01
```

## 反馈

欢迎在 Issues 反馈失效链接和导入问题，请说明客户端版本及错误提示，不要提交个人密码或私有订阅。

请遵守所在地法律法规及服务条款，谨慎通过公共代理传输敏感信息。

## Shadowrocket 客户端下载

| 平台 | 客户端 | 下载地址 |
| --- | --- | --- |
| iOS / iPadOS | Shadowrocket（小火箭） | [App Store](https://apps.apple.com/us/app/shadowrocket/id932747118) |

App Store 的可用地区和价格以商店页面为准。

