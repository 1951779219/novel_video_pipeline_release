# 小说推文长视频流水线 · 发布与更新通道

提供小说推文长视频流水线的发行附件、版本记录和在线更新清单。应用将小说或推文文本依次处理为文本切片、TTS 旁白、分镜图片、字幕和视频，并支持可选的 YouTube 上传。

- [源码、安装和使用说明](https://github.com/1951779219/novel_video_pipeline)
- [最新版本](https://github.com/1951779219/novel_video_pipeline_release/releases/latest)
- [全部版本](https://github.com/1951779219/novel_video_pipeline_release/releases)
- [macOS 项目](https://github.com/1951779219/novel_video_pipeline_mac)
- [macOS 发布通道](https://github.com/1951779219/novel_video_pipeline_mac_release)
- [问题反馈](https://github.com/1951779219/novel_video_pipeline_feedback/issues/new/choose)

## 如何使用

1. 初次使用，请先查看源码仓库的环境准备和启动说明，或选择 Releases 中明确标注的完整发行包。
2. 已有安装时，优先使用应用内在线更新；手动更新前关闭应用并备份个人配置和任务目录。
3. 在 **Assets** 中按版本说明选择对应附件。文件名带 `_update.zip` 的附件是更新包，需要已有安装环境。
4. 启动桌面 GUI，粘贴文本或导入 TXT，配置 TTS、文本模型和图片服务，先制作一段短文本验证配置。
5. 查看任务日志，完成后在任务输出目录获取 MP4、字幕和封面。YouTube 上传按需启用。

GitHub 自动生成的 **Source code (zip/tar.gz)** 只包含本发布仓库的文件。完整应用源码位于上面的源码仓库。

## 在线更新清单

```text
https://github.com/1951779219/novel_video_pipeline_release/releases/latest/download/latest.json
```

`latest.json` 供应用更新器读取，无需手动运行。具体功能和修复内容以各版本发布说明为准。

## 数据与服务

API Key、模型服务和浏览器登录状态需在自己的设备上配置。反馈问题时请隐藏凭据和私人正文，不要上传整个任务目录。


## 许可

本仓库的自有代码和文档按 [MIT License](LICENSE) 提供。应用发行包中的第三方组件、工具和模型仍遵循各自许可。
