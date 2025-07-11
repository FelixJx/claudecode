# Claude Code 部署教程

这是一个专业的Claude Code安装和部署教程网站，提供详细的安装指南和配置说明。

## 🌐 在线访问

网站部署在GitHub Pages上，可通过以下地址访问：
[https://your-username.github.io/claude-code-deploy](https://your-username.github.io/claude-code-deploy)

## 📋 功能特性

### 🎨 设计特性
- **响应式设计** - 完美适配桌面、平板和手机
- **现代化UI** - 采用最新的设计趋势和用户体验
- **深色模式支持** - 自动适应系统主题偏好
- **无障碍访问** - 完整的键盘导航和屏幕阅读器支持

### ⚡ 交互功能
- **智能导航** - 固定导航栏，滚动时背景自适应
- **标签页切换** - 多种安装方式的标签页展示
- **代码复制** - 一键复制代码块，支持复制状态反馈
- **FAQ手风琴** - 常见问题的展开/收起交互
- **平滑滚动** - 锚点跳转时的平滑动画效果

### 📚 内容覆盖
- **Claude Code概述** - AI编程助手的功能介绍
- **环境要求** - 支持macOS、Windows、Linux系统
- **安装方式** - NPM、二进制文件、源码编译三种方式
- **配置指南** - API密钥获取和环境变量设置
- **使用示例** - 基础代码生成、代码审查等实例
- **故障排除** - 常见问题的解决方案
- **高级功能** - 项目分析、智能调试等特性介绍

## 🛠️ 技术栈

- **HTML5** - 语义化标签和现代标准
- **CSS3** - Flexbox、Grid布局，CSS变量
- **JavaScript (ES6+)** - 模块化代码，现代语法
- **外部依赖**：
  - Prism.js - 代码高亮
  - Clipboard.js - 剪贴板操作
  - Font Awesome - 图标库

## 📁 项目结构

```
claude-code-deploy/
├── index.html          # 主页面
├── styles.css          # 样式文件
├── script.js           # 交互脚本
├── README.md           # 项目说明
└── .gitignore          # Git忽略规则
```

## 🚀 本地开发

1. **克隆仓库**
   ```bash
   git clone https://github.com/your-username/claude-code-deploy.git
   cd claude-code-deploy
   ```

2. **启动本地服务器**
   ```bash
   # 使用 Python
   python -m http.server 8000
   
   # 或使用 Node.js
   npx http-server
   
   # 或使用 PHP
   php -S localhost:8000
   ```

3. **访问网站**
   打开浏览器访问 `http://localhost:8000`

## 📱 浏览器支持

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ iOS Safari 12+
- ✅ Android Chrome 60+

## 🔧 自定义配置

### 主题颜色
可以通过修改CSS变量来自定义主题：

```css
:root {
    --primary-color: #2563eb;     /* 主色调 */
    --primary-dark: #1d4ed8;      /* 主色调深色 */
    --success-color: #10b981;     /* 成功色 */
    --warning-color: #f59e0b;     /* 警告色 */
    --error-color: #ef4444;       /* 错误色 */
}
```

### 注册链接
当前使用的注册链接为：`https://anyrouter.top/register?aff=MOqi`

如需修改，请在HTML文件中搜索并替换所有相关链接。

## 📊 性能优化

- **图片懒加载** - 延迟加载非关键图片资源
- **CSS优化** - 使用CSS变量和高效选择器
- **JavaScript优化** - 事件委托和节流处理
- **缓存策略** - 适当的缓存头设置

## 🌐 部署指南

### GitHub Pages 部署

1. **推送到GitHub**
   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```

2. **启用GitHub Pages**
   - 访问仓库设置
   - 找到"Pages"选项
   - 选择"Deploy from a branch"
   - 选择"main"分支和"/ (root)"目录
   - 保存设置

3. **访问网站**
   网站将在几分钟后可通过 `https://your-username.github.io/claude-code-deploy` 访问

### Render 部署

1. **连接GitHub仓库**
   - 登录 [Render](https://render.com)
   - 选择"New Static Site"
   - 连接GitHub仓库

2. **配置部署设置**
   - Build Command: 留空
   - Publish Directory: `.`
   - Auto-Deploy: 启用

## 🔍 SEO优化

- **语义化HTML** - 正确的标签层次结构
- **Meta标签** - 完整的描述和关键词
- **结构化数据** - 利于搜索引擎理解
- **友好URL** - 清晰的页面锚点

## 📈 分析和监控

建议集成以下工具：
- Google Analytics - 访问量分析
- Google Search Console - SEO监控
- Hotjar - 用户行为分析

## 🤝 贡献指南

欢迎提交问题和改进建议：

1. Fork本仓库
2. 创建特性分支 (`git checkout -b feature/amazing-feature`)
3. 提交更改 (`git commit -m 'Add amazing feature'`)
4. 推送到分支 (`git push origin feature/amazing-feature`)
5. 创建Pull Request

## 📄 许可证

本项目采用MIT许可证 - 查看 [LICENSE](LICENSE) 文件了解详情

## 📞 支持

如有问题或需要支持，请：
- 创建GitHub Issue
- 访问 [注册页面](https://anyrouter.top/register?aff=MOqi) 获取帮助

---

**⭐ 如果这个项目对您有帮助，请给一个Star！**