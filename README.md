# 小火箭 Shadowrocket 免费节点

这里整理 Shadowrocket 客户端可导入的节点 URI 和订阅，提供固定入口、导入说明和更新信息。

## 本次更新

- 最近成功整理：2026-11-23 20:05:12
- 节点数量：24
- 最低 TCP 延迟：40 ms（香港）
- 国家/地区：德国、意大利、美国、英国、荷兰、西班牙、香港
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
| 🇭🇰 香港_02 | 香港 | VMESS | 40 ms |
| 🇭🇰 香港_01 | 香港 | VLESS | 40 ms |
| 🇩🇪 德国_01 | 德国 | VLESS | 187 ms |
| 🇺🇸 美国_03 | 美国 | VMESS | 188 ms |
| 🇭🇰 香港_04 | 香港 | VMESS | 192 ms |
| 🇩🇪 德国_04 | 德国 | VLESS | 203 ms |
| 🇭🇰 香港_03 | 香港 | VMESS | 205 ms |
| 🇳🇱 荷兰_02 | 荷兰 | VLESS | 212 ms |
| 🇺🇸 美国_01 | 美国 | VLESS | 215 ms |
| 🇪🇸 西班牙_01 | 西班牙 | VLESS | 215 ms |
| 🇮🇹 意大利_05 | 意大利 | SS | 230 ms |
| 🇮🇹 意大利_10 | 意大利 | SS | 231 ms |
| 🇮🇹 意大利_02 | 意大利 | SS | 240 ms |
| 🇩🇪 德国_02 | 德国 | VLESS | 253 ms |
| 🇮🇹 意大利_04 | 意大利 | SS | 260 ms |
| 🇬🇧 英国_01 | 英国 | VLESS | 267 ms |
| 🇮🇹 意大利_06 | 意大利 | SS | 272 ms |
| 🇮🇹 意大利_09 | 意大利 | SS | 273 ms |
| 🇮🇹 意大利_08 | 意大利 | SS | 275 ms |
| 🇮🇹 意大利_07 | 意大利 | SS | 286 ms |
| 🇳🇱 荷兰_01 | 荷兰 | VLESS | 300 ms |
| 🇺🇸 美国_02 | 美国 | VLESS | 392 ms |
| 🇩🇪 德国_05 | 德国 | VLESS | 1231 ms |
| 🇮🇹 意大利_01 | 意大利 | SS | 2255 ms |

[查看完整延迟数据](latency.json)

## 免费节点列表

节点列表最多显示25个，订阅后查看全部节点

