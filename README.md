# 小火箭 Shadowrocket 免费节点

这里整理 Shadowrocket 客户端可导入的节点 URI 和订阅，提供固定入口、导入说明和更新信息。

## 本次更新

- 最近成功整理：2026-11-15 20:05:10
- 节点数量：25
- 最低 TCP 延迟：36 ms（香港）
- 国家/地区：AL、EE、德国、意大利、日本、泰国、澳大利亚、美国、芬兰、荷兰、西班牙、香港
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
| 🇭🇰 香港_01 | 香港 | VLESS | 36 ms |
| 🇯🇵 日本_01 | 日本 | SS | 66 ms |
| 🇦🇺 澳大利亚_01 | 澳大利亚 | VLESS | 91 ms |
| 🇹🇭 泰国_01 | 泰国 | VLESS | 91 ms |
| 🇯🇵 日本_02 | 日本 | VLESS | 103 ms |
| 🇺🇸 美国_01 | 美国 | VLESS | 138 ms |
| 🇫🇮 芬兰_01 | 芬兰 | VLESS | 192 ms |
| 🇪🇪 爱沙尼亚_01 | EE | VLESS | 234 ms |
| 🇮🇹 意大利_06 | 意大利 | SS | 235 ms |
| 🇮🇹 意大利_01 | 意大利 | SS | 238 ms |
| 🇳🇱 荷兰_01 | 荷兰 | VLESS | 245 ms |
| 🇮🇹 意大利_02 | 意大利 | SS | 245 ms |
| 🇪🇸 西班牙_01 | 西班牙 | VLESS | 260 ms |
| 🇦🇱 阿尔巴尼亚_01 | AL | VLESS | 263 ms |
| 🇮🇹 意大利_04 | 意大利 | SS | 264 ms |
| 🇮🇹 意大利_08 | 意大利 | SS | 265 ms |
| 🇮🇹 意大利_10 | 意大利 | VLESS | 274 ms |
| 🇩🇪 德国_02 | 德国 | VLESS | 282 ms |
| 🇩🇪 德国_01 | 德国 | VLESS | 319 ms |
| 🇺🇸 美国_03 | 美国 | VLESS | 435 ms |
| 🇺🇸 美国_02 | 美国 | VLESS | 1278 ms |
| 🇮🇹 意大利_07 | 意大利 | SS | 1286 ms |
| 🇮🇹 意大利_05 | 意大利 | SS | 1287 ms |
| 🇮🇹 意大利_03 | 意大利 | SS | 1289 ms |
| 🇮🇹 意大利_09 | 意大利 | SS | 1335 ms |

[查看完整延迟数据](latency.json)

## 免费节点列表

节点列表最多显示25个，订阅后查看全部节点

