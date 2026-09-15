# 免费节点订阅服务 (FreeSub)

> 自动抓取全球免费节点池，测活筛选后生成订阅链接
> 更新时间：每 6 小时自动运行

---

## 📡 订阅链接说明

### 1️⃣ v2ray.txt - V2RayN / v2rayNG 通用订阅
```
https://raw.githubusercontent.com/wdongxu2022/jiedian/master/output/v2ray.txt
```
**用途**：V2RayN（Windows）、v2rayNG（Android）、Nekoray 等客户端
**格式**：base64 编码的混合配置
**推荐客户端**：V2RayN、v2rayNG、Hiddify Next

---

### 2️⃣ clash.yaml - Clash 系列订阅
```
https://raw.githubusercontent.com/wdongxu2022/jiedian/master/output/clash.yaml
```
**用途**：Clash Verge、Clash Meta、Clash for Windows
**格式**：YAML 配置，包含代理组、规则、节点
**推荐客户端**：Clash Verge Rev、Clash Nyanpasu、Clash Meta

---

### 3️⃣ singbox.json - sing-box 订阅
```
https://raw.githubusercontent.com/wdongxu2022/jiedian/master/output/singbox.json
```
**用途**：sing-box、NekoBox、Hiddify
**格式**：JSON 配置，支持 VLESS/Reality/Trojan/VMess
**推荐客户端**：NekoBox（Win/Android/iOS）、Hiddify Next、sing-box

---

### 4️⃣ residential.txt - 家宽节点专区
```
https://raw.githubusercontent.com/wdongxu2022/jiedian/master/output/residential.txt
```
**用途**：家宽节点，适合挂机、PT下载、防止封号
**特点**：IP 真实住宅地址，稳定性高
**推荐场景**：长期挂机、PT 流量交换

---

### 5️⃣ by-country/ - 按国家分类
```
# 香港
https://raw.githubusercontent.com/wdongxu2022/jiedian/master/output/by-country/HK.txt

# 台湾
https://raw.githubusercontent.com/wdongxu2022/jiedian/master/output/by-country/TW.txt

# 美国
https://raw.githubusercontent.com/wdongxu2022/jiedian/master/output/by-country/US.txt

# 日本
https://raw.githubusercontent.com/wdongxu2022/jiedian/master/output/by-country/JP.txt

# 新加坡
https://raw.githubusercontent.com/wdongxu2022/jiedian/master/output/by-country/SG.txt
```
**用途**：按地区筛选节点
**地区列表**：HK（香港）、TW（台湾）、US（美国）、JP（日本）、SG（新加坡）、KR（韩国）、DE（德国）、GB（英国）等

---

## 🚀 快速上手

### Windows 用户
- 使用 **V2RayN** → 导入 `v2ray.txt` 链接
- 使用 **Clash Verge** → 导入 `clash.yaml` 链接

### Android 用户
- 使用 **v2rayNG** → 导入 `v2ray.txt` 链接
- 使用 **NekoBox** → 导入 `singbox.json` 链接

### iOS 用户
- 使用 **NekoBox** → 导入 `singbox.json` 链接
- 使用 **Hiddify Next** → 导入 `singbox.json` 链接

---

## ⚙️ 工作原理

1. **抓取**：从 53+ 个开源免费节点池抓取配置
2. **测活**：使用 sing-box v1.14 测试每个节点的可用性
3. **分类**：按国家、协议、家宽等分类整理
4. **生成**：自动输出多种格式的配置文件

---

## 📊 当前订阅源数量

**53 个** 开源节点池，包括：
- freefq/free（国内常用）
- 10ium/telegram-configs-collector（Telegram 频道）
- ShatakVPN/ConfigForge-V2Ray（印度节点）
- 0xRadikal/Free-v2ray-Configs（已测活验证）
- anonymouskeys/Free-configs（全量节点）
- hamedcode/port-based-v2ray-configs（按端口分类）
- free-nodes/v2rayfree（每日更新）
- MatinGhanbari/v2ray-configs（精选节点）
- VovaplusEXP/p-configs（按协议分离）
- zhuhaiuk/free-nodes（小时更新）
- 等等...

---

## 🔄 自动更新

本项目使用 GitHub Actions 自动运行：
- 每 6 小时执行一次（UTC 0:00, 6:00, 12:00, 18:00）
- 运行完成后自动提交结果到仓库

👉 查看运行状态：[Actions](https://github.com/wdongxu2022/jiedian/actions)

---

## 📝 注意事项

- 免费节点稳定性无法保证，可能随时失效
- 建议同时配置多个订阅作为备用
- 家宽节点适合挂机、PT 下载，普通节点适合翻墙
- 如果发现节点泄露，请勿用于非法用途

---

**项目来源**: [freesub](https://github.com/hezhanleiok/freesub)  
**更新日期**: 2026-09-15  
**维护者**: wdongxu2022
