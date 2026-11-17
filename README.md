# 小火箭 Shadowrocket 免费节点

这里整理 Shadowrocket 客户端可导入的节点 URI 和订阅，提供固定入口、导入说明和更新信息。

## 本次更新

- 最近成功整理：2026-11-17 08:05:13
- 节点数量：35
- 最低 TCP 延迟：36 ms（香港）
- 国家/地区：AL、LT、加拿大、德国、意大利、新加坡、日本、澳大利亚、瑞典、瑞士、美国、英国、荷兰、西班牙、越南、香港
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
| 🇭🇰 香港_02 | 香港 | VMESS | 36 ms |
| 🇭🇰 香港_01 | 香港 | VLESS | 37 ms |
| 🇸🇬 新加坡_02 | 新加坡 | VLESS | 138 ms |
| 🇦🇺 澳大利亚_01 | 澳大利亚 | VLESS | 144 ms |
| 🇻🇳 越南_01 | 越南 | VLESS | 146 ms |
| 🇨🇦 加拿大_01 | 加拿大 | VLESS | 190 ms |
| 🇯🇵 日本_01 | 日本 | SS | 194 ms |
| 🇨🇭 瑞士_01 | 瑞士 | VLESS | 197 ms |
| 🇩🇪 德国_05 | 德国 | SS | 204 ms |
| 🇩🇪 德国_03 | 德国 | VLESS | 207 ms |
| 🇳🇱 荷兰_04 | 荷兰 | VLESS | 209 ms |
| 🇩🇪 德国_02 | 德国 | SS | 211 ms |
| 🇳🇱 荷兰_02 | 荷兰 | VLESS | 213 ms |
| 🇺🇸 美国_01 | 美国 | VLESS | 224 ms |
| 🇩🇪 德国_01 | 德国 | VLESS | 225 ms |
| 🇪🇸 西班牙_01 | 西班牙 | VLESS | 225 ms |
| 🇱🇹 立陶宛_01 | LT | VLESS | 229 ms |
| 🇮🇹 意大利_07 | 意大利 | SS | 230 ms |
| 🇮🇹 意大利_02 | 意大利 | SS | 231 ms |
| 🇪🇸 西班牙_03 | 西班牙 | VLESS | 231 ms |
| 🇮🇹 意大利_05 | 意大利 | SS | 235 ms |
| 🇮🇹 意大利_01 | 意大利 | SS | 237 ms |
| 🇸🇪 瑞典_01 | 瑞典 | VLESS | 242 ms |
| 🇪🇸 西班牙_02 | 西班牙 | VLESS | 247 ms |
| 🇬🇧 英国_01 | 英国 | VLESS | 249 ms |

[查看完整延迟数据](latency.json)

## 免费节点列表

节点列表最多显示25个，订阅后查看全部节点

