# 小火箭 Shadowrocket 免费节点

这里整理 Shadowrocket 客户端可导入的节点 URI 和订阅，提供固定入口、导入说明和更新信息。

## 本次更新

- 最近成功整理：2026-11-24 20:05:10
- 节点数量：19
- 最低 TCP 延迟：86 ms（马来西亚）
- 国家/地区：德国、意大利、美国、荷兰、西班牙、马来西亚
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
| 🇲🇾 马来西亚_01 | 马来西亚 | VLESS | 86 ms |
| 🇳🇱 荷兰_03 | 荷兰 | VLESS | 212 ms |
| 🇪🇸 西班牙_01 | 西班牙 | VLESS | 213 ms |
| 🇮🇹 意大利_08 | 意大利 | SS | 219 ms |
| 🇳🇱 荷兰_01 | 荷兰 | VLESS | 220 ms |
| 🇳🇱 荷兰_02 | 荷兰 | VLESS | 221 ms |
| 🇩🇪 德国_01 | 德国 | VLESS | 230 ms |
| 🇮🇹 意大利_03 | 意大利 | SS | 236 ms |
| 🇮🇹 意大利_01 | 意大利 | SS | 245 ms |
| 🇩🇪 德国_03 | 德国 | VLESS | 245 ms |
| 🇮🇹 意大利_05 | 意大利 | SS | 265 ms |
| 🇩🇪 德国_02 | 德国 | SS | 266 ms |
| 🇮🇹 意大利_04 | 意大利 | SS | 267 ms |
| 🇮🇹 意大利_07 | 意大利 | SS | 268 ms |
| 🇮🇹 意大利_06 | 意大利 | SS | 270 ms |
| 🇮🇹 意大利_02 | 意大利 | SS | 273 ms |
| 🇺🇸 美国_02 | 美国 | VLESS | 405 ms |
| 🇮🇹 意大利_09 | 意大利 | SS | 1286 ms |
| 🇩🇪 德国_04 | 德国 | VLESS | 1321 ms |

[查看完整延迟数据](latency.json)

## 免费节点列表

节点列表最多显示25个，订阅后查看全部节点

```text
vless://33d67a80-909e-4cec-aa8f-601f6019a8f0@23.27.199.148:24378?encryption=none&security=reality&sni=shield.nvidia.hk&fp=chrome&pbk=neyQkmBRy_PQjVEN1c6a9UqGyTf-UePx1HNoRCmgFkw&sid=31a5fe51&spx=%2F64d290e8e33721f&type=tcp&headerType=none#%F0%9F%87%B2%F0%9F%87%BE%20%E9%A9%AC%E6%9D%A5%E8%A5%BF%E4%BA%9A_01
vless://cda0862a-0f87-4be9-8ed8-1d0c9e382839@717252g.nl8.h1clayd.click:443?security=reality&type=grpc&mode=gun&serviceName=204adda7e3da&packetEncoding=xudp&sni=717252g.nl8.h1clayd.click&fp=firefox&sid=d3bd772514c87d28&pbk=PD8Jdlg3xB9QY--jwQjp8PFPzCS8-Oryw6-HWBcHMFU&encryption=none#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_03
vless://4201786b-d99b-4147-a5f0-20d47acddb81@196.196.149.80:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=7aa271t.es1.h1clayd.click&fp=chrome&pbk=ZSmetD4e9QG5CiXhniHg5HJB68L4kwbgAkJmMHtVwEE&sid=42426c882c5fcd41&type=tcp&headerType=none#%F0%9F%87%AA%F0%9F%87%B8%20%E8%A5%BF%E7%8F%AD%E7%89%99_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.63:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_08
vless://a8e5585a-6020-4649-a364-c1ebf3a40548@193.111.248.54:443?&security=reality&flow=xtls-rprx-vision&pbk=0KDql59THS-DXg30wMR0QGgFB6rXARDhr8WoWyfVA2M&sid=6f0091ebe3029ebb&fp=firefox&sni=tagderdeutscheneinheit.de&type=tcp&headerType=none&host=tagderdeutscheneinheit.de&path=%2F#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_01
vless://cda0862a-0f87-4be9-8ed8-1d0c9e382839@5d0319t.nl7.h1clayd.click:443?encryption=none&security=reality&sni=5d0319t.nl7.h1clayd.click&fp=firefox&pbk=l-GzBDuNuhnjxoRlZqKvT7jAt_sbVAxhGFsAttO5kXs&sid=361d0dd59c70516f&type=tcp&headerType=none&host=5d0319t.nl7.h1clayd.click#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_02
vless://c16e8cdb-65dd-4049-bc65-14c051b8a6c6@2.26.251.236:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=mental-deprivation.ru&pbk=1iVMMhJZgXHRY7tRlR-1kypF0YeaBcB7EjcfHRsYZX4&sid=4ff31b18d1bd8227&type=tcp&headerType=none#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.18:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_03
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.45:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_01
vless://4201786b-d99b-4147-a5f0-20d47acddb81@4935e4t.de25.h1clayd.click:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=4935e4t.de25.h1clayd.click&fp=ios&pbk=MzgB17ZFbKqs8pbC3EscTzHid_ENc-k_Cp6nXl-2knw&sid=6976d670818644cc&type=tcp&headerType=none#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_03
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.81:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_05
ss://MjAyMi1ibGFrZTMtY2hhY2hhMjAtcG9seTEzMDU6OHlPM0FOV2VmdXVHczFsUktYRUNRQTFGRWh4bFdGVjJwcFFNY0JhWm81WT0=@47.254.128.109:443#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0@202.50.253.54:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_04
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.72:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_07
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.99:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_06
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.90:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_02
vless://cda0862a-0f87-4be9-8ed8-1d0c9e382839@196.245.52.187:443?encryption=none&security=reality&sni=04535dt.us8.h1clayd.click&fp=firefox&pbk=UoS8qZ74hP_ECcncCz55lzvlcVss3R7VA0WYZE0YQCY&sid=ba2a3dce62b99092&type=tcp&headerType=none#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.36:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_09
vless://4201786b-d99b-4147-a5f0-20d47acddb81@8a2e72t.nl11.h1clayd.click:443?security=reality&type=raw&packetEncoding=xudp&sni=8a2e72t.nl11.h1clayd.click&fp=chrome&flow=xtls-rprx-vision&sid=8d0d0679f42ffd98&pbk=VZS639V1i-35g7VXb9EoTYL-Srm7858sxcvFAunncmA#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_04
```

## 反馈

欢迎在 Issues 反馈失效链接和导入问题，请说明客户端版本及错误提示，不要提交个人密码或私有订阅。

请遵守所在地法律法规及服务条款，谨慎通过公共代理传输敏感信息。

## Shadowrocket 客户端下载

| 平台 | 客户端 | 下载地址 |
| --- | --- | --- |
| iOS / iPadOS | Shadowrocket（小火箭） | [App Store](https://apps.apple.com/us/app/shadowrocket/id932747118) |

App Store 的可用地区和价格以商店页面为准。

