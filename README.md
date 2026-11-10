# 小火箭 Shadowrocket 免费节点

这里整理 Shadowrocket 客户端可导入的节点 URI 和订阅，提供固定入口、导入说明和更新信息。

## 本次更新

- 最近成功整理：2026-11-10 08:05:12
- 节点数量：28
- 最低 TCP 延迟：35 ms（香港）
- 国家/地区：BY、俄罗斯、土耳其、德国、意大利、日本、瑞士、美国、英国、香港
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
| 🇯🇵 日本_01 | 日本 | SS | 59 ms |
| 🇺🇸 美国_03 | 美国 | VLESS | 74 ms |
| 🇺🇸 美国_02 | 美国 | VLESS | 78 ms |
| 🇺🇸 美国_01 | 美国 | VLESS | 142 ms |
| 🇨🇭 瑞士_01 | 瑞士 | VLESS | 192 ms |
| 🇧🇾 白俄罗斯_01 | BY | VLESS | 199 ms |
| 🇨🇭 瑞士_02 | 瑞士 | VLESS | 202 ms |
| 🇩🇪 德国_02 | 德国 | VLESS | 209 ms |
| 🇩🇪 德国_01 | 德国 | VLESS | 219 ms |
| 🇹🇷 土耳其_02 | 土耳其 | VLESS | 225 ms |
| 🇬🇧 英国_02 | 英国 | VLESS | 234 ms |
| 🇩🇪 德国_05 | 德国 | VLESS | 235 ms |
| 🇩🇪 德国_04 | 德国 | VLESS | 236 ms |
| 🇬🇧 英国_01 | 英国 | VLESS | 238 ms |
| 🇷🇺 俄罗斯_02 | 俄罗斯 | VLESS | 241 ms |
| 🇮🇹 意大利_03 | 意大利 | SS | 244 ms |
| 🇮🇹 意大利_08 | 意大利 | SS | 247 ms |
| 🇮🇹 意大利_10 | 意大利 | SS | 253 ms |
| 🇷🇺 俄罗斯_01 | 俄罗斯 | VLESS | 260 ms |
| 🇮🇹 意大利_01 | 意大利 | SS | 264 ms |
| 🇮🇹 意大利_04 | 意大利 | SS | 266 ms |
| 🇮🇹 意大利_07 | 意大利 | SS | 267 ms |
| 🇮🇹 意大利_09 | 意大利 | SS | 274 ms |
| 🇮🇹 意大利_05 | 意大利 | SS | 290 ms |

[查看完整延迟数据](latency.json)

## 免费节点列表

节点列表最多显示25个，订阅后查看全部节点

