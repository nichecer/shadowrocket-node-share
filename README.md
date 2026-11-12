# 小火箭 Shadowrocket 免费节点

这里整理 Shadowrocket 客户端可导入的节点 URI 和订阅，提供固定入口、导入说明和更新信息。

## 本次更新

- 最近成功整理：2026-11-12 08:05:09
- 节点数量：21
- 最低 TCP 延迟：31 ms（美国）
- 国家/地区：BY、EE、MD、德国、意大利、日本、美国、荷兰
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
| 🇺🇸 美国_03 | 美国 | VLESS | 31 ms |
| 🇺🇸 美国_02 | 美国 | VLESS | 34 ms |
| 🇯🇵 日本_01 | 日本 | SS | 149 ms |
| 🇩🇪 德国_01 | 德国 | VLESS | 161 ms |
| 🇩🇪 德国_02 | 德国 | VLESS | 184 ms |
| 🇩🇪 德国_03 | 德国 | VLESS | 186 ms |
| 🇲🇩 摩尔多瓦_01 | MD | VLESS | 187 ms |
| 🇺🇸 美国_01 | 美国 | VLESS | 195 ms |
| 🇳🇱 荷兰_02 | 荷兰 | VLESS | 205 ms |
| 🇮🇹 意大利_03 | 意大利 | SS | 216 ms |
| 🇮🇹 意大利_04 | 意大利 | SS | 221 ms |
| 🇮🇹 意大利_01 | 意大利 | SS | 223 ms |
| 🇮🇹 意大利_02 | 意大利 | SS | 224 ms |
| 🇪🇪 爱沙尼亚_01 | EE | VLESS | 245 ms |
| 🇮🇹 意大利_07 | 意大利 | SS | 252 ms |
| 🇮🇹 意大利_05 | 意大利 | SS | 252 ms |
| 🇮🇹 意大利_10 | 意大利 | SS | 252 ms |
| 🇮🇹 意大利_09 | 意大利 | SS | 258 ms |
| 🇮🇹 意大利_08 | 意大利 | SS | 260 ms |
| 🇮🇹 意大利_06 | 意大利 | SS | 261 ms |
| 🇧🇾 白俄罗斯_01 | BY | VLESS | 302 ms |

[查看完整延迟数据](latency.json)

## 免费节点列表

节点列表最多显示25个，订阅后查看全部节点

