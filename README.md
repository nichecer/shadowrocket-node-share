# 小火箭 Shadowrocket 免费节点

这里整理 Shadowrocket 客户端可导入的节点 URI 和订阅，提供固定入口、导入说明和更新信息。

## 本次更新

- 最近成功整理：2026-11-27 08:05:09
- 节点数量：32
- 最低 TCP 延迟：34 ms（香港）
- 国家/地区：EE、以色列、德国、意大利、新加坡、美国、荷兰、西班牙、韩国、香港
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
| 🇭🇰 香港_05 | 香港 | VMESS | 34 ms |
| 🇭🇰 香港_04 | 香港 | VMESS | 35 ms |
| 🇭🇰 香港_02 | 香港 | VLESS | 35 ms |
| 🇭🇰 香港_03 | 香港 | VLESS | 37 ms |
| 🇩🇪 德国_03 | 德国 | VLESS | 58 ms |
| 🇸🇬 新加坡_03 | 新加坡 | VLESS | 58 ms |
| 🇭🇰 香港_06 | 香港 | VLESS | 66 ms |
| 🇸🇬 新加坡_01 | 新加坡 | VLESS | 71 ms |
| 🇭🇰 香港_01 | 香港 | SS | 72 ms |
| 🇰🇷 韩国_01 | 韩国 | SS | 142 ms |
| 🇩🇪 德国_01 | 德国 | VLESS | 192 ms |
| 🇳🇱 荷兰_01 | 荷兰 | VLESS | 192 ms |
| 🇳🇱 荷兰_02 | 荷兰 | VLESS | 194 ms |
| 🇮🇹 意大利_08 | 意大利 | SS | 222 ms |
| 🇩🇪 德国_02 | 德国 | VLESS | 222 ms |
| 🇮🇹 意大利_01 | 意大利 | SS | 223 ms |
| 🇮🇹 意大利_07 | 意大利 | SS | 225 ms |
| 🇪🇪 爱沙尼亚_01 | EE | VLESS | 244 ms |
| 🇺🇸 美国_01 | 美国 | VLESS | 258 ms |
| 🇮🇹 意大利_06 | 意大利 | SS | 258 ms |
| 🇮🇹 意大利_03 | 意大利 | SS | 260 ms |
| 🇮🇹 意大利_02 | 意大利 | SS | 260 ms |
| 🇮🇹 意大利_09 | 意大利 | SS | 266 ms |
| 🇮🇹 意大利_04 | 意大利 | SS | 270 ms |
| 🇮🇹 意大利_05 | 意大利 | SS | 274 ms |

[查看完整延迟数据](latency.json)

## 免费节点列表

节点列表最多显示25个，订阅后查看全部节点

