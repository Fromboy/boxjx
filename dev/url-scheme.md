---
description: 收集已经知几个 App 的 URL Scheme
---

# URL Scheme

## 公开接口

由于 URL Scheme 不能直接在部分 App (Telegram 等) 以超链接的形式显示

我们提供几个的自动重定向 (302) 接口，欢迎使用：

```properties
# 前缀:
https://api.boxjs.app/loon/…
https://api.boxjs.app/quanx/…
https://api.boxjs.app/surge/…
https://api.boxjs.app/shadowrocket/…
https://api.boxjs.app/stash/…
https://api.boxjs.app/clash/…

# 实例:
loon://update?sub=all
# 转换为: 
https://api.boxjs.app/loon/update?sub=all

# 其他同理...
# 注意 url-encode

```

#### **Surge:**&#x20;

[https://manual.nssurge.com/others/url-scheme.html](https://manual.nssurge.com/others/url-scheme.html)

#### **Quantumult X:**&#x20;

[https://github.com/crossutility/Quantumult-X/blob/master/url-scheme.md](https://github.com/crossutility/Quantumult-X/blob/master/url-scheme.md)

#### **Loon:**

```properties
# 安装插件
loon://import?plugin=https://raw.githubusercontent.com/chavyleung/scripts/master/box/rewrite/boxjs.rewrite.loon.plugin

# 更新资源
loon://update?sub=all

```

#### Shadowrocket

```properties
# 安装 & 更新插件
shadowrocket://install?module=https://raw.githubusercontent.com/chavyleung/scripts/master/box/rewrite/boxjs.rewrite.surge.sgmodule

```

#### Stash

[https://stash.wiki/qna/url-schema](https://stash.wiki/qna/url-schema)
