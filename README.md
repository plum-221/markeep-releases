# Markeep 发布仓库

**不改你文件的 Markdown 编辑器** —— 功能对标 Typora 的 Windows 桌面应用。

本仓库**只存放安装包与更新元数据**，不含任何源代码。
应用内的「帮助 → 检查更新」也是从这里拉取更新的。

## 下载

到 [Releases](../../releases/latest) 下载最新的 `Markeep Setup x.y.z.exe`。

- 安装到当前用户目录（`%LOCALAPPDATA%\Programs\Markeep`），**不需要管理员权限**
- 自动创建桌面快捷方式、开始菜单项，并关联 `.md` / `.markdown`
- 装好后会自动检查更新，有新版会先征求你同意再下载

> ⚠️ 安装包**未做代码签名**，首次运行 Windows 会弹「已保护你的电脑」蓝色提示，
> 点「更多信息」→「仍要运行」即可。

## 许可

Markeep 为**专有软件**，Copyright © 2026 plum-221，保留所有权利。
不开源，不允许再分发、修改或逆向工程。完整条款见安装程序中的许可协议。

软件内含 Electron、Milkdown、ProseMirror、unified/remark 等第三方开源组件，
各自遵循其原有的开源许可证，完整清单随安装包分发
（安装目录 `resources\THIRD-PARTY-NOTICES.md`）。

## 反馈

问题与建议：plum221x@gmail.com
