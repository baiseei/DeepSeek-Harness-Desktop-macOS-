# DeepSeek Harness Desktop(macOS 版)

DeepSeek Harness Desktop 是一个 macOS 桌面应用外壳,将 [DeepSeek Harness](https://github.com/DeepSeek-Harness) 的 Web 操作界面封装为原生桌面应用。无需打开浏览器、无需记忆网址、无需命令行,双击图标即可开始使用。

> ⚠️ 本项目**仅提供桌面外壳封装**。AI 对话、工具调用等全部核心能力来自上游项目 DeepSeek Harness,本仓库不包含、也不修改其内核。

## ✨ 特点

- **桌面化体验**:独立应用窗口、Dock 图标,彻底告别浏览器标签页。
- **双击即用**:启动应用后自动拉起服务并打开窗口,无需任何命令行操作与配置。
- **免网址访问**:自动连接内置服务地址,无需手动输入网址和端口。
- **完整保留上游能力**:DeepSeek Harness 的 AI 对话、多工具调用、后台任务等功能全部可用。
- **轻量外壳**:只做封装、不改内核,可随上游项目同步升级。

## 📦 下载与安装(macOS)

1. 前往 [Releases](../../releases) 页面,下载最新版 `DeepSeek-Harness-x.x.x.dmg`。
2. 双击打开 DMG,将 DeepSeek Harness Desktop 拖入「应用程序」文件夹。
3. 首次打开时若系统提示「无法验证开发者」,请执行以下任一操作:

   - 前往「系统设置 → 隐私与安全性」,点击「仍要打开」;
   - 或在「终端」中运行:
     ```bash
     xattr -cr /Applications/DeepSeek-Harness.app
     ```

> 当前最新版本:**1.0.4**

## 🚀 快速开始

1. 在「应用程序」中双击打开 DeepSeek Harness Desktop。
2. 应用窗口自动打开,无需其他操作。
3. 在输入框中写下你的问题,开始与 AI 对话。

## 📄 更新日志

### v1.0.4

- 修复已知问题,提升稳定性与体验。

## ❓ 常见问题

**Q: 打开应用时提示「已损坏」或「无法验证开发者」?**
A: 这是 macOS 对未签名应用的正常提示。按「下载与安装」第 3 步操作即可。

**Q: 桌面版与浏览器版有什么区别?**
A: 二者使用同一内核,功能完全一致。桌面版只是把浏览器访问封装成了独立的桌面应用,省去打开浏览器、输入网址的步骤。

**Q: 支持哪些设备?**
A: 支持搭载 Apple Silicon(M 系列芯片)的 Mac。

## 🙏 致谢

核心功能由上游项目 [DeepSeek Harness](https://github.com/DeepSeek-Harness) 提供,本项目仅为其提供 macOS 桌面封装。

## 📄 许可证

本项目采用 [MIT License](LICENSE)。
