# 小火箭 Shadowrocket 免费节点

这里整理 Shadowrocket 客户端可导入的节点 URI 和订阅，提供固定入口、导入说明和更新信息。

## 本次更新

- 最近成功整理：2026-11-28 08:05:12
- 节点数量：25
- 最低 TCP 延迟：35 ms（香港）
- 国家/地区：以色列、德国、意大利、新加坡、法国、美国、荷兰、西班牙、香港
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
| 🇭🇰 香港_02 | 香港 | VLESS | 35 ms |
| 🇭🇰 香港_01 | 香港 | VMESS | 36 ms |
| 🇸🇬 新加坡_01 | 新加坡 | VLESS | 85 ms |
| 🇩🇪 德国_01 | 德国 | VLESS | 169 ms |
| 🇺🇸 美国_03 | 美国 | VLESS | 177 ms |
| 🇩🇪 德国_03 | 德国 | VLESS | 181 ms |
| 🇳🇱 荷兰_02 | 荷兰 | VLESS | 186 ms |
| 🇩🇪 德国_02 | 德国 | VLESS | 196 ms |
| 🇫🇷 法国_01 | 法国 | VLESS | 210 ms |
| 🇮🇹 意大利_09 | 意大利 | SS | 217 ms |
| 🇮🇹 意大利_10 | 意大利 | SS | 218 ms |
| 🇺🇸 美国_02 | 美国 | VLESS | 224 ms |
| 🇮🇹 意大利_01 | 意大利 | SS | 238 ms |
| 🇮🇹 意大利_07 | 意大利 | SS | 252 ms |
| 🇳🇱 荷兰_03 | 荷兰 | VLESS | 252 ms |
| 🇳🇱 荷兰_01 | 荷兰 | VLESS | 253 ms |
| 🇮🇹 意大利_04 | 意大利 | SS | 256 ms |
| 🇮🇹 意大利_08 | 意大利 | SS | 257 ms |
| 🇮🇹 意大利_05 | 意大利 | SS | 259 ms |
| 🇪🇸 西班牙_02 | 西班牙 | VLESS | 263 ms |
| 🇮🇹 意大利_02 | 意大利 | SS | 264 ms |
| 🇮🇹 意大利_03 | 意大利 | SS | 274 ms |
| 🇮🇹 意大利_06 | 意大利 | SS | 276 ms |
| 🇮🇱 以色列_01 | 以色列 | VLESS | 299 ms |
| 🇪🇸 西班牙_01 | 西班牙 | VLESS | 321 ms |

[查看完整延迟数据](latency.json)

## 免费节点列表

节点列表最多显示25个，订阅后查看全部节点

