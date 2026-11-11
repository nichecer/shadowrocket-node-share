# 小火箭 Shadowrocket 免费节点

这里整理 Shadowrocket 客户端可导入的节点 URI 和订阅，提供固定入口、导入说明和更新信息。

## 本次更新

- 最近成功整理：2026-11-11 20:05:13
- 节点数量：16
- 最低 TCP 延迟：33 ms（美国）
- 国家/地区：AL、EE、德国、意大利、美国、荷兰
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
| 🇺🇸 美国_01 | 美国 | VLESS | 33 ms |
| 🇺🇸 美国_02 | 美国 | VLESS | 36 ms |
| 🇩🇪 德国_01 | 德国 | VLESS | 190 ms |
| 🇦🇱 阿尔巴尼亚_01 | AL | VLESS | 237 ms |
| 🇳🇱 荷兰_01 | 荷兰 | VLESS | 262 ms |
| 🇪🇪 爱沙尼亚_01 | EE | VLESS | 295 ms |
| 🇮🇹 意大利_04 | 意大利 | SS | 310 ms |
| 🇮🇹 意大利_08 | 意大利 | SS | 324 ms |
| 🇮🇹 意大利_07 | 意大利 | SS | 332 ms |
| 🇮🇹 意大利_05 | 意大利 | SS | 332 ms |
| 🇮🇹 意大利_10 | 意大利 | SS | 335 ms |
| 🇮🇹 意大利_06 | 意大利 | SS | 337 ms |
| 🇮🇹 意大利_09 | 意大利 | SS | 339 ms |
| 🇮🇹 意大利_02 | 意大利 | SS | 352 ms |
| 🇮🇹 意大利_01 | 意大利 | SS | 354 ms |
| 🇮🇹 意大利_03 | 意大利 | SS | 432 ms |

[查看完整延迟数据](latency.json)

## 免费节点列表

节点列表最多显示25个，订阅后查看全部节点

```text
vless://0afc6426-606c-48e7-bd70-3c424a416842@us22.sofast.live:58011?encryption=none&security=none&fp=chrome&type=tcp&headerType=none#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_01
vless://399b6b23-cc40-4831-a494-61948e2df133@jp.sofast.live:52683?encryption=none&security=none&type=tcp&headerType=none#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_02
vless://c16e8cdb-65dd-4049-bc65-14c051b8a6c6@2.26.251.236:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=mental-deprivation.ru&fp=firefox&pbk=1iVMMhJZgXHRY7tRlR-1kypF0YeaBcB7EjcfHRsYZX4&sid=4ff31b18d1bd8227&spx=%2F5f73ebfc9ef9c37&type=tcp&headerType=none#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_01
vless://cda0862a-0f87-4be9-8ed8-1d0c9e382839@196.245.52.183:443?security=reality&type=xhttp&path=%2Fd20896a4ce30&packetEncoding=xudp&sni=e60833x.nl7.h1clayd.click&fp=firefox&sid=2d2598d60447a967&pbk=jIRVNEf9SpuWP2nJrAbHGGIUnfzOmwZZlrNGw-Y-O2Q&encryption=none#%F0%9F%87%A6%F0%9F%87%B1%20%E9%98%BF%E5%B0%94%E5%B7%B4%E5%B0%BC%E4%BA%9A_01
vless://Fluffy_VPN-zKZUa4Ie@72.56.38.83:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=absolute-disaster.org&fp=firefox&pbk=ZzIetLcQtENjIXQ9XZqFo8p3J81p8Emj0wi51Uy07n8&type=tcp&headerType=none&host=absolute-disaster.org#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_01
vless://7ad63b26-bf70-4872-8fab-ebaf73a1e19d@5.129.202.80:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=mirror-50.topp-con.xyz&fp=chrome&pbk=NY2bvH4IFKTstWkBWwyU5MmlzuKk0nU08cBoHlti2S8&sid=2ef2b10d5143d798&type=tcp&headerType=none#%F0%9F%87%AA%F0%9F%87%AA%20%E7%88%B1%E6%B2%99%E5%B0%BC%E4%BA%9A_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.45:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_04
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.18:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_08
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.27:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_07
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.36:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_05
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.90:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_10
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.72:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_06
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.63:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_09
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0@202.50.253.81:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.99:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0@202.50.253.54:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_03
```

## 反馈

欢迎在 Issues 反馈失效链接和导入问题，请说明客户端版本及错误提示，不要提交个人密码或私有订阅。

请遵守所在地法律法规及服务条款，谨慎通过公共代理传输敏感信息。

## Shadowrocket 客户端下载

| 平台 | 客户端 | 下载地址 |
| --- | --- | --- |
| iOS / iPadOS | Shadowrocket（小火箭） | [App Store](https://apps.apple.com/us/app/shadowrocket/id932747118) |

App Store 的可用地区和价格以商店页面为准。