```text
vmess://eyJhZGQiOiI0Ny4yNDQuMTIwLjE5NyIsImFpZCI6MCwiYWxsb3dfaW5zZWN1cmUiOiIxIiwiYWxsb3dJbnNlY3VyZSI6IjEiLCJpZCI6Ijg0NWU2YjA4LTI5MTktNDI5MC1hZGUwLTVkYzdkY2VhNTljYSIsImluc2VjdXJlIjoiMSIsIm5ldCI6IndzIiwicGF0aCI6Ii9hcmtpP2VkPTIwNDgiLCJwb3J0Ijo0NDg2NywicHMiOiLwn4et8J+HsCDpppnmuK9fMDIiLCJzZWN1cml0eSI6ImF1dG8ifQ==
vless://8b17beac-b143-447d-aa68-14cbb121a602@8.217.1.203:8443?security=reality&type=tcp&packetEncoding=xudp&sni=www.apple.com&fp=chrome&flow=xtls-rprx-vision&sid=0bf55f64&pbk=74P0QFvaK6B13rHsxR_t0lqRlg4YLuORD4VaHr5Jd38&encryption=none#%F0%9F%87%AD%F0%9F%87%B0%20%E9%A6%99%E6%B8%AF_01
vless://57beeeb0-03fc-4fc9-94da-7604488a7134@zfapi.zalolink.com:30322?security=reality&type=tcp&packetEncoding=xudp&sni=psstatic.cdn.bcebos.com&fp=chrome&flow=xtls-rprx-vision&sid=6a60e7e382d6&pbk=5gncThwqPFzLu23WO3mPTEhG7-KgVYlGVvveHjM2SUo#%F0%9F%87%B8%F0%9F%87%AC%20%E6%96%B0%E5%8A%A0%E5%9D%A1_02
vless://57beeeb0-03fc-4fc9-94da-7604488a7134@zfapi.zalolink.com:54528?encryption=none&flow=xtls-rprx-vision&security=reality&sni=www.apple.com&fp=ios&pbk=7GvJVbR6BRhtrc8-rcZvB8qTFUF1LPeM_MmoZ04mBxo&sid=54cca3c1c1c7&type=tcp&headerType=none&host=www.apple.com&path=%2F#%F0%9F%87%A6%F0%9F%87%BA%20%E6%BE%B3%E5%A4%A7%E5%88%A9%E4%BA%9A_01
vless://57beeeb0-03fc-4fc9-94da-7604488a7134@zfapi.zalolink.com:55688?security=reality&type=tcp&packetEncoding=none&sni=bilibili-vn.biliimg.com&fp=chrome&flow=xtls-rprx-vision&sid=865c1b2c&pbk=6dqd0hqbC0bht9RtsYamvlYdMpxyUbk7uXw0xtO8DzQ#%F0%9F%87%BB%F0%9F%87%B3%20%E8%B6%8A%E5%8D%97_01
vless://128ce9ab-63bc-48dc-92ca-1b5426a9eb46@23.155.44.105:443?security=reality&type=tcp&packetEncoding=none&sni=app.flyprotect.ca&fp=firefox&flow=xtls-rprx-vision&sid=70f75668dc5914b3&pbk=HE1CGzI0QBqhMRUsHqq_9v4Mj3M5dkluFmfyMBH_7kM#%F0%9F%87%A8%F0%9F%87%A6%20%E5%8A%A0%E6%8B%BF%E5%A4%A7_01
ss://YWVzLTI1Ni1nY206QmVhVWY5YzBBRVdINDBQdQ==@154.36.158.197:8388#%F0%9F%87%AF%F0%9F%87%B5%20%E6%97%A5%E6%9C%AC_01
vless://49db4ce7-ad48-41a3-9b6f-4c6dabd94504@179.43.170.73:443?security=reality&type=xhttp&path=%2F&host=forge.lakemont.top&packetEncoding=none&sni=forge.lakemont.top&fp=firefox&sid=80e81a0a&pbk=oI8uBtOZSUZ6paMGUrKhdMOuvQ08EyPfWpCfnveBjV8#%F0%9F%87%A8%F0%9F%87%AD%20%E7%91%9E%E5%A3%AB_01
ss://MjAyMi1ibGFrZTMtY2hhY2hhMjAtcG9seTEzMDU6OHlPM0FOV2VmdXVHczFsUktYRUNRQTFGRWh4bFdGVjJwcFFNY0JhWm81WT0=@47.254.175.2:443#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_05
vless://549766c3-fa5f-471e-8031-ffc1f8d5064f@95.85.232.83:2087?encryption=none&security=reality&sni=trips.blog-forme.ru&fp=edge&pbk=mbi4BZAuiq_L6pfhG2xxWmtosq0Z1Pzf18fvNSWKMxY&sid=3258252d44113e23&type=xhttp&host=trips.blog-forme.ru&path=%2Fv2%2Fsync%2F6e9367#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_03
vless://cda0862a-0f87-4be9-8ed8-1d0c9e382839@79.182.39.131:443?security=reality&sni=717252g.nl8.h1clayd.click&insecure=0&fp=chrome&pbk=PD8Jdlg3xB9QY--jwQjp8PFPzCS8-Oryw6-HWBcHMFU&sid=d3bd772514c87d28&type=grpc&serviceName=204adda7e3da#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_04
ss://MjAyMi1ibGFrZTMtY2hhY2hhMjAtcG9seTEzMDU6OHlPM0FOV2VmdXVHczFsUktYRUNRQTFGRWh4bFdGVjJwcFFNY0JhWm81WT0=@47.254.169.3:443#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_02
vless://cda0862a-0f87-4be9-8ed8-1d0c9e382839@f0d7aft.nl13.h1clayd.click:443?security=reality&type=tcp&packetEncoding=xudp&sni=f0d7aft.nl13.h1clayd.click&fp=chrome&sid=8956c57cb4c4f8d2&pbk=kkCGiCQCKnkozJR1KKCRNtmdBECmThCgI9VSv7iDcWI&encryption=none#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_02
vless://ccb8ff48-3934-4250-b4ec-bb76b95d154f@pl3.fox-lisa.ru:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=pl3.fox-lisa.ru&fp=firefox&pbk=NaCZ-sS4poEbFwKmD7ePAVyc5OhHxsD9nkAStjXkoWs&sid=027af64166562b09&type=tcp&headerType=none#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_01
vless://146d567c-6335-4e63-a8aa-7ec068642440@130.78.31.25:443?security=reality&type=xhttp&path=%2Fxhttp&host=pl2.obxodvpn.us&packetEncoding=xudp&sni=pl2.obxodvpn.us&fp=firefox&sid=5c42ed8c&pbk=fDrDDz_GCqhDgG8kMxWXk2vRuyfBHTTNwVa7k7nJHgw&mode=packet-up&encryption=none#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_01
vless://e75ad2eb-6c1f-45ce-8023-f5f10875df66@edge-d6d4b0609348.eu-cdn391.com:443?encryption=none&security=reality&sni=edge-d6d4b0609348.eu-cdn391.com&fp=firefox&pbk=aDqvXSCQ_psc3zy9P_5sfy4bVXMVZsyUEIiyTgq-OlA&sid=1a083bf915dd9164&type=xhttp&host=edge-d6d4b0609348.eu-cdn391.com&path=%2Fworkspace%2F52eac742269e976f&mode=stream-one&extra=%7B%22xmux%22%3A%7B%22cMaxReuseTimes%22%3A0%2C%22maxConcurrency%22%3A0%2C%22maxConnections%22%3A2%2C%22hKeepAlivePeriod%22%3A0%2C%22hMaxRequestTimes%22%3A%22600-900%22%2C%22hMaxReusableSecs%22%3A%221800-3000%22%7D%7D#%F0%9F%87%AA%F0%9F%87%B8%20%E8%A5%BF%E7%8F%AD%E7%89%99_01
vless://a30903dc-1bf0-4be5-8b1b-603a3a56211c@84.32.248.124:443?security=reality&type=tcp&packetEncoding=xudp&sni=net-io-api.galioncc.com&fp=firefox&sid=a7d309e4c16b825f&pbk=drl7nndYdfzZY1aQ0eUAWmNV0nsHig2uDnu9siy9biQ&encryption=none#%F0%9F%87%B1%F0%9F%87%B9%20%E7%AB%8B%E9%99%B6%E5%AE%9B_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.99:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_07
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.45:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_02
vless://4201786b-d99b-4147-a5f0-20d47acddb81@196.196.149.81:443?security=reality&type=tcp&packetEncoding=xudp&sni=7aa271t.es1.h1clayd.click&fp=firefox&flow=xtls-rprx-vision&sid=42426c882c5fcd41&pbk=ZSmetD4e9QG5CiXhniHg5HJB68L4kwbgAkJmMHtVwEE&encryption=none#%F0%9F%87%AA%F0%9F%87%B8%20%E8%A5%BF%E7%8F%AD%E7%89%99_03
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.18:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_05
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.36:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_01
vless://8197b9b9-8945-460f-99c9-325ef8a8a7c3@195.72.62.7:443?security=reality&type=tcp&packetEncoding=none&sni=fexzoo.net&fp=firefox&flow=xtls-rprx-vision&sid=2a67748b0d641e16&pbk=GQC47B2ZbBygpgJap7Em9lZmCZZkzlckiadXWXlVxGU#%F0%9F%87%B8%F0%9F%87%AA%20%E7%91%9E%E5%85%B8_01
vless://2208b003-78b1-453c-b5ca-ce847ff0efd6@3b3377x.es5.h1clayd.click:443?security=reality&type=xhttp&path=%2F&packetEncoding=xudp&sni=3b3377x.es5.h1clayd.click&fp=firefox&sid=dfd8d9d06bd8ce60&pbk=N4cPAkl5hvo7SchiN_WHEwLBLICAXGtq85BP7S_6ORI#%F0%9F%87%AA%F0%9F%87%B8%20%E8%A5%BF%E7%8F%AD%E7%89%99_02
vless://a30903dc-1bf0-4be5-8b1b-603a3a56211c@84.32.54.237:443?security=reality&type=tcp&packetEncoding=xudp&sni=rly-gw-cfg.galioncc.com&fp=firefox&sid=868419504747f6de&pbk=drl7nndYdfzZY1aQ0eUAWmNV0nsHig2uDnu9siy9biQ&encryption=none#%F0%9F%87%AC%F0%9F%87%A7%20%E8%8B%B1%E5%9B%BD_01
```

## 反馈

欢迎在 Issues 反馈失效链接和导入问题，请说明客户端版本及错误提示，不要提交个人密码或私有订阅。

请遵守所在地法律法规及服务条款，谨慎通过公共代理传输敏感信息。

## Shadowrocket 客户端下载

| 平台 | 客户端 | 下载地址 |
| --- | --- | --- |
| iOS / iPadOS | Shadowrocket（小火箭） | [App Store](https://apps.apple.com/us/app/shadowrocket/id932747118) |

App Store 的可用地区和价格以商店页面为准。