```text
vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7Ag6aaZ5rivXzAxIiwiYWRkIjoiNDcuMjQ0LjEyMC4xOTciLCJwb3J0IjoyMzAyNiwiYWlkIjowLCJzY3kiOiJhdXRvIiwibmV0Ijoid3MiLCJ0eXBlIjoibm9uZSIsInRscyI6IiIsImlkIjoiYjlkZTFiYzktYmFhNy00MWFjLTg2ZjctY2NkNTk2OTVjYjIxIiwic2tpcC1jZXJ0LXZlcmlmeSI6dHJ1ZSwiaG9zdCI6IjQ3LjI0NC4xMjAuMTk3IiwicGF0aCI6Ii9hcmtpIn0=
ss://YWVzLTI1Ni1nY206QmVhVWY5YzBBRVdINDBQdQ==@154.36.158.197:8388#%F0%9F%87%AF%F0%9F%87%B5%20%E6%97%A5%E6%9C%AC_01
vless://0afc6426-606c-48e7-bd70-3c424a416842@us22.sofast.live:58011?encryption=none&security=none&fp=chrome&type=tcp&headerType=none#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_03
vless://399b6b23-cc40-4831-a494-61948e2df133@jp.sofast.live:52683?encryption=none&security=none&type=tcp&headerType=none#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_02
vless://a715374a-a745-4800-889b-0c864fad5ca0@212.103.62.233:443?security=reality&type=tcp&packetEncoding=xudp&sni=www.apple.com&fp=chrome&flow=xtls-rprx-vision&sid=35d45334668b3ac5&pbk=d9PiZnm10DBNrlT1ixDCgEk0iU1Hv8Jk1xEI4-Oe6jU&encryption=none#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_01
vless://90157e25-cee1-4217-921e-91f300bc1a24@179.43.166.190:443?security=reality&type=tcp&packetEncoding=none&sni=perevodchiki.su&fp=chrome&flow=xtls-rprx-vision&sid=428ef87fd47a3a32&pbk=1vSZjvhZO01oAEH3b7eebR1qF5dLU1Dq2E7xu8pwGSs#%F0%9F%87%A8%F0%9F%87%AD%20%E7%91%9E%E5%A3%AB_01
vless://b7b8ee80-db83-4276-8c68-87dc88b0b0b5@79.182.39.108:443?security=reality&type=tcp&packetEncoding=xudp&sni=15d7fft.nl11.h1clayd.click&fp=firefox&sid=c71118d9399fb8c2&pbk=xv6OUZcyzEHXFMTfumuJH-1Rd4NQ0cdmWikek4mm0m4&encryption=none#%F0%9F%87%A7%F0%9F%87%BE%20%E7%99%BD%E4%BF%84%E7%BD%97%E6%96%AF_01
vless://90157e25-cee1-4217-921e-91f300bc1a24@prvtch.titun.su:443?security=reality&type=tcp&packetEncoding=none&allowInsecure=1&sni=perevodchiki.su&fp=firefox&flow=xtls-rprx-vision&sid=428ef87fd47a3a32&pbk=1vSZjvhZO01oAEH3b7eebR1qF5dLU1Dq2E7xu8pwGSs#%F0%9F%87%A8%F0%9F%87%AD%20%E7%91%9E%E5%A3%AB_02
vless://f8d52ece-fad4-478d-875d-df6eed3befa7@187.7.206.127:61374?security=reality&type=xhttp&path=%2F&host=fl-b2.golangwikito.cfd&packetEncoding=xudp&sni=fl-b2.golangwikito.cfd&fp=firefox&pbk=QrNs0ew7snHqLfpVXS9RAhlRzgAzzGZK9fXmDcx9xHI&mode=packet-up&extra=%7B%22xPaddingBytes%22%3A%22100-500%22%2C%22xmux%22%3A%7B%22maxConnections%22%3A%223%22%7D%7D&encryption=none#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_02
vless://12776e55-6230-48b9-b069-1bb8a04b4237@music.3apes.online:443?security=reality&type=tcp&packetEncoding=xudp&sni=music.3apes.online&fp=qq&flow=xtls-rprx-vision&pbk=q4_o7NvD6vQg4hYsyO29Q6PVufjTJHDUbQTqstre9EQ&encryption=none#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_01
vless://dbf3f074-3b18-43f3-b82a-debd8c879c69@185.246.155.91:10103?encryption=none&flow=xtls-rprx-vision&security=reality&sni=www.apple.com&fp=chrome&pbk=obQkp5VlQpnlt1hRLQ3VfHISYiiISZJyJZAMaIdjCko&sid=6859f5b59e55aa30&type=tcp&headerType=none#%F0%9F%87%B9%F0%9F%87%B7%20%E5%9C%9F%E8%80%B3%E5%85%B6_02
vless://a2e6a96e-395f-4125-917c-77c52c059339@5.104.74.124:8443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=uk-room07.filesnap.tech&fp=firefox&pbk=48j01Jsa4o8zfmCGEFoVjn-YeALM80-DSG_-nAZUBDM&sid=dbef98744832b751&type=tcp&headerType=none#%F0%9F%87%AC%F0%9F%87%A7%20%E8%8B%B1%E5%9B%BD_02
vless://c16e8cdb-65dd-4049-bc65-14c051b8a6c6@2.26.251.236:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=mental-deprivation.ru&pbk=1iVMMhJZgXHRY7tRlR-1kypF0YeaBcB7EjcfHRsYZX4&sid=4ff31b18d1bd8227&type=tcp&headerType=none#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_05
vless://b7b8ee80-db83-4276-8c68-87dc88b0b0b5@79.182.39.109:443?security=reality&type=tcp&packetEncoding=xudp&sni=71b840t.de7.h1clayd.click&fp=firefox&sid=e572b6579ea525d4&pbk=3wFF83gtIA0sXj-6GGCAa--oQbSr0MVUj0FBc-0QmiE&encryption=none#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_04
vless://73b518e9-c8aa-41f1-af51-b8baf24064cb@5.104.74.21:8443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=uk-room05.filesnap.tech&fp=chrome&pbk=FdZlh9FC4ay9OGnKG6K_iNqhz1I3tWDfNZhxrDYuQl8&sid=7da3ba09a037e956&type=tcp&headerType=none#%F0%9F%87%AC%F0%9F%87%A7%20%E8%8B%B1%E5%9B%BD_01
vless://c5f59ef3-9540-49fa-bd1e-c6c2f79df49a@92.243.66.79:443?security=reality&type=tcp&packetEncoding=xudp&sni=ru-mow.probe.geomyip.com&fp=chrome&flow=xtls-rprx-vision&sid=8d03c10b6a874a9c&pbk=siD4oj2gdtLLEphV6fUXb8ueIc2WHVn7msOUhNGPf2o&encryption=none#%F0%9F%87%B7%F0%9F%87%BA%20%E4%BF%84%E7%BD%97%E6%96%AF_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.36:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_03
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.45:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_08
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.63:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_10
vless://Fluffy_VPN-zKZUa4Ie@72.56.38.83:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=absolute-disaster.org&fp=firefox&pbk=ZzIetLcQtENjIXQ9XZqFo8p3J81p8Emj0wi51Uy07n8&type=tcp&headerType=none&host=absolute-disaster.org#%F0%9F%87%B7%F0%9F%87%BA%20%E4%BF%84%E7%BD%97%E6%96%AF_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.27:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.72:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_04
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.99:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_07
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.90:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_09
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.18:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_05
```

## 反馈

欢迎在 Issues 反馈失效链接和导入问题，请说明客户端版本及错误提示，不要提交个人密码或私有订阅。

请遵守所在地法律法规及服务条款，谨慎通过公共代理传输敏感信息。

## Shadowrocket 客户端下载

| 平台 | 客户端 | 下载地址 |
| --- | --- | --- |
| iOS / iPadOS | Shadowrocket（小火箭） | [App Store](https://apps.apple.com/us/app/shadowrocket/id932747118) |

App Store 的可用地区和价格以商店页面为准。

