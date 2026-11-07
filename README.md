# 小火箭 Shadowrocket 免费节点

这里整理 Shadowrocket 客户端可导入的节点 URI 和订阅，提供固定入口、导入说明和更新信息。

## 本次更新

- 最近成功整理：2026-11-07 08:05:10
- 节点数量：24
- 最低 TCP 延迟：35 ms（香港）
- 国家/地区：IR、奥地利、德国、意大利、新加坡、日本、波兰、美国、英国、荷兰、香港
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
| 🇺🇸 美国_01 | 美国 | VLESS | 37 ms |
| 🇺🇸 美国_02 | 美国 | VLESS | 38 ms |
| 🇯🇵 日本_01 | 日本 | SS | 152 ms |
| 🇩🇪 德国_01 | 德国 | VLESS | 213 ms |
| 🇸🇬 新加坡_01 | 新加坡 | VLESS | 222 ms |
| 🇮🇹 意大利_01 | 意大利 | SS | 228 ms |
| 🇳🇱 荷兰_01 | 荷兰 | VLESS | 229 ms |
| 🇬🇧 英国_02 | 英国 | VLESS | 233 ms |
| 🇮🇹 意大利_07 | 意大利 | SS | 234 ms |
| 🇳🇱 荷兰_03 | 荷兰 | VLESS | 238 ms |
| 🇦🇹 奥地利_01 | 奥地利 | VLESS | 240 ms |
| 🇬🇧 英国_01 | 英国 | VLESS | 244 ms |
| 🇵🇱 波兰_02 | 波兰 | VLESS | 244 ms |
| 🇵🇱 波兰_01 | 波兰 | VLESS | 247 ms |
| 🇮🇹 意大利_06 | 意大利 | SS | 248 ms |
| 🇮🇹 意大利_04 | 意大利 | SS | 253 ms |
| 🇬🇧 英国_03 | 英国 | VLESS | 253 ms |
| 🇮🇹 意大利_09 | 意大利 | SS | 267 ms |
| 🇮🇹 意大利_02 | 意大利 | SS | 267 ms |
| 🇮🇹 意大利_05 | 意大利 | SS | 272 ms |
| 🇮🇹 意大利_08 | 意大利 | SS | 273 ms |
| 🇮🇹 意大利_03 | 意大利 | SS | 290 ms |
| 🇮🇷 伊朗_01 | IR | VLESS | 311 ms |

[查看完整延迟数据](latency.json)

## 免费节点列表

节点列表最多显示25个，订阅后查看全部节点

