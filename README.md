
# IDE-AI-Rules

`ide-ai-rules` 是一个基于 AI 的 IDE 规则管理工具，旨在提升开发效率和代码质量。通过智能规则和高亮显示功能，帮助开发者更轻松地编写和管理代码。

---

## 功能特性

- **Cline Rules**: 自定义代码行规则，自动检测和修复代码格式问题。
- **Cursor Rules**: 自定义代码行规则，自动检测和修复代码格式问题。

---

## 安装与使用

### 安装

1. 克隆本仓库：
   ```bash
   git clone https://github.com/your-username/ide-ai-rules.git
   ```
2. 进入项目目录：
   ```bash
   cd ide-ai-rules
   ```
3. 安装依赖：
   ```bash
   npm install  # 如果是 Node.js 项目
   ```
   或
   ```bash
   pip install -r requirements.txt  # 如果是 Python 项目
   ```

### 使用

1. 在 IDE 中加载 `ide-ai-rules` 插件或扩展。
2. 配置 `cline rules` 和 `cursorline` 设置：
   - 打开设置面板，找到 `Cline Rules` 选项，添加或修改规则。
   - 启用 `Cursorline Highlighting`，自定义高亮颜色和样式。
3. 开始编码，享受 AI 驱动的智能提示和规则管理！

---

## 示例

### 配置 Cline Rules
```json
{
  "cline_rules": {
    "max_line_length": 80,
    "indent_size": 4,
    "trailing_whitespace": "remove"
  }
}
```

### 启用 Cursorline Highlighting
```json
{
  "cursorline": {
    "enable": true,
    "color": "#FFD700",
    "style": "underline"
  }
}
```

---

## 贡献

欢迎贡献代码或提出建议！请遵循以下步骤：

1. Fork 本仓库。
2. 创建新分支：
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. 提交更改：
   ```bash
   git commit -m "Add your feature"
   ```
4. 推送分支：
   ```bash
   git push origin feature/your-feature-name
   ```
5. 提交 Pull Request。

---

## 许可证

本项目采用 [MIT 许可证](LICENSE)。