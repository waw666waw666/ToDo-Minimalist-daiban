# Do - 极简待办与成就记录助手

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Android%20|%20Web-green.svg" alt="Platform">
  <img src="https://img.shields.io/badge/Built%20with-Trae%20Gemini--3--Pro-blueviolet" alt="Built with Trae">
  <img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License">
</p>

`Do` 是一款专为移动端设计的极简待办事项（To-Do）与成就记录（Done）工具。本项目由一位编程新手在 **Trae** AI 助手的辅助下，使用 **Gemini-3-Pro-Preview** 模型，历时约 **12 小时**，经过 **10 余个版本** 的迭代开发而成。

---

## 📸 界面预览

<p align="center">
  <img src="screenshots/todo_list.png" width="300" alt="To Do 列表界面">
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="screenshots/do_list.png" width="300" alt="Do 成就界面">
</p>

<p align="center">
  <em>左图：待办规划与已做完展示 | 右图：历史成就汇总</em>
</p>

---

## 🌟 核心功能

- **双维度任务流管理**：
  - **To Do（待办）**：规划未完成的任务。任务完成后，会**自动变灰并移至列表底部**的“已做完”区域。
  - **Do（成就）**：所有已完成的任务会同步汇总到此板块，带给你满满的成就感。
- **灵动交互体验**：
  - **一键排序**：点击底部导航栏激活的图标，即可切换时间的**升序与降序**。
  - **侧滑删除**：支持极简的**从左向右侧滑手势**，快速清理事项。
  - **长按排序**：支持长按拖拽灵活调整任务优先级。
- **全方位时间控制**：
  - **灵活修改**：支持对任务内容和执行时间进行二次编辑。
  - **智能识别**：内置“设为当前”快捷键，并能根据日期自动识别星期几。
- **多媒体记录**：
  - 支持为每个事项添加多张图片（Base64 本地存储），内置全屏查看器。
- **隐私与安全**：
  - **纯本地操作**：无需联网，数据存储在手机本地 `localStorage` 中，极速响应且隐私安全。

---

## 🛠️ 技术栈

- **编辑器**：[Trae](https://www.trae.ai/) (AI 驱动的下一代 IDE)
- **AI 模型**：Gemini-3-Pro-Preview
- **前端框架**：Tailwind CSS + Font Awesome
- **交互增强**：SortableJS (移动端拖拽排序)
- **打包工具**：[Demo2APK](https://demo2apk.lasuo.ai/)

---

## 🚀 开发故事

1. **起步**：作为一名编程新手，在 Trae 的帮助下从零开始构思。
2. **协作**：通过与 Gemini-3-Pro 模型深度对话，不断加入侧滑、排序、图片等复杂功能。
3. **迭代**：12 小时内经历了 10 多个版本的打磨，解决了移动端适配与手势冲突。
4. **转化**：通过 Demo2APK 将 HTML 页面转化为真正的手机 App。

---

## 📱 如何使用

1. **网页版**：直接打开 `index.html`。
2. **Android 版**：
   - 访问 [Demo2APK](https://demo2apk.lasuo.ai/)。
   - 上传 `index.html`，配置应用名称（如 "Do"）和图标。
   - 生成并下载 APK 安装至手机。

---

## 📄 开源协议

本项目采用 [MIT License](LICENSE) 协议。
