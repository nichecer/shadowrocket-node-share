# 小火箭 Shadowrocket 免费节点

这里整理 Shadowrocket 客户端可导入的节点 URI 和订阅，提供固定入口、导入说明和更新信息。

## 本次更新

- 最近成功整理：2026-11-28 20:05:12
- 节点数量：31
- 最低 TCP 延迟：35 ms（香港）
- 国家/地区：LY、以色列、德国、意大利、新加坡、法国、美国、芬兰、荷兰、西班牙、香港
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
| 🇭🇰 香港_03 | 香港 | VLESS | 35 ms |
| 🇭🇰 香港_04 | 香港 | VMESS | 35 ms |
| 🇭🇰 香港_02 | 香港 | VLESS | 36 ms |
| 🇸🇬 新加坡_02 | 新加坡 | VMESS | 67 ms |
| 🇭🇰 香港_01 | 香港 | SS | 85 ms |
| 🇸🇬 新加坡_01 | 新加坡 | VLESS | 130 ms |
| 🇩🇪 德国_01 | 德国 | VLESS | 160 ms |
| 🇩🇪 德国_02 | 德国 | VLESS | 182 ms |
| 🇳🇱 荷兰_05 | 荷兰 | VLESS | 201 ms |
| 🇳🇱 荷兰_03 | 荷兰 | VLESS | 205 ms |
| 🇫🇷 法国_02 | 法国 | VLESS | 213 ms |
| 🇮🇹 意大利_05 | 意大利 | SS | 219 ms |
| 🇺🇸 美国_01 | 美国 | VLESS | 222 ms |
| 🇳🇱 荷兰_01 | 荷兰 | VLESS | 227 ms |
| 🇮🇹 意大利_04 | 意大利 | SS | 232 ms |
| 🇫🇮 芬兰_01 | 芬兰 | VLESS | 239 ms |
| 🇫🇷 法国_01 | 法国 | VLESS | 255 ms |
| 🇮🇹 意大利_07 | 意大利 | SS | 263 ms |
| 🇮🇱 以色列_01 | 以色列 | VLESS | 264 ms |
| 🇮🇹 意大利_08 | 意大利 | SS | 264 ms |
| 🇮🇹 意大利_06 | 意大利 | SS | 265 ms |
| 🇮🇹 意大利_03 | 意大利 | SS | 267 ms |
| 🇱🇾 利比亚_01 | LY | VLESS | 272 ms |
| 🇳🇱 荷兰_02 | 荷兰 | VLESS | 420 ms |
| 🇮🇹 意大利_01 | 意大利 | SS | 1269 ms |

[查看完整延迟数据](latency.json)

## 免费节点列表

节点列表最多显示25个，订阅后查看全部节点