```text
vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7Ag6aaZ5rivXzAxIiwiYWRkIjoiNDcuMjQ0LjEyMC4xOTciLCJwb3J0Ijo0NDg2NywiYWlkIjowLCJzY3kiOiJhdXRvIiwibmV0Ijoid3MiLCJ0eXBlIjoibm9uZSIsInRscyI6IiIsImlkIjoiODQ1ZTZiMDgtMjkxOS00MjkwLWFkZTAtNWRjN2RjZWE1OWNhIiwic2tpcC1jZXJ0LXZlcmlmeSI6dHJ1ZSwicGF0aCI6Ii9hcmtpIn0=
vless://5aaa5259-f924-4682-a4a3-149d472a9dcc@jp.sofast.live:52683?encryption=none&security=none&type=tcp&headerType=none#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_01
vless://0afc6426-606c-48e7-bd70-3c424a416842@us22.sofast.live:58011?encryption=none&security=&type=tcp#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_02
ss://YWVzLTI1Ni1nY206QmVhVWY5YzBBRVdINDBQdQ==@154.36.158.197:8388#%F0%9F%87%AF%F0%9F%87%B5%20%E6%97%A5%E6%9C%AC_01
vless://94042dd1-d32a-4797-b88c-dc48459e2b34@100497t.de18.h1clayd.click:443?encryption=none&security=reality&sni=100497t.de18.h1clayd.click&fp=firefox&pbk=x-7K9P2E91DCL-0ONwm14gxDkUseukg98hYzB-1dW1A&sid=5be240e45d3c445c&spx=%2F&type=tcp&headerType=none#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_01
vless://0dedd47d-47b9-4ed1-9c9f-cbeecad57a68@43.163.112.174:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=www.cloudflare.com&fp=chrome&pbk=mXQudYHNu0pebcdk1_qn-UgcmwhjaV7y9UrYu3HX7Rg&sid=0123456789abcdef&type=tcp&headerType=none&host=www.cloudflare.com#%F0%9F%87%B8%F0%9F%87%AC%20%E6%96%B0%E5%8A%A0%E5%9D%A1_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.81:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_01
vless://cda0862a-0f87-4be9-8ed8-1d0c9e382839@5d0319t.nl7.h1clayd.click:443?security=reality&type=tcp&packetEncoding=none&sni=5d0319t.nl7.h1clayd.click&fp=firefox&sid=361d0dd59c70516f&pbk=l-GzBDuNuhnjxoRlZqKvT7jAt_sbVAxhGFsAttO5kXs#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_01
vless://c1b25259-727d-438a-bc7b-bc74f7b9917d@212.69.135.26:8443?security=reality&encryption=none&pbk=FdZlh9FC4ay9OGnKG6K_iNqhz1I3tWDfNZhxrDYuQl8&headerType=none&fp=chrome&type=tcp&flow=xtls-rprx-vision&sni=uk-room05.filesnap.tech&sid=7da3ba09a037e956#%F0%9F%87%AC%F0%9F%87%A7%20%E8%8B%B1%E5%9B%BD_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.99:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_07
vless://b7b8ee80-db83-4276-8c68-87dc88b0b0b5@15d7fft.nl11.h1clayd.click:443?encryption=none&security=reality&sni=15d7fft.nl11.h1clayd.click&pbk=xv6OUZcyzEHXFMTfumuJH-1Rd4NQ0cdmWikek4mm0m4&sid=c71118d9399fb8c2&type=tcp&headerType=none#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_03
vless://db80088c-32a1-4cb8-a907-0f3cb7844152@178.22.31.72:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=at1.japancase.site&fp=firefox&pbk=zEntiD6D81wY__YHPvIw78e09CBIgYkyQ5meIo7c_hg&sid=41ae8e266bc3346f&type=tcp&headerType=none#%F0%9F%87%A6%F0%9F%87%B9%20%E5%A5%A5%E5%9C%B0%E5%88%A9_01
vless://6e10d4e1-1f93-461b-b1c6-90e56c053a11@5.104.74.70:8443?security=reality&type=tcp&sni=uk-room07.filesnap.tech&flow=xtls-rprx-vision&fp=chrome&pbk=48j01Jsa4o8zfmCGEFoVjn-YeALM80-DSG_-nAZUBDM&sid=dbef98744832b751#%F0%9F%87%AC%F0%9F%87%A7%20%E8%8B%B1%E5%9B%BD_01
vless://db80088c-32a1-4cb8-a907-0f3cb7844152@pl3.japancase.site:443?security=reality&type=tcp&packetEncoding=xudp&sni=pl3.japancase.site&fp=chrome&flow=xtls-rprx-vision&sid=5037f0423dc4e4ff&pbk=COvqGpB7lUdZshmbn5zdqiVi81n8Iyha8RbEHtK93xc&encryption=none#%F0%9F%87%B5%F0%9F%87%B1%20%E6%B3%A2%E5%85%B0_02
vless://0806e6e2-e01d-482c-b530-be3b57d486d4@191.217.211.161:443?security=reality&encryption=none&pbk=5H_MmyfvF4SkwS84wTbLmtcZDecXJIJtZ3uisiKQpSM&headerType=none&fp=chrome&type=tcp&flow=xtls-rprx-vision&sni=pl1.song69.fun&sid=0c774b50#%F0%9F%87%B5%F0%9F%87%B1%20%E6%B3%A2%E5%85%B0_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.54:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_06
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.90:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_04
vless://95d0e214-eab0-4701-93ed-fea4f1b56062@prime.jarbook.net:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=prime.jarbook.net&fp=firefox&pbk=oAX7soFKfN3xURgCD26trmjeF-e-eEjW3pBVXuuvW0k&sid=77a8c8c8&type=tcp&headerType=none#%F0%9F%87%AC%F0%9F%87%A7%20%E8%8B%B1%E5%9B%BD_03
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.45:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_09
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.27:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.18:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_05
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.63:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_08
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.36:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_03
vless://f47057d5-120d-4b42-b6d6-30469aef6813@tunell2027.crackerbinam.org:48312?encryption=none&security=reality&sni=www.cloudflare.com&fp=chrome&pbk=d9eM_jy8ztZrOf3DMq1m55VQSo7bnKcG1dRnO9ktJ2Y&sid=902c315efc&type=tcp&headerType=http#%F0%9F%87%AE%F0%9F%87%B7%20%E4%BC%8A%E6%9C%97_01
```

## 反馈

欢迎在 Issues 反馈失效链接和导入问题，请说明客户端版本及错误提示，不要提交个人密码或私有订阅。

请遵守所在地法律法规及服务条款，谨慎通过公共代理传输敏感信息。

## Shadowrocket 客户端下载

| 平台 | 客户端 | 下载地址 |
| --- | --- | --- |
| iOS / iPadOS | Shadowrocket（小火箭） | [App Store](https://apps.apple.com/us/app/shadowrocket/id932747118) |

App Store 的可用地区和价格以商店页面为准。

