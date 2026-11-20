# 小火箭 Shadowrocket 免费节点

这里整理 Shadowrocket 客户端可导入的节点 URI 和订阅，提供固定入口、导入说明和更新信息。

## 本次更新

- 最近成功整理：2026-11-20 20:05:12
- 节点数量：14
- 最低 TCP 延迟：35 ms（香港）
- 国家/地区：NE、俄罗斯、德国、意大利、瑞士、美国、荷兰、西班牙、香港
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
| 🇺🇸 美国_01 | 美国 | VLESS | 159 ms |
| 🇺🇸 美国_02 | 美国 | VMESS | 164 ms |
| 🇳🇱 荷兰_02 | 荷兰 | VLESS | 213 ms |
| 🇩🇪 德国_01 | 德国 | VLESS | 237 ms |
| 🇮🇹 意大利_01 | 意大利 | SS | 254 ms |
| 🇨🇭 瑞士_01 | 瑞士 | VMESS | 267 ms |
| 🇷🇺 俄罗斯_01 | 俄罗斯 | VLESS | 271 ms |
| 🇳🇱 荷兰_04 | 荷兰 | VLESS | 285 ms |
| 🇳🇱 荷兰_01 | 荷兰 | VLESS | 1253 ms |
| 🇪🇸 西班牙_01 | 西班牙 | VLESS | 1261 ms |
| 🇮🇹 意大利_02 | 意大利 | SS | 1272 ms |
| 🇳🇪 尼日尔_01 | NE | VLESS | 1309 ms |
| 🇳🇱 荷兰_03 | 荷兰 | VLESS | 2323 ms |

[查看完整延迟数据](latency.json)

## 免费节点列表

节点列表最多显示25个，订阅后查看全部节点

