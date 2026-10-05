# Deck 下载

这是 Deck 的公开 Windows 二进制下载仓库。源代码仓库保持私有；这里不包含源代码、授权密钥、Dola 登录信息、Cookie、素材或客户数据。

## 0.6.2 测试版 · 2026-10-05 更新

[下载 Windows 安装包](https://github.com/cyou1314/Deck-downloads/releases/download/v0.6.2/Deck-Setup-0.6.2.exe) · [发布说明](https://github.com/cyou1314/Deck-downloads/releases/tag/v0.6.2)

Deck 是一个面向 AIGC 工作流的无限画布，支持 Dola 账号选择、图片与视频生成、结果回到画布、版本记录、多项目、自动备份，以及 PNG 和含音轨的 WebM 导出。

0.6.2 将图片与视频作为画布的主要内容：媒体卡片使用更大预览，生成、文字和音频节点保持紧凑。点击生成节点后，在独立侧边面板编辑提示词、Dola 账号、模型、画幅和适用参数；窄窗口使用底部面板。生成结果显示为独立媒体节点，可从生成节点定位最新版本。参考素材、镜头元数据、版本记录和提交核对继续折叠收纳。

连线可以单独选中、删除及撤销，支持 Delete / Backspace。将素材端口拖到空白区域，可选择生成图片或视频并自动连接素材；视频和音频参考禁用不适用的图片生成。按住空格可从连线上拖动画布。

新节点和结果自动避开已有节点；“整理”按输入 → 生成 → 结果排列，支持撤销。视图适配会避开编辑面板和时间线，编辑焦点与光标在结果回填时保留。

画布支持拖框多选、Shift/Ctrl 追加选区、多节点移动与批量删除、Ctrl+C/V 复制并保留内部输入连线、选区对齐、横向等距排列，以及方向键微调（Shift 加速）。复制不会复用生成任务，进行中的生成节点受到删除保护。

260 项单元测试、Chromium 画布交互回归、安全检查、Windows 安装打包与静默安装启动检查通过。安装包及更新文件的大小和摘要已校验。本轮未使用真实 Dola 账号扣额度，保留测试发布标记。

**旧版本用户请下载 0.6.2 覆盖安装，保留原 Deck 数据目录。** [0.6.1](https://github.com/cyou1314/Deck-downloads/releases/tag/v0.6.1) 和 [0.6.0](https://github.com/cyou1314/Deck-downloads/releases/tag/v0.6.0) 历史版本继续保留。

## 发布文件

- 安装版：`Deck-Setup-0.6.2.exe`。
- Release 同时提供 electron-builder 所需的 `latest.yml` 和 `.blockmap`。

只有 Release 附件是发布内容，仓库正文不会存放程序源码。
