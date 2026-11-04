# 小火箭 Shadowrocket 免费节点

这里整理 Shadowrocket 客户端可导入的节点 URI 和订阅，提供固定入口、导入说明和更新信息。

## 本次更新

- 最近成功整理：2026-11-04 08:05:09
- 节点数量：17
- 最低 TCP 延迟：77 ms（马来西亚）
- 国家/地区：EE、俄罗斯、德国、意大利、美国、荷兰、马来西亚
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
| 🇲🇾 马来西亚_01 | 马来西亚 | SS | 77 ms |
| 🇩🇪 德国_02 | 德国 | VLESS | 230 ms |
| 🇩🇪 德国_01 | 德国 | VLESS | 240 ms |
| 🇮🇹 意大利_09 | 意大利 | SS | 252 ms |
| 🇮🇹 意大利_05 | 意大利 | SS | 259 ms |
| 🇮🇹 意大利_04 | 意大利 | SS | 260 ms |
| 🇮🇹 意大利_02 | 意大利 | SS | 262 ms |
| 🇪🇪 爱沙尼亚_01 | EE | VLESS | 269 ms |
| 🇮🇹 意大利_03 | 意大利 | SS | 270 ms |
| 🇮🇹 意大利_08 | 意大利 | SS | 273 ms |
| 🇷🇺 俄罗斯_01 | 俄罗斯 | SS | 281 ms |
| 🇮🇹 意大利_07 | 意大利 | SS | 282 ms |
| 🇮🇹 意大利_06 | 意大利 | SS | 285 ms |
| 🇮🇹 意大利_01 | 意大利 | SS | 309 ms |
| 🇺🇸 美国_02 | 美国 | VLESS | 325 ms |
| 🇳🇱 荷兰_01 | 荷兰 | VLESS | 413 ms |
| 🇺🇸 美国_01 | 美国 | VLESS | 448 ms |

[查看完整延迟数据](latency.json)

## 免费节点列表

节点列表最多显示25个，订阅后查看全部节点

```text
ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNToyODc4OTk4OC04ODdlLTRlNDEtODNjZC0yN2JiZmI3OTk5YWQ=@xunlinknode.csdjhajkshdjkas.com:40006#%F0%9F%87%B2%F0%9F%87%BE%20%E9%A9%AC%E6%9D%A5%E8%A5%BF%E4%BA%9A_01
vless://ac36b6f8-d03d-46cb-808f-e655183fb76d@185.44.64.166:59397?encryption=mlkem768x25519plus.native.0rtt.sphudmOm4wKYnBGDTU6kl6-KH7fdQ1VzXp58hEAn3zU&flow=xtls-rprx-vision&security=reality&sni=la.blogs.nvidia.com&fp=chrome&pbk=7w6m1Z7wZk1KX7bBlCi50t_8T-HdC8aMizOcIyqcaS4&sid=1430&type=tcp&headerType=none#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_02
vless://ebdfaf99-41d8-4e48-8196-d54510ffb556@45.129.242.56:443?security=reality&type=tcp&packetEncoding=xudp&sni=www.cloudflare.com&fp=chrome&flow=xtls-rprx-vision&sid=abcdef&pbk=YURKlEQ3rap4KOXXGsVFZyYev2oDU2gCEbNTXPdKWRY#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND1AMjAyLjUwLjI1My4yNzoxOTk5OQ==#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_09
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.18:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_05
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.99:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_04
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.36:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_02
vless://7ad63b26-bf70-4872-8fab-ebaf73a1e19d@5.129.202.80:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=mirror-50.topp-con.xyz&fp=chrome&pbk=NY2bvH4IFKTstWkBWwyU5MmlzuKk0nU08cBoHlti2S8&sid=2ef2b10d5143d798&type=tcp&headerType=none#%F0%9F%87%AA%F0%9F%87%AA%20%E7%88%B1%E6%B2%99%E5%B0%BC%E4%BA%9A_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.90:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_03
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.54:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_08
ss://YWVzLTI1Ni1nY206Y0NNSmdKVEEzQkE0ODlZVVlyRnE3WEhYU2lTcFdsTGE=@46.17.46.27:18443#%F0%9F%87%B7%F0%9F%87%BA%20%E4%BF%84%E7%BD%97%E6%96%AF_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.45:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_07
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.72:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_06
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.63:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_01
vless://056405e8-de9f-4d0d-8145-956f13cc34da@79.182.39.57:443?encryption=none&security=reality&sni=a0688bt.us4.h1clayd.click&fp=firefox&pbk=5-9YzvyXcZ4J5Z4OaVTUbxUU2InvnwT17m0XY-Jse1E&sid=257420d9d430152a&type=tcp&headerType=none#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_02
vless://b2847c3b-5278-4b06-9c66-bc919d2dfec7@186.246.9.29:443?encryption=none&security=reality&sni=wordpress.com&fp=firefox&pbk=MPNMomAMn_lu9YMYjD2jAQWrI-rTM4hj9Jgg9d6qzTA&sid=50ad5564&type=tcp&headerType=none#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_01
vless://7ad63b26-bf70-4872-8fab-ebaf73a1e19d@201.51.4.89:443?&security=reality&flow=xtls-rprx-vision&pbk=LEziyH-E4k9hehGRJkVi1FadVObB_NZJy8U7oUCVWXU&sid=b9120cd53ffd7bba&fp=chrome&sni=cache-89.topp-con.xyz&type=tcp&headerType=none&host=cache-89.topp-con.xyz&path=%2F#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_01
```

## 反馈

欢迎在 Issues 反馈失效链接和导入问题，请说明客户端版本及错误提示，不要提交个人密码或私有订阅。

请遵守所在地法律法规及服务条款，谨慎通过公共代理传输敏感信息。

## Shadowrocket 客户端下载

| 平台 | 客户端 | 下载地址 |
| --- | --- | --- |
| iOS / iPadOS | Shadowrocket（小火箭） | [App Store](https://apps.apple.com/us/app/shadowrocket/id932747118) |

App Store 的可用地区和价格以商店页面为准。

