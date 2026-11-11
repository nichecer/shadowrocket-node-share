# 小火箭 Shadowrocket 免费节点

这里整理 Shadowrocket 客户端可导入的节点 URI 和订阅，提供固定入口、导入说明和更新信息。

## 本次更新

- 最近成功整理：2026-11-11 08:05:12
- 节点数量：18
- 最低 TCP 延迟：35 ms（香港）
- 国家/地区：加拿大、德国、意大利、法国、波兰、瑞士、美国、荷兰、香港
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
| 🇩🇪 德国_01 | 德国 | VLESS | 159 ms |
| 🇵🇱 波兰_01 | 波兰 | VLESS | 193 ms |
| 🇫🇷 法国_01 | 法国 | VLESS | 206 ms |
| 🇨🇭 瑞士_01 | 瑞士 | VLESS | 239 ms |
| 🇨🇦 加拿大_01 | 加拿大 | VLESS | 251 ms |
| 🇺🇸 美国_01 | 美国 | VLESS | 256 ms |
| 🇳🇱 荷兰_01 | 荷兰 | VLESS | 269 ms |
| 🇮🇹 意大利_01 | 意大利 | SS | 279 ms |
| 🇮🇹 意大利_07 | 意大利 | SS | 288 ms |
| 🇮🇹 意大利_06 | 意大利 | SS | 291 ms |
| 🇮🇹 意大利_02 | 意大利 | SS | 299 ms |
| 🇮🇹 意大利_04 | 意大利 | SS | 299 ms |
| 🇮🇹 意大利_09 | 意大利 | SS | 303 ms |
| 🇮🇹 意大利_10 | 意大利 | SS | 305 ms |
| 🇮🇹 意大利_05 | 意大利 | SS | 308 ms |
| 🇮🇹 意大利_03 | 意大利 | SS | 314 ms |
| 🇮🇹 意大利_08 | 意大利 | SS | 320 ms |

[查看完整延迟数据](latency.json)

## 免费节点列表

节点列表最多显示25个，订阅后查看全部节点

```text
vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7Ag6aaZ5rivXzAxIiwiYWRkIjoiNDcuMjQ0LjEyMC4xOTciLCJwb3J0IjoiMzY3MDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNDViODM1MTktOWM0Zi00MDUyLWExMWItMDJlMDE3YjYzNmQ0IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9hcmtpIiwiaG9zdCI6IiIsInRscyI6IiJ9
vless://c16e8cdb-65dd-4049-bc65-14c051b8a6c6@2.26.251.236:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=mental-deprivation.ru&pbk=1iVMMhJZgXHRY7tRlR-1kypF0YeaBcB7EjcfHRsYZX4&sid=4ff31b18d1bd8227&type=tcp&headerType=none#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_01
vless://b86451af-4c98-4b7d-96e5-16f2e9df1d46@uyt24-k2.miniseries.ir:49673?security=none&type=tcp&headerType=http&path=%2F&host=docs.github.com&packetEncoding=xudp&flow=xtls-rprx-vision&encryption=mlkem768x25519plus.native.0rtt.y5JdNqCVO7XqO9RT4eXLtujAUrOcx_xjNI5us06yMBI#%F0%9F%87%B5%F0%9F%87%B1%20%E6%B3%A2%E5%85%B0_01
vless://52030136-eee3-4675-baae-a50f17b2bb8b@212.69.86.159:8447?security=reality&type=grpc&mode=gun&serviceName=grpc&packetEncoding=none&sni=github.com&fp=chrome&sid=732ef4f5320b5e19&pbk=Pe1-DgXHoB_IGysYKHHhjppQD88mHkzYkqISdSXQxT4#%F0%9F%87%AB%F0%9F%87%B7%20%E6%B3%95%E5%9B%BD_01
vless://4ad9f982-b56a-444a-9684-35ce51307a36@157.22.185.68:2058?&security=reality&flow=xtls-rprx-vision&pbk=lJBsn9ndieTIUBzXkJUhf6O0OE8pm29_z1fUtARwL0s&sid=937255313d6ce673&fp=firefox&sni=www.cloudflare.com&type=tcp&headerType=none&host=www.cloudflare.com&path=%2F#%F0%9F%87%A8%F0%9F%87%AD%20%E7%91%9E%E5%A3%AB_01
vless://b48e1596-e835-4547-bdae-31daadf9ea17@5.53.124.191:8008?security=none&type=xhttp&path=%2F&packetEncoding=xudp&sni=5.53.124.191&mode=auto&encryption=none#%F0%9F%87%A8%F0%9F%87%A6%20%E5%8A%A0%E6%8B%BF%E5%A4%A7_01
vless://4dbf1ade-33f1-40dc-9273-e51babd570fe@104.225.239.235:443?security=reality&type=tcp&packetEncoding=none&sni=portal.citygrainla.com&fp=firefox&flow=xtls-rprx-vision&sid=051f20c2344a2dfd&pbk=BlSccfT5tvDIOS7v9VaPd0ulUNhUdvlMjGiNzDNDUHE#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_01
vless://Fluffy_VPN-zKZUa4Ie@72.56.38.83:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=absolute-disaster.org&fp=firefox&pbk=ZzIetLcQtENjIXQ9XZqFo8p3J81p8Emj0wi51Uy07n8&type=tcp&headerType=none&host=absolute-disaster.org#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.36:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND1AMjAyLjUwLjI1My43MjoxOTk5OQ==#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_07
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.27:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_06
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.99:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0@202.50.253.81:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_04
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.54:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_09
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.18:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_10
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.90:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_05
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.63:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_03
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.45:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_08
```

## 反馈

欢迎在 Issues 反馈失效链接和导入问题，请说明客户端版本及错误提示，不要提交个人密码或私有订阅。

请遵守所在地法律法规及服务条款，谨慎通过公共代理传输敏感信息。

## Shadowrocket 客户端下载

| 平台 | 客户端 | 下载地址 |
| --- | --- | --- |
| iOS / iPadOS | Shadowrocket（小火箭） | [App Store](https://apps.apple.com/us/app/shadowrocket/id932747118) |

App Store 的可用地区和价格以商店页面为准。

