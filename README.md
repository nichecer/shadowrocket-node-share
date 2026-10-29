# 小火箭 Shadowrocket 免费节点

这里整理 Shadowrocket 客户端可导入的节点 URI 和订阅，提供固定入口、导入说明和更新信息。

## 本次更新

- 最近成功整理：2026-10-29 20:05:13
- 节点数量：21
- 最低 TCP 延迟：35 ms（香港）
- 国家/地区：CZ、德国、意大利、挪威、日本、美国、荷兰、香港
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
| 🇭🇰 香港_02 | 香港 | VLESS | 35 ms |
| 🇯🇵 日本_02 | 日本 | SS | 56 ms |
| 🇳🇱 荷兰_02 | 荷兰 | VLESS | 202 ms |
| 🇩🇪 德国_01 | 德国 | VLESS | 203 ms |
| 🇨🇿 捷克_01 | CZ | VLESS | 205 ms |
| 🇺🇸 美国_01 | 美国 | VLESS | 245 ms |
| 🇳🇴 挪威_01 | 挪威 | VLESS | 255 ms |
| 🇳🇱 荷兰_01 | 荷兰 | VLESS | 264 ms |
| 🇮🇹 意大利_01 | 意大利 | SS | 283 ms |
| 🇮🇹 意大利_07 | 意大利 | SS | 299 ms |
| 🇮🇹 意大利_06 | 意大利 | SS | 301 ms |
| 🇮🇹 意大利_03 | 意大利 | SS | 325 ms |
| 🇮🇹 意大利_02 | 意大利 | SS | 332 ms |
| 🇮🇹 意大利_05 | 意大利 | SS | 333 ms |
| 🇺🇸 美国_03 | 美国 | VLESS | 337 ms |
| 🇮🇹 意大利_04 | 意大利 | SS | 338 ms |
| 🇮🇹 意大利_08 | 意大利 | SS | 338 ms |
| 🇮🇹 意大利_10 | 意大利 | SS | 356 ms |
| 🇮🇹 意大利_09 | 意大利 | SS | 386 ms |
| 🇺🇸 美国_02 | 美国 | VLESS | 1325 ms |
| 🇩🇪 德国_02 | 德国 | VLESS | 1590 ms |

[查看完整延迟数据](latency.json)

## 免费节点列表

节点列表最多显示25个，订阅后查看全部节点

