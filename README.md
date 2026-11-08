# 小火箭 Shadowrocket 免费节点

这里整理 Shadowrocket 客户端可导入的节点 URI 和订阅，提供固定入口、导入说明和更新信息。

## 本次更新

- 最近成功整理：2026-11-08 20:05:12
- 节点数量：26
- 最低 TCP 延迟：32 ms（美国）
- 国家/地区：EE、俄罗斯、德国、意大利、日本、波兰、瑞士、美国、英国、香港
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
| 🇺🇸 美国_03 | 美国 | VLESS | 32 ms |
| 🇺🇸 美国_04 | 美国 | VLESS | 33 ms |
| 🇭🇰 香港_01 | 香港 | VMESS | 34 ms |
| 🇯🇵 日本_01 | 日本 | SS | 58 ms |
| 🇩🇪 德国_03 | 德国 | VLESS | 203 ms |
| 🇨🇭 瑞士_03 | 瑞士 | VLESS | 212 ms |
| 🇺🇸 美国_02 | 美国 | VMESS | 218 ms |
| 🇮🇹 意大利_08 | 意大利 | SS | 229 ms |
| 🇩🇪 德国_02 | 德国 | VLESS | 231 ms |
| 🇬🇧 英国_01 | 英国 | VLESS | 240 ms |
| 🇺🇸 美国_01 | 美国 | VLESS | 242 ms |
| 🇬🇧 英国_02 | 英国 | VLESS | 242 ms |
| 🇮🇹 意大利_09 | 意大利 | SS | 248 ms |
| 🇮🇹 意大利_05 | 意大利 | SS | 248 ms |
| 🇪🇪 爱沙尼亚_01 | EE | VLESS | 262 ms |
| 🇨🇭 瑞士_01 | 瑞士 | VLESS | 267 ms |
| 🇮🇹 意大利_07 | 意大利 | SS | 267 ms |
| 🇮🇹 意大利_03 | 意大利 | SS | 274 ms |
| 🇮🇹 意大利_06 | 意大利 | SS | 280 ms |
| 🇷🇺 俄罗斯_01 | 俄罗斯 | SS | 284 ms |
| 🇨🇭 瑞士_02 | 瑞士 | VLESS | 288 ms |
| 🇮🇹 意大利_02 | 意大利 | SS | 289 ms |
| 🇩🇪 德国_01 | 德国 | VLESS | 292 ms |
| 🇵🇱 波兰_01 | 波兰 | VLESS | 294 ms |
| 🇮🇹 意大利_04 | 意大利 | SS | 299 ms |

[查看完整延迟数据](latency.json)

## 免费节点列表

节点列表最多显示25个，订阅后查看全部节点

