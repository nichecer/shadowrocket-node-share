# 小火箭 Shadowrocket 免费节点

这里整理 Shadowrocket 客户端可导入的节点 URI 和订阅，提供固定入口、导入说明和更新信息。

## 本次更新

- 最近成功整理：2026-11-14 20:05:12
- 节点数量：18
- 最低 TCP 延迟：35 ms（香港）
- 国家/地区：意大利、日本、波兰、美国、英国、荷兰、西班牙、香港
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
| 🇯🇵 日本_01 | 日本 | SS | 61 ms |
| 🇳🇱 荷兰_01 | 荷兰 | VLESS | 215 ms |
| 🇵🇱 波兰_01 | 波兰 | VLESS | 222 ms |
| 🇮🇹 意大利_01 | 意大利 | SS | 226 ms |
| 🇮🇹 意大利_02 | 意大利 | SS | 226 ms |
| 🇮🇹 意大利_10 | 意大利 | SS | 234 ms |
| 🇪🇸 西班牙_01 | 西班牙 | VLESS | 250 ms |
| 🇮🇹 意大利_06 | 意大利 | SS | 256 ms |
| 🇮🇹 意大利_07 | 意大利 | SS | 256 ms |
| 🇮🇹 意大利_08 | 意大利 | SS | 257 ms |
| 🇮🇹 意大利_05 | 意大利 | SS | 263 ms |
| 🇮🇹 意大利_03 | 意大利 | SS | 265 ms |
| 🇮🇹 意大利_09 | 意大利 | SS | 268 ms |
| 🇬🇧 英国_01 | 英国 | VLESS | 294 ms |
| 🇺🇸 美国_03 | 美国 | VLESS | 428 ms |
| 🇮🇹 意大利_04 | 意大利 | SS | 1264 ms |
| 🇳🇱 荷兰_02 | 荷兰 | VLESS | 2358 ms |

[查看完整延迟数据](latency.json)

## 免费节点列表

节点列表最多显示25个，订阅后查看全部节点

```text
vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7Ag6aaZ5rivXzAxIiwiYWRkIjoiNDcuMjQ0LjEyMC4xOTciLCJwb3J0IjoiMzY3MDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNDViODM1MTktOWM0Zi00MDUyLWExMWItMDJlMDE3YjYzNmQ0IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9hcmtpIiwiaG9zdCI6IiIsInRscyI6IiJ9
ss://YWVzLTI1Ni1nY206QmVhVWY5YzBBRVdINDBQdQ==@154.36.158.197:8388#%F0%9F%87%AF%F0%9F%87%B5%20%E6%97%A5%E6%9C%AC_01
vless://549766c3-fa5f-471e-8031-ffc1f8d5064f@5.35.44.218:8443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=nl17.blog-forme.ru&fp=qq&pbk=bxCIwojWO_edyWgi_QS-BOEnbX-prYu5B1hN_7Skgnc&sid=b6efdae4d829da97&type=tcp&headerType=none#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_01
vless://26cfcdeb-3bdc-4b55-9a7f-a5f8c38aafd8@5b1b23x.pl5.h1clayd.click:443?security=reality&type=xhttp&path=%2Feb278d1e559e&packetEncoding=xudp&sni=5b1b23x.pl5.h1clayd.click&fp=safari&sid=bc67acebb01173a7&pbk=aC3_cPgcJMJUtJkRodl6Al7yDhWa5Gbzyka8xWhbuWw&mode=auto#%F0%9F%87%B5%F0%9F%87%B1%20%E6%B3%A2%E5%85%B0_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.63:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.18:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.45:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_10
vless://4201786b-d99b-4147-a5f0-20d47acddb81@196.196.149.80:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=7aa271t.es1.h1clayd.click&fp=firefox&pbk=ZSmetD4e9QG5CiXhniHg5HJB68L4kwbgAkJmMHtVwEE&sid=42426c882c5fcd41&type=tcp&headerType=none#%F0%9F%87%AA%F0%9F%87%B8%20%E8%A5%BF%E7%8F%AD%E7%89%99_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.81:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_06
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.27:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_07
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.72:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_08
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.99:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_05
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.36:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_03
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.90:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_09
vless://b771804e-a62c-429f-a56c-9f0a452d8f6e@185.122.167.103:59130?encryption=mlkem768x25519plus.native.0rtt.8oUBloz7dC7Dj2HwtrH_gsqKLAfv3sw1me3xB5yBQjA&flow=xtls-rprx-vision&security=reality&sni=nvplm.stg.nvidia.com&fp=chrome&pbk=6Lh48ni3w8oe9QW3xVzNMIE5LU-p5VPHPMCUtVMOmgo&sid=14&type=tcp&headerType=none#%F0%9F%87%AC%F0%9F%87%A7%20%E8%8B%B1%E5%9B%BD_01
vless://cda0862a-0f87-4be9-8ed8-1d0c9e382839@196.245.52.187:443?security=reality&type=xhttp&path=%2F1812842934d4&packetEncoding=xudp&sni=35295cx.us8.h1clayd.click&fp=firefox&sid=9acff4d98e2fbcc6&pbk=LsaTohbE6CqCH9UbYKwIybVXG3E5Wgz_X9czqas2LAI&encryption=none#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_03
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND1AMjAyLjUwLjI1My41NDoxOTk5OQ==#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_04
vless://cda0862a-0f87-4be9-8ed8-1d0c9e382839@196.196.148.63:443?security=reality&sni=717252g.nl8.h1clayd.click&insecure=0&fp=firefox&pbk=PD8Jdlg3xB9QY--jwQjp8PFPzCS8-Oryw6-HWBcHMFU&sid=d3bd772514c87d28&type=grpc&serviceName=204adda7e3da#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_02
```

## 反馈

欢迎在 Issues 反馈失效链接和导入问题，请说明客户端版本及错误提示，不要提交个人密码或私有订阅。

请遵守所在地法律法规及服务条款，谨慎通过公共代理传输敏感信息。

## Shadowrocket 客户端下载

| 平台 | 客户端 | 下载地址 |
| --- | --- | --- |
| iOS / iPadOS | Shadowrocket（小火箭） | [App Store](https://apps.apple.com/us/app/shadowrocket/id932747118) |

App Store 的可用地区和价格以商店页面为准。

