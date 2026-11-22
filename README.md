# 小火箭 Shadowrocket 免费节点

这里整理 Shadowrocket 客户端可导入的节点 URI 和订阅，提供固定入口、导入说明和更新信息。

## 本次更新

- 最近成功整理：2026-11-22 20:05:12
- 节点数量：17
- 最低 TCP 延迟：35 ms（香港）
- 国家/地区：德国、意大利、美国、荷兰、香港
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
| 🇩🇪 德国_01 | 德国 | VLESS | 206 ms |
| 🇮🇹 意大利_03 | 意大利 | SS | 220 ms |
| 🇮🇹 意大利_10 | 意大利 | SS | 236 ms |
| 🇺🇸 美国_01 | 美国 | SS | 236 ms |
| 🇮🇹 意大利_08 | 意大利 | SS | 254 ms |
| 🇳🇱 荷兰_02 | 荷兰 | VLESS | 259 ms |
| 🇮🇹 意大利_01 | 意大利 | SS | 263 ms |
| 🇮🇹 意大利_02 | 意大利 | SS | 264 ms |
| 🇳🇱 荷兰_01 | 荷兰 | VLESS | 289 ms |
| 🇩🇪 德国_02 | 德国 | VLESS | 313 ms |
| 🇺🇸 美国_02 | 美国 | VLESS | 399 ms |
| 🇮🇹 意大利_05 | 意大利 | SS | 487 ms |
| 🇮🇹 意大利_06 | 意大利 | SS | 1230 ms |
| 🇮🇹 意大利_09 | 意大利 | SS | 1266 ms |
| 🇮🇹 意大利_04 | 意大利 | SS | 1272 ms |
| 🇮🇹 意大利_07 | 意大利 | SS | 2253 ms |

[查看完整延迟数据](latency.json)

## 免费节点列表

节点列表最多显示25个，订阅后查看全部节点

```text
vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7Ag6aaZ5rivXzAxIiwiYWRkIjoiNDcuMjQ0LjEyMC4xOTciLCJwb3J0IjoiMjMwMjYiLCJpZCI6ImI5ZGUxYmM5LWJhYTctNDFhYy04NmY3LWNjZDU5Njk1Y2IyMSIsImFpZCI6IjAiLCJzY3kiOiJhdXRvIiwibmV0Ijoid3MiLCJ0eXBlIjoibm9uZSIsImhvc3QiOiIiLCJwYXRoIjoiL2Fya2kiLCJ0bHMiOiIiLCJzbmkiOiIiLCJhbHBuIjoiIiwiZnAiOiIiLCJpbnNlY3VyZSI6IjAifQ==
vless://c16e8cdb-65dd-4049-bc65-14c051b8a6c6@2.26.251.236:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=mental-deprivation.ru&pbk=1iVMMhJZgXHRY7tRlR-1kypF0YeaBcB7EjcfHRsYZX4&sid=4ff31b18d1bd8227&type=tcp&headerType=none#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.63:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_03
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.18:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_10
ss://YWVzLTI1Ni1nY206NW1LalhBR3JsaUlBbFl3V0RlRnprQ0VNSWdRZEZRTGU@48.103.218.77:18443#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.90:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_08
vless://cda0862a-0f87-4be9-8ed8-1d0c9e382839@196.196.148.63:443?encryption=none&security=reality&sni=717252g.nl8.h1clayd.click&fp=firefox&pbk=PD8Jdlg3xB9QY--jwQjp8PFPzCS8-Oryw6-HWBcHMFU&sid=d3bd772514c87d28&type=grpc&authority=&serviceName=204adda7e3da&mode=gun#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.27:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.72:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_02
vless://cda0862a-0f87-4be9-8ed8-1d0c9e382839@196.245.52.183:443?encryption=none&security=reality&sni=15b171g.nl7.h1clayd.click&fp=firefox&pbk=zbz--PMjcIC4Ggr3j-ibDf0fzXRTj0lM_HzjPJyMkVE&sid=50a749f0eccb628c&type=grpc&authority=&serviceName=5b79e8a94241&mode=gun#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_01
vless://d92038b6-b470-4267-9c69-2c649bf3f4a4@136.234.9.19:443?&security=reality&pbk=43bHrvqzL5Sw8lvtDSE3LAlp_0WbixVc7nYcAf17bhg&sid=16b6715de8577aaa&fp=firefox&sni=8ba6c3t.nl2.h1clayd.click&type=tcp&headerType=none&host=8ba6c3t.nl2.h1clayd.click&path=%2F#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_02
vless://cda0862a-0f87-4be9-8ed8-1d0c9e382839@13.141.51.2:443?encryption=none&security=reality&sni=04535dt.us8.h1clayd.click&fp=firefox&pbk=UoS8qZ74hP_ECcncCz55lzvlcVss3R7VA0WYZE0YQCY&sid=ba2a3dce62b99092&type=tcp&headerType=none#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.81:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_05
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.45:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_06
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.99:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_09
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.36:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_04
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.54:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_07
```

## 反馈

欢迎在 Issues 反馈失效链接和导入问题，请说明客户端版本及错误提示，不要提交个人密码或私有订阅。

请遵守所在地法律法规及服务条款，谨慎通过公共代理传输敏感信息。

## Shadowrocket 客户端下载

| 平台 | 客户端 | 下载地址 |
| --- | --- | --- |
| iOS / iPadOS | Shadowrocket（小火箭） | [App Store](https://apps.apple.com/us/app/shadowrocket/id932747118) |

App Store 的可用地区和价格以商店页面为准。