```text
vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7Ag6aaZ5rivXzAyIiwiYWRkIjoiNDcuMjQ0LjEyMC4xOTciLCJwb3J0IjoiMjMwMjYiLCJpZCI6ImI5ZGUxYmM5LWJhYTctNDFhYy04NmY3LWNjZDU5Njk1Y2IyMSIsImFpZCI6IjAiLCJzY3kiOiJhdXRvIiwibmV0Ijoid3MiLCJ0eXBlIjoibm9uZSIsImhvc3QiOiI0Ny4yNDQuMTIwLjE5NyIsInBhdGgiOiIvYXJraSIsInRscyI6IiIsInNuaSI6IjQ3LjI0NC4xMjAuMTk3IiwiYWxwbiI6IiIsImZwIjoiIiwiaW5zZWN1cmUiOiIwIn0=
vless://8b17beac-b143-447d-aa68-14cbb121a602@8.217.1.203:8443?security=reality&type=tcp&packetEncoding=xudp&sni=www.apple.com&fp=chrome&flow=xtls-rprx-vision&sid=0bf55f64&pbk=74P0QFvaK6B13rHsxR_t0lqRlg4YLuORD4VaHr5Jd38&encryption=none#%F0%9F%87%AD%F0%9F%87%B0%20%E9%A6%99%E6%B8%AF_01
vless://c16e8cdb-65dd-4049-bc65-14c051b8a6c6@2.26.251.236:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=mental-deprivation.ru&fp=chrome&pbk=1iVMMhJZgXHRY7tRlR-1kypF0YeaBcB7EjcfHRsYZX4&sid=4ff31b18d1bd8227&type=tcp&headerType=none#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_01
vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzAzIiwiYWRkIjoicGRtdjQueGlhb3lhbi5pbyIsInBvcnQiOiIxNjY0OCIsImlkIjoiOTA0ZjA1NjktODY5NS00NjZmLTk3Y2YtMGRlMmZhY2UxYjQ2IiwiYWlkIjoiMCIsInNjeSI6ImF1dG8iLCJuZXQiOiJ3cyIsInR5cGUiOiIiLCJ0bHMiOiIiLCJwYXRoIjoiLyIsImhvc3QiOiJmOTMwOWNjODg2MzdjMjZmNTUyYTFhNjRmYjMxMWNhZS5tb2Jnc2xiLnRiY2FjaGUuY29tIn0=
vmess://eyJhZGQiOiJwZG12NC54aWFveWFuLmlvIiwiYWlkIjowLCJhbHBuIjoiIiwiZnAiOiIiLCJob3N0IjoiZjkzMDljYzg4NjM3YzI2ZjU1MmExYTY0ZmIzMTFjYWUubW9iZ3NsYi50YmNhY2hlLmNvbSIsImlkIjoiOTA0ZjA1NjktODY5NS00NjZmLTk3Y2YtMGRlMmZhY2UxYjQ2IiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsInBvcnQiOjE2NjMyLCJwcyI6IvCfh63wn4ewIOmmmea4r18wNCIsInNjeSI6ImF1dG8iLCJzZWN1cml0eSI6ImF1dG8iLCJza2lwLWNlcnQtdmVyaWZ5IjpmYWxzZSwic25pIjoiIiwidGxzIjoiIiwidHlwZSI6Im5vbmUiLCJ2IjoiMiJ9
vless://cda0862a-0f87-4be9-8ed8-1d0c9e382839@f0d7aft.nl13.h1clayd.click:443?encryption=none&security=reality&sni=f0d7aft.nl13.h1clayd.click&fp=chrome&pbk=kkCGiCQCKnkozJR1KKCRNtmdBECmThCgI9VSv7iDcWI&sid=8956c57cb4c4f8d2&type=tcp&headerType=none#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_04
vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7Ag6aaZ5rivXzAzIiwiYWRkIjoiYnlyM2EueGlhb3lhbi5pbyIsInBvcnQiOiIxNjYyMiIsImlkIjoiOTA0ZjA1NjktODY5NS00NjZmLTk3Y2YtMGRlMmZhY2UxYjQ2IiwiYWlkIjoiMCIsInNjeSI6ImF1dG8iLCJuZXQiOiJ3cyIsInR5cGUiOiIiLCJ0bHMiOiIiLCJwYXRoIjoiLyIsImhvc3QiOiJmOTMwOWNjODg2MzdjMjZmNTUyYTFhNjRmYjMxMWNhZS5tb2Jnc2xiLnRiY2FjaGUuY29tIn0=
vless://cda0862a-0f87-4be9-8ed8-1d0c9e382839@fc82dfx.nl8.h1clayd.click:443?security=reality&type=xhttp&path=%2F0616f2d729aa&packetEncoding=xudp&sni=fc82dfx.nl8.h1clayd.click&fp=firefox&sid=7b2b1a14a6e0630d&pbk=dtO7khFLUkpFDQOtNzo4Th4hJKLoPSY2VtD_9k4Hgiw&mode=auto&encryption=none#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_02
vless://26843758-24de-4f76-b5d0-624038e353c4@71b840t.de7.h1clayd.click:443?security=reality&type=tcp&packetEncoding=xudp&sni=71b840t.de7.h1clayd.click&fp=chrome&sid=e572b6579ea525d4&pbk=3wFF83gtIA0sXj-6GGCAa--oQbSr0MVUj0FBc-0QmiE&encryption=none#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_01
vless://4201786b-d99b-4147-a5f0-20d47acddb81@196.196.149.80:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=7aa271t.es1.h1clayd.click&fp=chrome&pbk=ZSmetD4e9QG5CiXhniHg5HJB68L4kwbgAkJmMHtVwEE&sid=42426c882c5fcd41&type=tcp&headerType=none&host=7aa271t.es1.h1clayd.click#%F0%9F%87%AA%F0%9F%87%B8%20%E8%A5%BF%E7%8F%AD%E7%89%99_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.54:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_05
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.45:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_10
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.18:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_02
vless://4201786b-d99b-4147-a5f0-20d47acddb81@196.196.148.177:443?&security=reality&flow=xtls-rprx-vision&pbk=MzgB17ZFbKqs8pbC3EscTzHid_ENc-k_Cp6nXl-2knw&sid=6976d670818644cc&fp=firefox&sni=4935e4t.de25.h1clayd.click&type=tcp&headerType=none&host=4935e4t.de25.h1clayd.click&path=%2F#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.81:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_04
vless://cae99415-10a6-4317-81bd-19a4586b5d76@196.196.208.22:443?security=reality&type=xhttp&path=%2Ff57a81c99fea&host=9303d6x.fi-p1b.h1clayd.click&packetEncoding=none&sni=9303d6x.fi-p1b.h1clayd.click&fp=firefox&sid=621290c77645b731&pbk=_yJGJ5q-8IxTuWFcoy5wpKKYtk9p9q4lQ6svfXC1IUU&mode=auto#%F0%9F%87%AC%F0%9F%87%A7%20%E8%8B%B1%E5%9B%BD_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.36:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_06
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.99:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_09
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.72:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_08
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.90:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_07
vless://cda0862a-0f87-4be9-8ed8-1d0c9e382839@196.196.148.85:443?encryption=none&security=reality&sni=5d0319t.nl7.h1clayd.click&fp=chrome&pbk=l-GzBDuNuhnjxoRlZqKvT7jAt_sbVAxhGFsAttO5kXs&sid=361d0dd59c70516f&type=tcp&headerType=none#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_01
vless://cda0862a-0f87-4be9-8ed8-1d0c9e382839@13.141.51.2:443?encryption=none&security=reality&sni=04535dt.us8.h1clayd.click&fp=firefox&pbk=UoS8qZ74hP_ECcncCz55lzvlcVss3R7VA0WYZE0YQCY&sid=ba2a3dce62b99092&type=tcp&headerType=none&host=04535dt.us8.h1clayd.click#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_02
vless://4201786b-d99b-4147-a5f0-20d47acddb81@8a2e72t.nl20.h1clayd.shop:443?&security=reality&flow=xtls-rprx-vision&pbk=VZS639V1i-35g7VXb9EoTYL-Srm7858sxcvFAunncmA&sid=8d0d0679f42ffd98&fp=chrome&sni=8a2e72t.nl20.h1clayd.shop&type=tcp&headerType=none&host=8a2e72t.nl20.h1clayd.shop&path=%2F#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_05
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.63:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_01
```

## 反馈

欢迎在 Issues 反馈失效链接和导入问题，请说明客户端版本及错误提示，不要提交个人密码或私有订阅。

请遵守所在地法律法规及服务条款，谨慎通过公共代理传输敏感信息。

## Shadowrocket 客户端下载

| 平台 | 客户端 | 下载地址 |
| --- | --- | --- |
| iOS / iPadOS | Shadowrocket（小火箭） | [App Store](https://apps.apple.com/us/app/shadowrocket/id932747118) |

App Store 的可用地区和价格以商店页面为准。

