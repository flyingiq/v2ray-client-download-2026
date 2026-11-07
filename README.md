> 📅 最后更新：2026-11-07 · 节点与套餐信息实时同步

# 📦 全平台代理客户端下载与配置（2026 持续更新）

> Windows / macOS / Linux / Android / iOS 全平台客户端下载地址与快速配置说明。
> 全部为官方或可信来源，拒绝捆绑与修改版。

[![Platform](https://img.shields.io/badge/Platform-All-blue)]()
[![Updated](https://img.shields.io/badge/Updated-2026--11-brightgreen)]()
[![Safe](https://img.shields.io/badge/Source-Official-success)]()

📖 配套节点与线路推荐：[2026 最新平价稳定机场推荐](https://github.com/flyingiq/airport-recommended-2026)

---

## 目录

- [桌面端](#桌面端)
- [移动端](#移动端)
- [订阅格式对照](#订阅格式对照)
- [导入订阅](#导入订阅)
- [选择建议](#选择建议)

---

## 桌面端

### Windows

| 客户端 | 内核 | 特点 | 下载 |
|---|---|---|---|
| **Clash Verge Rev** | Mihomo | TUN 模式、规则可视化，推荐首选 | [Releases](https://github.com/clash-verge-rev/clash-verge-rev/releases) |
| **v2rayN** | Xray | 老牌稳定，支持 VLESS/REALITY | [Releases](https://github.com/2dust/v2rayN/releases) |
| **NekoRay** | sing-box / Xray | 轻量，协议覆盖广 | [Releases](https://github.com/MatsuriDayo/nekoray/releases) |
| **sing-box GUI** | sing-box | 官方图形界面 | [Releases](https://github.com/SagerNet/sing-box/releases) |

### macOS

| 客户端 | 说明 |
|---|---|
| **Clash Verge Rev** | 支持 Apple Silicon，推荐 |
| **ClashX Meta** | 菜单栏轻量方案 |
| **sing-box** | 命令行 / 图形版均有 |

### Linux

```bash
# Clash Verge Rev
wget https://github.com/clash-verge-rev/clash-verge-rev/releases/latest/download/clash-verge_x64.deb
sudo dpkg -i clash-verge_x64.deb

# sing-box（官方脚本）
curl -fsSL https://sing-box.app/install.sh | sh
```

---

## 移动端

### Android

| 客户端 | 特点 |
|---|---|
| **v2rayNG** | 最常用，支持 VLESS/REALITY/Hysteria2 |
| **NekoBox** | sing-box 内核，协议最全 |
| **Clash Meta for Android** | Clash 规则体系 |

**下载**：[v2rayNG Releases](https://github.com/2dust/v2rayNG/releases) · [NekoBox Releases](https://github.com/MatsuriDayo/NekoBoxForAndroid/releases)

### iOS

App Store 区域限制，需要非中国区账号：

| 客户端 | 价格 | 说明 |
|---|---|---|
| **Shadowrocket（小火箭）** | $2.99 | 最通用，协议支持全 |
| **Quantumult X** | $7.99 | 规则强大，进阶用户 |
| **sing-box** | 免费 | 官方客户端 |
| **Stash** | $3.99 | Clash 规则兼容 |

> 购买礼品卡充值非中国区账号即可，无需代购。

---

## 订阅格式对照

同一订阅链接，加不同后缀可获得不同格式：

```
原链接                     → 按 UA 自动判断
/sub/xxx/clash_meta       → Mihomo (Clash Meta)
/sub/xxx/clash            → Clash 旧版
/sub/xxx/sing_box         → sing-box
/sub/xxx/xray             → Xray / v2rayN
/sub/xxx/links            → 明文节点链接
```

**注意**：Clash Verge Rev 用 `clash_meta`，不要用 `clash`，否则新协议节点会丢失。

---

## 导入订阅

**v2rayNG**：
1. 左上角 ☰ → 订阅分组设置 → 添加订阅
2. 粘贴链接 → 返回首页 → 右上角刷新

**Clash Verge Rev**：
1. 订阅 → 新建 → 粘贴链接 → 更新

**Shadowrocket**：
1. 首页右上角 ➕ → 类型选 Subscribe → 粘贴链接 → 完成

**sing-box**：
1. 配置 → 新建 → 远程 → 粘贴链接 → 下载

---

## 选择建议

**按需求选**：

```
只求能用、要稳定      → Clash Verge Rev（桌面）/ v2rayNG（安卓）
需要规则分流          → Clash Meta 系
协议最新最全          → sing-box / NekoBox
iOS 省心              → Shadowrocket
命令行 / 服务器       → sing-box 或 mihomo
```

**常见误区**：

- ❌ 用旧版 Clash for Windows → 不支持 REALITY / Hysteria2
- ❌ 订阅用 `/clash` 后缀 → 新协议节点丢失
- ❌ 装了客户端就以为能上网 → 还需要可用节点

---

## 节点从哪来

客户端只是工具，真正决定体验的是**节点质量**：

- 协议：VLESS + REALITY 抗封锁最强
- 线路：CN2 GIA / 软银 / 9929 延迟更低
- IP：原生 IP 更适合流媒体与 AI 服务

📌 我整理的实测数据与选购建议：
**[2026 最新平价稳定机场推荐](https://github.com/flyingiq/airport-recommended-2026)**

🌐 商城：https://two.harnesscom.com
📊 节点状态：https://status.harnesscom.com

---

## 免责声明

本仓库仅整理公开客户端的官方下载地址，不提供任何节点或订阅。
请遵守所在地区法律法规。
