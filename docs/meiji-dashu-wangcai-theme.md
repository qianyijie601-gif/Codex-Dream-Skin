# 美叽、大鼠、旺财 Codex 主题

这是基于 Codex Dream Skin 制作的个人非商业同人主题。主题包含暖色便签桌面、官方表情包状态提示、四个任务入口、思考短句、主题浓度切换、专注模式和更新兼容自检。

## 安装与启动

需要 Windows 版 Codex 和 Node.js 22 或更高版本。下载仓库后，在 PowerShell 中进入仓库目录并运行：

```powershell
powershell.exe -NoProfile -ExecutionPolicy Bypass -File .\windows\scripts\install-dream-skin.ps1
powershell.exe -NoProfile -ExecutionPolicy Bypass -File .\windows\scripts\start-dream-skin.ps1
```

安装脚本只需运行一次。以后启动主题时运行 `start-dream-skin.ps1` 即可。

## 使用

- 点击右上角状态条，可循环切换“安静、标准、热闹”三档，选择会保存在本机。
- 输入文字或任务运行时，主题会自动进入专注模式，收起部分装饰。
- 检测到 Codex 更新造成的兼容异常时，右上角会出现“修复主题”。
- 恢复官方外观时运行 `windows\scripts\restore-dream-skin.ps1`。

## 桌面宠物

成品宠物精灵图位于：

```text
pets/dashu-meiji-wangcai-run/final/spritesheet.webp
```

同时保留 PNG 版本，方便预览或二次处理。

## 声明

本主题仅用于个人学习、交流和非商业分享。角色形象与表情包权利归原权利方所有；Codex 及相关权利归 OpenAI 所有。本仓库不是官方产品。
