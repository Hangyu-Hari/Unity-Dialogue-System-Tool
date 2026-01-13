# 文档网站更新说明

## 📋 当前状态

已完成文件拆分：
- ✅ `index.html` - 自动跳转到英文版
- ✅ `index-en.html` - 英文文档框架
- ✅ `index-zh.html` - 中文文档框架  
- ✅ `styles.css` - 共享样式
- ✅ `script.js` - 共享脚本

## ⚠️ 需要补充的内容

两个HTML文件目前只包含基本章节，需要补充以下完整内容：

### 需要补充到 index-en.html 的章节：

在 `</section>` (features) 和 `<section id="manager-window">` 之间添加：

1. **Quick Start** - 完整的5步入门指南
2. **Core Components** - DialogueController和DialogueDisplaySettings详细说明
3. **Localization System** - 本地化系统详细教程（包含两种模式的完整说明）
4. **Dialogue Editor** - 对话树编辑器使用指南
5. **Advanced Features** - 高级功能（条件系统、事件系统）
6. **API Reference** - 完整API文档
7. **Best Practices** - 最佳实践建议
8. **FAQ** - 常见问题解答

### 需要补充到 index-zh.html 的章节：

同样的章节，中文翻译版本

## 🔧 快速修复方法

### 方法1：从原始文件复制（推荐）

如果你有备份的原始 `index.html`（2000+行的那个），可以：

1. 打开原始 `index.html`
2. 找到 `<div id="content-en"` class="lang-content active">` 部分
3. 复制所有 `<section>` 标签的内容
4. 粘贴到 `index-en.html` 中对应位置

对中文版做同样操作：
1. 找到 `<div id="content-zh" class="lang-content">` 部分
2. 复制内容到 `index-zh.html`

### 方法2：保留原文件结构

如果你想保留原来的单文件结构：

1. 将原始的 `index.html` 恢复
2. 只修改语言切换按钮的功能即可

## 💡 建议

由于完整内容很长（约2000行），建议：

**选项A：** 保留原来的单文件 `index.html`（有语言切换功能）
- 优点：内容完整，一个文件搞定
- 缺点：文件较大

**选项B：** 使用拆分后的结构，手动补充内容
- 优点：文件小，易维护
- 缺点：需要手动复制粘贴内容

你希望我帮你哪种方式？

1. 恢复原始单文件版本（保留所有内容）
2. 我帮你补充完整的拆分版本内容（会分几次操作）

请告诉我你的选择！