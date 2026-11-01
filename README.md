# 小火箭 Shadowrocket 免费节点

这里整理 Shadowrocket 客户端可导入的节点 URI 和订阅，提供固定入口、导入说明和更新信息。

## 本次更新

- 最近成功整理：2026-11-01 20:05:09
- 节点数量：22
- 最低 TCP 延迟：35 ms（美国）
- 国家/地区：EE、加拿大、意大利、法国、波兰、瑞典、美国、荷兰
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
| 🇺🇸 美国_02 | 美国 | VLESS | 35 ms |
| 🇺🇸 美国_03 | 美国 | VLESS | 36 ms |
| 🇳🇱 荷兰_01 | 荷兰 | VLESS | 161 ms |
| 🇫🇷 法国_01 | 法国 | VLESS | 192 ms |
| 🇳🇱 荷兰_03 | 荷兰 | VLESS | 200 ms |
| 🇳🇱 荷兰_02 | 荷兰 | VLESS | 211 ms |
| 🇳🇱 荷兰_06 | 荷兰 | VLESS | 212 ms |
| 🇨🇦 加拿大_01 | 加拿大 | VLESS | 217 ms |
| 🇸🇪 瑞典_01 | 瑞典 | VLESS | 221 ms |
| 🇳🇱 荷兰_04 | 荷兰 | VLESS | 247 ms |
| 🇵🇱 波兰_01 | 波兰 | VLESS | 263 ms |
| 🇮🇹 意大利_09 | 意大利 | SS | 306 ms |
| 🇮🇹 意大利_03 | 意大利 | SS | 317 ms |
| 🇮🇹 意大利_06 | 意大利 | SS | 321 ms |
| 🇮🇹 意大利_04 | 意大利 | SS | 323 ms |
| 🇮🇹 意大利_07 | 意大利 | SS | 324 ms |
| 🇮🇹 意大利_01 | 意大利 | SS | 324 ms |
| 🇮🇹 意大利_05 | 意大利 | SS | 338 ms |
| 🇮🇹 意大利_02 | 意大利 | SS | 348 ms |
| 🇮🇹 意大利_08 | 意大利 | SS | 378 ms |
| 🇳🇱 荷兰_05 | 荷兰 | VLESS | 454 ms |
| 🇪🇪 爱沙尼亚_01 | EE | VLESS | 590 ms |

[查看完整延迟数据](latency.json)

## 免费节点列表

节点列表最多显示25个，订阅后查看全部节点

