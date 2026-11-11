<p align="center">
  <a href="https://ymsv2.top" target="_blank" rel="noopener">
    <img src="static/logo_1.png" height="120" alt="YourMusicStation" />
  </a>
</p>

<h2 align="center">YourMusicStation</h2>

<p align="center">
  你的点歌台 · 简约美观的桌面音乐播放器<br />
  <strong>V1 · 当前版本 1.5.5</strong>
</p>

<p align="center">
  <a href="https://ymsv2.top"><strong>官网</strong></a> ·
  <a href="https://ymsv2.top/views/download/"><strong>下载</strong></a> ·
  <a href="https://github.com/kiko-love/YourMusicStation/releases"><strong>Releases</strong></a> ·
  <a href="https://ymsv2.top/views/changelog/"><strong>更新日志</strong></a> ·
  <a href="https://txc.qq.com/products/634166"><strong>问题反馈</strong></a>
</p>

> **仓库说明**：本仓库是 YourMusicStation V1 的安装引导与版本发布仓库。V1 源码不在本仓库维护，仓库内只保留产品介绍、下载安装、常见问题与反馈入口；历史源码可在 git 历史中查看。

## 关于 V1

YourMusicStation（YMS）是一款面向中文音乐用户的 Windows 桌面播放器。它把在线音源、本地曲库、逐字歌词、下载、收听统计与 AI 助手放在同一套播放队列里：在线歌曲与本地文件可以混排播放，喜欢的声音也能留在自己的设备上。

当前 **1.5.5** 是 V1 维护线的最新版本，包含多源音源、本地音乐、桌面歌词、AutoMix、AI 助手「悠米 Yomi」、AI 工具箱与全屏自定义背景等能力。

## 功能亮点

| 模块       | 能力                                                                                                                    |
| ---------- | ----------------------------------------------------------------------------------------------------------------------- |
| 在线音乐   | 每日推荐、私人 FM、排行榜、歌单 / 专辑 / 歌手 / 搜索、MV 播放与画质切换                                                 |
| 本地音乐   | 目录扫描与监听、全格式标签读写、封面、本地歌单，与在线歌曲共用同一播放队列                                              |
| 音源与音质 | 多源音源解析、多档音质、不可用音源自动降级、智能缓存                                                                    |
| 播放体验   | Gapless、AutoMix 交叉渐混音、智能音量平衡、均衡器 / 音效工作台、8D 环绕、播放速度、睡眠定时、AB 循环                    |
| 歌词       | 多源逐字 / 翻译 / 音译歌词、偏移校正、桌面歌词、双语显示；本地同名歌词优先，结果自动缓存                                |
| AI 助手    | 「悠米 Yomi」自然语言找歌、播放、建单、整理曲库、调音、改设置；AI 工具箱、AI 调音、人声分离，支持多家服务商与自定义接入 |
| 数据与账号 | 播放历史与听歌统计、下载任务中心与额度、本地数据备份 / 导入 / 撤销、网易云扫码登录、爱发电赞助绑定                      |
| 个性化     | Light / Dark 双主题、封面取色背景、全屏自定义背景、图标动效、迷你播放器、任务栏播控、SMTC、托盘、全局快捷键             |

## 预览

| 首页                                           | 播放页                                            |
| ---------------------------------------------- | ------------------------------------------------- |
| ![首页](https://ymsv2.top/home.png)            | ![播放页](https://ymsv2.top/player.png)           |
| **本地音乐**                                   | **桌面歌词**                                      |
| ![本地音乐](https://ymsv2.top/local-music.png) | ![桌面歌词](https://ymsv2.top/desktop-lyrics.png) |

## 安装

1. 浏览器访问 [ymsv2.top](https://ymsv2.top)，或直接前往 [Releases](https://github.com/kiko-love/YourMusicStation/releases) 下载最新安装包。
2. 下载 `your-music-station-1.5.5-setup.exe` 及对应的 `.sha256` / `.md5` 校验文件（可选）。
3. 运行安装包，按提示完成安装。
4. 首次启动可选登录网易云账号，同步歌单、每日推荐与云盘。

系统要求：Windows 10 / 11 x64。

> 若安装包被杀毒软件误报，可先校验 SHA-256，再将安装包加入信任后运行；本软件不包含广告与捆绑组件。

## 常见问题

| 问题                 | 说明                                                                                         |
| -------------------- | -------------------------------------------------------------------------------------------- |
| 高音质仍播放标准音质 | 系统会按可用音源自动降级；高音源缺失时会回退到标准音质，可在播放页查看当前音质标记。         |
| 歌词没有完全同步     | 自动匹配可能命中 Live / 翻唱版本；可在歌词页手动切换来源或调整偏移，本地同名歌词会优先使用。 |
| 本地歌曲没有歌词     | 将同名 `.lrc` 文件放在歌曲旁，或在设置中配置歌词来源；也支持内嵌歌词。                       |
| 下载失败             | 检查网络与下载额度；客户端会自动重试，也可在任务中心手动重试。                               |
| 更新后出现异常       | 退出应用后清空缓存并重启；若仍异常，请携带版本号与日志到反馈区提交。                         |

## 反馈

- 产品区反馈：[txc.qq.com/products/634166](https://txc.qq.com/products/634166)
- GitHub Issues：[kiko-love/YourMusicStation/issues](https://github.com/kiko-love/YourMusicStation/issues)
- QQ 交流群：`376047513` / `763036486` / `1019733982`
- 内测群：`971409447`
- QQ 频道：`ymusictation`

反馈时请附上客户端版本、Windows 版本、问题现象与复现步骤；崩溃或播放异常可同时提供日志。

## 更新日志

- 当前版本：**1.5.5**（自动切歌稳定性、机器密钥兼容、未登录动态封面修复）
- 完整历史：[CHANGELOG](https://ymsv2.top/views/changelog/) · [GitHub Releases](https://github.com/kiko-love/YourMusicStation/releases)
- 1.5.3 上线 AI 助手「悠米 Yomi」、AI 工具箱、AI 调音、人声分离与多源在线歌词
- 1.5.0 上线 AutoMix 自动混音、智能音量平衡与歌曲可用状态检测
- 1.4.9 引入听歌识曲、自研播放引擎与桌面歌词增强

## 许可与声明

- 本仓库仅用于 YourMusicStation V1 的安装引导与版本发布；V1 源码不在本仓库维护。
- 软件免费提供，**任何付费下载或倒卖行为均与作者无关**，请立即停止。
- 本项目仅供学习研究使用，禁止商业用途或批量爬虫下载音乐内容；音乐、封面、歌词版权归各平台与权利人所有。
- 对因使用本软件下载音乐等行为引起的版权风险不承担任何法律责任；如有侵权，请联系项目删除。
- 历史源码与第三方组件适用其各自许可证，见仓库根目录 `LICENSE`。
