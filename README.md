# 小火箭 Shadowrocket 免费节点

这里整理 Shadowrocket 客户端可导入的节点 URI 和订阅，提供固定入口、导入说明和更新信息。

## 本次更新

- 最近成功整理：2026-11-21 08:05:12
- 节点数量：23
- 最低 TCP 延迟：35 ms（香港）
- 国家/地区：德国、意大利、瑞士、美国、芬兰、英国、荷兰、西班牙、香港
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
| 🇬🇧 英国_02 | 英国 | VLESS | 58 ms |
| 🇭🇰 香港_02 | 香港 | VLESS | 70 ms |
| 🇺🇸 美国_01 | 美国 | VLESS | 161 ms |
| 🇫🇮 芬兰_01 | 芬兰 | VLESS | 176 ms |
| 🇳🇱 荷兰_01 | 荷兰 | VLESS | 203 ms |
| 🇨🇭 瑞士_01 | 瑞士 | VMESS | 218 ms |
| 🇮🇹 意大利_02 | 意大利 | SS | 222 ms |
| 🇮🇹 意大利_01 | 意大利 | SS | 223 ms |
| 🇮🇹 意大利_06 | 意大利 | SS | 230 ms |
| 🇮🇹 意大利_07 | 意大利 | SS | 238 ms |
| 🇩🇪 德国_01 | 德国 | VLESS | 256 ms |
| 🇮🇹 意大利_09 | 意大利 | SS | 256 ms |
| 🇮🇹 意大利_04 | 意大利 | SS | 256 ms |
| 🇮🇹 意大利_08 | 意大利 | SS | 257 ms |
| 🇪🇸 西班牙_01 | 西班牙 | VLESS | 259 ms |
| 🇮🇹 意大利_05 | 意大利 | SS | 260 ms |
| 🇮🇹 意大利_10 | 意大利 | SS | 262 ms |
| 🇮🇹 意大利_03 | 意大利 | SS | 265 ms |
| 🇳🇱 荷兰_03 | 荷兰 | VLESS | 269 ms |
| 🇬🇧 英国_01 | 英国 | VLESS | 277 ms |
| 🇳🇱 荷兰_04 | 荷兰 | VLESS | 309 ms |
| 🇩🇪 德国_02 | 德国 | VLESS | 1315 ms |

[查看完整延迟数据](latency.json)

## 免费节点列表

节点列表最多显示25个，订阅后查看全部节点

