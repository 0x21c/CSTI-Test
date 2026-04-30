# CSTI 游戏人格测试

一个基于网页的 CS2/CSGO 游戏人格测试，通过35道题目分析你的游戏风格，并匹配职业选手。

## ✨ 功能特性

- 👤 **15种游戏人格** - 突破手、狙击手、战术大师、支援手等
- ⭐ **职业选手匹配** - 匹配最相似的职业玩家（donk、kennyS、s1mple等）
- 🏆 **段位预估** - 六边形段位显示（D到S级）
- 🌍 **多语言支持** - 简体中文、English、繁体中文
- 📱 **响应式设计** - 完美支持移动端和PC端
- 🎨 **炫酷特效** - 结果页面动画和音效

## 🚀 快速开始

### 方法一：使用 Python
```bash
# 解压安装包

# 进入目录
cd csti-test

# 启动本地服务器
python -m http.server 8848

# 打开浏览器访问
http://localhost:8848
```

### 方法二：使用 Node.js
```bash
# 安装 serve（如果未安装）
npm install -g serve

# 启动服务器
serve . -p 8848

# 打开浏览器访问
http://localhost:8848
```

## 📁 项目结构

```
csti-test/
├── index.html          # 主页面（包含所有页面）
├── css/
│   └── main.css        # 样式文件
├── js/
│   └── script.js       # 核心逻辑（题目、评分、结果）
├── README.md           # 项目说明
├── .gitignore          # Git忽略配置
└── LICENSE             # MIT许可证
```

## 🎮 测试说明

⚠️ **友情提示**：本测试仅供娱乐，别拿它当诊断、面试、相亲、分手、招魂、算命或人生判决书。你可以笑，但别太当真。

## 🛠️ 技术栈

- **前端框架**: 纯 HTML/CSS/JavaScript（无框架）
- **样式**: CSS3（自定义属性、动画、渐变）
- **图标**: Emoji + 自定义图标
- **音效**: Web Audio API

## 📄 许可证

MIT License - 详见 LICENSE 文件

## 📧 联系

博客地址：https://0x21c.cc
