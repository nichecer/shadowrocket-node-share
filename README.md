# 小火箭 Shadowrocket 免费节点

这里整理 Shadowrocket 客户端可导入的节点 URI 和订阅，提供固定入口、导入说明和更新信息。

## 本次更新

- 最近成功整理：2026-11-27 20:05:12
- 节点数量：24
- 最低 TCP 延迟：33 ms（香港）
- 国家/地区：德国、意大利、波兰、美国、荷兰、西班牙、香港
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
| 🇭🇰 香港_02 | 香港 | VLESS | 33 ms |
| 🇭🇰 香港_03 | 香港 | VLESS | 35 ms |
| 🇭🇰 香港_04 | 香港 | VMESS | 35 ms |
| 🇭🇰 香港_01 | 香港 | SS | 92 ms |
| 🇭🇰 香港_05 | 香港 | VLESS | 116 ms |
| 🇩🇪 德国_01 | 德国 | VLESS | 187 ms |
| 🇩🇪 德国_02 | 德国 | VLESS | 204 ms |
| 🇵🇱 波兰_01 | 波兰 | VLESS | 211 ms |
| 🇳🇱 荷兰_01 | 荷兰 | VLESS | 212 ms |
| 🇳🇱 荷兰_02 | 荷兰 | VLESS | 214 ms |
| 🇮🇹 意大利_09 | 意大利 | SS | 228 ms |
| 🇮🇹 意大利_07 | 意大利 | SS | 228 ms |
| 🇪🇸 西班牙_02 | 西班牙 | VLESS | 231 ms |
| 🇮🇹 意大利_06 | 意大利 | SS | 261 ms |
| 🇮🇹 意大利_02 | 意大利 | SS | 264 ms |
| 🇮🇹 意大利_04 | 意大利 | SS | 266 ms |
| 🇮🇹 意大利_10 | 意大利 | SS | 267 ms |
| 🇮🇹 意大利_03 | 意大利 | SS | 287 ms |
| 🇺🇸 美国_01 | 美国 | VLESS | 484 ms |
| 🇩🇪 德国_03 | 德国 | SS | 1237 ms |
| 🇮🇹 意大利_01 | 意大利 | SS | 1250 ms |
| 🇮🇹 意大利_05 | 意大利 | SS | 1273 ms |
| 🇮🇹 意大利_08 | 意大利 | SS | 1294 ms |
| 🇳🇱 荷兰_03 | 荷兰 | VLESS | 1332 ms |

[查看完整延迟数据](latency.json)

## 免费节点列表

节点列表最多显示25个，订阅后查看全部节点

