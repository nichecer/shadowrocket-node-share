# 小火箭 Shadowrocket 免费节点

这里整理 Shadowrocket 客户端可导入的节点 URI 和订阅，提供固定入口、导入说明和更新信息。

## 本次更新

- 最近成功整理：2026-11-06 20:05:12
- 节点数量：24
- 最低 TCP 延迟：31 ms（美国）
- 国家/地区：LV、德国、意大利、新加坡、日本、法国、美国、英国、荷兰
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
| 🇺🇸 美国_02 | 美国 | VLESS | 31 ms |
| 🇺🇸 美国_03 | 美国 | VLESS | 34 ms |
| 🇩🇪 德国_01 | 德国 | VLESS | 193 ms |
| 🇫🇷 法国_01 | 法国 | VLESS | 195 ms |
| 🇺🇸 美国_01 | 美国 | VLESS | 197 ms |
| 🇩🇪 德国_02 | 德国 | VLESS | 212 ms |
| 🇮🇹 意大利_10 | 意大利 | SS | 230 ms |
| 🇮🇹 意大利_09 | 意大利 | SS | 232 ms |
| 🇱🇻 拉脱维亚_01 | LV | VLESS | 234 ms |
| 🇳🇱 荷兰_01 | 荷兰 | VLESS | 241 ms |
| 🇮🇹 意大利_04 | 意大利 | SS | 242 ms |
| 🇩🇪 德国_04 | 德国 | VLESS | 244 ms |
| 🇬🇧 英国_01 | 英国 | VLESS | 246 ms |
| 🇮🇹 意大利_06 | 意大利 | SS | 248 ms |
| 🇮🇹 意大利_03 | 意大利 | SS | 249 ms |
| 🇬🇧 英国_02 | 英国 | VLESS | 253 ms |
| 🇮🇹 意大利_05 | 意大利 | SS | 259 ms |
| 🇮🇹 意大利_08 | 意大利 | SS | 272 ms |
| 🇮🇹 意大利_07 | 意大利 | SS | 273 ms |
| 🇮🇹 意大利_01 | 意大利 | SS | 278 ms |
| 🇩🇪 德国_03 | 德国 | VLESS | 281 ms |
| 🇮🇹 意大利_02 | 意大利 | SS | 286 ms |
| 🇯🇵 日本_01 | 日本 | SS | 605 ms |
| 🇸🇬 新加坡_01 | 新加坡 | VLESS | 1240 ms |

[查看完整延迟数据](latency.json)

## 免费节点列表

节点列表最多显示25个，订阅后查看全部节点