```text
vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7Ag6aaZ5rivXzAxIiwiYWRkIjoiNDcuMjQ0LjEyMC4xOTciLCJwb3J0IjoiNDQ4NjciLCJpZCI6Ijg0NWU2YjA4LTI5MTktNDI5MC1hZGUwLTVkYzdkY2VhNTljYSIsImFpZCI6IjAiLCJzY3kiOiJhdXRvIiwibmV0Ijoid3MiLCJ0eXBlIjoibm9uZSIsImhvc3QiOiI0Ny4yNDQuMTIwLjE5NyIsInBhdGgiOiIvYXJraSIsInRscyI6IiIsInNuaSI6IjQ3LjI0NC4xMjAuMTk3IiwiYWxwbiI6IiIsImZwIjoiIiwiaW5zZWN1cmUiOiIwIn0=
vless://ead3595f-4020-4e76-a3ec-c248e1a2f2f7@free.fugui.lol:62015?encryption=none&flow=xtls-rprx-vision&security=reality&sni=swdist.apple.com&fp=chrome&pbk=IjWYbHNrZb3UCQxsTJyekEOA3tHq42L6Jw3O8MmLYVQ&sid=fa514b83&type=tcp&headerType=none&host=swdist.apple.com#%F0%9F%87%AC%F0%9F%87%A7%20%E8%8B%B1%E5%9B%BD_02
vless://ead3595f-4020-4e76-a3ec-c248e1a2f2f7@free.fugui.lol:47396?encryption=none&flow=xtls-rprx-vision&security=reality&sni=swdist.apple.com&fp=chrome&pbk=IjWYbHNrZb3UCQxsTJyekEOA3tHq42L6Jw3O8MmLYVQ&sid=fa514b83&type=tcp&headerType=none&host=swdist.apple.com#%F0%9F%87%AD%F0%9F%87%B0%20%E9%A6%99%E6%B8%AF_02
vless://cda0862a-0f87-4be9-8ed8-1d0c9e382839@162.35.101.177:443?encryption=none&security=reality&sni=0592efg.us8.h1clayd.click&fp=edge&pbk=cO3wYHISTeorXcM8ffaDCDdqZ-olBQL-GyZqb-W7rTk&sid=bd8f712209a9c283&type=grpc&authority=&serviceName=99f2107b03f8&mode=gun#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_01
vless://ea1bee20-9217-42c0-acee-d12bf0c42602@178.17.53.154:48982?encryption=none&security=reality&sni=cdn6-91.yahoo.com&fp=chrome&pbk=A1ygNS8bIvKp7ZlUnjjHX_Z2AS_e4suvSs_IkWICvGE&type=xhttp&path=%2F&mode=auto#%F0%9F%87%AB%F0%9F%87%AE%20%E8%8A%AC%E5%85%B0_01
vless://03786aa4-21a5-4e7c-83d6-873aafc41217@185.112.59.157:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=nl-06.neverspy.tech&fp=firefox&pbk=sZXAejndrxL9cgna_fPXmbSB28y8yAJ9Ln6hRzy5TV0&sid=86af85a72387ef02&type=tcp&headerType=none#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_01
vmess://eyJ2IjoiMiIsInBzIjoi8J+HqPCfh60g55Ge5aOrXzAxIiwiYWRkIjoiMTc5LjQzLjE0MC4yNCIsInBvcnQiOjQyODMxLCJpZCI6ImE5MjVhOThjLWFkN2EtNDBjNi05ZmRmLTEzMGExZGU2OTQxNiIsImFpZCI6MCwic2N5IjoiYXV0byIsIm5ldCI6InRjcCIsInR5cGUiOiJodHRwIiwidGxzIjoiIiwiYWxwbiI6IiIsInBhdGgiOiIvM3giLCJob3N0IjoiZG93bi1jZG4uZGluZ3RhbGsuY29tIn0=
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.18:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.63:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.54:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_06
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.45:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_07
vless://c16e8cdb-65dd-4049-bc65-14c051b8a6c6@2.26.251.236:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=mental-deprivation.ru&fp=firefox&pbk=1iVMMhJZgXHRY7tRlR-1kypF0YeaBcB7EjcfHRsYZX4&sid=4ff31b18d1bd8227&spx=%2F5f73ebfc9ef9c37&type=tcp&headerType=none#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.36:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_09
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.72:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_04
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.99:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_08
vless://4201786b-d99b-4147-a5f0-20d47acddb81@196.196.149.81:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=7aa271t.es1.h1clayd.click&fp=firefox&pbk=ZSmetD4e9QG5CiXhniHg5HJB68L4kwbgAkJmMHtVwEE&sid=42426c882c5fcd41&type=tcp&headerType=none#%F0%9F%87%AA%F0%9F%87%B8%20%E8%A5%BF%E7%8F%AD%E7%89%99_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.81:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_05
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.90:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_10
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.27:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_03
vless://cda0862a-0f87-4be9-8ed8-1d0c9e382839@196.245.52.183:443?encryption=none&security=reality&sni=e60833x.nl7.h1clayd.click&fp=firefox&pbk=jIRVNEf9SpuWP2nJrAbHGGIUnfzOmwZZlrNGw-Y-O2Q&sid=2d2598d60447a967&type=xhttp&path=%2Fd20896a4ce30#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_03
vless://40992c2a-513e-4837-9594-23411fd42afd@161.35.37.106:443?security=none&type=tcp&headerType=http&path=%2F&host=fast.com&packetEncoding=xudp&encryption=none#%F0%9F%87%AC%F0%9F%87%A7%20%E8%8B%B1%E5%9B%BD_01
vless://cda0862a-0f87-4be9-8ed8-1d0c9e382839@196.196.148.63:443?security=reality&type=xhttp&path=%2F0616f2d729aa&packetEncoding=xudp&sni=fc82dfx.nl8.h1clayd.click&fp=chrome&sid=7b2b1a14a6e0630d&pbk=dtO7khFLUkpFDQOtNzo4Th4hJKLoPSY2VtD_9k4Hgiw&mode=auto&encryption=none#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_04
vless://4201786b-d99b-4147-a5f0-20d47acddb81@196.196.148.76:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=8a2e72t.nl20.h1clayd.shop&fp=firefox&pbk=VZS639V1i-35g7VXb9EoTYL-Srm7858sxcvFAunncmA&sid=8d0d0679f42ffd98&type=tcp&headerType=none&host=8a2e72t.nl20.h1clayd.shop&path=%2F#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_02
```

## 反馈

欢迎在 Issues 反馈失效链接和导入问题，请说明客户端版本及错误提示，不要提交个人密码或私有订阅。

请遵守所在地法律法规及服务条款，谨慎通过公共代理传输敏感信息。

## Shadowrocket 客户端下载

| 平台 | 客户端 | 下载地址 |
| --- | --- | --- |
| iOS / iPadOS | Shadowrocket（小火箭） | [App Store](https://apps.apple.com/us/app/shadowrocket/id932747118) |

App Store 的可用地区和价格以商店页面为准。

