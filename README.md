# NanoChat

> 极致轻量的单文件 AI 聊天界面，兼容 OpenAI 格式，支持多供应商、多语言、多主题。

Demo 体验：https://lite.weblab.top

---

## ✨ 功能特性

### 模型与接口
- 支持多供应商切换（OpenAI、Anthropic Claude、Google Gemini、DeepSeek 等）
- 兼容所有 OpenAI 格式的第三方接口
- 自定义 API Key、接口地址、模型 ID
- 在线获取供应商最新模型列表
- 按供应商独立保存配置，切换自动恢复

### 对话能力
- 连续上下文对话
- 长回复支持（自动续写）
- 思考模式（支持 Claude 扩展思考 / DeepSeek reasoning）
- 自定义系统角色与预设角色
- 代码自动识别、语法高亮与一键复制
- HTML 内容安全预览
- 聊天记录导出 / 导入 / 清空

### 语音
- 语音合成（Azure 语音 / Edge 语音 / 系统语音）
- 语音识别输入
- 自定义语音类型、音量、语速、音调
- 连续朗读 / 自动朗读

### 界面与体验
- **6 种主题**：浅色、深色、自然、暖橙、海洋、玫瑰
- **10 种界面语言**：简体中文、繁體中文、English、日本語、한국어、Français、Deutsch、Español、Русский、Português
- 打字机效果（可调速度）
- 单 HTML 文件，零依赖，秒级部署

---

## 🚀 部署方式

### GitHub Pages（推荐）

直接 fork 本仓库，然后参考 GitHub 官方文档一键启用 Pages：

https://docs.github.com/en/pages/quickstart

### 本地使用

下载 `index.html`，用任意浏览器打开即可，无需安装任何依赖。

---

## ⚙️ 使用说明

1. 点击右上角 **设置** 按钮
2. 在 **模型** 面板选择供应商，填入 API Key 和接口地址，点击**应用**
3. 开始对话

> 若使用国内代理或自建接口，在**接口地址**处填入对应的 base URL 即可。

---

## 📋 更新日志

### 最近更新
- 新增主题设置（6 种主题，含深色模式）
- 新增多语言支持（10 种语言）
- 新增思考模式开关（兼容 Claude / DeepSeek）
- 新增关于页面
- 支持多供应商配置独立保存与恢复
- 移除冗余配置项，精简设置界面
- 修复设置菜单切换时的 TypeError 报错

---

## 🔗 相关链接

- Demo：https://lite.weblab.top
- 开发者：[WebLab.top](https://weblab.top/)
