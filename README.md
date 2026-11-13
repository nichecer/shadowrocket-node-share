# 小火箭 Shadowrocket 免费节点

这里整理 Shadowrocket 客户端可导入的节点 URI 和订阅，提供固定入口、导入说明和更新信息。

## 本次更新

- 最近成功整理：2026-11-13 20:05:10
- 节点数量：16
- 最低 TCP 延迟：35 ms（香港）
- 国家/地区：德国、意大利、日本、芬兰、荷兰、西班牙、香港
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
| 🇩🇪 德国_01 | 德国 | VLESS | 170 ms |
| 🇪🇸 西班牙_01 | 西班牙 | VLESS | 212 ms |
| 🇮🇹 意大利_07 | 意大利 | SS | 233 ms |
| 🇮🇹 意大利_10 | 意大利 | SS | 242 ms |
| 🇮🇹 意大利_04 | 意大利 | SS | 249 ms |
| 🇮🇹 意大利_06 | 意大利 | SS | 265 ms |
| 🇮🇹 意大利_02 | 意大利 | SS | 266 ms |
| 🇮🇹 意大利_09 | 意大利 | SS | 266 ms |
| 🇳🇱 荷兰_01 | 荷兰 | VLESS | 272 ms |
| 🇮🇹 意大利_01 | 意大利 | SS | 274 ms |
| 🇫🇮 芬兰_01 | 芬兰 | VLESS | 281 ms |
| 🇮🇹 意大利_03 | 意大利 | SS | 304 ms |
| 🇯🇵 日本_01 | 日本 | SS | 350 ms |
| 🇮🇹 意大利_05 | 意大利 | SS | 1229 ms |
| 🇮🇹 意大利_08 | 意大利 | SS | 1263 ms |

[查看完整延迟数据](latency.json)

## 免费节点列表

节点列表最多显示25个，订阅后查看全部节点

```text
vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7Ag6aaZ5rivXzAxIiwiYWRkIjoiNDcuMjQ0LjEyMC4xOTciLCJwb3J0IjoiNDQ4NjciLCJpZCI6Ijg0NWU2YjA4LTI5MTktNDI5MC1hZGUwLTVkYzdkY2VhNTljYSIsImFpZCI6IjAiLCJzY3kiOiJhdXRvIiwibmV0Ijoid3MiLCJ0eXBlIjoibm9uZSIsImhvc3QiOiIiLCJwYXRoIjoiL2Fya2kiLCJ0bHMiOiIiLCJzbmkiOiIiLCJhbHBuIjoiIiwiZnAiOiIiLCJpbnNlY3VyZSI6IjAifQ==
vless://c16e8cdb-65dd-4049-bc65-14c051b8a6c6@2.26.251.236:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=mental-deprivation.ru&fp=firefox&pbk=1iVMMhJZgXHRY7tRlR-1kypF0YeaBcB7EjcfHRsYZX4&sid=4ff31b18d1bd8227&spx=%2F5f73ebfc9ef9c37&type=tcp&headerType=none#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_01
vless://4201786b-d99b-4147-a5f0-20d47acddb81@196.196.149.80:443?encryption=none&security=reality&sni=b3cd32g.es1.h1clayd.click&fp=firefox&pbk=7efBhLzPwoTtEC1GlukCdiTllobUfa2_XuAKNSLJx30&sid=e7cffac9f8cfb434&type=grpc#%F0%9F%87%AA%F0%9F%87%B8%20%E8%A5%BF%E7%8F%AD%E7%89%99_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.45:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_07
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.63:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_10
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.72:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_04
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.36:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_06
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.90:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.27:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_09
vless://Fluffy_VPN-zKZUa4Ie@72.56.38.83:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=absolute-disaster.org&fp=firefox&pbk=ZzIetLcQtENjIXQ9XZqFo8p3J81p8Emj0wi51Uy07n8&type=tcp&headerType=none&host=absolute-disaster.org#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.99:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_01
vless://3f3160a0-747d-4fed-bf3d-4d884bfa964d@178.214.125.1:443?&security=reality&flow=xtls-rprx-vision&pbk=ZxCwJxbsZWJYYCPzeWj7_fxJMVhwh4XGfpvjmEIQjHY&sid=6172ba9cffe9c22f&fp=edge&sni=conf.emaar.ru&type=tcp&headerType=none&host=conf.emaar.ru&path=%2F#%F0%9F%87%AB%F0%9F%87%AE%20%E8%8A%AC%E5%85%B0_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.81:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_03
ss://YWVzLTI1Ni1nY206QmVhVWY5YzBBRVdINDBQdQ==@154.36.158.197:8388#%F0%9F%87%AF%F0%9F%87%B5%20%E6%97%A5%E6%9C%AC_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.54:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_05
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.18:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_08
```

## 反馈

欢迎在 Issues 反馈失效链接和导入问题，请说明客户端版本及错误提示，不要提交个人密码或私有订阅。

请遵守所在地法律法规及服务条款，谨慎通过公共代理传输敏感信息。

## Shadowrocket 客户端下载

| 平台 | 客户端 | 下载地址 |
| --- | --- | --- |
| iOS / iPadOS | Shadowrocket（小火箭） | [App Store](https://apps.apple.com/us/app/shadowrocket/id932747118) |

App Store 的可用地区和价格以商店页面为准。

