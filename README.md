# 小火箭 Shadowrocket 免费节点

这里整理 Shadowrocket 客户端可导入的节点 URI 和订阅，提供固定入口、导入说明和更新信息。

## 本次更新

- 最近成功整理：2026-11-06 08:05:10
- 节点数量：17
- 最低 TCP 延迟：32 ms（美国）
- 国家/地区：IR、意大利、日本、法国、美国
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
| 🇺🇸 美国_01 | 美国 | VLESS | 32 ms |
| 🇺🇸 美国_02 | 美国 | VLESS | 33 ms |
| 🇫🇷 法国_02 | 法国 | VLESS | 187 ms |
| 🇮🇹 意大利_03 | 意大利 | SS | 228 ms |
| 🇫🇷 法国_01 | 法国 | VLESS | 230 ms |
| 🇮🇷 伊朗_01 | IR | VLESS | 231 ms |
| 🇮🇹 意大利_08 | 意大利 | SS | 235 ms |
| 🇮🇹 意大利_04 | 意大利 | SS | 247 ms |
| 🇮🇹 意大利_09 | 意大利 | SS | 252 ms |
| 🇮🇹 意大利_07 | 意大利 | SS | 270 ms |
| 🇮🇹 意大利_05 | 意大利 | SS | 274 ms |
| 🇮🇹 意大利_02 | 意大利 | SS | 275 ms |
| 🇮🇹 意大利_10 | 意大利 | SS | 276 ms |
| 🇮🇹 意大利_06 | 意大利 | SS | 278 ms |
| 🇮🇹 意大利_01 | 意大利 | SS | 297 ms |
| 🇯🇵 日本_01 | 日本 | SS | 736 ms |
| 🇮🇷 伊朗_02 | IR | VLESS | 1306 ms |

[查看完整延迟数据](latency.json)

## 免费节点列表

节点列表最多显示25个，订阅后查看全部节点

