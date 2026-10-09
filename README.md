# 万灵漫剧社区版 · Windows 下载

Windows 本机 AI 漫剧制作工作台：原文、剧本、角色与场景、分镜画布、模型生成、审片、MP4 合成及剪映草稿导出。数据保存在自己的电脑，模型账户由使用者配置。

**[下载社区版 MSI / ZIP](https://github.com/jieg19274/wanling-manju-community/releases/tag/v0.4.24-community.1)** · [软件截图](#软件截图) · [微信联系](#联系作者与反馈) · **[公开社区源码](https://github.com/jieg19274/wanling-manju-community)** · [安装说明](docs/INSTALL.md) · [反馈问题](https://github.com/jieg19274/wanling-manju-community/issues)

<!-- screenshot-gallery:start -->
## 软件截图

以下为软件真实界面，使用内置公开演示项目。点击图片可查看原图。

**项目首页：创建作品、搜索项目和打开演示。**

[![万灵漫剧项目首页](https://raw.githubusercontent.com/jieg19274/wanling-manju-community/c86e9ec8eab091e59d48cb5ae9cffa8d7385e83a/docs/screenshots/home.jpg)](https://raw.githubusercontent.com/jieg19274/wanling-manju-community/c86e9ec8eab091e59d48cb5ae9cffa8d7385e83a/docs/screenshots/home.jpg)

**制作画布：把剧本、角色与场景、分镜和视频连接起来。**

[![万灵漫剧制作画布](https://raw.githubusercontent.com/jieg19274/wanling-manju-community/c86e9ec8eab091e59d48cb5ae9cffa8d7385e83a/docs/screenshots/canvas.jpg)](https://raw.githubusercontent.com/jieg19274/wanling-manju-community/c86e9ec8eab091e59d48cb5ae9cffa8d7385e83a/docs/screenshots/canvas.jpg)

**视频预览：在工作台中查看已有片段。**

[![万灵漫剧视频预览](https://raw.githubusercontent.com/jieg19274/wanling-manju-community/c86e9ec8eab091e59d48cb5ae9cffa8d7385e83a/docs/screenshots/video-preview.jpg)](https://raw.githubusercontent.com/jieg19274/wanling-manju-community/c86e9ec8eab091e59d48cb5ae9cffa8d7385e83a/docs/screenshots/video-preview.jpg)
<!-- screenshot-gallery:end -->

## 普通用户安装

1. 下载 Windows x64 MSI 并安装。
2. 打开桌面“万灵漫剧 社区版”，首次启动会联网从官方来源获取并校验运行依赖，不必手动安装 Node.js。
3. 打开内置演示项目，查看素材和播放样片，无需模型密钥。
4. 制作自己的内容时配置模型账户，并按界面确认费用。

也可下载 ZIP，完整解压到可写文件夹，双击“启动社区版.cmd”。首次准备约下载 170 MB，建议预留至少 1 GB 空间。适用于 Windows 10/11 x64。

<!-- author-contact:start -->
## 联系作者与反馈

- 微信交流：打开 [作者微信联系二维码](https://raw.githubusercontent.com/jieg19274/wanling-manju-community/c86e9ec8eab091e59d48cb5ae9cffa8d7385e83a/assets/release/contact-wechat.jpg)，用微信扫码添加好友。
- 使用问题和功能建议：提交 [GitHub Issue](https://github.com/jieg19274/wanling-manju-community/issues)。请说明软件版本、操作步骤和报错信息，不要发送模型密钥。

<img src="https://raw.githubusercontent.com/jieg19274/wanling-manju-community/c86e9ec8eab091e59d48cb5ae9cffa8d7385e83a/assets/release/contact-wechat.jpg" alt="作者微信联系二维码" width="240">

MSI 和 ZIP 都附有“联系与反馈.md”和“微信联系二维码.jpg”。MSI 默认安装目录为 `%LOCALAPPDATA%\WanlingManjuCommunity`；ZIP 用户直接在解压目录打开这两个文件。
<!-- author-contact:end -->

## 开源与来源

万灵原创程序和文档采用 [Apache-2.0](LICENSE)，署名见 [NOTICE](NOTICE)。第三方部分保留各自的 [许可和版权声明](THIRD_PARTY_NOTICES.md)。公开源码和源码构建说明在 [社区仓库](https://github.com/jieg19274/wanling-manju-community)。本下载仓库的 Code ZIP 包含介绍和许可文件，软件下载使用 Releases 的 MSI/ZIP 附件。

旧私有仓库的开发历史没有复制到公开社区仓库。公开版不包含旧开发记录、私人制作原文和素材、账户、密钥、任务账本或本机专用付费授权。用户自行导入内容和模型服务按各自权利与条款使用。

## 版本与校验

社区预览版 `v0.4.24-community.1` 通过 343 项业务测试、类型检查、构建和独立安装/卸载检查；首次依赖准备、无密钥演示启动与媒体编码检查通过。没有执行收费模型生成。Releases 附有 SHA256SUMS.txt，MSI 尚未数字签名。

原 `v0.4.24-trial.1` 为历史本地试用版本，仍保留原附件和当时的许可文件。现在推荐下载采用 Apache-2.0 的社区版。