```text
vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7Ag6aaZ5rivXzA1IiwiYWRkIjoiNDcuMjQ0LjEyMC4xOTciLCJwb3J0Ijo0NDg2NywiYWlkIjowLCJzY3kiOiJhdXRvIiwibmV0Ijoid3MiLCJ0eXBlIjoibm9uZSIsInRscyI6IiIsImlkIjoiODQ1ZTZiMDgtMjkxOS00MjkwLWFkZTAtNWRjN2RjZWE1OWNhIiwic2tpcC1jZXJ0LXZlcmlmeSI6dHJ1ZSwiaG9zdCI6IjQ3LjI0NC4xMjAuMTk3IiwicGF0aCI6Ii9hcmtpIn0=
vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7Ag6aaZ5rivXzA0IiwiYWRkIjoiNDcuMjQyLjgxLjk0IiwicG9ydCI6NTIwODAsImlkIjoiZTQ3YjlmNzctNjBlNC00NzM4LThkNTMtNzcyYjYwMDJlMTQ2IiwiYWlkIjowLCJzY3kiOiJhdXRvIiwibmV0IjoidGNwIiwidHlwZSI6Imh0dHAiLCJ0bHMiOiIiLCJwYXRoIjoiL1FRcXVuLTczNzgwNTQ0MyIsImhvc3QiOiJvcGVuYWkuY29tIn0=
vless://4fc9dc3d-0d57-49e7-9bc0-e323165241bf@8.210.92.38:443?security=reality&type=tcp&packetEncoding=xudp&sni=www.ebay.com&fp=chrome&flow=xtls-rprx-vision&sid=d78318845237d9a9&pbk=vhu6gifBQ8-hRzW1gqKFkEXDlQbf6Ex8kKj1FcxhmzA#%F0%9F%87%AD%F0%9F%87%B0%20%E9%A6%99%E6%B8%AF_02
vless://8b17beac-b143-447d-aa68-14cbb121a602@8.217.1.203:8443?security=reality&type=tcp&packetEncoding=xudp&sni=www.apple.com&fp=chrome&flow=xtls-rprx-vision&sid=0bf55f64&pbk=74P0QFvaK6B13rHsxR_t0lqRlg4YLuORD4VaHr5Jd38&encryption=none#%F0%9F%87%AD%F0%9F%87%B0%20%E9%A6%99%E6%B8%AF_03
vless://ead3595f-4020-4e76-a3ec-c248e1a2f2f7@free.fugui.lol:19482?encryption=none&flow=xtls-rprx-vision&security=reality&sni=swdist.apple.com&fp=ios&pbk=IjWYbHNrZb3UCQxsTJyekEOA3tHq42L6Jw3O8MmLYVQ&sid=fa514b83&type=tcp&headerType=none#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_03
vless://ead3595f-4020-4e76-a3ec-c248e1a2f2f7@free.fugui.lol:51283?encryption=none&flow=xtls-rprx-vision&security=reality&sni=swdist.apple.com&fp=ios&pbk=IjWYbHNrZb3UCQxsTJyekEOA3tHq42L6Jw3O8MmLYVQ&sid=fa514b83&type=tcp&headerType=none#%F0%9F%87%B8%F0%9F%87%AC%20%E6%96%B0%E5%8A%A0%E5%9D%A1_03
vless://ead3595f-4020-4e76-a3ec-c248e1a2f2f7@free.fugui.lol:47396?encryption=none&flow=xtls-rprx-vision&security=reality&sni=swdist.apple.com&fp=chrome&pbk=IjWYbHNrZb3UCQxsTJyekEOA3tHq42L6Jw3O8MmLYVQ&sid=fa514b83&type=tcp&headerType=none#%F0%9F%87%AD%F0%9F%87%B0%20%E9%A6%99%E6%B8%AF_06
vless://5807f1c4-b50e-4ec0-8d01-274045da0da5@dddz-1-x.473221.xyz:43113?security=reality&type=tcp&packetEncoding=xudp&sni=v1-dy.ixigua.com&fp=edge&flow=xtls-rprx-vision&sid=ff2c978a0b&pbk=EK3prcfF8VKm3CoTXWQguRj67LxGbkPIpKmEUKsMKGs#%F0%9F%87%B8%F0%9F%87%AC%20%E6%96%B0%E5%8A%A0%E5%9D%A1_01
ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTphYmM2MmYwMC05NWE4LTRjMmUtYTg1ZC0zNmEyY2RjOTc3ZGE=@waic.pro.main.sys-metric-report.com:28014#%F0%9F%87%AD%F0%9F%87%B0%20%E9%A6%99%E6%B8%AF_01
ss://YWVzLTI1Ni1nY206cXBvd2lfdmlwX3R1bm5lbF8yMDI2X3NlY3VyZQ==@211.233.33.228:8388#%F0%9F%87%B0%F0%9F%87%B7%20%E9%9F%A9%E5%9B%BD_01
vless://c16e8cdb-65dd-4049-bc65-14c051b8a6c6@2.26.251.236:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=mental-deprivation.ru&fp=firefox&pbk=1iVMMhJZgXHRY7tRlR-1kypF0YeaBcB7EjcfHRsYZX4&sid=4ff31b18d1bd8227&spx=%2F5f73ebfc9ef9c37&type=tcp&headerType=none#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_01
vless://86420b69-84f9-4726-ab17-fb0a7bc05d8f@31.58.191.93:443?encryption=none&security=reality&sni=n4.fernstatic.com&pbk=0MSoevDfxrS1SB5IVdzFT2sMmicWY3Q1FjgZWbqsvXo&sid=3b1a6acf74e481e7&type=xhttp&path=%2F&mode=auto#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_01
vless://cda0862a-0f87-4be9-8ed8-1d0c9e382839@153.56.231.73:443?encryption=none&security=reality&sni=717252g.nl8.h1clayd.click&fp=firefox&pbk=PD8Jdlg3xB9QY--jwQjp8PFPzCS8-Oryw6-HWBcHMFU&sid=d3bd772514c87d28&type=grpc&authority=&serviceName=204adda7e3da&mode=gun#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.99:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_08
vless://a71d6c6d-c95e-4ec1-a892-22e21733bf09@178.248.236.229:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=144.hexdey.com&fp=firefox&pbk=_3mkK8SY6YVqws73SUVPKL77tzxDVNUt4ag9J9ec-D0&sid=d05a120d3506d2cc&type=tcp&headerType=none#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.27:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.81:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_07
vless://73ebb72a-e2a8-44c8-a0e3-938740a4f578@13.141.36.127:443?security=reality&type=tcp&packetEncoding=xudp&sni=079b6et.ee5.h1clayd.shop&fp=firefox&sid=35a329a23bb50d2b&pbk=NMS-P97L7IrYGl7mQv1j2K_EBX6G57fu6DvREZYl01U&encryption=none#%F0%9F%87%AA%F0%9F%87%AA%20%E7%88%B1%E6%B2%99%E5%B0%BC%E4%BA%9A_01
vless://148917bd-0b37-42b8-98f4-aa94ca73e75a@170.168.32.125:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=travel.yandex.ru&pbk=tp7awfnKLbhIDkdYlT7Avf-SfUwt7ncX5oyWS5wQmR0&sid=6d&type=tcp&headerType=none#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.36:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_06
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.72:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_03
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.63:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.18:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_09
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.90:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_04
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.45:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_05
```

## 反馈

欢迎在 Issues 反馈失效链接和导入问题，请说明客户端版本及错误提示，不要提交个人密码或私有订阅。

请遵守所在地法律法规及服务条款，谨慎通过公共代理传输敏感信息。

## Shadowrocket 客户端下载

| 平台 | 客户端 | 下载地址 |
| --- | --- | --- |
| iOS / iPadOS | Shadowrocket（小火箭） | [App Store](https://apps.apple.com/us/app/shadowrocket/id932747118) |

App Store 的可用地区和价格以商店页面为准。