```text
vless://399b6b23-cc40-4831-a494-61948e2df133@jp.sofast.live:52683?encryption=none&security=none&type=tcp&headerType=none#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_03
vless://0afc6426-606c-48e7-bd70-3c424a416842@us22.sofast.live:58011?encryption=none&security=none&fp=chrome&type=tcp&headerType=none#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_02
ss://YWVzLTI1Ni1nY206QmVhVWY5YzBBRVdINDBQdQ==@154.36.158.197:8388#%F0%9F%87%AF%F0%9F%87%B5%20%E6%97%A5%E6%9C%AC_01
vless://3a667b02-3e6e-439e-9fdb-720ab7a5d306@167.233.182.104:2091?security=none&type=tcp&headerType=http&path=%2F%40TurboConfigs---%40TurboConfigs---%40TurboConfigs--%40TurboConfigs---%40TurboConfigs---%40TurboConfigs---%40TurboConfigs---%40TurboConfigs---%40TurboConfigs--%40TurboConfigs---%40TurboConfigs---%40TurboConfigs---%40TurboConfigs---%40TurboConfigs---%40TurboConfigs--%40TurboConfigs---%40TurboConfigs---%40TurboConfigs---&host=tgju.org&packetEncoding=xudp&flow=xtls-rprx-vision&encryption=mlkem768x25519plus.native.0rtt.idIqJLbBRhVvjLcCi75qK-I68clo9tz132HIDrp6JVA#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_01
vless://c16e8cdb-65dd-4049-bc65-14c051b8a6c6@2.26.251.236:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=mental-deprivation.ru&fp=firefox&pbk=1iVMMhJZgXHRY7tRlR-1kypF0YeaBcB7EjcfHRsYZX4&sid=4ff31b18d1bd8227&spx=%2F5f73ebfc9ef9c37&type=tcp&headerType=none#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_02
vless://b86451af-4c98-4b7d-96e5-16f2e9df1d46@shh-hja-bbw.speedbluepanel.sbs:2053?security=none&type=tcp&headerType=http&path=%2F&host=docs.github.com&packetEncoding=xudp&encryption=mlkem768x25519plus.native.0rtt.4ABzCb9yeBZzvV-bRT5Tqpb3kejYBGn4Vib4PJiSyUg#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_03
vless://0f11b72f-1af1-4f0a-b992-87a8241d9213@srv21.buddygpt.ru:443?encryption=none&security=reality&sni=packages.gitlab.com&fp=firefox&pbk=YEyZf6GvVcUG2VJnxyWOJQd8_ORz0n8Tw8Hs417OPxo&sid=5b524cdb28b6824a&type=xhttp&path=%2Fassets%2F1117b6ce&mode=auto#%F0%9F%87%B2%F0%9F%87%A9%20%E6%91%A9%E5%B0%94%E5%A4%9A%E7%93%A6_01
vless://e68cd1c5-6a74-4156-a931-cc63a46a4f18@homestead-walloping.sports-streams.org:443?security=reality&type=xhttp&path=%2F&host=repost.uz&packetEncoding=xudp&sni=repost.uz&fp=chrome&pbk=iQCvXMQZR-eT2MVmXP7c99cvcle22mVWuKem_345BWM&mode=auto&encryption=none#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_01
vless://3f5e89d5-591f-4ac9-b071-b05680b573c3@msk10.gacvpn.site:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=nl3-edge.gacvpn.site&fp=edge&pbk=Caj4X3VjnHfdRQzWLmjFCiG_CGw0scYYni6UxVfBs38&sid=db6a4219fb&type=tcp&headerType=none#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.54:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_03
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.63:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_04
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.18:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND1AMjAyLjUwLjI1My40NToxOTk5OQ==#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_02
vless://7ad63b26-bf70-4872-8fab-ebaf73a1e19d@5.129.202.80:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=mirror-50.topp-con.xyz&fp=chrome&pbk=NY2bvH4IFKTstWkBWwyU5MmlzuKk0nU08cBoHlti2S8&sid=2ef2b10d5143d798&type=tcp&headerType=none#%F0%9F%87%AA%F0%9F%87%AA%20%E7%88%B1%E6%B2%99%E5%B0%BC%E4%BA%9A_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.27:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_07
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.90:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_05
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.36:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_10
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.99:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_09
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.72:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_08
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.81:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_06
vless://cda0862a-0f87-4be9-8ed8-1d0c9e382839@196.196.148.63:443?security=reality&type=grpc&mode=gun&serviceName=204adda7e3da&packetEncoding=none&sni=717252g.nl8.h1clayd.click&fp=firefox&sid=d3bd772514c87d28&pbk=PD8Jdlg3xB9QY--jwQjp8PFPzCS8-Oryw6-HWBcHMFU#%F0%9F%87%A7%F0%9F%87%BE%20%E7%99%BD%E4%BF%84%E7%BD%97%E6%96%AF_01
```

## 反馈

欢迎在 Issues 反馈失效链接和导入问题，请说明客户端版本及错误提示，不要提交个人密码或私有订阅。

请遵守所在地法律法规及服务条款，谨慎通过公共代理传输敏感信息。

## Shadowrocket 客户端下载

| 平台 | 客户端 | 下载地址 |
| --- | --- | --- |
| iOS / iPadOS | Shadowrocket（小火箭） | [App Store](https://apps.apple.com/us/app/shadowrocket/id932747118) |

App Store 的可用地区和价格以商店页面为准。

