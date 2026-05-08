# 待办标签

一个轻量的手机端待办标签管理 PWA。

## 功能

- 添加/完成/删除待办事项
- 自定义标签分类（工作、生活、学习等）
- 按标签和状态筛选
- 支持添加到手机桌面，离线可用
- 数据存储在手机本地

## 部署到 GitHub Pages（免费）

### 前提
- 一个 GitHub 账号

### 步骤

1. 打开 [github.com](https://github.com) 登录
2. 点右上角 `+` → **New repository**
   - Repository name: `todo-app`（或其他名字）
   - 设为 **Public**
   - 点 **Create repository**

3. 进入仓库后，把文件传上去：

   ```bash
   # 在电脑上打开终端执行：
   cd e:/myproject/oms/todo-app

   git init
   git add .
   git commit -m "init"
   git branch -M main
   git remote add origin https://github.com/你的用户名/todo-app.git
   git push -u origin main
   ```

4. 在 GitHub 仓库页面点 **Settings** → **Pages**
   - Source: **Deploy from a branch**
   - Branch: `main`，目录 `/ (root)`
   - 点 **Save**

5. 等 1-2 分钟，访问 `https://你的用户名.github.io/todo-app/`

### 手机安装

1. 手机浏览器打开上面的地址
2. 弹出"添加到主屏幕"提示 → 点**安装**
3. 如果没有弹出提示，点浏览器菜单 → **添加到主屏幕**
4. 桌面出现图标，点开即用，离线也能访问
