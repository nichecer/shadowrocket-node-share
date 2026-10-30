# 小火箭 Shadowrocket 免费节点

这里整理 Shadowrocket 客户端可导入的节点 URI 和订阅，提供固定入口、导入说明和更新信息。

## 本次更新

- 最近成功整理：2026-10-30 08:05:09
- 节点数量：27
- 最低 TCP 延迟：7 ms（美国）
- 国家/地区：CZ、EE、俄罗斯、印度、德国、意大利、新加坡、瑞典、美国、英国、阿联酋、香港
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
| 🇺🇸 美国_05 | 美国 | VLESS | 7 ms |
| 🇭🇰 香港_02 | 香港 | VLESS | 36 ms |
| 🇭🇰 香港_03 | 香港 | VLESS | 126 ms |
| 🇮🇳 印度_01 | 印度 | VLESS | 148 ms |
| 🇺🇸 美国_04 | 美国 | VLESS | 190 ms |
| 🇩🇪 德国_01 | 德国 | VLESS | 199 ms |
| 🇨🇿 捷克_01 | CZ | VLESS | 204 ms |
| 🇸🇪 瑞典_01 | 瑞典 | VLESS | 216 ms |
| 🇮🇹 意大利_07 | 意大利 | SS | 225 ms |
| 🇦🇪 阿联酋_01 | 阿联酋 | VLESS | 230 ms |
| 🇮🇹 意大利_01 | 意大利 | SS | 241 ms |
| 🇷🇺 俄罗斯_01 | 俄罗斯 | VLESS | 242 ms |
| 🇬🇧 英国_01 | 英国 | VLESS | 243 ms |
| 🇺🇸 美国_01 | 美国 | VLESS | 248 ms |
| 🇮🇹 意大利_03 | 意大利 | SS | 254 ms |
| 🇮🇹 意大利_08 | 意大利 | SS | 258 ms |
| 🇮🇹 意大利_04 | 意大利 | SS | 264 ms |
| 🇮🇹 意大利_09 | 意大利 | SS | 265 ms |
| 🇺🇸 美国_02 | 美国 | VLESS | 274 ms |
| 🇮🇹 意大利_10 | 意大利 | SS | 276 ms |
| 🇮🇹 意大利_02 | 意大利 | SS | 277 ms |
| 🇮🇹 意大利_06 | 意大利 | SS | 280 ms |
| 🇸🇪 瑞典_02 | 瑞典 | VLESS | 287 ms |
| 🇮🇹 意大利_05 | 意大利 | SS | 301 ms |
| 🇺🇸 美国_03 | 美国 | VLESS | 307 ms |

[查看完整延迟数据](latency.json)

## 免费节点列表

节点列表最多显示25个，订阅后查看全部节点