```text
vless://8b17beac-b143-447d-aa68-14cbb121a602@8.217.1.203:8443?security=reality&type=tcp&packetEncoding=xudp&sni=www.apple.com&fp=chrome&flow=xtls-rprx-vision&sid=0bf55f64&pbk=74P0QFvaK6B13rHsxR_t0lqRlg4YLuORD4VaHr5Jd38&encryption=none#%F0%9F%87%AD%F0%9F%87%B0%20%E9%A6%99%E6%B8%AF_03
vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7Ag6aaZ5rivXzA0IiwiYWRkIjoiNDcuMjQ0LjEyMC4xOTciLCJwb3J0IjoiMjMwMjYiLCJ0eXBlIjoibm9uZSIsImlkIjoiYjlkZTFiYzktYmFhNy00MWFjLTg2ZjctY2NkNTk2OTVjYjIxIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9hcmtpIiwiaG9zdCI6IjQ3LjI0NC4xMjAuMTk3IiwidGxzIjoiIn0=
vless://4fc9dc3d-0d57-49e7-9bc0-e323165241bf@8.210.92.38:443?&security=reality&flow=xtls-rprx-vision&pbk=vhu6gifBQ8-hRzW1gqKFkEXDlQbf6Ex8kKj1FcxhmzA&sid=d78318845237d9a9&fp=chrome&sni=www.ebay.com&type=tcp&headerType=none&host=www.ebay.com&path=%2F#%F0%9F%87%AD%F0%9F%87%B0%20%E9%A6%99%E6%B8%AF_02
vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wg5paw5Yqg5Z2hXzAyIiwiYWRkIjoiZmN0d2kueGlhb3lhbi5pbyIsInBvcnQiOiIxNjYxOCIsImlkIjoiOTY3ZmJjOTQtZmNjZC00NmMyLTkyNDEtYmU5MmQ0OTA2MTg2IiwiYWlkIjoiMCIsInNjeSI6ImF1dG8iLCJuZXQiOiJ3cyIsInR5cGUiOiIiLCJ0bHMiOiIiLCJwYXRoIjoiLyIsImhvc3QiOiI4NjcxNGFjYzRjYzU5MjRlODEyZGIxYzExN2RiODMyZi5tb2Jnc2xiLnRiY2FjaGUuY29tIn0=
ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTphYmM2MmYwMC05NWE4LTRjMmUtYTg1ZC0zNmEyY2RjOTc3ZGE=@waic.pro.main.sys-metric-report.com:28014#%F0%9F%87%AD%F0%9F%87%B0%20%E9%A6%99%E6%B8%AF_01
vless://218345b7-3589-4c5e-9c6c-15a6c2de6895@jp2chat.xyy123.win:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=blog.api.www.cloudflare.com&fp=chrome&pbk=I4sC7wO_OjKQcby3249aC1qGAmoMgHEFtRUvoLUy2yc&sid=c92cbef726ee8169&type=tcp&headerType=none#%F0%9F%87%B8%F0%9F%87%AC%20%E6%96%B0%E5%8A%A0%E5%9D%A1_01
vless://c16e8cdb-65dd-4049-bc65-14c051b8a6c6@2.26.251.236:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=mental-deprivation.ru&fp=chrome&pbk=1iVMMhJZgXHRY7tRlR-1kypF0YeaBcB7EjcfHRsYZX4&sid=4ff31b18d1bd8227&type=tcp&headerType=none#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_01
vless://a71d6c6d-c95e-4ec1-a892-22e21733bf09@178.248.236.229:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=144.hexdey.com&fp=firefox&pbk=_3mkK8SY6YVqws73SUVPKL77tzxDVNUt4ag9J9ec-D0&sid=d05a120d3506d2cc&type=tcp&headerType=none#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_02
vless://4201786b-d99b-4147-a5f0-20d47acddb81@8a2e72t.nl20.h1clayd.shop:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=8a2e72t.nl20.h1clayd.shop&fp=random&pbk=VZS639V1i-35g7VXb9EoTYL-Srm7858sxcvFAunncmA&sid=8d0d0679f42ffd98&type=tcp&headerType=none&host=8a2e72t.nl20.h1clayd.shop#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_05
vless://85432578-96fd-4613-a255-e235a81cc94b@185.16.110.62:2052?encryption=none&security=none&sni=cd90.u8o.lol&type=ws&path=%2F#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_03
vless://e894c08a-fecc-46f5-bf03-c95d0274c79d@13.141.36.43:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=6bf329t.nl18.h1clayd.click&fp=chrome&pbk=p35RUaaaItuoyNiCrLpGeStBUpEJMSiZ2AajdfhhmiM&sid=92aee92130b46fe2&type=tcp&headerType=none#%F0%9F%87%AB%F0%9F%87%B7%20%E6%B3%95%E5%9B%BD_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.27:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_05
vless://9e92bb57-2332-4c30-bb97-f269a94e53a3@204.138.145.163:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=www.microsoft.com&fp=chrome&pbk=SkR5Vn9gdkPsr7MInaC9rkAaJz57VeGN4U2AgXaol0s&sid=296654cee8d6832e&type=tcp&headerType=none#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_01
vless://9c69546a-e435-4037-bc63-f9e5829a8be3@185.141.34.93:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=static.lormit.digital&fp=chrome&pbk=k_DjUz2cP6QGuDVwyvTrk3QTuJVntXCPjxJmO-UZchI&sid=9f07e56cfce2b9a3&type=tcp&headerType=none#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.99:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_04
vless://b63bc3fe-8852-4ead-8d25-8d8d5bae79ae@2.29.62.181:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=api.steampowered.com&fp=firefox&pbk=4hAezOnHPiz2LUH0NBpS7KmGVd7-AyOODfHWwyQ50kM&sid=fdea6c48da968d75&spx=%2F310b856fdca2513&type=tcp&headerType=none#%F0%9F%87%AB%F0%9F%87%AE%20%E8%8A%AC%E5%85%B0_01
vless://c53ea5e9-ed8b-4990-805d-7f1d6451426c@92.118.206.218:8443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=dur.sky-vault.top&fp=chrome&pbk=fSVfR9NB-6J6smrZlavi0GWd8JfDh0aXuEkKbtuFzUI&sid=3cbc3d737fb9c4af&type=tcp&headerType=none#%F0%9F%87%AB%F0%9F%87%B7%20%E6%B3%95%E5%9B%BD_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.18:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_07
vless://4201786b-d99b-4147-a5f0-20d47acddb81@196.196.148.177:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=4935e4t.de25.h1clayd.click&fp=firefox&pbk=MzgB17ZFbKqs8pbC3EscTzHid_ENc-k_Cp6nXl-2knw&sid=6976d670818644cc&type=tcp&headerType=none#%F0%9F%87%AE%F0%9F%87%B1%20%E4%BB%A5%E8%89%B2%E5%88%97_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.54:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_08
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.72:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_06
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.45:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_03
vless://4201786b-d99b-4147-a5f0-20d47acddb81@196.199.122.2:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=7aa271t.es1.h1clayd.click&fp=chrome&pbk=ZSmetD4e9QG5CiXhniHg5HJB68L4kwbgAkJmMHtVwEE&sid=42426c882c5fcd41&type=tcp&headerType=none&host=7aa271t.es1.h1clayd.click&path=%2F#%F0%9F%87%B1%F0%9F%87%BE%20%E5%88%A9%E6%AF%94%E4%BA%9A_01
vless://86420b69-84f9-4726-ab17-fb0a7bc05d8f@31.58.191.93:443?encryption=none&security=reality&sni=n4.fernstatic.com&pbk=0MSoevDfxrS1SB5IVdzFT2sMmicWY3Q1FjgZWbqsvXo&sid=3b1a6acf74e481e7&type=xhttp&path=%2F&mode=auto#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.81:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_01
```

## 反馈

欢迎在 Issues 反馈失效链接和导入问题，请说明客户端版本及错误提示，不要提交个人密码或私有订阅。

请遵守所在地法律法规及服务条款，谨慎通过公共代理传输敏感信息。

## Shadowrocket 客户端下载

| 平台 | 客户端 | 下载地址 |
| --- | --- | --- |
| iOS / iPadOS | Shadowrocket（小火箭） | [App Store](https://apps.apple.com/us/app/shadowrocket/id932747118) |

App Store 的可用地区和价格以商店页面为准。

