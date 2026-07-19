# Rx Generator

> **在线演示：** [https://rxg.20110208.xyz](https://rxg.20110208.xyz)

一个用于处方笺版式编辑与导出的静态网页工具。

> 本项目仅用于网页排版、UI 设计和文档样式演示学习，不具备真实医疗文书或诊疗服务效力。

## 功能

- 直接编辑医院名称、患者信息、诊断、药品、签名和审核信息
- 支持导出当前处方内容为：JPG、PNG、PDF、SVG
- 导出时仅包含处方笺区域，不包含页面背景、免责声明或导出工具栏
- PDF 会自动选择适合的横竖方向并缩放至单页 A4

## 使用方法

1. 使用浏览器打开 `index.html`。
2. 阅读并关闭免责声明。
3. 点击或输入以编辑处方内容。
4. 点击页面右上方的“导出”，选择所需格式下载文件。

## 技术栈

- HTML
- CSS
- JavaScript
- [html-to-image](https://github.com/bubkoo/html-to-image)
- [jsPDF](https://github.com/parallax/jsPDF)

## 注意事项

图片、PDF 和 SVG 导出依赖 CDN 加载的第三方库，请确保使用时网络连接正常。
