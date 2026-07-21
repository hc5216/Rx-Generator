# 贡献指南

感谢你对 Rx Generator 的关注！🎉

本项目是一个用于处方笺版式编辑与导出的静态网页工具，欢迎任何形式的贡献——无论是提出建议、报告问题，还是直接提交代码。

## 📬 如何参与

### 1. 提交 Issue（建议与问题反馈）

如果你有改进想法或发现了 Bug，欢迎[新建 Issue](https://github.com/hc5216/Rx-Generator/issues/new/choose)：

- **改进建议**：描述你希望增加或优化的功能，以及它解决了什么问题。
- **Bug 报告**：说明复现步骤、预期行为与实际行为，最好附上截图。

新建 Issue 时会自动出现模板，按提示填写即可，无需拘泥于格式。

### 2. 提交 Pull Request（代码贡献）

如果你想直接修改代码：

1. **Fork** 本仓库到你的账号下。
2. **克隆**你 Fork 后的仓库到本地：
   ```bash
   git clone https://github.com/<你的用户名>/Rx-Generator.git
   cd Rx-Generator
   ```
3. **新建分支**（不要直接在 `main` 上开发）：
   ```bash
   git checkout -b feat/your-feature
   ```
4. **修改代码**并保证改动符合项目风格。
5. **本地测试**：用浏览器打开 `index.html`，确认各预设、签名字体以及导出（JPG/PNG/PDF/SVG）均正常。
6. **提交**，请使用清晰的提交信息：
   ```bash
   git commit -m "feat: 添加 XX 预设"
   ```
7. **推送**到你的 Fork：
   ```bash
   git push origin feat/your-feature
   ```
8. 在 GitHub 上发起 **Pull Request**，目标分支为 `main`，并在描述中关联相关 Issue（例如 `Closes #12`）。

## 🧭 约定

为了保持项目整洁，请遵循以下约定：

- **分支命名**：`feat/xxx`（新功能）、`fix/xxx`（修复）、`docs/xxx`（文档）、`style/xxx`（样式）。
- **提交信息**：简洁明了，说明本次改动做了什么，建议使用中文或英文均可。
- **代码风格**：与现有代码保持一致。本项目为纯静态页面（HTML/CSS/JavaScript），无构建步骤，请避免引入框架或打包工具。
- **单次 PR 范围**：一个 PR 聚焦一个主题，便于评审与合并。
- **版权与许可**：如需新增字体或第三方资源，请确认其许可证并一并在 `assets/fonts/` 中附带许可文本（参考现有 OFL 字体）。

## ⚠️ 重要声明

本项目**仅用于网页排版、UI 设计和文档样式演示学习**，不具备真实医疗文书或诊疗服务效力。贡献内容不应：

- 复刻或对应任何**真实医疗机构**、官方处方或正式医疗文书；
- 仿制或验证**真实手写签名、电子签章**；
- 增加任何可能被误用于伪造医疗文书的字段或视觉元素。

请在贡献时遵守上述原则，涉及医疗、法律敏感性的改动将不会被合并。

## 🌟 贡献者

本项目由 **[Rcst20](https://github.com/backrooms-yrc)** 与 **[hc5216](https://github.com/hc5216)** 共同维护，并感谢所有提交 Issue 与 PR 的贡献者。

## 💬 联系方式

如有疑问，可通过 [Issues](https://github.com/hc5216/Rx-Generator/issues) 联系我们，我们会尽快回复。

再次感谢你的参与！每一份建议和代码都能让 Rx Generator 变得更好。