```text
vless://399b6b23-cc40-4831-a494-61948e2df133@jp.sofast.live:52683?encryption=none&type=tcp#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_05
vless://928e6cce-8ced-4243-9a48-a6642edd09b0@47.238.210.5:13779?security=reality&type=raw&packetEncoding=xudp&sni=tesla.com&fp=chrome&sid=af1bdd293097b664&pbk=llTyp52oRXnJmQ3I9UUrmlwbMA79B-wLCRHCu-8dLGg#%F0%9F%87%AD%F0%9F%87%B0%20%E9%A6%99%E6%B8%AF_02
vless://d98b67d4-024a-4bba-91e2-e6ebece6df11@38.76.180.144:1443?&fp=chrome&sni=38.76.180.144&type=ws&headerType=none&host=38.76.180.144&path=%2Fvless-ws#%F0%9F%87%AD%F0%9F%87%B0%20%E9%A6%99%E6%B8%AF_03
vless://5e679ccd-1586-4d5f-b87b-48251046cad8@hydra.yokkastars.com:2443?security=reality&type=grpc&mode=gun&serviceName=rex-eb0bf76b710ce763&packetEncoding=xudp&sni=deepl.com&fp=qq&sid=92c32de179e5d908&pbk=h85e28MxBgNyT9d9cNeOLVtWfHq6cT_1_oxZOTajtTg#%F0%9F%87%AE%F0%9F%87%B3%20%E5%8D%B0%E5%BA%A6_01
vless://1fe01c8a-ab37-4e95-bbfc-95d4a608931e@185.168.208.190:47443?security=reality&type=tcp&packetEncoding=xudp&sni=us-1.waspguard.ru&fp=firefox&flow=xtls-rprx-vision&sid=ae97246a8f799854&pbk=hz7rzdHvTAVwfy48pa6313yBF-sV7V0svvPVnl95bgY&encryption=none#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_04
vless://9c6e83fc-b755-4ad4-9b0a-14b610153d8f@5.187.4.75:8443?security=reality&type=tcp&packetEncoding=xudp&sni=www.samsung.com&fp=qq&flow=xtls-rprx-vision&sid=25115fee0590a21e&pbk=0bmhEnhtswgFKbBedH4ez5O4xmgMfXIuEuSdFLy0PmI#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_01
vless://b18d5990-96eb-4587-a386-7f8ef7591e6a@cz-prg.dontblockmepls.com:2063?encryption=none&security=reality&sni=rusbid.de&fp=firefox&pbk=MMpt_jWc4J3oySBdf5sPDVRkiWlZmOObth6A1scM9BM&type=tcp&headerType=none&insecure=0&flow=xtls-rprx-vision#%F0%9F%87%A8%F0%9F%87%BF%20%E6%8D%B7%E5%85%8B_01
vless://f8d52ece-fad4-478d-875d-df6eed3befa7@se-2.pythonsetupbib.online:61374?encryption=none&security=reality&sni=se-2.pythonsetupbib.online&fp=chrome&pbk=QrNs0ew7snHqLfpVXS9RAhlRzgAzzGZK9fXmDcx9xHI&type=xhttp&host=se-2.pythonsetupbib.online&path=%2F&mode=packet-up&extra=%7B%22xPaddingBytes%22%3A%22100-500%22%2C%22xmux%22%3A%7B%22maxConnections%22%3A%223%22%7D%7D#%F0%9F%87%B8%F0%9F%87%AA%20%E7%91%9E%E5%85%B8_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.99:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_07
vless://1fe01c8a-ab37-4e95-bbfc-95d4a608931e@187.52.44.20:47443?security=reality&type=tcp&packetEncoding=xudp&sni=nl4.waspnest.space&fp=firefox&flow=xtls-rprx-vision&sid=ae97223a8f799872&pbk=g5am2VhZkx_xH2TSKfUU8OYLxAzFrmcszNQg8AbOenE#%F0%9F%87%A6%F0%9F%87%AA%20%E9%98%BF%E8%81%94%E9%85%8B_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.63:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_01
vless://9ea8b000-58ce-0005-b108-989dd4f248f1@146.185.197.95:443?security=none&type=ws&path=%2Flive%2Fws2&packetEncoding=xudp&encryption=mlkem768x25519plus.native.0rtt.8th1uEEPtl2BhPfgxINwmVO_Kq6V1htSghiTMdjWkRM#%F0%9F%87%B7%F0%9F%87%BA%20%E4%BF%84%E7%BD%97%E6%96%AF_01
vless://ca14493b-b984-4ffb-bc0e-9cb5da969e15@tau1.freerunet.online:443?encryption=none&security=reality&sni=tau1.freerunet.online&fp=safari&pbk=l1mx_plNc2oiWxJCcZLh3SGfFU-5QxYpgQ__Ea59WEg&sid=4a7b1c8d&type=tcp&headerType=none&insecure=0&flow=xtls-rprx-vision#%F0%9F%87%AC%F0%9F%87%A7%20%E8%8B%B1%E5%9B%BD_01
vless://50a87e21-f0e2-4b53-a787-91adfe748f63@swedenafteraventura.space:443?security=reality&encryption=none&pbk=TyuIIquHoesD9YwMQJHda0YZ3Hy9Dh123dQ00iGK0QY&headerType=none&fp=chrome&type=tcp&flow=xtls-rprx-vision&sni=swedenafteraventura.space#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.90:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_03
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.27:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_08
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.36:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_04
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.45:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_09
vless://50a87e21-f0e2-4b53-a787-91adfe748f63@swidenafterlanzerotte.space:443?security=reality&type=tcp&packetEncoding=xudp&sni=swidenafterlanzerotte.space&fp=qq&flow=xtls-rprx-vision&pbk=MQrvfivvEfLGzDee7h0j5uC-DwaD_38_NXOY9-NhqxM&encryption=none#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.54:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_10
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.18:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.72:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_06
vless://a0fa7e19-70ec-41e0-b0cc-bcc984d4201a@s12.bsh-net.ru:443?security=reality&type=tcp&packetEncoding=xudp&sni=s12.bsh-net.ru&fp=chrome&flow=xtls-rprx-vision&sid=51079f144d661484&pbk=QvT-t_h_AF2EAT4Ggh_a6pcCK3StY8G9WCXn6-dJbxk&encryption=none#%F0%9F%87%B8%F0%9F%87%AA%20%E7%91%9E%E5%85%B8_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.81:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_05
vless://6c713691-3ca2-4446-ad25-113d1bed6b03@78.17.178.125:443?encryption=none&security=reality&sni=cdn.tbank.ru&fp=chrome&pbk=jcp4Lj_qYzxtkalm_XFjrmvqEMGRG7sb19yMwLe16WE&sid=e0215064d8d1fd7c&type=tcp&headerType=none&host=%2F%3FTELEGRAM---MARAMBASHI---MARAMBASHI---MARAMBASHI---MARAMBASHI&insecure=0&flow=xtls-rprx-vision#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_03
```

## 反馈

欢迎在 Issues 反馈失效链接和导入问题，请说明客户端版本及错误提示，不要提交个人密码或私有订阅。

请遵守所在地法律法规及服务条款，谨慎通过公共代理传输敏感信息。

## Shadowrocket 客户端下载

| 平台 | 客户端 | 下载地址 |
| --- | --- | --- |
| iOS / iPadOS | Shadowrocket（小火箭） | [App Store](https://apps.apple.com/us/app/shadowrocket/id932747118) |

App Store 的可用地区和价格以商店页面为准。

