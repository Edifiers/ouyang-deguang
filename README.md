# 作品集网站

一个简洁、现代的个人作品集网站模板。

## 使用方法

1. **修改内容**：编辑 `index.html` 文件，替换以下内容：
   - `[你的名字]` - 你的真实姓名
   - `[你的职业/专业描述]` - 你的职业描述
   - `[your-email]` - 你的邮箱地址
   - `[your-username]` - 你的 GitHub 用户名
   - 添加你的作品图片和描述

2. **添加作品**：
   - 将作品图片放在项目文件夹中
   - 在 `index.html` 的作品展示部分添加更多作品项
   - 更新图片路径和描述

3. **本地预览**：
   - 直接双击 `index.html` 文件在浏览器中打开
   - 或使用本地服务器（推荐）

## 部署到网站

### 方式 1: GitHub Pages（免费）
1. 在 GitHub 创建新仓库
2. 上传所有文件
3. 在仓库设置中启用 GitHub Pages
4. 访问 `https://[你的用户名].github.io/[仓库名]`

### 方式 2: Netlify（免费）
1. 访问 netlify.com
2. 拖拽整个文件夹到 Netlify
3. 获得免费域名

### 方式 3: Vercel（免费）
1. 访问 vercel.com
2. 导入项目
3. 自动部署

## 文件结构

- `index.html` - 主页面
- `style.css` - 样式文件
- `script.js` - 交互脚本
- `projects/` - 项目详情页文件夹
  - `project1.html` - 项目1详情页
  - `project2.html` - 项目2详情页
  - `project3.html` - 项目3详情页
- `README.md` - 说明文档

## 如何添加新项目

1. 复制 `projects/project1.html` 创建新的项目页面
2. 修改项目标题、描述、技术栈等内容
3. 在 `index.html` 的作品展示区添加新的作品卡片
4. 更新链接指向新的项目页面

## 投递简历时的项目链接

部署后，每个项目的链接格式为：
- 项目1：`https://你的域名/projects/project1.html`
- 项目2：`https://你的域名/projects/project2.html`
- 项目3：`https://你的域名/projects/project3.html`

## 特性

- 响应式设计，支持手机和平板
- 平滑滚动导航
- 现代化的视觉效果
- 易于定制