```text
vless://5aaa5259-f924-4682-a4a3-149d472a9dcc@jp.sofast.live:52683?encryption=none&security=&type=tcp#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_01
vless://0afc6426-606c-48e7-bd70-3c424a416842@us22.sofast.live:58011?encryption=none&security=none&fp=chrome&type=tcp&headerType=none#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_02
vless://ffaa2141-759b-424f-f28c-23dbeae00f10@122.8.47.4:8443?security=reality&type=grpc&mode=gun&serviceName=TunService&packetEncoding=xudp&sni=www.philips.com&fp=chrome&pbk=Sq7mtLmaanwsTVNBR9gU7ECU87ftrb_wFGRLLNRBlmQ&encryption=none#%F0%9F%87%AB%F0%9F%87%B7%20%E6%B3%95%E5%9B%BD_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.18:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_03
vless://a289c660-1b12-432b-a06c-c2ae469272b0@62.210.70.194:37783?encryption=mlkem768x25519plus.native.0rtt.I5ge5qOTUhKE8xpufKI84yktvqqG9qkViwYe20uFZUyGwbnK7QMv6Tih0subInSmZTyem1QFG1CDFvGfgMBu3Yw1ryNJfGjMnALAqZawBoukaROcTzxXmFAzuejDalyhxxfNJkeUefW3biOHIzcu_AairYSvJ8l_iHJpKVEKXZWPQWiq-tm_nPJz_oDDhFElaCHKnCslodSen2M6afQQ0HYKc6nKZmZwc1cHG1GKW9xHx6CBfLhFVOhT62tCvbxShul1NJgL-shELnovAtS1aHBFQKDOIiJYC7Ww0awUfsyGIFhnJIhdnqFHnkG7sOcdiWiH-ZkQ11p065zAWEQ14HTOi-aqCAsnWNwdRxwj1_qlArYd3nNF1dXKARRikbMFutC5GyyvSJxk7XwHRGWoK_q6_zK2amtIrsin6tov5kKs3UqywFJMJ2rMtgYZXpvK_TdXumLGUimIq9vFW7idpbMlv9F84NY8UbtrkyB87IQwdKqbtnuOMzxkYik-i9N5vaKcXLSdOGRpMgAKSMt5NbSyllcEh6qUTZoVb_h8ZmYij8csvbGWxodCj1WvOGoRtGGnTSpWMdG3X3ZxXlhNQ6tpIPGTfxkzjPtRjHQDcqm0fgrLjWONnkGxMQRO-Wi50vzNPzW9Vuy5BlZszdGqpjLNRLGw24JTAYKXpxiUkTxUxhO3LRC8kMvGVBgxjImwmwev1IqfPiVIMSwhV0FAMNw27nALh0qyPnNLbFpbTFuTL6V83YypFDl1yahns_AE86ufKnSAaSs_0PwMM_ZDfkhE7nRKCygaD9UjWWygRWq6fZarZahcTAqrZUYPXWxqDsrE7VRYO3ch70AHi6ZXTyKR1YcyM0Kiw3S0kxpjbtWReOJ3lXwry-BjcusDKhRsAxErDIBD6IFuY5ucRTtpfPoNgiq7rSFG8SFNvTe-_wh39Bwjj3JeRnw6kzujiKgxGiAH9GYm6LVvG2ljdWacJjSyoDE6mbFwgRCGdDh4h6eMCPs7hjQmNByx76lb0PYt-BuD9xCfiEFMoKJzTjWUvOy1gbmOrjY5xtkkByo8PCS40YRqXiYQ0Me9U5t_lsdxrvO6f7ajFHBNp_IiQOAstWu9UKC2hiABnVWbHaTFeQSp0tAx9rm5vehC0_a3EAHByGzGFUQ-QWpUO5mvGzZKpPVQrgovg2GsgepxgOMymOgv2CbLNKiwAJJyjDe5d5yXiueH3ZdppJqepXrOGuGOn3e-8RKVu3I-nCp-aMS769Yl5mmS8BYOpxW3HseSzZZMIta4hjsa7hqSgmycflvLV5x-8bM9iBFZ7iOey9oYyEkEbFN-6-Alh2dQfopjE2QNFqW6KatBKHXKHNVoayoc4ZegDKPNAEnAo9wIHkBpDFC-fVoCkGMDcRSeNbF67keruuE0xfMA8ltaklEyRwMcxVQwMhILq6vKlzpJF9OJMGVg5amP_-i4NAsKEfC8Ayp61gByykoWKTWkuLAEAYtXXNIfQ9BPvZca1BITgpC69lapO4SH1UAZ4KRxOTVtbHES_GsjM_lkTv940p3IDkG7jfvxIfY_Q9C3QVbkilRpPvg&security=reality&sni=www.yahoo.com&fp=chrome&pbk=tQeEamJmYVUUfjRLX7ETvMnPj4DrHzRhR5TI684oYgg&sid=21569dd6&type=xhttp&path=%2FOCrp5Ajs&mode=auto#%F0%9F%87%AB%F0%9F%87%B7%20%E6%B3%95%E5%9B%BD_01
vless://f47057d5-120d-4b42-b6d6-30469aef6813@tunell2027.crackerbinam.org:48312?encryption=none&security=reality&sni=www.cloudflare.com&fp=chrome&pbk=d9eM_jy8ztZrOf3DMq1m55VQSo7bnKcG1dRnO9ktJ2Y&sid=902c315efc&type=tcp&headerType=http#%F0%9F%87%AE%F0%9F%87%B7%20%E4%BC%8A%E6%9C%97_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.90:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_08
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.36:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_04
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.81:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_09
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.54:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_07
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.45:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_05
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.63:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.99:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_10
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0@202.50.253.72:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_06
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.27:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_01
ss://YWVzLTI1Ni1nY206QmVhVWY5YzBBRVdINDBQdQ==@154.36.158.197:8388#%F0%9F%87%AF%F0%9F%87%B5%20%E6%97%A5%E6%9C%AC_01
vless://e3e0e1c3-599e-4ae1-8ad4-d9e90effacc4@198.16.113.219:8443?security=reality&type=tcp&packetEncoding=xudp&sni=www.apple.com&fp=chrome&flow=xtls-rprx-vision&sid=69984b9e02545831&pbk=8NkTRxC5Q7bptx-8ADobkuhPK-ZN0kEEbzv6tCFGMzE#%F0%9F%87%AE%F0%9F%87%B7%20%E4%BC%8A%E6%9C%97_02
```

## 反馈

欢迎在 Issues 反馈失效链接和导入问题，请说明客户端版本及错误提示，不要提交个人密码或私有订阅。

请遵守所在地法律法规及服务条款，谨慎通过公共代理传输敏感信息。

## Shadowrocket 客户端下载

| 平台 | 客户端 | 下载地址 |
| --- | --- | --- |
| iOS / iPadOS | Shadowrocket（小火箭） | [App Store](https://apps.apple.com/us/app/shadowrocket/id932747118) |

App Store 的可用地区和价格以商店页面为准。

