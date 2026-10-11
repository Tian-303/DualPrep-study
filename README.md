# DualPrep 双考计划 PWA

这是一个手机优先的静态 PWA，可安装到 iPhone / Android 主屏幕。

## 已内置
- CET-6：当前 528，目标 560+，阅读 182，弱项为听力与写译
- TOEFL：目标 5.0（2026 新 1–6 分制）
- 六级日期：2026-12-12
- 托福默认目标日期：2026-11-29（可在“设置”修改）
- 工作日约 2h、周末约 3h 的每日任务
- 本地打卡、学习分钟数、模考成绩记录
- 断网缓存（Service Worker）

## 最快部署方法
### GitHub Pages
1. 新建一个 GitHub 仓库。
2. 上传本目录全部文件。
3. Settings → Pages → Deploy from a branch → main / root。
4. 等页面生成 HTTPS 地址。

### Netlify / Vercel
把整个文件夹拖入静态部署项目即可。

## 安装到 iPhone
1. 用 Safari 打开部署后的 HTTPS 地址。
2. 点“分享”。
3. 选择“添加到主屏幕”。

## 说明
浏览器打卡数据使用 localStorage，数据只保存在当前手机浏览器中。
清理浏览器网站数据会清空记录。
