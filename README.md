# Azure Reader Plus

一个基于 Azure Cognitive Services 的文本朗读应用，支持 Markdown 渲染、多 API 轮询、字体调节等功能。

## 功能特性

### 核心功能
- 🎙️ **高质量语音合成** - 基于 Azure Speech Services，支持多种语音模型
- 📝 **Markdown 渲染** - 支持实时 Markdown 解析和渲染
- 🔄 **多 API 轮询** - 支持配置多个 Azure API 密钥，自动轮询分散请求避免限流
- 📖 **朗读位置跟随滚动** - 自动滚动到当前朗读位置（可开关）
- 🔤 **字体大小调节** - 支持 12px-32px 字体大小调节

### 播放控制
- ▶️ 播放/暂停
- ⏹️ 停止/编辑模式切换
- ⏮️ 上一句/下一句跳转
- 🎚️ 语速调节 (0.5x - 2.0x)
- 🔊 音量控制

### 界面特性
- 🌙 深色模式支持
- 📱 响应式设计，适配移动端
- ⚡ iOS 风格切换开关
- 💾 设置自动保存到 LocalStorage

## 使用方法

1. 点击右上角「设置」按钮
2. 输入 Azure Speech Service 的区域和 API 密钥
3. 支持添加多个 API 配置（轮询模式）
4. 在文本框中粘贴或输入 Markdown 内容
5. 选择语音模型，点击播放按钮开始朗读

## 配置导出/恢复

- 点击「导出」按钮可下载当前 API 配置
- 点击「恢复」按钮可导入之前保存的配置

## 技术栈

- HTML5 + CSS3 + JavaScript
- Tailwind CSS
- Font Awesome
- Azure Cognitive Services Speech SDK

## 版本历史

### v6.4
- 缩小控制区域高度，界面更紧凑
- 新增字体大小调节功能（A-/A+）
- 跟随滚动开关改为 iOS 风格

### v6.3
- 朗读位置跟随滚动开关
- 快进/后退按钮更靠近播放按钮
- 配置导出/恢复功能

### v6.2
- 多 API 轮询支持

## 许可证

MIT License
