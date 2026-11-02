# 小火箭 Shadowrocket 免费节点

这里整理 Shadowrocket 客户端可导入的节点 URI 和订阅，提供固定入口、导入说明和更新信息。

## 本次更新

- 最近成功整理：2026-11-02 08:05:12
- 节点数量：20
- 最低 TCP 延迟：37 ms（美国）
- 国家/地区：CZ、EE、俄罗斯、印度、德国、意大利、美国、荷兰、香港
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
| 🇺🇸 美国_01 | 美国 | VLESS | 37 ms |
| 🇺🇸 美国_02 | 美国 | VLESS | 37 ms |
| 🇭🇰 香港_01 | 香港 | VMESS | 37 ms |
| 🇨🇿 捷克_01 | CZ | VLESS | 202 ms |
| 🇳🇱 荷兰_02 | 荷兰 | VLESS | 202 ms |
| 🇮🇳 印度_01 | 印度 | VLESS | 241 ms |
| 🇷🇺 俄罗斯_01 | 俄罗斯 | SS | 296 ms |
| 🇮🇹 意大利_04 | 意大利 | SS | 313 ms |
| 🇮🇹 意大利_07 | 意大利 | SS | 323 ms |
| 🇮🇹 意大利_08 | 意大利 | SS | 324 ms |
| 🇮🇹 意大利_01 | 意大利 | SS | 324 ms |
| 🇳🇱 荷兰_01 | 荷兰 | VLESS | 328 ms |
| 🇮🇹 意大利_05 | 意大利 | SS | 335 ms |
| 🇮🇹 意大利_06 | 意大利 | SS | 337 ms |
| 🇮🇹 意大利_10 | 意大利 | SS | 343 ms |
| 🇮🇹 意大利_02 | 意大利 | SS | 353 ms |
| 🇮🇹 意大利_03 | 意大利 | SS | 363 ms |
| 🇮🇹 意大利_11 | 意大利 | SS | 372 ms |
| 🇪🇪 爱沙尼亚_01 | EE | VLESS | 417 ms |
| 🇩🇪 德国_01 | 德国 | VLESS | 1253 ms |

[查看完整延迟数据](latency.json)

## 免费节点列表

节点列表最多显示25个，订阅后查看全部节点

```text
vless://399b6b23-cc40-4831-a494-61948e2df133@jp.sofast.live:52683?encryption=none&security=&type=tcp#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_01
vless://0afc6426-606c-48e7-bd70-3c424a416842@us22.sofast.live:58011?encryption=none&type=tcp#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_02
vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7Ag6aaZ5rivXzAxIiwiYWRkIjoiNDcuMjQ0LjEyMC4xOTciLCJwb3J0IjoiMjMwMjYiLCJ0eXBlIjoibm9uZSIsImlkIjoiYjlkZTFiYzktYmFhNy00MWFjLTg2ZjctY2NkNTk2OTVjYjIxIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9hcmtpIiwiaG9zdCI6IjQ3LjI0NC4xMjAuMTk3IiwidGxzIjoiIn0=
vless://b18d5990-96eb-4587-a386-7f8ef7591e6a@cz-prg.dontblockmepls.com:2063?encryption=none&flow=xtls-rprx-vision&security=reality&sni=rusbid.de&fp=chrome&pbk=MMpt_jWc4J3oySBdf5sPDVRkiWlZmOObth6A1scM9BM&type=tcp&headerType=none#%F0%9F%87%A8%F0%9F%87%BF%20%E6%8D%B7%E5%85%8B_01
vless://07680ffb-0666-4836-b6ad-ec0de62bc38f@app-mi-26.spbstudentlife.com:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=assets-mi-26.spbstudentlife.com&fp=chrome&pbk=cYtAkO6yUCuRTxHvF8EH76bybk1yfS005KLls-at2yc&sid=a7856800c2deb7b2&type=tcp&headerType=none#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_02
vless://5e679ccd-1586-4d5f-b87b-48251046cad8@hydra.yokkastars.com:2443?encryption=none&security=reality&sni=deepl.com&fp=qq&pbk=h85e28MxBgNyT9d9cNeOLVtWfHq6cT_1_oxZOTajtTg&sid=92c32de179e5d908&type=grpc&authority=&serviceName=rex-eb0bf76b710ce763&mode=gun#%F0%9F%87%AE%F0%9F%87%B3%20%E5%8D%B0%E5%BA%A6_01
ss://YWVzLTI1Ni1nY206Y0NNSmdKVEEzQkE0ODlZVVlyRnE3WEhYU2lTcFdsTGE@46.17.46.27:18443#%F0%9F%87%B7%F0%9F%87%BA%20%E4%BF%84%E7%BD%97%E6%96%AF_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.90:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_04
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND1AMjAyLjUwLjI1My42MzoxOTk5OQ==#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_07
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND1AMjAyLjUwLjI1My43MjoxOTk5OQ==#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_08
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.27:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_01
vless://b2847c3b-5278-4b06-9c66-bc919d2dfec7@186.246.9.29:443?security=reality&type=tcp&packetEncoding=xudp&sni=wordpress.com&fp=firefox&sid=50ad5564&pbk=MPNMomAMn_lu9YMYjD2jAQWrI-rTM4hj9Jgg9d6qzTA#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND1AMjAyLjUwLjI1My45OToxOTk5OQ==#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_05
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.18:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_06
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.36:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_10
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND1AMjAyLjUwLjI1My40NToxOTk5OQ==#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND1AMjAyLjUwLjI1My44MToxOTk5OQ==#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_03
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.54:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_11
vless://f90b7d43-69e2-4b46-a672-8029bc6796a2@79.182.39.237:25895?security=reality&type=tcp&packetEncoding=xudp&sni=www.samsung.com&fp=firefox&sid=a73f0410d728c823&pbk=jOVKSP-bS9OkILJ8Epz8hadh6qhavCrOiJYeF0NCn0k&encryption=none#%F0%9F%87%AA%F0%9F%87%AA%20%E7%88%B1%E6%B2%99%E5%B0%BC%E4%BA%9A_01
vless://36fb6650-8a50-42b5-9f66-06538806f32c@de15.h1cloud.net:25362?security=reality&type=tcp&packetEncoding=xudp&sni=www.chip.de&fp=chrome&sid=23732d14a527990d&pbk=hFee7zTreqlv_wccK_8zxN5v23hj9u-DshByvGf-KAA&encryption=none#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_01
```

## 反馈

欢迎在 Issues 反馈失效链接和导入问题，请说明客户端版本及错误提示，不要提交个人密码或私有订阅。

请遵守所在地法律法规及服务条款，谨慎通过公共代理传输敏感信息。

## Shadowrocket 客户端下载

| 平台 | 客户端 | 下载地址 |
| --- | --- | --- |
| iOS / iPadOS | Shadowrocket（小火箭） | [App Store](https://apps.apple.com/us/app/shadowrocket/id932747118) |

App Store 的可用地区和价格以商店页面为准。