```text
vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7Ag6aaZ5rivXzAxIiwiYWRkIjoiNDcuMjQ0LjEyMC4xOTciLCJwb3J0IjoiNDQ4NjciLCJpZCI6Ijg0NWU2YjA4LTI5MTktNDI5MC1hZGUwLTVkYzdkY2VhNTljYSIsImFpZCI6IjAiLCJzY3kiOiJhdXRvIiwibmV0Ijoid3MiLCJ0eXBlIjoibm9uZSIsImhvc3QiOiI0Ny4yNDQuMTIwLjE5NyIsInBhdGgiOiIvYXJraSIsInRscyI6IiIsInNuaSI6IjQ3LjI0NC4xMjAuMTk3IiwiYWxwbiI6IiIsImZwIjoiIiwiaW5zZWN1cmUiOiIwIn0=
vless://cda0862a-0f87-4be9-8ed8-1d0c9e382839@162.35.101.177:443?encryption=none&security=reality&sni=0592efg.us8.h1clayd.click&fp=edge&pbk=cO3wYHISTeorXcM8ffaDCDdqZ-olBQL-GyZqb-W7rTk&sid=bd8f712209a9c283&type=grpc&authority=&serviceName=99f2107b03f8&mode=gun#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_01
vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzAyIiwiYWRkIjoiMTkyLjIyMC40Ny44NSIsInBvcnQiOjQ0NDQxLCJpZCI6ImRlNGUwMzM1LTJhM2ItNDAwNi1kNzQ2LWM5MzlmYTg1ZmRjMyIsImFpZCI6MCwic2N5IjoiYXV0byIsIm5ldCI6InRjcCIsInR5cGUiOiJodHRwIiwidGxzIjoiIiwicGF0aCI6Ii8ifQ==
vless://03786aa4-21a5-4e7c-83d6-873aafc41217@185.112.59.157:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=nl-06.neverspy.tech&fp=firefox&pbk=sZXAejndrxL9cgna_fPXmbSB28y8yAJ9Ln6hRzy5TV0&sid=86af85a72387ef02&type=tcp&headerType=none#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_02
vless://c16e8cdb-65dd-4049-bc65-14c051b8a6c6@2.26.251.236:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=mental-deprivation.ru&fp=firefox&pbk=1iVMMhJZgXHRY7tRlR-1kypF0YeaBcB7EjcfHRsYZX4&sid=4ff31b18d1bd8227&spx=%2F5f73ebfc9ef9c37&type=tcp&headerType=none#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.99:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_01
vmess://eyJ2IjoiMiIsInBzIjoi8J+HqPCfh60g55Ge5aOrXzAxIiwiYWRkIjoiMTc5LjQzLjE0MC4yNCIsInBvcnQiOjQyODMxLCJpZCI6ImE5MjVhOThjLWFkN2EtNDBjNi05ZmRmLTEzMGExZGU2OTQxNiIsImFpZCI6MCwic2N5IjoiYXV0byIsIm5ldCI6InRjcCIsInR5cGUiOiJodHRwIiwidGxzIjoiIiwiYWxwbiI6IiIsInBhdGgiOiIvM3giLCJob3N0IjoiZG93bi1jZG4uZGluZ3RhbGsuY29tIn0=
vless://Fluffy_VPN-Oth8rOq3@104.171.135.229:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=absolute-disaster.org&fp=chrome&pbk=mpo4BIcoWiMXAQGt5a8IJ4MFkPJQyLC50dO_bXzC7z0&type=tcp&headerType=none&host=absolute-disaster.org#%F0%9F%87%B7%F0%9F%87%BA%20%E4%BF%84%E7%BD%97%E6%96%AF_01
vless://cda0862a-0f87-4be9-8ed8-1d0c9e382839@196.245.52.183:443?encryption=none&security=reality&sni=e60833x.nl7.h1clayd.click&fp=firefox&pbk=jIRVNEf9SpuWP2nJrAbHGGIUnfzOmwZZlrNGw-Y-O2Q&sid=2d2598d60447a967&type=xhttp&path=%2Fd20896a4ce30#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_04
vless://6b1607f1-3a08-4681-8abd-83663a8155e7@185.14.29.29:443?encryption=none&security=reality&sni=static.gcore.pro&fp=chrome&pbk=bPxKgZHO13GJGKjbHz0BVnsw8UIcOjz2yz8VCgGv5BI&sid=6fce2d08&type=xhttp&host=static.gcore.pro&path=%2Fjs%2Flibs&mode=auto#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_01
vless://4201786b-d99b-4147-a5f0-20d47acddb81@196.199.122.2:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=7aa271t.es1.h1clayd.click&fp=chrome&pbk=ZSmetD4e9QG5CiXhniHg5HJB68L4kwbgAkJmMHtVwEE&sid=42426c882c5fcd41&type=tcp&headerType=none&host=7aa271t.es1.h1clayd.click#%F0%9F%87%AA%F0%9F%87%B8%20%E8%A5%BF%E7%8F%AD%E7%89%99_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.72:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_02
vless://4201786b-d99b-4147-a5f0-20d47acddb81@196.196.148.76:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=8a2e72t.nl20.h1clayd.shop&fp=firefox&pbk=VZS639V1i-35g7VXb9EoTYL-Srm7858sxcvFAunncmA&sid=8d0d0679f42ffd98&type=tcp&headerType=none&host=8a2e72t.nl20.h1clayd.shop#%F0%9F%87%B3%F0%9F%87%AA%20%E5%B0%BC%E6%97%A5%E5%B0%94_01
vless://cda0862a-0f87-4be9-8ed8-1d0c9e382839@196.196.148.63:443?encryption=none&security=reality&sni=fc82dfx.nl8.h1clayd.click&pbk=dtO7khFLUkpFDQOtNzo4Th4hJKLoPSY2VtD_9k4Hgiw&sid=7b2b1a14a6e0630d&type=xhttp&path=%2F0616f2d729aa&mode=auto#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_03
```

## 反馈

欢迎在 Issues 反馈失效链接和导入问题，请说明客户端版本及错误提示，不要提交个人密码或私有订阅。

请遵守所在地法律法规及服务条款，谨慎通过公共代理传输敏感信息。

## Shadowrocket 客户端下载

| 平台 | 客户端 | 下载地址 |
| --- | --- | --- |
| iOS / iPadOS | Shadowrocket（小火箭） | [App Store](https://apps.apple.com/us/app/shadowrocket/id932747118) |

App Store 的可用地区和价格以商店页面为准。

