# 小火箭 Shadowrocket 免费节点

这里整理 Shadowrocket 客户端可导入的节点 URI 和订阅，提供固定入口、导入说明和更新信息。

## 本次更新

- 最近成功整理：2026-11-13 08:05:10
- 节点数量：21
- 最低 TCP 延迟：39 ms（香港）
- 国家/地区：AL、BY、EE、MD、意大利、日本、美国、荷兰、西班牙、香港
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
| 🇭🇰 香港_01 | 香港 | VMESS | 39 ms |
| 🇺🇸 美国_02 | 美国 | VLESS | 180 ms |
| 🇳🇱 荷兰_01 | 荷兰 | VLESS | 199 ms |
| 🇺🇸 美国_01 | 美国 | VLESS | 213 ms |
| 🇮🇹 意大利_10 | 意大利 | SS | 218 ms |
| 🇯🇵 日本_01 | 日本 | SS | 220 ms |
| 🇮🇹 意大利_02 | 意大利 | SS | 234 ms |
| 🇪🇸 西班牙_02 | 西班牙 | VLESS | 238 ms |
| 🇮🇹 意大利_04 | 意大利 | SS | 245 ms |
| 🇮🇹 意大利_01 | 意大利 | SS | 246 ms |
| 🇮🇹 意大利_03 | 意大利 | SS | 248 ms |
| 🇪🇸 西班牙_01 | 西班牙 | VLESS | 251 ms |
| 🇮🇹 意大利_07 | 意大利 | SS | 254 ms |
| 🇮🇹 意大利_08 | 意大利 | SS | 260 ms |
| 🇲🇩 摩尔多瓦_01 | MD | VLESS | 262 ms |
| 🇦🇱 阿尔巴尼亚_01 | AL | VLESS | 265 ms |
| 🇮🇹 意大利_05 | 意大利 | SS | 271 ms |
| 🇮🇹 意大利_09 | 意大利 | SS | 272 ms |
| 🇪🇪 爱沙尼亚_01 | EE | VLESS | 279 ms |
| 🇮🇹 意大利_06 | 意大利 | SS | 281 ms |
| 🇧🇾 白俄罗斯_01 | BY | VLESS | 1251 ms |

[查看完整延迟数据](latency.json)

## 免费节点列表

节点列表最多显示25个，订阅后查看全部节点

