# 小火箭 Shadowrocket 免费节点

少一点四处寻找，多一点清楚明白。

这里整理 Shadowrocket 客户端可导入的节点 URI 和订阅，提供固定入口、导入说明和更新信息。

## 本次更新

- 最近成功整理：2026-10-28 19:29:31
- 节点数量：40
- 定时更新：**08:00、20:00**
- 节点协议：VMess、VLESS、Trojan、Shadowsocks。

## 订阅入口

| 文件 | 地址 | 用途 |
| --- | --- | --- |
| Base64 订阅 | [sub.txt](https://raw.githubusercontent.com/nichecer/shadowrocket-node-share/main/sub.txt) | 在兼容的 Shadowrocket 客户端中添加订阅 |
| 明文节点 | [nodes.txt](https://raw.githubusercontent.com/nichecer/shadowrocket-node-share/main/nodes.txt) | 按需复制单条节点并导入 |

### 订阅二维码

![Shadowrocket 订阅二维码](sub.svg)

## 免费节点列表

```text
vless://928e6cce-8ced-4243-9a48-a6642edd09b0@47.238.210.5:13779?security=reality&type=raw&packetEncoding=xudp&sni=tesla.com&fp=chrome&sid=af1bdd293097b664&pbk=llTyp52oRXnJmQ3I9UUrmlwbMA79B-wLCRHCu-8dLGg#%F0%9F%87%AD%F0%9F%87%B0%20%E9%A6%99%E6%B8%AF_02
vless://4d8cc1c2-2605-43c4-8e17-dcafa86d9757@213.152.180.55:2092?encryption=none&security=reality&sni=www.apple.com&fp=chrome&pbk=zeyIqmHylDrPbbtdG9BleBt0-fqKCHpZ0OZ9OY2_WUI&sid=716b7eba38125f3a&type=tcp&headerType=none&insecure=0&flow=xtls-rprx-vision#%F0%9F%87%AB%F0%9F%87%B7%20%E6%B3%95%E5%9B%BD_01
vless://a346c521-7a7f-452b-9356-a4893feb5982@62.133.63.45:8444?security=reality&type=grpc&mode=gun&serviceName=GunService&packetEncoding=xudp&sni=github.com&fp=safari&sid=457fab2ac885dbe0&pbk=FWitre1jinQR7qz5HQ0q2Q4Gg9xA9B0SyizCziN7Ch0#%F0%9F%87%B9%F0%9F%87%B7%20%E5%9C%9F%E8%80%B3%E5%85%B6_01
vless://846cedee-2a52-0002-a0b9-11850ead6a8b@nl-central.v8x2b.lol:443?encryption=none&security=reality&sni=nl-central.v8x2b.lol&fp=chrome&pbk=q3UXFUE5yYxNE4ugLUnYdpc9WRtR-sjsDTrKsiqzDHE&type=tcp&headerType=none&insecure=0&flow=xtls-rprx-vision#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_01
vless://16107a06-1b5e-4060-8b48-e13a04b15e56@213.152.180.55:2095?encryption=none&security=reality&sni=www.apple.com&fp=chrome&pbk=OKksVHWL5JepTv7if7Ta_L_7vn8OxW0INwV71HJM1jI&sid=3869d49a9a79e06a&type=tcp&headerType=none&insecure=0&flow=xtls-rprx-vision#%F0%9F%87%AA%F0%9F%87%B8%20%E8%A5%BF%E7%8F%AD%E7%89%99_01
vless://19456d94-8f54-4f82-ae9c-0e19afb5c29c@213.152.180.104:2093?encryption=none&security=reality&sni=www.apple.com&fp=chrome&pbk=C_GA8wVjeLmyqLK6em5OHn4WPlsbndA-RyvyNU1aGFM&sid=8a9725533854a7e8&type=tcp&headerType=none&insecure=0&flow=xtls-rprx-vision#%F0%9F%87%A8%F0%9F%87%A6%20%E5%8A%A0%E6%8B%BF%E5%A4%A7_01
vless://50a87e21-f0e2-4b53-a787-91adfe748f63@sundaylanzgem.site:443?encryption=none&security=reality&sni=sundaylanzgem.site&fp=qq&pbk=-BN9yCN0ECqxOPoJOan1-CIMEYc5e7wdJwaeDxsUM20&type=tcp&headerType=none&insecure=0&flow=xtls-rprx-vision#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_01
vless://e5c3d067-7a15-4977-90c0-7e0f6e896a09@216.167.126.97:443?security=reality&type=tcp&packetEncoding=xudp&sni=www.cloudflare.com&fp=chrome&flow=xtls-rprx-vision&sid=0123456789abcdef&pbk=yFvOpugh65xKQNAwKrhitv4d2pflD8QwNFMj-jDOmT8#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_02
vless://5a519754-a673-4462-83f6-5eb25d2af141@79.182.39.35:25548?encryption=none&security=reality&sni=www.cloudflare.com&fp=firefox&pbk=lceynvFy326oU4ew9OPR7079m-L5ZcFELgCl0sqxU2M&sid=bceb5b2197b76818&type=tcp&headerType=none&insecure=0#%F0%9F%87%B5%F0%9F%87%B1%20%E6%B3%A2%E5%85%B0_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND1AMjAyLjUwLjI1My45OToxOTk5OQ==#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_01
vless://372af4ce-2153-4061-822c-b657172308f6@213.152.180.104:2094?encryption=none&security=reality&sni=www.apple.com&fp=chrome&pbk=jHtC6ayzhkd_GVNF5TIGPu9iVpqUltBAQj1dpGJHwxs&sid=55986a94e2228791&type=tcp&headerType=none&insecure=0&flow=xtls-rprx-vision#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0@202.50.253.18:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_02
vless://ca14493b-b984-4ffb-bc0e-9cb5da969e15@tau1.freerunet.online:443?encryption=none&security=reality&sni=tau1.freerunet.online&fp=safari&pbk=l1mx_plNc2oiWxJCcZLh3SGfFU-5QxYpgQ__Ea59WEg&sid=4a7b1c8d&type=tcp&headerType=none&insecure=0&flow=xtls-rprx-vision#%F0%9F%87%AC%F0%9F%87%A7%20%E8%8B%B1%E5%9B%BD_01
vless://405b964e-a2d2-454f-aaaa-711cc218897c@5.253.28.240:40443?encryption=none&security=reality&sni=deepl.com&fp=chrome&pbk=cwmcqsfS7klQlkcoUNuATEk0NiPY-NnRb9z8rCJDQw0&sid=88b6&type=tcp&headerType=none&insecure=0&flow=xtls-rprx-vision#%F0%9F%87%AE%F0%9F%87%B3%20%E5%8D%B0%E5%BA%A6_01
vless://6a26029d-5639-473a-9234-3e80d0633d7d@213.152.165.198:2091?encryption=none&security=reality&sni=www.apple.com&fp=chrome&pbk=1N6AW5YuEwBoYcZK5KuugDzBHsa0NKZMT8QI-EmyL0k&sid=08a4b1f473932632&type=tcp&headerType=none&insecure=0&flow=xtls-rprx-vision#%F0%9F%87%AD%F0%9F%87%B0%20%E9%A6%99%E6%B8%AF_03
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.81:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_03
vless://6c713691-3ca2-4446-ad25-113d1bed6b03@78.17.178.125:443?encryption=none&security=reality&sni=cdn.tbank.ru&fp=chrome&pbk=jcp4Lj_qYzxtkalm_XFjrmvqEMGRG7sb19yMwLe16WE&sid=e0215064d8d1fd7c&type=tcp&headerType=none&insecure=0&flow=xtls-rprx-vision#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_03
vless://846cedee-2a52-4a62-a0b9-11850ead6a8b@46.8.43.125:443?encryption=none&security=reality&sni=kz-central.v8x2b.lol&fp=firefox&pbk=ER-T5En54-sn6IXy7jU8vQVcBbOiWvznnezf3qZ273w&type=tcp&headerType=none&insecure=0#%F0%9F%87%B0%F0%9F%87%BF%20%E5%93%88%E8%90%A8%E5%85%8B%E6%96%AF%E5%9D%A6_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.72:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_04
vless://a0fa7e19-70ec-41e0-b0cc-bcc984d4201a@snp.bsh-net.ru:443?encryption=none&security=reality&sni=snp.bsh-net.ru&fp=chrome&pbk=iE4sTz-Q2Frkm7WM32P1wm4at49Wpaj5vo-2FsLcN1M&sid=8854f17e2a5af2d8&type=tcp&headerType=none&insecure=0&flow=xtls-rprx-vision#%F0%9F%87%B8%F0%9F%87%AC%20%E6%96%B0%E5%8A%A0%E5%9D%A1_01
vless://b18d5990-96eb-4587-a386-7f8ef7591e6a@cz-prg.dontblockmepls.com:2063?encryption=none&security=reality&sni=rusbid.de&fp=firefox&pbk=MMpt_jWc4J3oySBdf5sPDVRkiWlZmOObth6A1scM9BM&type=tcp&headerType=none&insecure=0&flow=xtls-rprx-vision#%F0%9F%87%A8%F0%9F%87%BF%20%E6%8D%B7%E5%85%8B_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.27:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_05
vless://9a92729a-7b89-475b-a651-cfd246524403@213.152.180.55:2090?encryption=none&security=reality&sni=www.apple.com&fp=chrome&pbk=qBobe6KSNkFLqTPCffcJo0nXgxy-3JKru9WRqY9rkjk&sid=bb472a184677af64&type=tcp&headerType=none&insecure=0&flow=xtls-rprx-vision#%F0%9F%87%AF%F0%9F%87%B5%20%E6%97%A5%E6%9C%AC_01
vless://f90b7d43-69e2-4b46-a672-8029bc6796a2@ee.h1cloud.net:25895?security=reality&type=tcp&packetEncoding=xudp&sni=www.samsung.com&fp=firefox&sid=a73f0410d728c823&pbk=jOVKSP-bS9OkILJ8Epz8hadh6qhavCrOiJYeF0NCn0k#%F0%9F%87%AA%F0%9F%87%AA%20%E7%88%B1%E6%B2%99%E5%B0%BC%E4%BA%9A_01
vless://5a519754-a673-4462-83f6-5eb25d2af141@f36f5ft.us4.h1clayd.click:443?&security=reality&pbk=5KZVzOFqMgdL47--JzLlg5HmPlAYp-cmQsXxkTXngS0&sid=8d50d3a4df71468c&fp=chrome&sni=f36f5ft.us4.h1clayd.click&type=tcp&headerType=none&host=f36f5ft.us4.h1clayd.click&path=%2F#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_04
```

## 反馈

欢迎在 Issues 反馈失效链接和导入问题，请说明客户端版本及错误提示，不要提交个人密码或私有订阅。

请遵守所在地法律法规及服务条款，谨慎通过公共代理传输敏感信息。

## Shadowrocket 客户端下载

| 平台 | 客户端 | 下载地址 |
| --- | --- | --- |
| iOS / iPadOS | Shadowrocket（小火箭） | [App Store](https://apps.apple.com/us/app/shadowrocket/id932747118) |

App Store 的可用地区和价格以商店页面为准。