```text
vless://399b6b23-cc40-4831-a494-61948e2df133@jp.sofast.live:52683?encryption=none&security=&type=tcp#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_02
vless://0afc6426-606c-48e7-bd70-3c424a416842@us22.sofast.live:58011?encryption=none&security=&type=tcp#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_03
vless://caedb3a1-6395-40b9-a9a8-4b9694eb224a@13.143.192.200:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=kulek.tech&fp=firefox&pbk=gOzBi_a99jyGQyM5tVwDpi7EQ_3eaj-v15mHOTs9xkY&type=tcp&headerType=none&host=kulek.tech#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_01
vless://a289c660-1b12-432b-a06c-c2ae469272b0@62.210.70.194:37783?encryption=mlkem768x25519plus.native.0rtt.I5ge5qOTUhKE8xpufKI84yktvqqG9qkViwYe20uFZUyGwbnK7QMv6Tih0subInSmZTyem1QFG1CDFvGfgMBu3Yw1ryNJfGjMnALAqZawBoukaROcTzxXmFAzuejDalyhxxfNJkeUefW3biOHIzcu_AairYSvJ8l_iHJpKVEKXZWPQWiq-tm_nPJz_oDDhFElaCHKnCslodSen2M6afQQ0HYKc6nKZmZwc1cHG1GKW9xHx6CBfLhFVOhT62tCvbxShul1NJgL-shELnovAtS1aHBFQKDOIiJYC7Ww0awUfsyGIFhnJIhdnqFHnkG7sOcdiWiH-ZkQ11p065zAWEQ14HTOi-aqCAsnWNwdRxwj1_qlArYd3nNF1dXKARRikbMFutC5GyyvSJxk7XwHRGWoK_q6_zK2amtIrsin6tov5kKs3UqywFJMJ2rMtgYZXpvK_TdXumLGUimIq9vFW7idpbMlv9F84NY8UbtrkyB87IQwdKqbtnuOMzxkYik-i9N5vaKcXLSdOGRpMgAKSMt5NbSyllcEh6qUTZoVb_h8ZmYij8csvbGWxodCj1WvOGoRtGGnTSpWMdG3X3ZxXlhNQ6tpIPGTfxkzjPtRjHQDcqm0fgrLjWONnkGxMQRO-Wi50vzNPzW9Vuy5BlZszdGqpjLNRLGw24JTAYKXpxiUkTxUxhO3LRC8kMvGVBgxjImwmwev1IqfPiVIMSwhV0FAMNw27nALh0qyPnNLbFpbTFuTL6V83YypFDl1yahns_AE86ufKnSAaSs_0PwMM_ZDfkhE7nRKCygaD9UjWWygRWq6fZarZahcTAqrZUYPXWxqDsrE7VRYO3ch70AHi6ZXTyKR1YcyM0Kiw3S0kxpjbtWReOJ3lXwry-BjcusDKhRsAxErDIBD6IFuY5ucRTtpfPoNgiq7rSFG8SFNvTe-_wh39Bwjj3JeRnw6kzujiKgxGiAH9GYm6LVvG2ljdWacJjSyoDE6mbFwgRCGdDh4h6eMCPs7hjQmNByx76lb0PYt-BuD9xCfiEFMoKJzTjWUvOy1gbmOrjY5xtkkByo8PCS40YRqXiYQ0Me9U5t_lsdxrvO6f7ajFHBNp_IiQOAstWu9UKC2hiABnVWbHaTFeQSp0tAx9rm5vehC0_a3EAHByGzGFUQ-QWpUO5mvGzZKpPVQrgovg2GsgepxgOMymOgv2CbLNKiwAJJyjDe5d5yXiueH3ZdppJqepXrOGuGOn3e-8RKVu3I-nCp-aMS769Yl5mmS8BYOpxW3HseSzZZMIta4hjsa7hqSgmycflvLV5x-8bM9iBFZ7iOey9oYyEkEbFN-6-Alh2dQfopjE2QNFqW6KatBKHXKHNVoayoc4ZegDKPNAEnAo9wIHkBpDFC-fVoCkGMDcRSeNbF67keruuE0xfMA8ltaklEyRwMcxVQwMhILq6vKlzpJF9OJMGVg5amP_-i4NAsKEfC8Ayp61gByykoWKTWkuLAEAYtXXNIfQ9BPvZca1BITgpC69lapO4SH1UAZ4KRxOTVtbHES_GsjM_lkTv940p3IDkG7jfvxIfY_Q9C3QVbkilRpPvg&security=reality&sni=www.yahoo.com&fp=chrome&pbk=tQeEamJmYVUUfjRLX7ETvMnPj4DrHzRhR5TI684oYgg&sid=21569dd6&type=xhttp&path=%2FOCrp5Ajs&mode=auto#%F0%9F%87%AB%F0%9F%87%B7%20%E6%B3%95%E5%9B%BD_01
vless://52080382-bc5e-4712-81a8-f9da66e3f444@23.95.112.78:33607?encryption=mlkem768x25519plus.native.0rtt.Bg1scpshInQLLzE8hzvLTWnf3F-ZWc4SkkgT31hIISw&flow=xtls-rprx-vision&security=reality&sni=hdprogressive.3dvisionlive.com&fp=chrome&pbk=940MCE_EbMOUIEpfcjDPXxjBIeWjq--_atMA0IdKwQQ&sid=262269&type=tcp&headerType=none#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_01
vless://7e92da20-d9da-4d78-a64c-d032bc998e54@167.233.25.137:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=www.microsoft.com&fp=chrome&pbk=h-sTqV9wF_ZHio3JzDJ0QE11PUXH8fK-wKO7-aN581Y&sid=f6db8516b3d67b62&type=tcp&headerType=none#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.72:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_10
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.18:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_09
vless://bbe37c75-d097-4b72-a074-445a56fe3969@test.wolf-moose.test-cdn-kkk.com:443?security=reality&type=tcp&packetEncoding=xudp&sni=la.cdn-tech-images.com&fp=qq&flow=xtls-rprx-vision&sid=50&pbk=-tePObR3oZwGAUOb5kqTYkNWl6rtUKl0RFuzuu06wgw&encryption=none#%F0%9F%87%B1%F0%9F%87%BB%20%E6%8B%89%E8%84%B1%E7%BB%B4%E4%BA%9A_01
vless://b7b8ee80-db83-4276-8c68-87dc88b0b0b5@15d7fft.nl11.h1clayd.click:443?encryption=none&security=reality&sni=15d7fft.nl11.h1clayd.click&pbk=xv6OUZcyzEHXFMTfumuJH-1Rd4NQ0cdmWikek4mm0m4&sid=c71118d9399fb8c2&type=tcp&headerType=none#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.81:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_04
vless://ac36b6f8-d03d-46cb-808f-e655183fb76d@185.44.64.166:59397?encryption=mlkem768x25519plus.native.0rtt.sphudmOm4wKYnBGDTU6kl6-KH7fdQ1VzXp58hEAn3zU&flow=xtls-rprx-vision&security=reality&sni=la.blogs.nvidia.com&fp=chrome&pbk=7w6m1Z7wZk1KX7bBlCi50t_8T-HdC8aMizOcIyqcaS4&sid=1430&type=tcp&headerType=none#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_04
vless://a3d15e40-fa6b-4d11-af0b-24815c4b82fb@5.104.74.70:8443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=uk-room07.filesnap.tech&fp=firefox&pbk=48j01Jsa4o8zfmCGEFoVjn-YeALM80-DSG_-nAZUBDM&sid=dbef98744832b751&type=tcp&headerType=none#%F0%9F%87%AC%F0%9F%87%A7%20%E8%8B%B1%E5%9B%BD_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.27:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_06
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0@202.50.253.54:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_03
vless://857e5668-88b9-45cd-a600-79e55c04d8a8@212.69.135.27:8443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=uk-room05.filesnap.tech&fp=firefox&pbk=FdZlh9FC4ay9OGnKG6K_iNqhz1I3tWDfNZhxrDYuQl8&sid=7da3ba09a037e956&type=tcp&headerType=none#%F0%9F%87%AC%F0%9F%87%A7%20%E8%8B%B1%E5%9B%BD_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.63:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_05
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.99:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_08
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND1AMjAyLjUwLjI1My40NToxOTk5OQ==#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_07
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.36:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_01
vless://db80088c-32a1-4cb8-a907-0f3cb7844152@at1.japancase.site:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=at1.japancase.site&fp=edge&pbk=zEntiD6D81wY__YHPvIw78e09CBIgYkyQ5meIo7c_hg&sid=41ae8e266bc3346f&type=tcp&headerType=none#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_03
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND1AMjAyLjUwLjI1My45MDoxOTk5OQ==#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_02
ss://YWVzLTI1Ni1nY206QmVhVWY5YzBBRVdINDBQdQ==@154.36.158.197:8388#%F0%9F%87%AF%F0%9F%87%B5%20%E6%97%A5%E6%9C%AC_01
vless://0dedd47d-47b9-4ed1-9c9f-cbeecad57a68@43.163.112.174:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=www.cloudflare.com&fp=chrome&pbk=mXQudYHNu0pebcdk1_qn-UgcmwhjaV7y9UrYu3HX7Rg&sid=0123456789abcdef&type=tcp&headerType=none&host=www.cloudflare.com#%F0%9F%87%B8%F0%9F%87%AC%20%E6%96%B0%E5%8A%A0%E5%9D%A1_01
```

## 反馈

欢迎在 Issues 反馈失效链接和导入问题，请说明客户端版本及错误提示，不要提交个人密码或私有订阅。

请遵守所在地法律法规及服务条款，谨慎通过公共代理传输敏感信息。

## Shadowrocket 客户端下载

| 平台 | 客户端 | 下载地址 |
| --- | --- | --- |
| iOS / iPadOS | Shadowrocket（小火箭） | [App Store](https://apps.apple.com/us/app/shadowrocket/id932747118) |

App Store 的可用地区和价格以商店页面为准。

