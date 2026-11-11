<div align="center">
  <a href="https://ymsv2.top">
    <img src="static/logo_1.png" width="120" alt="YourMusicStation" />
  </a>

  <h1>YourMusicStation</h1>

  <p>你的点歌台 · 一款简约美观的桌面音乐播放器</p>

  <p>
    <a href="https://ymsv2.top"><strong>官网</strong></a> ·
    <a href="https://ymsv2.top/views/download/"><strong>下载</strong></a> ·
    <a href="https://github.com/kiko-love/YourMusicStation/releases"><strong>Releases</strong></a> ·
    <a href="https://ymsv2.top/views/changelog/"><strong>更新日志</strong></a> ·
    <a href="https://txc.qq.com/products/634166"><strong>反馈</strong></a>
  </p>

  <p>
    <img src="https://img.shields.io/badge/platform-Windows%2010%2F11-0078D4" alt="platform" />
  </p>
</div>

## 简介

YourMusicStation（YMS）是一款面向中文音乐用户的 Windows 桌面播放器。它把在线音源、本地曲库、逐字歌词、下载、收听统计与 AI 助手放在同一套播放队列里：在线歌曲与本地文件可以混排播放，喜欢的声音也能留在自己的设备上。

> 本仓库用于发布安装包与使用引导，产品源码不在本仓库维护。

## ✨ 特性

- **在线与本地同队列**：多源音源解析、多档音质、每日推荐、私人 FM、排行榜、MV，以及本地目录扫描、标签读写与本地歌单。
- **完整的歌词体验**：多源逐字 / 翻译 / 音译歌词、偏移校正、桌面歌词与双语显示，本地同名歌词优先。
- **播放增强**：Gapless、AutoMix 交叉渐混音、智能音量平衡、均衡器 / 音效工作台、8D 环绕、播放速度、睡眠定时与 AB 循环。
- **AI 助手**：内置「悠米 Yomi」，用自然语言找歌、播放、建单、整理曲库、调音与改设置；提供 AI 工具箱、AI 调音与人声分离。
- **数据与账号**：播放历史、听歌统计、下载任务中心与额度、本地数据备份 / 导入 / 撤销、网易云扫码登录。
- **个性化与系统集成**：Light / Dark 双主题、封面取色背景、全屏自定义背景、迷你播放器、任务栏播控、SMTC、托盘、全局快捷键与深链。

## 📸 预览

<p align="center">
  <img src="https://ymsv2.top/home.png" width="49%" alt="首页" />
  <img src="https://ymsv2.top/player.png" width="49%" alt="播放页" />
</p>
<p align="center">
  <img src="https://ymsv2.top/local-music.png" width="49%" alt="本地音乐" />
  <img src="https://ymsv2.top/desktop-lyrics.png" width="49%" alt="桌面歌词" />
</p>

## 🚀 下载与安装

1. 访问 [官网](https://ymsv2.top) 或 [Releases](https://github.com/kiko-love/YourMusicStation/releases) 下载最新安装包。
2. 按需下载对应的 `.sha256` / `.md5` 校验文件。
3. 运行安装包，按提示完成安装。
4. 首次启动可选登录网易云账号，同步歌单、每日推荐与云盘。

系统要求：Windows 10 / 11 x64。

> 若安装包被杀毒软件误报，可先校验 SHA-256，再将安装包加入信任后运行；本软件不包含广告与捆绑组件。

## ❓ 常见问题

| 问题                 | 说明                                                                                         |
| -------------------- | -------------------------------------------------------------------------------------------- |
| 高音质仍播放标准音质 | 系统会按可用音源自动降级；高音源缺失时会回退到标准音质，可在播放页查看当前音质标记。         |
| 歌词没有完全同步     | 自动匹配可能命中 Live / 翻唱版本；可在歌词页手动切换来源或调整偏移，本地同名歌词会优先使用。 |
| 本地歌曲没有歌词     | 将同名 `.lrc` 文件放在歌曲旁，或在设置中配置歌词来源；也支持内嵌歌词。                       |
| 下载失败             | 检查网络与下载额度；客户端会自动重试，也可在任务中心手动重试。                               |
| 更新后出现异常       | 退出应用后清空缓存并重启；若仍异常，请携带版本号与日志到反馈区提交。                         |

## 💬 社区与反馈

- 产品区反馈：[兔小巢](https://txc.qq.com/products/634166)
- GitHub Issues：[kiko-love/YourMusicStation/issues](https://github.com/kiko-love/YourMusicStation/issues)
- QQ 交流群：`376047513` / `763036486` / `1019733982`
- 内测群：`971409447`
- QQ 频道：`ymusictation`

反馈时请附上客户端版本、Windows 版本、问题现象与复现步骤；崩溃或播放异常可同时提供日志。

## 📄 许可证与声明

- 软件免费提供，**任何付费下载或倒卖行为均与作者无关**，请立即停止。
- 本项目仅供学习研究使用，禁止商业用途或批量爬虫下载音乐内容；音乐、封面、歌词版权归各平台与权利人所有。
- 对因使用本软件下载音乐等行为引起的版权风险不承担任何法律责任；如有侵权，请联系项目删除。
- 本仓库内容遵循 [MIT](LICENSE) 许可；软件与音乐、封面、歌词等内容的版权归各自权利人所有。
