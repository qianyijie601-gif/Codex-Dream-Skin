# 美叽、大鼠、旺财 Codex 主题

这是基于 Codex Dream Skin 制作的个人非商业同人主题。主题包含暖色便签桌面、官方表情包状态提示、四个任务入口、思考短句、主题浓度切换、专注模式和更新兼容自检。

分享地址：https://github.com/qianyijie601-gif/Codex-Dream-Skin-Dashu-Meiji-Wangcai

## 安装与启动

需要 Windows 版 Codex 和 Node.js 22 或更高版本。下载仓库后，在 PowerShell 中进入仓库目录并运行：

```powershell
powershell.exe -NoProfile -ExecutionPolicy Bypass -File .\windows\scripts\install-dream-skin.ps1
powershell.exe -NoProfile -ExecutionPolicy Bypass -File .\windows\scripts\start-dream-skin.ps1
```

安装脚本只需运行一次。以后启动主题时运行 `start-dream-skin.ps1` 即可。

## 使用

- 顶部“值班”区域可以在大鼠、美叽、旺财之间切换，选择会保存在本机。
- 点击右上角状态条，可循环切换“安静、标准、热闹”三档，选择会保存在本机。
- 思考期间文案约每 10 秒更新；长任务约每 20 秒进行角色接力，完成后停止更新并显示一次验收印章。
- 新建任务首页每天显示一张固定便签，同一天内不会反复变化。
- 输入文字或任务运行时，主题会自动进入专注模式，收起部分装饰。
- 检测到 Codex 更新造成的兼容异常时，右上角会出现“修复主题”。
- 恢复官方外观时运行 `windows\scripts\restore-dream-skin.ps1`。

## 桌面宠物

右侧桌宠直接使用作者公开发布的官方透明表情图，不重新绘制角色。页面一次只显示当前值班角色：空闲、工作和完成会切换对应神态；输入和专注时自动收起，窄窗口中隐藏，避免遮挡正文与输入框。

官方动态素材及逐文件来源记录位于 `windows/assets/official-motion/`，角色与动作边界见 `pets/ip-character-guide.md`。

## 常见问题

- **直接启动 Codex 没有主题**：请使用桌面的 **Codex Dream Skin** 快捷方式，主题需要本机注入器随 Codex 一起运行。
- **Codex 已经打开**：关闭后使用主题快捷方式重新启动；不要同时运行多个 Codex 窗口版本。
- **Codex 更新后界面异常**：重新运行 `start-dream-skin.ps1`，脚本会自动定位当前 Store 版本；右上角出现“修复主题”时也可直接点击。
- **想彻底恢复官方外观**：运行 `restore-dream-skin.ps1`，不会删除任务、账号、插件或宠物数据。

## 声明

本主题仅用于个人学习、交流和非商业分享。角色形象与表情包权利归作者砂糖仙贝 / 美叽和大鼠所有，转载分享请注明作者，禁止商用；Codex 及相关权利归 OpenAI 所有。本仓库不是官方产品。
