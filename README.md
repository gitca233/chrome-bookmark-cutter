# Chrome 书签文件夹裁剪器

单文件静态网页工具：选择一个 Chrome 导出的 `bookmarks.html`，勾选要保留的文件夹，导出裁剪后的全新书签 HTML，可直接导入 Chrome。

## 功能

- 解析 Chrome `书签管理器 → 导出书签` 生成的 `bookmarks.html`
- 目录树勾选：全选 / 全不选 / 只选顶层文件夹
- 只导出勾选的文件夹及其全部子内容；未勾选的父级自动跳过，勾选的子文件夹提升为顶层导出
- 导出前可自定义文件名（默认 `chrome-bookmarks-selected.html`）
- 导出的文件保持 Chrome Bookmark HTML 标准结构，可直接在 Chrome `书签管理器 → 导入书签` 中使用

## 使用

1. 打开本页面
2. 选择 Chrome 导出的 `bookmarks.html`
3. 在目录树中勾选需要保留的文件夹
4. 点击「导出选中的文件夹」，输入文件名后保存
5. 在 Chrome 书签管理器中导入导出的 HTML 文件

## 隐私

所有处理完全在浏览器本地完成，书签内容不会上传到任何服务器。

## 部署

纯静态单页，可直接打开 `index.html` 使用，也可部署到 Vercel / GitHub Pages 等静态托管服务。