```text
vless://0afc6426-606c-48e7-bd70-3c424a416842@us22.sofast.live:58011?encryption=none&type=tcp#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_02
vless://399b6b23-cc40-4831-a494-61948e2df133@jp.sofast.live:52683?encryption=none&type=tcp#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_03
vless://85fe968d-fbb5-40dc-8422-30635eccb149@c20s5.portablesubmarines.com:443?security=reality&type=tcp&packetEncoding=xudp&sni=portal.citygrainla.com&fp=chrome&flow=xtls-rprx-vision&sid=051f20c2344a2dfd&pbk=BlSccfT5tvDIOS7v9VaPd0ulUNhUdvlMjGiNzDNDUHE&encryption=none#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_01
vless://a289c660-1b12-432b-a06c-c2ae469272b0@62.210.70.194:37783?security=reality&type=xhttp&path=%2FOCrp5Ajs&packetEncoding=xudp&sni=www.yahoo.com&fp=firefox&sid=21569dd6&pbk=tQeEamJmYVUUfjRLX7ETvMnPj4DrHzRhR5TI684oYgg&encryption=mlkem768x25519plus.native.0rtt.I5ge5qOTUhKE8xpufKI84yktvqqG9qkViwYe20uFZUyGwbnK7QMv6Tih0subInSmZTyem1QFG1CDFvGfgMBu3Yw1ryNJfGjMnALAqZawBoukaROcTzxXmFAzuejDalyhxxfNJkeUefW3biOHIzcu_AairYSvJ8l_iHJpKVEKXZWPQWiq-tm_nPJz_oDDhFElaCHKnCslodSen2M6afQQ0HYKc6nKZmZwc1cHG1GKW9xHx6CBfLhFVOhT62tCvbxShul1NJgL-shELnovAtS1aHBFQKDOIiJYC7Ww0awUfsyGIFhnJIhdnqFHnkG7sOcdiWiH-ZkQ11p065zAWEQ14HTOi-aqCAsnWNwdRxwj1_qlArYd3nNF1dXKARRikbMFutC5GyyvSJxk7XwHRGWoK_q6_zK2amtIrsin6tov5kKs3UqywFJMJ2rMtgYZXpvK_TdXumLGUimIq9vFW7idpbMlv9F84NY8UbtrkyB87IQwdKqbtnuOMzxkYik-i9N5vaKcXLSdOGRpMgAKSMt5NbSyllcEh6qUTZoVb_h8ZmYij8csvbGWxodCj1WvOGoRtGGnTSpWMdG3X3ZxXlhNQ6tpIPGTfxkzjPtRjHQDcqm0fgrLjWONnkGxMQRO-Wi50vzNPzW9Vuy5BlZszdGqpjLNRLGw24JTAYKXpxiUkTxUxhO3LRC8kMvGVBgxjImwmwev1IqfPiVIMSwhV0FAMNw27nALh0qyPnNLbFpbTFuTL6V83YypFDl1yahns_AE86ufKnSAaSs_0PwMM_ZDfkhE7nRKCygaD9UjWWygRWq6fZarZahcTAqrZUYPXWxqDsrE7VRYO3ch70AHi6ZXTyKR1YcyM0Kiw3S0kxpjbtWReOJ3lXwry-BjcusDKhRsAxErDIBD6IFuY5ucRTtpfPoNgiq7rSFG8SFNvTe-_wh39Bwjj3JeRnw6kzujiKgxGiAH9GYm6LVvG2ljdWacJjSyoDE6mbFwgRCGdDh4h6eMCPs7hjQmNByx76lb0PYt-BuD9xCfiEFMoKJzTjWUvOy1gbmOrjY5xtkkByo8PCS40YRqXiYQ0Me9U5t_lsdxrvO6f7ajFHBNp_IiQOAstWu9UKC2hiABnVWbHaTFeQSp0tAx9rm5vehC0_a3EAHByGzGFUQ-QWpUO5mvGzZKpPVQrgovg2GsgepxgOMymOgv2CbLNKiwAJJyjDe5d5yXiueH3ZdppJqepXrOGuGOn3e-8RKVu3I-nCp-aMS769Yl5mmS8BYOpxW3HseSzZZMIta4hjsa7hqSgmycflvLV5x-8bM9iBFZ7iOey9oYyEkEbFN-6-Alh2dQfopjE2QNFqW6KatBKHXKHNVoayoc4ZegDKPNAEnAo9wIHkBpDFC-fVoCkGMDcRSeNbF67keruuE0xfMA8ltaklEyRwMcxVQwMhILq6vKlzpJF9OJMGVg5amP_-i4NAsKEfC8Ayp61gByykoWKTWkuLAEAYtXXNIfQ9BPvZca1BITgpC69lapO4SH1UAZ4KRxOTVtbHES_GsjM_lkTv940p3IDkG7jfvxIfY_Q9C3QVbkilRpPvg#%F0%9F%87%AB%F0%9F%87%B7%20%E6%B3%95%E5%9B%BD_01
vless://f5e70ce3-cfb4-4df1-b25c-d19bfae627c0@185.14.30.98:8443?security=reality&type=tcp&packetEncoding=xudp&sni=twitch.tv&fp=chrome&flow=xtls-rprx-vision&sid=1433a38abea1191c&pbk=Q0dPyF2hFWgxL7hxntJWJammcb6zcRCyA-NOiOFrsAo#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_03
vless://f8d52ece-fad4-478d-875d-df6eed3befa7@fr.golangwikito.cfd:443?security=reality&type=tcp&packetEncoding=xudp&sni=fr.golangwikito.cfd&fp=firefox&flow=xtls-rprx-vision&sid=e6d589857d1cec5e&pbk=isYQuhKDrgc7IQ7G0LHywFnt57wffrkZ-er18DkVsBA#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_02
vless://07680ffb-0666-4836-b6ad-ec0de62bc38f@app-mi-26.spbstudentlife.com:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=assets-mi-26.spbstudentlife.com&fp=chrome&pbk=cYtAkO6yUCuRTxHvF8EH76bybk1yfS005KLls-at2yc&sid=a7856800c2deb7b2&type=tcp&headerType=none#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_06
vless://e5cc16a6-ea42-46b2-82ae-ad2157e1641b@172.67.75.172:8080?security=none&type=ws&path=%2Fsg-melbi&host=hhlfy.twiladaphne.ndjp.net&packetEncoding=xudp&sni=hhlfy.twiladaphne.ndjp.net#%F0%9F%87%A8%F0%9F%87%A6%20%E5%8A%A0%E6%8B%BF%E5%A4%A7_01
vless://50a87e21-f0e2-4b53-a787-91adfe748f63@swedenafteraventura.space:443?security=reality&encryption=none&pbk=TyuIIquHoesD9YwMQJHda0YZ3Hy9Dh123dQ00iGK0QY&headerType=none&fp=chrome&type=tcp&flow=xtls-rprx-vision&sni=swedenafteraventura.space#%F0%9F%87%B8%F0%9F%87%AA%20%E7%91%9E%E5%85%B8_01
vless://Fluffy_VPN-Oth8rOq3@104.171.135.229:443?&security=reality&flow=xtls-rprx-vision&pbk=mpo4BIcoWiMXAQGt5a8IJ4MFkPJQyLC50dO_bXzC7z0&fp=firefox&sni=absolute-disaster.org&type=tcp&headerType=none&host=absolute-disaster.org&path=%2F#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_04
vless://056405e8-de9f-4d0d-8145-956f13cc34da@79.182.39.37:27591?encryption=none&security=reality&sni=www.samsung.com&fp=chrome&pbk=LY0H47MWx87_L_JBzxFAuTzKZB53U7MrZQK8-dNnMxM&sid=6c5c7900406a1ae7&type=tcp&headerType=none&host=www.samsung.com&path=%2F#%F0%9F%87%B5%F0%9F%87%B1%20%E6%B3%A2%E5%85%B0_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND1AMjAyLjUwLjI1My40NToxOTk5OQ==#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_09
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0@202.50.253.27:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_03
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.81:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_06
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0@202.50.253.63:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_04
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND1AMjAyLjUwLjI1My43MjoxOTk5OQ==#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_07
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.18:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.36:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_05
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.54:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND1AMjAyLjUwLjI1My45MDoxOTk5OQ==#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_08
vless://b2847c3b-5278-4b06-9c66-bc919d2dfec7@186.246.9.29:443?security=reality&type=tcp&packetEncoding=xudp&sni=wordpress.com&fp=firefox&sid=50ad5564&pbk=MPNMomAMn_lu9YMYjD2jAQWrI-rTM4hj9Jgg9d6qzTA#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_05
vless://f90b7d43-69e2-4b46-a672-8029bc6796a2@79.182.39.232:25895?encryption=none&security=reality&sni=www.samsung.com&fp=firefox&pbk=jOVKSP-bS9OkILJ8Epz8hadh6qhavCrOiJYeF0NCn0k&sid=a73f0410d728c823&type=tcp&headerType=none#%F0%9F%87%AA%F0%9F%87%AA%20%E7%88%B1%E6%B2%99%E5%B0%BC%E4%BA%9A_01
```

## 反馈

欢迎在 Issues 反馈失效链接和导入问题，请说明客户端版本及错误提示，不要提交个人密码或私有订阅。

请遵守所在地法律法规及服务条款，谨慎通过公共代理传输敏感信息。

## Shadowrocket 客户端下载

| 平台 | 客户端 | 下载地址 |
| --- | --- | --- |
| iOS / iPadOS | Shadowrocket（小火箭） | [App Store](https://apps.apple.com/us/app/shadowrocket/id932747118) |

App Store 的可用地区和价格以商店页面为准。

