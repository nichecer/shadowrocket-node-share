# 小火箭 Shadowrocket 免费节点

这里整理 Shadowrocket 客户端可导入的节点 URI 和订阅，提供固定入口、导入说明和更新信息。

## 本次更新

- 最近成功整理：2026-11-24 08:05:12
- 节点数量：25
- 最低 TCP 延迟：32 ms（香港）
- 国家/地区：NE、俄罗斯、德国、意大利、美国、英国、荷兰、西班牙、香港
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
| 🇭🇰 香港_01 | 香港 | VMESS | 32 ms |
| 🇪🇸 西班牙_01 | 西班牙 | VLESS | 205 ms |
| 🇩🇪 德国_05 | 德国 | VLESS | 205 ms |
| 🇩🇪 德国_02 | 德国 | SS | 212 ms |
| 🇳🇱 荷兰_01 | 荷兰 | VLESS | 212 ms |
| 🇮🇹 意大利_06 | 意大利 | SS | 218 ms |
| 🇮🇹 意大利_02 | 意大利 | SS | 225 ms |
| 🇮🇹 意大利_05 | 意大利 | SS | 229 ms |
| 🇮🇹 意大利_01 | 意大利 | SS | 232 ms |
| 🇺🇸 美国_02 | 美国 | VLESS | 235 ms |
| 🇩🇪 德国_03 | 德国 | VLESS | 237 ms |
| 🇺🇸 美国_03 | 美国 | VLESS | 250 ms |
| 🇩🇪 德国_01 | 德国 | SS | 250 ms |
| 🇬🇧 英国_01 | 英国 | VLESS | 253 ms |
| 🇮🇹 意大利_08 | 意大利 | SS | 257 ms |
| 🇳🇪 尼日尔_01 | NE | VLESS | 260 ms |
| 🇮🇹 意大利_10 | 意大利 | SS | 263 ms |
| 🇮🇹 意大利_04 | 意大利 | SS | 265 ms |
| 🇮🇹 意大利_09 | 意大利 | SS | 268 ms |
| 🇬🇧 英国_02 | 英国 | VLESS | 268 ms |
| 🇮🇹 意大利_07 | 意大利 | SS | 269 ms |
| 🇬🇧 英国_03 | 英国 | VLESS | 290 ms |
| 🇩🇪 德国_04 | 德国 | VLESS | 307 ms |
| 🇷🇺 俄罗斯_01 | 俄罗斯 | VLESS | 317 ms |
| 🇮🇹 意大利_03 | 意大利 | SS | 1263 ms |

[查看完整延迟数据](latency.json)

## 免费节点列表

节点列表最多显示25个，订阅后查看全部节点