```text
vless://8b17beac-b143-447d-aa68-14cbb121a602@8.217.1.203:8443?&security=reality&flow=xtls-rprx-vision&pbk=74P0QFvaK6B13rHsxR_t0lqRlg4YLuORD4VaHr5Jd38&sid=0bf55f64&fp=chrome&sni=www.apple.com&type=tcp&headerType=none&host=www.apple.com&path=%2F#%F0%9F%87%AD%F0%9F%87%B0%20%E9%A6%99%E6%B8%AF_01
ss://YWVzLTI1Ni1nY206QmVhVWY5YzBBRVdINDBQdQ==@154.36.158.197:8388#%F0%9F%87%AF%F0%9F%87%B5%20%E6%97%A5%E6%9C%AC_01
vless://57beeeb0-03fc-4fc9-94da-7604488a7134@zfapi.zalolink.com:54528?encryption=none&flow=xtls-rprx-vision&security=reality&sni=www.apple.com&fp=ios&pbk=7GvJVbR6BRhtrc8-rcZvB8qTFUF1LPeM_MmoZ04mBxo&sid=54cca3c1c1c7&type=tcp&headerType=none&host=www.apple.com#%F0%9F%87%A6%F0%9F%87%BA%20%E6%BE%B3%E5%A4%A7%E5%88%A9%E4%BA%9A_01
vless://57beeeb0-03fc-4fc9-94da-7604488a7134@zfapi.zalolink.com:11802?security=reality&type=tcp&packetEncoding=xudp&sni=psstatic.cdn.bcebos.com&fp=ios&flow=xtls-rprx-vision&sid=6c84fbac2d&pbk=FUBjYwXlKIVwF7IuJf5dt_HU2sUnrEt10s4TIlTe8Q4#%F0%9F%87%B9%F0%9F%87%AD%20%E6%B3%B0%E5%9B%BD_01
vless://57beeeb0-03fc-4fc9-94da-7604488a7134@zfapi.zalolink.com:43149?encryption=none&flow=xtls-rprx-vision&security=reality&sni=psstatic.cdn.bcebos.com&fp=firefox&pbk=cvong7paE8XIzzbKWgV5iUruP1pBqI2IhMuBHc8c0UE&sid=15aa0ad4&type=tcp&headerType=none#%F0%9F%87%AF%F0%9F%87%B5%20%E6%97%A5%E6%9C%AC_02
vless://6f6318b1-3ba5-4106-9365-8a8e19f04bd3@217.217.47.140:50769?encryption=mlkem768x25519plus.native.0rtt.Q87mgMmTfbfB0W6gBMUjZGuHSPmo8Ot7-obrW5-BD3o&security=reality&sni=ops.gx.nvidia.com&fp=chrome&pbk=7Q09Z_KU9vXvif4-pLfVc_Zwil-X4k41Iesv-HCk4wI&sid=7f3d68ed44&type=tcp&headerType=none#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_01
vless://b7977b65-cfd8-4db9-a029-6ef014a4ae4a@217.163.76.118:2086?encryption=none&security=none&type=xhttp&host=xvh.andishehparenting.com&path=%2F&mode=auto#%F0%9F%87%AB%F0%9F%87%AE%20%E8%8A%AC%E5%85%B0_01
vless://555b35c4-30f9-40c6-a61a-7f53ab1bea45@13.143.176.250:443?&security=reality&flow=xtls-rprx-vision&pbk=kBTMVLCNE0jjwuJF6H5-65l5Pe0QToS0Hg-9Tmaa7Sk&sid=1a2b3c4d&fp=firefox&sni=images.porsche.com&type=tcp&headerType=none&host=images.porsche.com&path=%2F#%F0%9F%87%AA%F0%9F%87%AA%20%E7%88%B1%E6%B2%99%E5%B0%BC%E4%BA%9A_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.45:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_06
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.63:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_01
vless://Fluffy_VPN-Oth8rOq3@104.171.135.229:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=absolute-disaster.org&fp=chrome&pbk=mpo4BIcoWiMXAQGt5a8IJ4MFkPJQyLC50dO_bXzC7z0&type=tcp&headerType=none&host=absolute-disaster.org#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.54:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_02
vless://4201786b-d99b-4147-a5f0-20d47acddb81@196.199.122.2:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=7aa271t.es1.h1clayd.click&fp=firefox&pbk=ZSmetD4e9QG5CiXhniHg5HJB68L4kwbgAkJmMHtVwEE&sid=42426c882c5fcd41&type=tcp&headerType=none#%F0%9F%87%AA%F0%9F%87%B8%20%E8%A5%BF%E7%8F%AD%E7%89%99_01
vless://cda0862a-0f87-4be9-8ed8-1d0c9e382839@196.196.148.85:443?encryption=none&security=reality&sni=5d0319t.nl7.h1clayd.click&fp=firefox&pbk=l-GzBDuNuhnjxoRlZqKvT7jAt_sbVAxhGFsAttO5kXs&sid=361d0dd59c70516f&type=tcp&headerType=none#%F0%9F%87%A6%F0%9F%87%B1%20%E9%98%BF%E5%B0%94%E5%B7%B4%E5%B0%BC%E4%BA%9A_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.18:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_04
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.27:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_08
vless://555b35c4-30f9-40c6-a61a-7f53ab1bea45@83.141.92.190:443?&security=reality&flow=xtls-rprx-vision&pbk=kBTMVLCNE0jjwuJF6H5-65l5Pe0QToS0Hg-9Tmaa7Sk&sid=1a2b3c4d&fp=firefox&sni=images.porsche.com&type=tcp&headerType=none&host=images.porsche.com&path=%2F#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_10
vless://c16e8cdb-65dd-4049-bc65-14c051b8a6c6@2.26.251.236:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=mental-deprivation.ru&pbk=1iVMMhJZgXHRY7tRlR-1kypF0YeaBcB7EjcfHRsYZX4&sid=4ff31b18d1bd8227&type=tcp&headerType=none#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_02
vless://7ad63b26-bf70-4872-8fab-ebaf73a1e19d@147.45.153.29:443?&security=reality&flow=xtls-rprx-vision&pbk=LEziyH-E4k9hehGRJkVi1FadVObB_NZJy8U7oUCVWXU&sid=b9120cd53ffd7bba&fp=firefox&sni=patch-46.topp-con.xyz&type=tcp&headerType=none&host=patch-46.topp-con.xyz&path=%2F#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_01
vless://cda0862a-0f87-4be9-8ed8-1d0c9e382839@196.245.52.187:443?security=reality&type=xhttp&path=%2F1812842934d4&packetEncoding=xudp&sni=35295cx.us8.h1clayd.click&fp=firefox&sid=9acff4d98e2fbcc6&pbk=LsaTohbE6CqCH9UbYKwIybVXG3E5Wgz_X9czqas2LAI&encryption=none#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_03
vless://a88d4614-2134-404c-9479-6aba1ca9cdfd@162.35.38.156:443?&security=reality&flow=xtls-rprx-vision&pbk=UkUbCx7k5ykWTJTr1jqCOxns6TwvTAbfR0JvJzuALjM&sid=a62b22480f962a1d&fp=firefox&sni=2499dbt.us12.h1clayd.click&type=tcp&headerType=none&host=2499dbt.us12.h1clayd.click&path=%2F#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.81:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_07
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.36:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_05
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0@202.50.253.90:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_03
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.72:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_09
```

## 反馈

欢迎在 Issues 反馈失效链接和导入问题，请说明客户端版本及错误提示，不要提交个人密码或私有订阅。

请遵守所在地法律法规及服务条款，谨慎通过公共代理传输敏感信息。

## Shadowrocket 客户端下载

| 平台 | 客户端 | 下载地址 |
| --- | --- | --- |
| iOS / iPadOS | Shadowrocket（小火箭） | [App Store](https://apps.apple.com/us/app/shadowrocket/id932747118) |

App Store 的可用地区和价格以商店页面为准。

