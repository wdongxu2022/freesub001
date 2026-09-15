# 免费节点订阅服务 (FreeSub)

> 自动抓取全球免费节点池，测活筛选后生成订阅链接
> 更新时间：每 6 小时自动运行

---

## 📡 订阅链接（运行完成后使用）

### V2RayN / v2rayNG 通用订阅
```
https://cdn.jsdelivr.net/gh/wdongxu2022/jiedian@master/output/v2ray.txt
```

### Clash / Clash Verge / ClashMeta
```
https://cdn.jsdelivr.net/gh/wdongxu2022/jiedian@master/output/clash.yaml
```

### sing-box / Hiddify / NekoBox
```
https://cdn.jsdelivr.net/gh/wdongxu2022/jiedian@master/output/singbox.json
```

### 按国家分类
| 地区 | 链接 |
|------|------|
| 香港 | `by-country/HK.txt` |
| 台湾 | `by-country/TW.txt` |
| 美国 | `by-country/US.txt` |
| 日本 | `by-country/JP.txt` |

---

## 🚀 使用方法

### V2RayN (Windows)
1. 打开 V2RayN
2. 点击「订阅」→「添加 URL」
3. 粘贴订阅链接 → 确定
4. 右键订阅 → 「更新订阅」

### Clash Verge
1. 打开 Clash Verge
2. 点击左侧「配置」
3. 点击「远程」→「添加」
4. 粘贴链接 → 确定

### NekoBox (Android/iOS)
1. 打开 NekoBox
2. 点击「+」→「导入 URL」
3. 粘贴链接

---

## ⚙️ 工作原理

1. **抓取**：从 53+ 个开源免费节点池抓取配置
2. **测活**：使用 sing-box 测试每个节点的可用性
3. **分类**：按国家、协议、家宽等分类
4. **生成**：输出 v2ray.txt、clash.yaml、singbox.json 等格式

---

## 🔄 自动更新

本项目使用 GitHub Actions 自动运行：
- 每 6 小时执行一次
- 运行完成后自动提交结果到仓库

访问 [Actions](https://github.com/wdongxu2022/jiedian/actions) 查看运行状态

---

## 📝 注意事项

- 免费节点稳定性无法保证，可能随时失效
- 建议同时配置多个订阅作为备用
- 家宽节点适合挂机、PT 下载，普通节点适合翻墙

---

**项目来源**: [freesub](https://github.com/hezhanleiok/freesub)  
**更新日期**: 2026-09-15