```text
vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7Ag6aaZ5rivXzAxIiwiYWRkIjoiNDcuMjQ0LjEyMC4xOTciLCJwb3J0IjoiMjMwMjYiLCJpZCI6ImI5ZGUxYmM5LWJhYTctNDFhYy04NmY3LWNjZDU5Njk1Y2IyMSIsImFpZCI6IjAiLCJzY3kiOiJhdXRvIiwibmV0Ijoid3MiLCJ0eXBlIjoibm9uZSIsImhvc3QiOiI0Ny4yNDQuMTIwLjE5NyIsInBhdGgiOiIvYXJraSIsInRscyI6IiIsInNuaSI6IjQ3LjI0NC4xMjAuMTk3IiwiYWxwbiI6IiIsImZwIjoiIiwiaW5zZWN1cmUiOiIwIn0=
vless://4201786b-d99b-4147-a5f0-20d47acddb81@196.196.149.80:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=7aa271t.es1.h1clayd.click&fp=chrome&pbk=ZSmetD4e9QG5CiXhniHg5HJB68L4kwbgAkJmMHtVwEE&sid=42426c882c5fcd41&type=tcp&headerType=none&host=7aa271t.es1.h1clayd.click#%F0%9F%87%AA%F0%9F%87%B8%20%E8%A5%BF%E7%8F%AD%E7%89%99_01
vless://4201786b-d99b-4147-a5f0-20d47acddb81@8a2e72t.nl20.h1clayd.shop:443?&security=reality&flow=xtls-rprx-vision&pbk=VZS639V1i-35g7VXb9EoTYL-Srm7858sxcvFAunncmA&sid=8d0d0679f42ffd98&fp=chrome&sni=8a2e72t.nl20.h1clayd.shop&type=tcp&headerType=none&host=8a2e72t.nl20.h1clayd.shop&path=%2F#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_05
ss://MjAyMi1ibGFrZTMtY2hhY2hhMjAtcG9seTEzMDU6OHlPM0FOV2VmdXVHczFsUktYRUNRQTFGRWh4bFdGVjJwcFFNY0JhWm81WT0=@47.254.167.157:443#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_02
vless://cda0862a-0f87-4be9-8ed8-1d0c9e382839@5d0319t.nl7.h1clayd.click:443?encryption=none&security=reality&sni=5d0319t.nl7.h1clayd.click&fp=firefox&pbk=l-GzBDuNuhnjxoRlZqKvT7jAt_sbVAxhGFsAttO5kXs&sid=361d0dd59c70516f&type=tcp&headerType=none#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.63:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_06
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.54:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.18:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_05
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.45:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_01
vless://cda0862a-0f87-4be9-8ed8-1d0c9e382839@162.35.101.177:443?security=reality&type=grpc&mode=gun&serviceName=99f2107b03f8&packetEncoding=none&sni=0592efg.us8.h1clayd.click&fp=edge&sid=bd8f712209a9c283&pbk=cO3wYHISTeorXcM8ffaDCDdqZ-olBQL-GyZqb-W7rTk#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_02
vless://fdbd8fb8-7d27-4bd8-9da1-1e42c4876835@finlandnovemberone.best:443?security=reality&type=xhttp&path=%2F1269af64dcc9%2F726643dd&host=finlandnovemberone.best&packetEncoding=xudp&sni=finlandnovemberone.best&fp=firefox&sid=a8329724e1e60d85&pbk=5INjcaKWv9Yfn62Igz2_xfw1PNgEtroCkKqd0c-wMA4&mode=auto#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_03
vless://cda0862a-0f87-4be9-8ed8-1d0c9e382839@196.196.148.63:443?security=reality&sni=717252g.nl8.h1clayd.click&insecure=0&fp=firefox&pbk=PD8Jdlg3xB9QY--jwQjp8PFPzCS8-Oryw6-HWBcHMFU&sid=d3bd772514c87d28&type=grpc&serviceName=204adda7e3da#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_03
ss://MjAyMi1ibGFrZTMtY2hhY2hhMjAtcG9seTEzMDU6OHlPM0FOV2VmdXVHczFsUktYRUNRQTFGRWh4bFdGVjJwcFFNY0JhWm81WT0=@47.254.128.109:443#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_01
vless://2ccb06b6-9eac-44eb-ade7-c1e5afb8e7df@a80b5386.fi2.h1clayd.click:443?security=reality&type=tcp&packetEncoding=xudp&sni=a80b5386.fi2.h1clayd.click&fp=chrome&sid=cc678f10161992a9&pbk=PslSaSQWP4BZZmkL7irab4FMti8sW6BvoC7ytFjJFyc#%F0%9F%87%AC%F0%9F%87%A7%20%E8%8B%B1%E5%9B%BD_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.36:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_08
vless://4201786b-d99b-4147-a5f0-20d47acddb81@196.196.148.76:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=8a2e72t.nl20.h1clayd.shop&fp=firefox&pbk=VZS639V1i-35g7VXb9EoTYL-Srm7858sxcvFAunncmA&sid=8d0d0679f42ffd98&type=tcp&headerType=none&host=8a2e72t.nl20.h1clayd.shop#%F0%9F%87%B3%F0%9F%87%AA%20%E5%B0%BC%E6%97%A5%E5%B0%94_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.99:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_10
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.27:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_04
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.72:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_09
vless://cae99415-10a6-4317-81bd-19a4586b5d76@196.196.208.22:443?security=reality&type=xhttp&path=%2Ff57a81c99fea&host=9303d6x.fi-p1b.h1clayd.click&packetEncoding=none&sni=9303d6x.fi-p1b.h1clayd.click&fp=firefox&sid=621290c77645b731&pbk=_yJGJ5q-8IxTuWFcoy5wpKKYtk9p9q4lQ6svfXC1IUU&mode=auto#%F0%9F%87%AC%F0%9F%87%A7%20%E8%8B%B1%E5%9B%BD_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.90:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_07
vless://40992c2a-513e-4837-9594-23411fd42afd@167.99.203.0:443?security=none&type=tcp&headerType=http&path=%2F&host=fast.com&method=GET&packetEncoding=none#%F0%9F%87%AC%F0%9F%87%A7%20%E8%8B%B1%E5%9B%BD_03
vless://4201786b-d99b-4147-a5f0-20d47acddb81@196.196.148.177:443?security=reality&type=tcp&packetEncoding=xudp&sni=4935e4t.de25.h1clayd.click&fp=firefox&flow=xtls-rprx-vision&sid=6976d670818644cc&pbk=MzgB17ZFbKqs8pbC3EscTzHid_ENc-k_Cp6nXl-2knw#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_04
vless://4201786b-d99b-4147-a5f0-20d47acddb81@8a2e72t.nl11.h1clayd.click:443?security=reality&type=raw&packetEncoding=xudp&sni=8a2e72t.nl11.h1clayd.click&fp=chrome&flow=xtls-rprx-vision&sid=8d0d0679f42ffd98&pbk=VZS639V1i-35g7VXb9EoTYL-Srm7858sxcvFAunncmA#%F0%9F%87%B7%F0%9F%87%BA%20%E4%BF%84%E7%BD%97%E6%96%AF_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.81:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_03
```

## 反馈

欢迎在 Issues 反馈失效链接和导入问题，请说明客户端版本及错误提示，不要提交个人密码或私有订阅。

请遵守所在地法律法规及服务条款，谨慎通过公共代理传输敏感信息。

## Shadowrocket 客户端下载

| 平台 | 客户端 | 下载地址 |
| --- | --- | --- |
| iOS / iPadOS | Shadowrocket（小火箭） | [App Store](https://apps.apple.com/us/app/shadowrocket/id932747118) |

App Store 的可用地区和价格以商店页面为准。