```text
vless://928e6cce-8ced-4243-9a48-a6642edd09b0@47.238.210.5:13779?security=reality&type=raw&packetEncoding=xudp&sni=tesla.com&fp=chrome&sid=af1bdd293097b664&pbk=llTyp52oRXnJmQ3I9UUrmlwbMA79B-wLCRHCu-8dLGg#%F0%9F%87%AD%F0%9F%87%B0%20%E9%A6%99%E6%B8%AF_02
ss://YWVzLTI1Ni1nY206QmVhVWY5YzBBRVdINDBQdQ==@154.36.158.197:8388#%F0%9F%87%AF%F0%9F%87%B5%20%E6%97%A5%E6%9C%AC_02
vless://b18d5990-96eb-4587-a386-7f8ef7591e6a@31.77.13.22:2063?encryption=none&security=reality&sni=rusbid.de&fp=firefox&pbk=MMpt_jWc4J3oySBdf5sPDVRkiWlZmOObth6A1scM9BM&type=tcp&headerType=none&insecure=0&flow=xtls-rprx-vision#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_02
vless://846cedee-2a52-0002-a0b9-11850ead6a8b@nl-central.v8x2b.lol:443?encryption=none&security=reality&sni=nl-central.v8x2b.lol&fp=chrome&pbk=q3UXFUE5yYxNE4ugLUnYdpc9WRtR-sjsDTrKsiqzDHE&type=tcp&headerType=none&insecure=0&flow=xtls-rprx-vision#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_01
vless://b18d5990-96eb-4587-a386-7f8ef7591e6a@cz-prg.dontblockmepls.com:2063?encryption=none&security=reality&sni=rusbid.de&fp=firefox&pbk=MMpt_jWc4J3oySBdf5sPDVRkiWlZmOObth6A1scM9BM&type=tcp&headerType=none&insecure=0&flow=xtls-rprx-vision#%F0%9F%87%A8%F0%9F%87%BF%20%E6%8D%B7%E5%85%8B_01
vless://f8d52ece-fad4-478d-875d-df6eed3befa7@nl-s-2.pythonmakemigreat.wiki:61374?security=reality&type=xhttp&path=%2F&host=nl-s-1.pythonmakemigreat.wiki&packetEncoding=xudp&sni=nl-s-2.pythonmakemigreat.wiki&fp=chrome&pbk=QrNs0ew7snHqLfpVXS9RAhlRzgAzzGZK9fXmDcx9xHI&mode=packet-up&extra=%7B%22xPaddingBytes%22%3A%22100-500%22%2C%22xmux%22%3A%7B%22maxConnections%22%3A%223%22%7D%7D&encryption=none#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_01
vless://5a519754-a673-4462-83f6-5eb25d2af141@79.182.39.35:25548?encryption=none&security=reality&sni=www.cloudflare.com&fp=firefox&pbk=lceynvFy326oU4ew9OPR7079m-L5ZcFELgCl0sqxU2M&sid=bceb5b2197b76818&type=tcp&headerType=none&insecure=0#%F0%9F%87%B3%F0%9F%87%B4%20%E6%8C%AA%E5%A8%81_01
vless://1e2b9c0c-4f9b-56f5-a062-1c4f2d2aa200@72.56.38.83:443?&security=reality&flow=xtls-rprx-vision&pbk=ZzIetLcQtENjIXQ9XZqFo8p3J81p8Emj0wi51Uy07n8&fp=chrome&sni=absolute-disaster.org&type=tcp&headerType=none&host=absolute-disaster.org&path=%2F#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.99:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.45:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_07
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.27:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_06
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.90:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_03
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.72:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.54:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_05
vless://5a519754-a673-4462-83f6-5eb25d2af141@79.182.39.57:443?encryption=none&security=reality&sni=f36f5ft.us4.h1clayd.click&fp=firefox&pbk=5KZVzOFqMgdL47--JzLlg5HmPlAYp-cmQsXxkTXngS0&sid=8d50d3a4df71468c&type=tcp&headerType=none&insecure=0#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_03
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.36:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_04
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.18:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_08
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.81:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_10
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.63:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_09
vless://6c713691-3ca2-4446-ad25-113d1bed6b03@78.17.178.125:443?encryption=none&security=reality&sni=cdn.tbank.ru&fp=chrome&pbk=jcp4Lj_qYzxtkalm_XFjrmvqEMGRG7sb19yMwLe16WE&sid=e0215064d8d1fd7c&type=tcp&headerType=none&host=%2F%3FTELEGRAM---MARAMBASHI---MARAMBASHI---MARAMBASHI---MARAMBASHI&insecure=0&flow=xtls-rprx-vision#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_02
vless://36fb6650-8a50-42b5-9f66-06538806f32c@de15.h1cloud.net:25362?security=reality&type=tcp&packetEncoding=xudp&sni=www.chip.de&fp=chrome&sid=23732d14a527990d&pbk=hFee7zTreqlv_wccK_8zxN5v23hj9u-DshByvGf-KAA&encryption=none#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_02
```

## 反馈

欢迎在 Issues 反馈失效链接和导入问题，请说明客户端版本及错误提示，不要提交个人密码或私有订阅。

请遵守所在地法律法规及服务条款，谨慎通过公共代理传输敏感信息。

## Shadowrocket 客户端下载

| 平台 | 客户端 | 下载地址 |
| --- | --- | --- |
| iOS / iPadOS | Shadowrocket（小火箭） | [App Store](https://apps.apple.com/us/app/shadowrocket/id932747118) |

App Store 的可用地区和价格以商店页面为准。

