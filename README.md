# 小火箭 Shadowrocket 免费节点

这里整理 Shadowrocket 客户端可导入的节点 URI 和订阅，提供固定入口、导入说明和更新信息。

## 本次更新

- 最近成功整理：2026-11-12 20:05:11
- 节点数量：20
- 最低 TCP 延迟：34 ms（香港）
- 国家/地区：EE、意大利、日本、美国、荷兰、西班牙、香港
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
| 🇭🇰 香港_01 | 香港 | VMESS | 34 ms |
| 🇺🇸 美国_03 | 美国 | VLESS | 36 ms |
| 🇺🇸 美国_04 | 美国 | VLESS | 38 ms |
| 🇯🇵 日本_01 | 日本 | SS | 59 ms |
| 🇺🇸 美国_02 | 美国 | VLESS | 185 ms |
| 🇺🇸 美国_01 | 美国 | VLESS | 196 ms |
| 🇺🇸 美国_05 | 美国 | VLESS | 211 ms |
| 🇮🇹 意大利_01 | 意大利 | SS | 221 ms |
| 🇮🇹 意大利_02 | 意大利 | SS | 230 ms |
| 🇮🇹 意大利_06 | 意大利 | SS | 234 ms |
| 🇮🇹 意大利_03 | 意大利 | SS | 253 ms |
| 🇮🇹 意大利_07 | 意大利 | SS | 254 ms |
| 🇮🇹 意大利_05 | 意大利 | SS | 266 ms |
| 🇮🇹 意大利_04 | 意大利 | SS | 266 ms |
| 🇮🇹 意大利_08 | 意大利 | SS | 271 ms |
| 🇮🇹 意大利_09 | 意大利 | SS | 274 ms |
| 🇳🇱 荷兰_01 | 荷兰 | VLESS | 283 ms |
| 🇪🇪 爱沙尼亚_01 | EE | VLESS | 287 ms |
| 🇪🇸 西班牙_01 | 西班牙 | VLESS | 1241 ms |
| 🇮🇹 意大利_11 | 意大利 | SS | 1264 ms |

[查看完整延迟数据](latency.json)

## 免费节点列表

节点列表最多显示25个，订阅后查看全部节点

```text
vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7Ag6aaZ5rivXzAxIiwiYWRkIjoiNDcuMjQ0LjEyMC4xOTciLCJwb3J0IjozNjcwMywiYWlkIjowLCJzY3kiOiJhdXRvIiwibmV0Ijoid3MiLCJ0eXBlIjoibm9uZSIsInRscyI6IiIsImlkIjoiNDViODM1MTktOWM0Zi00MDUyLWExMWItMDJlMDE3YjYzNmQ0Iiwic2tpcC1jZXJ0LXZlcmlmeSI6dHJ1ZSwicGF0aCI6Ii9hcmtpIn0=
vless://5aaa5259-f924-4682-a4a3-149d472a9dcc@jp.sofast.live:52683?encryption=none&security=&type=tcp#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_03
vless://0afc6426-606c-48e7-bd70-3c424a416842@us22.sofast.live:58011?encryption=none&security=&type=tcp#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_04
ss://YWVzLTI1Ni1nY206QmVhVWY5YzBBRVdINDBQdQ==@154.36.158.197:8388#%F0%9F%87%AF%F0%9F%87%B5%20%E6%97%A5%E6%9C%AC_01
vless://50a87e21-f0e2-4b53-a787-91adfe748f63@gemsubbgem.world:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=gemsubbgem.world&fp=chrome&pbk=6PJlXT9xrgJP8RXfhpWDMKPh4eqGt_IZmenc_a6v0gg&type=tcp&headerType=none#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_02
vless://50a87e21-f0e2-4b53-a787-91adfe748f63@sundaylanzgem.site:443?encryption=none&flow=xtls-rprx-vision&fp=qq&headerType=none&pbk=%2DBN9yCN0ECqxOPoJOan1-CIMEYc5e7wdJwaeDxsUM20&security=reality&sni=sundaylanzgem.site&type=tcp#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_01
vless://50a87e21-f0e2-4b53-a787-91adfe748f63@hollandlanzerotte.xyz:443?security=reality&type=tcp&sni=hollandlanzerotte.xyz&flow=xtls-rprx-vision&fp=chrome&pbk=EEL-yDPBfol_fiEEM8Pd0zue7SSz5MtZlXEePVak2jc#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_05
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.63:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.54:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.45:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_06
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.36:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_03
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.90:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_07
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.27:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_05
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.81:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_04
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.18:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_08
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.99:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_09
vless://1e2b9c0c-4f9b-56f5-a062-1c4f2d2aa200@72.56.38.83:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=absolute-disaster.org&fp=chrome&pbk=ZzIetLcQtENjIXQ9XZqFo8p3J81p8Emj0wi51Uy07n8&type=tcp&headerType=none&host=absolute-disaster.org#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_01
vless://7ad63b26-bf70-4872-8fab-ebaf73a1e19d@5.129.202.80:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=mirror-50.topp-con.xyz&fp=chrome&pbk=NY2bvH4IFKTstWkBWwyU5MmlzuKk0nU08cBoHlti2S8&sid=2ef2b10d5143d798&type=tcp&headerType=none#%F0%9F%87%AA%F0%9F%87%AA%20%E7%88%B1%E6%B2%99%E5%B0%BC%E4%BA%9A_01
vless://4201786b-d99b-4147-a5f0-20d47acddb81@196.199.122.2:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=7aa271t.es1.h1clayd.click&fp=firefox&pbk=ZSmetD4e9QG5CiXhniHg5HJB68L4kwbgAkJmMHtVwEE&sid=42426c882c5fcd41&type=tcp&headerType=none#%F0%9F%87%AA%F0%9F%87%B8%20%E8%A5%BF%E7%8F%AD%E7%89%99_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.72:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_11
```

## 反馈

欢迎在 Issues 反馈失效链接和导入问题，请说明客户端版本及错误提示，不要提交个人密码或私有订阅。

请遵守所在地法律法规及服务条款，谨慎通过公共代理传输敏感信息。

## Shadowrocket 客户端下载

| 平台 | 客户端 | 下载地址 |
| --- | --- | --- |
| iOS / iPadOS | Shadowrocket（小火箭） | [App Store](https://apps.apple.com/us/app/shadowrocket/id932747118) |

App Store 的可用地区和价格以商店页面为准。

