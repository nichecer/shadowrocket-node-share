# 小火箭 Shadowrocket 免费节点

这里整理 Shadowrocket 客户端可导入的节点 URI 和订阅，提供固定入口、导入说明和更新信息。

## 本次更新

- 最近成功整理：2026-11-21 20:05:12
- 节点数量：19
- 最低 TCP 延迟：202 ms（德国）
- 国家/地区：德国、意大利、美国、芬兰、荷兰、西班牙
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
| 🇩🇪 德国_05 | 德国 | VLESS | 202 ms |
| 🇫🇮 芬兰_01 | 芬兰 | VLESS | 208 ms |
| 🇪🇸 西班牙_01 | 西班牙 | VLESS | 212 ms |
| 🇩🇪 德国_01 | 德国 | VLESS | 217 ms |
| 🇮🇹 意大利_04 | 意大利 | SS | 220 ms |
| 🇩🇪 德国_02 | 德国 | SS | 220 ms |
| 🇮🇹 意大利_07 | 意大利 | SS | 225 ms |
| 🇮🇹 意大利_03 | 意大利 | SS | 240 ms |
| 🇫🇮 芬兰_03 | 芬兰 | VLESS | 251 ms |
| 🇮🇹 意大利_06 | 意大利 | SS | 255 ms |
| 🇮🇹 意大利_09 | 意大利 | SS | 258 ms |
| 🇮🇹 意大利_01 | 意大利 | SS | 264 ms |
| 🇮🇹 意大利_02 | 意大利 | SS | 270 ms |
| 🇳🇱 荷兰_02 | 荷兰 | VLESS | 289 ms |
| 🇳🇱 荷兰_01 | 荷兰 | VLESS | 311 ms |
| 🇺🇸 美国_02 | 美国 | VLESS | 351 ms |
| 🇮🇹 意大利_05 | 意大利 | SS | 1290 ms |
| 🇮🇹 意大利_08 | 意大利 | SS | 1290 ms |
| 🇩🇪 德国_03 | 德国 | VLESS | 1297 ms |

[查看完整延迟数据](latency.json)

## 免费节点列表

节点列表最多显示25个，订阅后查看全部节点

```text
vless://c16e8cdb-65dd-4049-bc65-14c051b8a6c6@2.26.251.236:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=mental-deprivation.ru&pbk=1iVMMhJZgXHRY7tRlR-1kypF0YeaBcB7EjcfHRsYZX4&sid=4ff31b18d1bd8227&type=tcp&headerType=none#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_05
vless://ea1bee20-9217-42c0-acee-d12bf0c42602@178.17.53.154:48982?encryption=none&security=reality&sni=cdn6-91.yahoo.com&fp=chrome&pbk=A1ygNS8bIvKp7ZlUnjjHX_Z2AS_e4suvSs_IkWICvGE&type=xhttp&path=%2F&mode=auto#%F0%9F%87%AB%F0%9F%87%AE%20%E8%8A%AC%E5%85%B0_01
vless://4201786b-d99b-4147-a5f0-20d47acddb81@196.196.149.80:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=7aa271t.es1.h1clayd.click&fp=chrome&pbk=ZSmetD4e9QG5CiXhniHg5HJB68L4kwbgAkJmMHtVwEE&sid=42426c882c5fcd41&type=tcp&headerType=none&host=7aa271t.es1.h1clayd.click&path=%2F#%F0%9F%87%AA%F0%9F%87%B8%20%E8%A5%BF%E7%8F%AD%E7%89%99_01
vless://bc93a03d-13b5-0004-8ee7-d50c11459dab@109.106.15.99:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=key-master-saver.com&fp=chrome&pbk=6VMgXXhZdJCiOG05EyK_zTHh00kpFGrZJeZIEPgqhjY&sid=1c3e8241a8743df9&type=tcp&headerType=none&host=key-master-saver.com#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.54:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_04
ss://MjAyMi1ibGFrZTMtY2hhY2hhMjAtcG9seTEzMDU6OHlPM0FOV2VmdXVHczFsUktYRUNRQTFGRWh4bFdGVjJwcFFNY0JhWm81WT0=@47.254.167.157:443#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.45:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_07
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.18:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_03
vless://66c78912-4e2d-41dc-8742-aaae2590804e@13.143.187.220:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=fi-s1.kadrhub.tech&fp=firefox&pbk=eDzVz3bxkv3IoN3BUCa_aA-RicoeG7ACylYSnmS2Pgg&type=tcp&headerType=none#%F0%9F%87%AB%F0%9F%87%AE%20%E8%8A%AC%E5%85%B0_03
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.27:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_06
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.36:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_09
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.90:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.72:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_02
vless://cda0862a-0f87-4be9-8ed8-1d0c9e382839@196.245.52.183:443?encryption=none&security=reality&sni=15b171g.nl7.h1clayd.click&fp=firefox&pbk=zbz--PMjcIC4Ggr3j-ibDf0fzXRTj0lM_HzjPJyMkVE&sid=50a749f0eccb628c&type=grpc&authority=&serviceName=5b79e8a94241&mode=gun#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_02
vless://cda0862a-0f87-4be9-8ed8-1d0c9e382839@196.196.148.63:443?encryption=none&security=reality&sni=717252g.nl8.h1clayd.click&fp=firefox&pbk=PD8Jdlg3xB9QY--jwQjp8PFPzCS8-Oryw6-HWBcHMFU&sid=d3bd772514c87d28&type=grpc&authority=&serviceName=204adda7e3da&mode=gun#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_01
vless://cda0862a-0f87-4be9-8ed8-1d0c9e382839@13.141.51.2:443?encryption=none&security=reality&sni=04535dt.us8.h1clayd.click&fp=firefox&pbk=UoS8qZ74hP_ECcncCz55lzvlcVss3R7VA0WYZE0YQCY&sid=ba2a3dce62b99092&type=tcp&headerType=none#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.81:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_05
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.99:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_08
vless://4201786b-d99b-4147-a5f0-20d47acddb81@136.148.208.221:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=8a2e72t.nl20.h1clayd.shop&fp=chrome&pbk=VZS639V1i-35g7VXb9EoTYL-Srm7858sxcvFAunncmA&sid=8d0d0679f42ffd98&type=tcp&headerType=none&host=8a2e72t.nl20.h1clayd.shop#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_03
```

## 反馈

欢迎在 Issues 反馈失效链接和导入问题，请说明客户端版本及错误提示，不要提交个人密码或私有订阅。

请遵守所在地法律法规及服务条款，谨慎通过公共代理传输敏感信息。

## Shadowrocket 客户端下载

| 平台 | 客户端 | 下载地址 |
| --- | --- | --- |
| iOS / iPadOS | Shadowrocket（小火箭） | [App Store](https://apps.apple.com/us/app/shadowrocket/id932747118) |

App Store 的可用地区和价格以商店页面为准。

