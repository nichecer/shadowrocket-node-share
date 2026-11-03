# 小火箭 Shadowrocket 免费节点

这里整理 Shadowrocket 客户端可导入的节点 URI 和订阅，提供固定入口、导入说明和更新信息。

## 本次更新

- 最近成功整理：2026-11-03 20:05:12
- 节点数量：18
- 最低 TCP 延迟：36 ms（美国）
- 国家/地区：EE、德国、意大利、美国、荷兰、香港
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
| 🇺🇸 美国_03 | 美国 | VLESS | 36 ms |
| 🇭🇰 香港_01 | 香港 | VMESS | 37 ms |
| 🇺🇸 美国_04 | 美国 | VLESS | 37 ms |
| 🇺🇸 美国_01 | 美国 | VLESS | 137 ms |
| 🇩🇪 德国_01 | 德国 | VLESS | 236 ms |
| 🇳🇱 荷兰_01 | 荷兰 | VLESS | 261 ms |
| 🇮🇹 意大利_06 | 意大利 | SS | 305 ms |
| 🇮🇹 意大利_01 | 意大利 | SS | 314 ms |
| 🇮🇹 意大利_03 | 意大利 | SS | 314 ms |
| 🇮🇹 意大利_09 | 意大利 | SS | 316 ms |
| 🇮🇹 意大利_04 | 意大利 | SS | 317 ms |
| 🇮🇹 意大利_02 | 意大利 | SS | 317 ms |
| 🇪🇪 爱沙尼亚_01 | EE | VLESS | 337 ms |
| 🇮🇹 意大利_08 | 意大利 | SS | 340 ms |
| 🇮🇹 意大利_05 | 意大利 | SS | 340 ms |
| 🇮🇹 意大利_07 | 意大利 | SS | 344 ms |
| 🇳🇱 荷兰_02 | 荷兰 | VLESS | 452 ms |
| 🇺🇸 美国_02 | 美国 | VLESS | 488 ms |

[查看完整延迟数据](latency.json)

## 免费节点列表

节点列表最多显示25个，订阅后查看全部节点

```text
vless://399b6b23-cc40-4831-a494-61948e2df133@jp.sofast.live:52683?encryption=none&security=none&type=tcp&headerType=none#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_03
vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7Ag6aaZ5rivXzAxIiwiYWRkIjoiNDcuMjQ0LjEyMC4xOTciLCJwb3J0IjoiNDQ4NjciLCJ0eXBlIjoibm9uZSIsImlkIjoiODQ1ZTZiMDgtMjkxOS00MjkwLWFkZTAtNWRjN2RjZWE1OWNhIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9hcmtpIiwiaG9zdCI6IiIsInRscyI6IiJ9
vless://0afc6426-606c-48e7-bd70-3c424a416842@us22.sofast.live:58011?encryption=none&security=&type=tcp#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_04
vless://1bd6c8a2-01db-4a3d-8b2c-0b2f2c3e8b5a@38.244.5.231:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=www.cloudflare.com&fp=chrome&pbk=DUpNPvLjiL1GzeF7DfKWba-LYLz1KPuQXewhgNGPiDM&sid=ab0a5b56&type=tcp&headerType=none#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_01
vless://ac36b6f8-d03d-46cb-808f-e655183fb76d@185.44.64.166:59397?encryption=mlkem768x25519plus.native.0rtt.sphudmOm4wKYnBGDTU6kl6-KH7fdQ1VzXp58hEAn3zU&flow=xtls-rprx-vision&security=reality&sni=la.blogs.nvidia.com&fp=chrome&pbk=7w6m1Z7wZk1KX7bBlCi50t_8T-HdC8aMizOcIyqcaS4&sid=1430&type=tcp&headerType=none#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_01
vless://Fluffy_VPN-zKZUa4Ie@147.45.108.45:443?&security=reality&flow=xtls-rprx-vision&pbk=IuzAWh6UM62Txrnh_No9y5n6wmZecyR1ki8z5xor-0g&fp=firefox&sni=absolute-disaster.org&type=tcp&headerType=none&host=absolute-disaster.org&path=%2F#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.81:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_06
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.99:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.36:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_03
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.18:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_09
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.90:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_04
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.45:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_02
vless://7ad63b26-bf70-4872-8fab-ebaf73a1e19d@5.129.202.80:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=mirror-50.topp-con.xyz&fp=chrome&pbk=NY2bvH4IFKTstWkBWwyU5MmlzuKk0nU08cBoHlti2S8&sid=2ef2b10d5143d798&type=tcp&headerType=none#%F0%9F%87%AA%F0%9F%87%AA%20%E7%88%B1%E6%B2%99%E5%B0%BC%E4%BA%9A_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.27:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_08
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.72:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_05
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.54:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_07
vless://b2847c3b-5278-4b06-9c66-bc919d2dfec7@186.246.9.29:443?encryption=none&security=reality&sni=wordpress.com&fp=firefox&pbk=MPNMomAMn_lu9YMYjD2jAQWrI-rTM4hj9Jgg9d6qzTA&sid=50ad5564&type=tcp&headerType=none#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_02
vless://7ad63b26-bf70-4872-8fab-ebaf73a1e19d@201.51.4.89:443?&security=reality&flow=xtls-rprx-vision&pbk=LEziyH-E4k9hehGRJkVi1FadVObB_NZJy8U7oUCVWXU&sid=b9120cd53ffd7bba&fp=chrome&sni=cache-89.topp-con.xyz&type=tcp&headerType=none&host=cache-89.topp-con.xyz&path=%2F#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_02
```

## 反馈

欢迎在 Issues 反馈失效链接和导入问题，请说明客户端版本及错误提示，不要提交个人密码或私有订阅。

请遵守所在地法律法规及服务条款，谨慎通过公共代理传输敏感信息。

## Shadowrocket 客户端下载

| 平台 | 客户端 | 下载地址 |
| --- | --- | --- |
| iOS / iPadOS | Shadowrocket（小火箭） | [App Store](https://apps.apple.com/us/app/shadowrocket/id932747118) |

App Store 的可用地区和价格以商店页面为准。

