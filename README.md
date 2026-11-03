# 家宽 Clash 订阅

自动维护的家宽（住宅 IP）节点 Clash / Mihomo 订阅，每 6 小时自动更新一次。

## 订阅地址

```
https://raw.githubusercontent.com/325106/dy/main/clash-jiakuan-sub.yaml
```

把这个地址粘贴到 Clash Verge Rev、FlClash、NekoBox 等 **Mihomo 内核**客户端的订阅导入里即可（节点含 SOCKS4，老版 Clash 内核不支持）。

## 说明

- 文件：`clash-jiakuan-sub.yaml`，含「家宽自动」（自动测速选最快）和「家宽手动」（手动选择）两个组。
- 数据来源：[kael-odin/awesome-free-proxy-list](https://github.com/kael-odin/awesome-free-proxy-list)，只保留标记为 residential（住宅）的节点。
- 免费公共节点存活时间短、质量参差，请仅用于临时测试，不要用来登录重要账号或支付。
