# 面积计算器

这是一个可部署到 GitHub Pages 的纯前端网页程序。用户可以选择圆形或方形模式，输入直径或长宽，点击按钮后计算面积。

## 本地预览

直接用浏览器打开 `index.html` 即可预览，不需要安装依赖或启动服务。

## 部署到 GitHub Pages

1. 在 GitHub 创建一个新仓库，例如 `area-calculator`。
2. 在本地当前目录初始化 Git 仓库并提交代码：

   ```powershell
   git init
   git add index.html README.md
   git commit -m "Add area calculator"
   ```

3. 关联远程仓库并推送到 GitHub。把下面的地址替换成你的仓库地址：

   ```powershell
   git branch -M main
   git remote add origin https://github.com/你的用户名/area-calculator.git
   git push -u origin main
   ```

4. 打开 GitHub 仓库页面，进入 `Settings`。
5. 在左侧选择 `Pages`。
6. 在 `Build and deployment` 中选择：
   - `Source`: `Deploy from a branch`
   - `Branch`: `main`
   - 文件夹选择 `/ (root)`
7. 点击 `Save`，等待 GitHub Pages 完成发布。

发布成功后，公网访问地址通常是：

```text
https://你的用户名.github.io/area-calculator/
```

## 文件说明

- `index.html`: 网页结构、样式和计算逻辑。
- `README.md`: 项目说明和部署流程。
