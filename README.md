# 小火箭 Shadowrocket 免费节点

这里整理 Shadowrocket 客户端可导入的节点 URI 和订阅，提供固定入口、导入说明和更新信息。

## 本次更新

- 最近成功整理：2026-11-05 20:05:09
- 节点数量：14
- 最低 TCP 延迟：34 ms（美国）
- 国家/地区：CZ、意大利、美国
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
| 🇺🇸 美国_04 | 美国 | VLESS | 34 ms |
| 🇺🇸 美国_05 | 美国 | VLESS | 35 ms |
| 🇺🇸 美国_01 | 美国 | VLESS | 237 ms |
| 🇨🇿 捷克_01 | CZ | VLESS | 243 ms |
| 🇺🇸 美国_02 | 美国 | VLESS | 287 ms |
| 🇮🇹 意大利_04 | 意大利 | SS | 322 ms |
| 🇮🇹 意大利_05 | 意大利 | SS | 325 ms |
| 🇮🇹 意大利_09 | 意大利 | SS | 339 ms |
| 🇮🇹 意大利_06 | 意大利 | SS | 343 ms |
| 🇮🇹 意大利_01 | 意大利 | SS | 345 ms |
| 🇮🇹 意大利_07 | 意大利 | SS | 355 ms |
| 🇮🇹 意大利_08 | 意大利 | SS | 361 ms |
| 🇮🇹 意大利_02 | 意大利 | SS | 369 ms |
| 🇮🇹 意大利_03 | 意大利 | SS | 371 ms |

[查看完整延迟数据](latency.json)

## 免费节点列表

节点列表最多显示25个，订阅后查看全部节点

```text
vless://0afc6426-606c-48e7-bd70-3c424a416842@us22.sofast.live:58011?encryption=none&security=none&fp=chrome&type=tcp&headerType=none#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_04
vless://399b6b23-cc40-4831-a494-61948e2df133@jp.sofast.live:52683?encryption=none&security=none&type=tcp&headerType=none#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_05
vless://50a87e21-f0e2-4b53-a787-91adfe748f63@swedenafteraventura.space:443?security=reality&encryption=none&pbk=TyuIIquHoesD9YwMQJHda0YZ3Hy9Dh123dQ00iGK0QY&headerType=none&fp=chrome&type=tcp&flow=xtls-rprx-vision&sni=swedenafteraventura.space#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_01
vless://b18d5990-96eb-4587-a386-7f8ef7591e6a@cz-prg.dontblockmepls.com:2063?encryption=none&flow=xtls-rprx-vision&security=reality&sni=rusbid.de&fp=chrome&pbk=MMpt_jWc4J3oySBdf5sPDVRkiWlZmOObth6A1scM9BM&type=tcp&headerType=none#%F0%9F%87%A8%F0%9F%87%BF%20%E6%8D%B7%E5%85%8B_01
vless://e08d9bc5-6832-4dd4-bd44-d9bbe61e5817@87.232.88.27:443?security=reality&sni=max.ru&insecure=0&fp=firefox&pbk=4qE0kXmxDvNzsns2jdwd74AN35RptcTD4eKo5REa9w8&sid=04&type=grpc&serviceName=grpc-67#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.45:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_04
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.81:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_05
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.27:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_09
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.99:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_06
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.18:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.90:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_07
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.72:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_08
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.63:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.54:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_03
```

## 反馈

欢迎在 Issues 反馈失效链接和导入问题，请说明客户端版本及错误提示，不要提交个人密码或私有订阅。

请遵守所在地法律法规及服务条款，谨慎通过公共代理传输敏感信息。

## Shadowrocket 客户端下载

| 平台 | 客户端 | 下载地址 |
| --- | --- | --- |
| iOS / iPadOS | Shadowrocket（小火箭） | [App Store](https://apps.apple.com/us/app/shadowrocket/id932747118) |

App Store 的可用地区和价格以商店页面为准。

