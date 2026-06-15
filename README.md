# 投资 × 英语 · 每日打卡 (PWA)

一个纯静态的每日打卡 PWA：投资 + 英语同步学习。无后端、无服务器，打卡数据保存在本机浏览器。

## 在线使用

GitHub Pages: https://songrsp.github.io/invest-english-checkin/

iPhone：用 **Safari** 打开上面网址 → 分享 → **添加到主屏幕**，即可像原生 app 一样使用，离线可用。

## 文件说明

- `index.html` — 应用本体（打卡、连续天数、热力图、单词卡）
- `manifest.webmanifest` — PWA 配置
- `sw.js` — 离线缓存（改版时把 `inv-en-v1` 改成 `v2`… 强制更新）
- `icon-192.png` / `icon-512.png` / `apple-touch-icon.png` — 图标

## 更新方法

修改文件后提交并推送到 `main` 分支，GitHub Pages 会自动重新部署。
