<br />
<p align="center">
  <a href="https://music.qier222.com" target="blank">
    <img src="static/logo_1.png" alt="Logo" width="156" height="156">
  </a>
  <h2 align="center" style="font-weight: 600">YourMusicStation</h2>

  <p align="center">
    简约高颜值的音乐播放器
    <br />
    <a href="https://ymsv2.top/" target="blank"><strong>🌎 访问官网</strong></a>&nbsp;&nbsp;|&nbsp;&nbsp;
    <a href="https://t.me/yesplaymusic" target="blank"><strong>💬 加入交流群</strong></a>
    <br />
    <br />
  </p>
</p>

![Electron](https://img.shields.io/badge/-Electron-47848F?style=flat&logo=electron&logoColor=white)
![Vue.js](https://img.shields.io/badge/-Vue.js-4FC08D?style=flat&logo=vue.js&logoColor=white)
[![GitHub stars](https://img.shields.io/github/stars/kiko-love/your-music-station-v1.svg)](https://github.com/kikolove/yourmusicstation-v1)


# 🎵 YourMusicStation  
#### 从 V1 (@学生时期练手项目) 平滑过渡到 V2 重构稳定版本（Windows）

---

## 📘 简要概览

### V1 · 本仓库（初版）  
V1 使用 Vue 3 + Electron 开发，包括：
- 基于 网易云音乐 API 的在线歌曲搜索与播放  
- 歌词逐句锁定与翻译功能  
- MV 支持与实时频谱可视化  
- 简易主题切换（暗／亮／莫兰迪色系）

*⚠️ V1 已退出维护，不适用于生产开发，仅建议作为学习参考。若需正式稳定体验，请直接查看正式版*

---

## 🌟 V2 · 正式 Windows 版

此版本为 **唯一推荐下载渠道**，严格遵循绿色、安全、简约的设计理念：

| ✅ 官方渠道下载 | 🔄 Windows 10/11 兼容 |
|----------------|------------------------|
| `https://ymsv2.top` | 不支持windows10以下版本 | 

---

### 🔥 Features

#### 🎨 个性化主题
- 暗色、亮色、莫兰迪等主题随心切换  
- 自定义配色方案导入 / 导出  
- 可调节布局，打造专属播放界面

#### 🎧 音乐体验全面升级
- **在线音乐**：网易云每日推荐、私人 FM、排行榜、MV 播放  
- **本地音乐**：扫描本地目录自动导入识别，离线播放无压力  

#### 📝 智能歌词系统
- 实时逐行定位歌词  
- 自动翻译外语歌词  
- 支持双语显示，适配不同主题背景

#### 🔄 云同步与账号支持
- 网易云账号扫码 / 登录同步歌单与播放历史  
- 播放记录和每日听歌排行本地化保存并可同步

#### ⚡ 流畅与稳定
- 原子级 UI 组件，非 WebView 渲染，毫秒级响应  
- 全局快捷键控制播放、切歌、调音量  
- 无广告、无隐私上传，绿色纯净

---

## ⚙️ 安装

1. 浏览器访问：[https://ymsv2.top](https://ymsv2.top)  
2. 点击“立即下载（Windows）”按钮，获取 `.exe` 安装包  
3. 双击安装包，系统将自动识别系统架构（x64 / ia32）并安装  
4. 安装完成后从开始菜单或桌面启动应用  
5. 首次启动推荐登录网易云账号以开启云端同步（可选）

> 若安装包被杀毒软件拦截，可信任程序并验证 SHA‑256 校验码。

---

## 💡 常见问题

| 问题 | 原因 & 解决方法 |
|------|------------------|
| 被杀软拦截 | 安装包临时写入 `%AppData%\Temp`，请设置信任或暂时关闭防护，安装后启用并校验安装签名 |
| 即使开启高音质仍播放标准音质 | 系统按“高 → 中 → 低”音质顺序尝试，若高音源缺失将自动回退 |
| 歌词不完全同步 | 自动匹配机制可能匹配 live 版本，如需修正可提交反馈，我们将持续优化 |

---

## 🛠 如何参与 / 贡献建议

- 本项目完全免费，长期由作者维护；**任何付费行为请立即停止**  
- 欢迎到官方反馈区提交建议、Bug、功能请求：  
  - 🐧群（若群满按提示加入备用群）：`376047513`
  - 🐧频道：`ymusictation`  
  - [产品区反馈：https://txc.qq.com/products/634166](https://txc.qq.com/products/634166)

---

## 📝 许可与声明
- YMS‑V1 与 V2 **仅供教育研究及源码学习使用**，严禁进行商业用途或批量爬虫下载音乐内容  
- 对因使用该软件下载音乐等行为引起的版权风险不承担任何法律责任  
- 遇到项目盗用、恶意传播等问题，请立即反馈并提报平台处理

---

📣 **感谢你使用 YourMusicStation，愿每一次“按下播放键”都成为温暖的陪伴。我们将继续优化开发，如你有热情和想法，欢迎一起探索！** 😊