```text
vless://8b17beac-b143-447d-aa68-14cbb121a602@8.217.1.203:8443?security=reality&type=tcp&packetEncoding=xudp&sni=www.apple.com&fp=chrome&flow=xtls-rprx-vision&sid=0bf55f64&pbk=74P0QFvaK6B13rHsxR_t0lqRlg4YLuORD4VaHr5Jd38&encryption=none#%F0%9F%87%AD%F0%9F%87%B0%20%E9%A6%99%E6%B8%AF_02
vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7Ag6aaZ5rivXzAxIiwiYWRkIjoiNDcuMjQ0LjEyMC4xOTciLCJwb3J0Ijo0NDg2NywiYWlkIjowLCJzY3kiOiJhdXRvIiwibmV0Ijoid3MiLCJ0eXBlIjoibm9uZSIsInRscyI6IiIsImlkIjoiODQ1ZTZiMDgtMjkxOS00MjkwLWFkZTAtNWRjN2RjZWE1OWNhIiwic2tpcC1jZXJ0LXZlcmlmeSI6dHJ1ZSwiaG9zdCI6IjQ3LjI0NC4xMjAuMTk3IiwicGF0aCI6Ii9hcmtpIn0=
vless://ead3595f-4020-4e76-a3ec-c248e1a2f2f7@free.fugui.lol:51283?encryption=none&flow=xtls-rprx-vision&security=reality&sni=swdist.apple.com&fp=chrome&pbk=IjWYbHNrZb3UCQxsTJyekEOA3tHq42L6Jw3O8MmLYVQ&sid=fa514b83&type=tcp&headerType=none&host=swdist.apple.com&path=%2F#%F0%9F%87%B8%F0%9F%87%AC%20%E6%96%B0%E5%8A%A0%E5%9D%A1_01
vless://a71d6c6d-c95e-4ec1-a892-22e21733bf09@178.248.236.229:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=144.hexdey.com&fp=firefox&pbk=_3mkK8SY6YVqws73SUVPKL77tzxDVNUt4ag9J9ec-D0&sid=d05a120d3506d2cc&type=tcp&headerType=none#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_01
vless://cda0862a-0f87-4be9-8ed8-1d0c9e382839@162.35.101.177:443?security=reality&type=grpc&mode=gun&serviceName=99f2107b03f8&packetEncoding=none&sni=0592efg.us8.h1clayd.click&fp=edge&sid=bd8f712209a9c283&pbk=cO3wYHISTeorXcM8ffaDCDdqZ-olBQL-GyZqb-W7rTk#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_03
vless://dc780059-8b89-42d1-94eb-1c1d1bbbdd2f@quirivoo.ir:2052?security=none&type=ws&path=%2F&host=quirivoo.ir&packetEncoding=xudp&encryption=mlkem768x25519plus.native.0rtt.7cEi3EYubZPwXl754zAXJkMQRhE95FMPVVhP8613QEA#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_03
vless://cda0862a-0f87-4be9-8ed8-1d0c9e382839@153.56.231.73:443?encryption=none&security=reality&sni=717252g.nl8.h1clayd.click&fp=firefox&pbk=PD8Jdlg3xB9QY--jwQjp8PFPzCS8-Oryw6-HWBcHMFU&sid=d3bd772514c87d28&type=grpc&authority=&serviceName=204adda7e3da&mode=gun#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_02
vless://c16e8cdb-65dd-4049-bc65-14c051b8a6c6@2.26.251.236:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=mental-deprivation.ru&pbk=1iVMMhJZgXHRY7tRlR-1kypF0YeaBcB7EjcfHRsYZX4&sid=4ff31b18d1bd8227&type=tcp&headerType=none#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_02
vless://e894c08a-fecc-46f5-bf03-c95d0274c79d@13.141.36.43:443?security=reality&type=tcp&packetEncoding=none&sni=6bf329t.nl18.h1clayd.click&fp=chrome&flow=xtls-rprx-vision&sid=92aee92130b46fe2&pbk=p35RUaaaItuoyNiCrLpGeStBUpEJMSiZ2AajdfhhmiM#%F0%9F%87%AB%F0%9F%87%B7%20%E6%B3%95%E5%9B%BD_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0@202.50.253.27:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_09
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.99:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_10
vless://ea759639-a58c-4c46-8e0b-4cc834bf6658@us-tube-01.funky-monkey.app:443?security=reality&type=tcp&packetEncoding=xudp&sni=steam-videos.cc&fp=firefox&flow=xtls-rprx-vision&pbk=SbVKOEMjK0sIlbwg4akyBg5mL5KZwwB-ed4eEE7YnRc&encryption=none#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.81:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.54:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_07
vless://cda0862a-0f87-4be9-8ed8-1d0c9e382839@196.196.148.85:443?encryption=none&security=reality&sni=5d0319t.nl7.h1clayd.click&fp=firefox&pbk=l-GzBDuNuhnjxoRlZqKvT7jAt_sbVAxhGFsAttO5kXs&sid=361d0dd59c70516f&type=tcp&headerType=none&host=5d0319t.nl7.h1clayd.click&path=%2F#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_03
vless://86420b69-84f9-4726-ab17-fb0a7bc05d8f@31.58.191.93:443?encryption=none&security=reality&sni=n4.fernstatic.com&pbk=0MSoevDfxrS1SB5IVdzFT2sMmicWY3Q1FjgZWbqsvXo&sid=3b1a6acf74e481e7&type=xhttp&path=%2F&mode=auto#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.45:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_04
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.36:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_08
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.90:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_05
vless://4201786b-d99b-4147-a5f0-20d47acddb81@196.196.149.81:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=7aa271t.es1.h1clayd.click&fp=firefox&pbk=ZSmetD4e9QG5CiXhniHg5HJB68L4kwbgAkJmMHtVwEE&sid=42426c882c5fcd41&type=tcp&headerType=none&host=7aa271t.es1.h1clayd.click&path=%2F#%F0%9F%87%AA%F0%9F%87%B8%20%E8%A5%BF%E7%8F%AD%E7%89%99_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.63:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.18:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_03
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.72:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_06
vless://4201786b-d99b-4147-a5f0-20d47acddb81@196.196.148.177:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=4935e4t.de25.h1clayd.click&fp=firefox&pbk=MzgB17ZFbKqs8pbC3EscTzHid_ENc-k_Cp6nXl-2knw&sid=6976d670818644cc&type=tcp&headerType=none&host=4935e4t.de25.h1clayd.click&path=%2F#%F0%9F%87%AE%F0%9F%87%B1%20%E4%BB%A5%E8%89%B2%E5%88%97_01
vless://bbbee51e-021e-4e65-ba03-bf7de175116f@194.58.60.228:443?security=reality&type=grpc&mode=gun&serviceName=livestreamcontent&packetEncoding=none&sni=node43.lmdscdn.ru&fp=edge&sid=c5548af15927b698&pbk=PVlnR_I9tZ8hKhOHW6ySpSofhsaShcBQ_JV2-0TePVA#%F0%9F%87%AA%F0%9F%87%B8%20%E8%A5%BF%E7%8F%AD%E7%89%99_01
```

## 反馈

欢迎在 Issues 反馈失效链接和导入问题，请说明客户端版本及错误提示，不要提交个人密码或私有订阅。

请遵守所在地法律法规及服务条款，谨慎通过公共代理传输敏感信息。

## Shadowrocket 客户端下载

| 平台 | 客户端 | 下载地址 |
| --- | --- | --- |
| iOS / iPadOS | Shadowrocket（小火箭） | [App Store](https://apps.apple.com/us/app/shadowrocket/id932747118) |

App Store 的可用地区和价格以商店页面为准。