```text
vless://4fc9dc3d-0d57-49e7-9bc0-e323165241bf@8.210.92.38:443?&security=reality&flow=xtls-rprx-vision&pbk=vhu6gifBQ8-hRzW1gqKFkEXDlQbf6Ex8kKj1FcxhmzA&sid=d78318845237d9a9&fp=chrome&sni=www.ebay.com&type=tcp&headerType=none&host=www.ebay.com&path=%2F#%F0%9F%87%AD%F0%9F%87%B0%20%E9%A6%99%E6%B8%AF_02
vless://8b17beac-b143-447d-aa68-14cbb121a602@8.217.1.203:8443?security=reality&type=tcp&packetEncoding=xudp&sni=www.apple.com&fp=chrome&flow=xtls-rprx-vision&sid=0bf55f64&pbk=74P0QFvaK6B13rHsxR_t0lqRlg4YLuORD4VaHr5Jd38&encryption=none#%F0%9F%87%AD%F0%9F%87%B0%20%E9%A6%99%E6%B8%AF_03
vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7Ag6aaZ5rivXzA0IiwiYWRkIjoiNDcuMjQ0LjEyMC4xOTciLCJwb3J0IjoiNDQ4NjciLCJ0eXBlIjoibm9uZSIsImlkIjoiODQ1ZTZiMDgtMjkxOS00MjkwLWFkZTAtNWRjN2RjZWE1OWNhIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9hcmtpIiwiaG9zdCI6IjQ3LjI0NC4xMjAuMTk3IiwidGxzIjoiIn0=
ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTphYmM2MmYwMC05NWE4LTRjMmUtYTg1ZC0zNmEyY2RjOTc3ZGE=@waic.pro.main.sys-metric-report.com:28014#%F0%9F%87%AD%F0%9F%87%B0%20%E9%A6%99%E6%B8%AF_01
vless://ead3595f-4020-4e76-a3ec-c248e1a2f2f7@free.fugui.lol:47396?encryption=none&flow=xtls-rprx-vision&security=reality&sni=swdist.apple.com&fp=chrome&pbk=IjWYbHNrZb3UCQxsTJyekEOA3tHq42L6Jw3O8MmLYVQ&sid=fa514b83&type=tcp&headerType=none&host=swdist.apple.com#%F0%9F%87%AD%F0%9F%87%B0%20%E9%A6%99%E6%B8%AF_05
vless://c16e8cdb-65dd-4049-bc65-14c051b8a6c6@2.26.251.236:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=mental-deprivation.ru&pbk=1iVMMhJZgXHRY7tRlR-1kypF0YeaBcB7EjcfHRsYZX4&sid=4ff31b18d1bd8227&type=tcp&headerType=none#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_01
vless://a71d6c6d-c95e-4ec1-a892-22e21733bf09@178.248.236.229:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=144.hexdey.com&fp=firefox&pbk=_3mkK8SY6YVqws73SUVPKL77tzxDVNUt4ag9J9ec-D0&sid=d05a120d3506d2cc&type=tcp&headerType=none#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_02
vless://639b131f-d0f3-460c-aa17-423047f8a5df@177.3.252.114:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=poland.mcufa.pro&fp=chrome&pbk=-P8DgKISSG4jnLuj6ihZDqZs1_zt-juBrhVhTylHiAo&type=tcp&headerType=none#%F0%9F%87%B5%F0%9F%87%B1%20%E6%B3%A2%E5%85%B0_01
vless://cda0862a-0f87-4be9-8ed8-1d0c9e382839@153.56.231.73:443?encryption=none&security=reality&sni=717252g.nl8.h1clayd.click&fp=firefox&pbk=PD8Jdlg3xB9QY--jwQjp8PFPzCS8-Oryw6-HWBcHMFU&sid=d3bd772514c87d28&type=grpc&authority=&serviceName=204adda7e3da&mode=gun#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_01
vless://cda0862a-0f87-4be9-8ed8-1d0c9e382839@79.182.39.135:443?security=reality&type=grpc&mode=gun&serviceName=5b79e8a94241&packetEncoding=xudp&sni=15b171g.nl7.h1clayd.click&fp=firefox&sid=50a749f0eccb628c&pbk=zbz--PMjcIC4Ggr3j-ibDf0fzXRTj0lM_HzjPJyMkVE&encryption=none#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.81:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_09
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.27:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_07
vless://4201786b-d99b-4147-a5f0-20d47acddb81@196.196.149.81:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=7aa271t.es1.h1clayd.click&fp=firefox&pbk=ZSmetD4e9QG5CiXhniHg5HJB68L4kwbgAkJmMHtVwEE&sid=42426c882c5fcd41&type=tcp&headerType=none&host=7aa271t.es1.h1clayd.click&path=%2F#%F0%9F%87%AA%F0%9F%87%B8%20%E8%A5%BF%E7%8F%AD%E7%89%99_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.63:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_06
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.90:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.72:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_04
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.45:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_10
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.18:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_03
vless://cda0862a-0f87-4be9-8ed8-1d0c9e382839@196.245.52.187:443?encryption=none&security=reality&sni=04535dt.us8.h1clayd.click&fp=firefox&pbk=UoS8qZ74hP_ECcncCz55lzvlcVss3R7VA0WYZE0YQCY&sid=ba2a3dce62b99092&type=tcp&headerType=none#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_01
ss://MjAyMi1ibGFrZTMtY2hhY2hhMjAtcG9seTEzMDU6OHlPM0FOV2VmdXVHczFsUktYRUNRQTFGRWh4bFdGVjJwcFFNY0JhWm81WT0=@47.254.167.157:443#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_03
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0@202.50.253.99:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.36:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_05
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.54:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_08
vless://4201786b-d99b-4147-a5f0-20d47acddb81@196.196.148.76:443?&security=reality&flow=xtls-rprx-vision&pbk=VZS639V1i-35g7VXb9EoTYL-Srm7858sxcvFAunncmA&sid=8d0d0679f42ffd98&fp=firefox&sni=8a2e72t.nl20.h1clayd.shop&type=tcp&headerType=none&host=8a2e72t.nl20.h1clayd.shop&path=%2F#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_03
```

## 反馈

欢迎在 Issues 反馈失效链接和导入问题，请说明客户端版本及错误提示，不要提交个人密码或私有订阅。

请遵守所在地法律法规及服务条款，谨慎通过公共代理传输敏感信息。

## Shadowrocket 客户端下载

| 平台 | 客户端 | 下载地址 |
| --- | --- | --- |
| iOS / iPadOS | Shadowrocket（小火箭） | [App Store](https://apps.apple.com/us/app/shadowrocket/id932747118) |

App Store 的可用地区和价格以商店页面为准。

