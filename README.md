# Deck 下载

这是 Deck 的公开 Windows 二进制下载仓库。源代码仓库保持私有；这里不包含源代码、授权密钥、Dola 登录信息、Cookie、素材或客户数据。

## 0.6.0 测试版 · 2026-10-03 更新

[下载 Windows 安装包](https://github.com/cyou1314/Deck-downloads/releases/download/v0.6.0/Deck-Setup-0.6.0.exe) · [发布说明](https://github.com/cyou1314/Deck-downloads/releases/tag/v0.6.0)

无限画布采用简洁浅色界面，支持选择 Dola 账号、核对生成参数、结果回到画布、生成版本记录、多项目与自动备份，并可导出 PNG 和含音轨的 WebM。

本次加入参考 ComfyUI 的画布操作：拖框多选、Shift/Ctrl 追加选区、多节点移动与批量删除、Ctrl+C/V 复制粘贴并保留内部输入连线，以及选区对齐和定位。复制不会复用生成任务，进行中的生成节点受到删除保护。

247 项测试、画布交互回归、安全检查、Windows 静默安装及启动检查通过。本轮未使用真实 Dola 账号扣额度生成，保留测试发布标记。

**已安装旧 0.6.0 的用户请重新下载并覆盖安装，保留原 Deck 数据目录。** 0.5.x 用户也可手动安装此版本。

## 发布文件

- 安装版：`Deck-Setup-<版本>.exe`，支持 Deck 内检查更新。
- 便携版：`Deck-<版本>.exe`，通过 Release 手动下载更新。
- 安装版更新所需的 `latest.yml` 和 `.blockmap` 与同一版本放在同一个 Release 中。

只有 Release 附件是发布内容，仓库正文不会存放程序源码。