```text
vless://399b6b23-cc40-4831-a494-61948e2df133@jp.sofast.live:52683?encryption=none&security=&type=tcp#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_03
vless://0afc6426-606c-48e7-bd70-3c424a416842@us22.sofast.live:58011?encryption=none&security=none&fp=chrome&type=tcp&headerType=none#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_04
vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7Ag6aaZ5rivXzAxIiwiYWRkIjoiNDcuMjQ0LjEyMC4xOTciLCJwb3J0Ijo0NDg2NywiYWlkIjowLCJzY3kiOiJhdXRvIiwibmV0Ijoid3MiLCJ0eXBlIjoibm9uZSIsInRscyI6IiIsImlkIjoiODQ1ZTZiMDgtMjkxOS00MjkwLWFkZTAtNWRjN2RjZWE1OWNhIiwic2tpcC1jZXJ0LXZlcmlmeSI6dHJ1ZSwicGF0aCI6Ii9hcmtpIn0=
ss://YWVzLTI1Ni1nY206QmVhVWY5YzBBRVdINDBQdQ==@154.36.158.197:8388#%F0%9F%87%AF%F0%9F%87%B5%20%E6%97%A5%E6%9C%AC_01
vless://c16e8cdb-65dd-4049-bc65-14c051b8a6c6@2.26.251.236:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=mental-deprivation.ru&fp=firefox&pbk=1iVMMhJZgXHRY7tRlR-1kypF0YeaBcB7EjcfHRsYZX4&sid=4ff31b18d1bd8227&spx=%2F5f73ebfc9ef9c37&type=tcp&headerType=none#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_03
vless://90157e25-cee1-4217-921e-91f300bc1a24@46.19.138.214:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=perevodchiki.su&fp=firefox&pbk=1vSZjvhZO01oAEH3b7eebR1qF5dLU1Dq2E7xu8pwGSs&sid=428ef87fd47a3a32&type=tcp&headerType=none#%F0%9F%87%A8%F0%9F%87%AD%20%E7%91%9E%E5%A3%AB_03
vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzAyIiwiYWRkIjoiMTA0LjE3LjE0Ny4yMjIiLCJwb3J0Ijo4MCwiaWQiOiIwY2Y2ZDk3MC0zZjFkLTRhYWUtYTk4OS05MmE4Zjc2YWUzZGIiLCJhaWQiOjAsInNjeSI6ImF1dG8iLCJuZXQiOiJ3cyIsInR5cGUiOiIiLCJ0bHMiOiIiLCJwYXRoIjoiL3dzIiwiaG9zdCI6InZtZXNzLmxidzY2Ni5kcGRucy5vcmcifQ==
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.99:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_08
vless://0dcefe19-a42a-4d57-96be-83dcbffd425f@200.96.106.2:9889?encryption=none&flow=xtls-rprx-vision&security=reality&sni=tiktok2.transitbp2systems.com&fp=firefox&pbk=GPwEGfRBoztNbcAvfX4ojY9FJ1vaMD3v21tnIrN2xyE&type=tcp&headerType=none#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_02
vless://c6320c2e-15b3-4c3f-9d5a-d371828ea818@5.104.74.69:8443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=uk-room06.filesnap.tech&fp=firefox&pbk=D9IxnCLtXuDLR1yBNZwWdxxbNDfsZgN3C9IsqKgG8Ec&sid=17a35165f9d25923&type=tcp&headerType=none#%F0%9F%87%AC%F0%9F%87%A7%20%E8%8B%B1%E5%9B%BD_01
vless://50a87e21-f0e2-4b53-a787-91adfe748f63@hollandlanzerotte.xyz:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=hollandlanzerotte.xyz&fp=chrome&pbk=EEL-yDPBfol_fiEEM8Pd0zue7SSz5MtZlXEePVak2jc&type=tcp&headerType=none#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_01
vless://6d477a1e-40ec-4e27-940a-d398092e63af@5.104.74.117:8443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=uk-room05.filesnap.tech&fp=firefox&pbk=FdZlh9FC4ay9OGnKG6K_iNqhz1I3tWDfNZhxrDYuQl8&sid=7da3ba09a037e956&type=tcp&headerType=none#%F0%9F%87%AC%F0%9F%87%A7%20%E8%8B%B1%E5%9B%BD_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.81:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_09
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.54:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_05
vless://92b79c22-f68b-4713-8b21-52f264cb92f5@132.243.74.104:2087?encryption=none&flow=xtls-rprx-vision&security=reality&sni=ee.song69.fun&fp=firefox&pbk=HRmmr0Ii4Tr9jPLwratvLhee3_VWFNK47T8AAo7kzww&type=tcp&headerType=none#%F0%9F%87%AA%F0%9F%87%AA%20%E7%88%B1%E6%B2%99%E5%B0%BC%E4%BA%9A_01
vless://90157e25-cee1-4217-921e-91f300bc1a24@179.43.166.190:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=perevodchiki.su&pbk=1vSZjvhZO01oAEH3b7eebR1qF5dLU1Dq2E7xu8pwGSs&sid=428ef87fd47a3a32&type=tcp&headerType=none#%F0%9F%87%A8%F0%9F%87%AD%20%E7%91%9E%E5%A3%AB_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.72:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_07
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.90:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_03
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.36:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_06
ss://YWVzLTI1Ni1nY206Y0NNSmdKVEEzQkE0ODlZVVlyRnE3WEhYU2lTcFdsTGE=@46.17.47.58:18443#%F0%9F%87%B7%F0%9F%87%BA%20%E4%BF%84%E7%BD%97%E6%96%AF_01
vless://4ad9f982-b56a-444a-9684-35ce51307a36@62.109.1.5:2058?encryption=none&flow=xtls-rprx-vision&security=reality&sni=www.cloudflare.com&fp=chrome&pbk=lJBsn9ndieTIUBzXkJUhf6O0OE8pm29_z1fUtARwL0s&sid=937255313d6ce673&type=tcp&headerType=none#%F0%9F%87%A8%F0%9F%87%AD%20%E7%91%9E%E5%A3%AB_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.18:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_02
vless://3bb97d46-789b-4229-88f6-9beb222a4137@176.100.37.154:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=modx-au.bachidze.com&fp=firefox&pbk=EVmZyqEbtEI8d93h1MkFjNVj-DVZRATr9C1Dh1OODmE&type=tcp&headerType=none#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_01
vless://f8d52ece-fad4-478d-875d-df6eed3befa7@cz.pythonmakemigreat.wiki:61374?security=reality&type=xhttp&path=%2F&host=cz.pythonmakemigreat.wiki&packetEncoding=xudp&sni=cz.pythonmakemigreat.wiki&fp=chrome&pbk=QrNs0ew7snHqLfpVXS9RAhlRzgAzzGZK9fXmDcx9xHI&mode=packet-up&extra=%7B%22xPaddingBytes%22%3A%22100-500%22%2C%22xmux%22%3A%7B%22maxConnections%22%3A%223%22%7D%7D&encryption=none#%F0%9F%87%B5%F0%9F%87%B1%20%E6%B3%A2%E5%85%B0_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0@202.50.253.27:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_04
```

## 反馈

欢迎在 Issues 反馈失效链接和导入问题，请说明客户端版本及错误提示，不要提交个人密码或私有订阅。

请遵守所在地法律法规及服务条款，谨慎通过公共代理传输敏感信息。

## Shadowrocket 客户端下载

| 平台 | 客户端 | 下载地址 |
| --- | --- | --- |
| iOS / iPadOS | Shadowrocket（小火箭） | [App Store](https://apps.apple.com/us/app/shadowrocket/id932747118) |

App Store 的可用地区和价格以商店页面为准。