```text
vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7Ag6aaZ5rivXzAxIiwiYWRkIjoiNDcuMjQ0LjEyMC4xOTciLCJwb3J0IjoyMzAyNiwiYWlkIjowLCJzY3kiOiJhdXRvIiwibmV0Ijoid3MiLCJ0eXBlIjoibm9uZSIsInRscyI6IiIsImlkIjoiYjlkZTFiYzktYmFhNy00MWFjLTg2ZjctY2NkNTk2OTVjYjIxIiwic2tpcC1jZXJ0LXZlcmlmeSI6dHJ1ZSwic25pIjoiNDcuMjQ0LjEyMC4xOTciLCJob3N0IjoiNDcuMjQ0LjEyMC4xOTciLCJwYXRoIjoiL2Fya2kifQ==
vless://50a87e21-f0e2-4b53-a787-91adfe748f63@gemsubbgem.world:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=gemsubbgem.world&fp=chrome&pbk=6PJlXT9xrgJP8RXfhpWDMKPh4eqGt_IZmenc_a6v0gg&type=tcp&headerType=none#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_02
vless://1e2b9c0c-4f9b-56f5-a062-1c4f2d2aa200@201.51.11.65:443?&security=reality&flow=xtls-rprx-vision&pbk=GiDgVRVYrTkv1mZJeFVWkr736Iey2kqLM6L0eUbffV8&fp=chrome&sni=absolute-disaster.org&type=tcp&headerType=none&host=absolute-disaster.org&path=%2F#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_01
vless://7ad63b26-bf70-4872-8fab-ebaf73a1e19d@192.177.26.55:443?&security=reality&flow=xtls-rprx-vision&pbk=cC6kqzQ1mdCXyPey8xRXS7TQ1S4kF3nJW-h1ItJ4SH8&sid=bdaddda4cbc8c7bf&fp=chrome&sni=repo-16.topp-con.xyz&type=tcp&headerType=none&host=repo-16.topp-con.xyz&path=%2F#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.63:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_10
ss://YWVzLTI1Ni1nY206QmVhVWY5YzBBRVdINDBQdQ==@154.36.158.197:8388#%F0%9F%87%AF%F0%9F%87%B5%20%E6%97%A5%E6%9C%AC_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.18:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_02
vless://4201786b-d99b-4147-a5f0-20d47acddb81@196.196.149.80:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=7aa271t.es1.h1clayd.click&fp=firefox&pbk=ZSmetD4e9QG5CiXhniHg5HJB68L4kwbgAkJmMHtVwEE&sid=42426c882c5fcd41&type=tcp&headerType=none#%F0%9F%87%AA%F0%9F%87%B8%20%E8%A5%BF%E7%8F%AD%E7%89%99_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.72:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_04
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0@202.50.253.54:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.45:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_03
vless://585a421d-d782-4420-912e-dd58ff5966d7@9.247.174.134:8443?&security=reality&pbk=7jPluypHwPilf_Mq7JOY96SwKkbK35WuIlN1HwGQ_0A&sid=974f7f8f&fp=chrome&sni=play.googleapis.com&type=tcp&headerType=none&host=play.googleapis.com&path=%2F#%F0%9F%87%AA%F0%9F%87%B8%20%E8%A5%BF%E7%8F%AD%E7%89%99_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.81:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_07
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.99:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_08
vless://0f11b72f-1af1-4f0a-b992-87a8241d9213@srv21.buddygpt.ru:443?encryption=none&security=reality&sni=packages.gitlab.com&fp=firefox&pbk=YEyZf6GvVcUG2VJnxyWOJQd8_ORz0n8Tw8Hs417OPxo&sid=5b524cdb28b6824a&type=xhttp&path=%2Fassets%2F1117b6ce&mode=auto#%F0%9F%87%B2%F0%9F%87%A9%20%E6%91%A9%E5%B0%94%E5%A4%9A%E7%93%A6_01
vless://cda0862a-0f87-4be9-8ed8-1d0c9e382839@196.245.52.183:443?security=reality&type=xhttp&path=%2Fd20896a4ce30&packetEncoding=xudp&sni=e60833x.nl7.h1clayd.click&fp=firefox&sid=2d2598d60447a967&pbk=jIRVNEf9SpuWP2nJrAbHGGIUnfzOmwZZlrNGw-Y-O2Q&encryption=none#%F0%9F%87%A6%F0%9F%87%B1%20%E9%98%BF%E5%B0%94%E5%B7%B4%E5%B0%BC%E4%BA%9A_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0@202.50.253.90:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_05
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.27:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_09
vless://7ad63b26-bf70-4872-8fab-ebaf73a1e19d@5.129.202.80:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=mirror-50.topp-con.xyz&fp=chrome&pbk=NY2bvH4IFKTstWkBWwyU5MmlzuKk0nU08cBoHlti2S8&sid=2ef2b10d5143d798&type=tcp&headerType=none#%F0%9F%87%AA%F0%9F%87%AA%20%E7%88%B1%E6%B2%99%E5%B0%BC%E4%BA%9A_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.36:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_06
vless://cda0862a-0f87-4be9-8ed8-1d0c9e382839@79.182.39.131:443?security=reality&type=grpc&mode=gun&serviceName=204adda7e3da&packetEncoding=xudp&sni=717252g.nl8.h1clayd.click&fp=chrome&sid=d3bd772514c87d28&pbk=PD8Jdlg3xB9QY--jwQjp8PFPzCS8-Oryw6-HWBcHMFU&encryption=none#%F0%9F%87%A7%F0%9F%87%BE%20%E7%99%BD%E4%BF%84%E7%BD%97%E6%96%AF_01
```

## 反馈

欢迎在 Issues 反馈失效链接和导入问题，请说明客户端版本及错误提示，不要提交个人密码或私有订阅。

请遵守所在地法律法规及服务条款，谨慎通过公共代理传输敏感信息。

## Shadowrocket 客户端下载

| 平台 | 客户端 | 下载地址 |
| --- | --- | --- |
| iOS / iPadOS | Shadowrocket（小火箭） | [App Store](https://apps.apple.com/us/app/shadowrocket/id932747118) |

App Store 的可用地区和价格以商店页面为准。

