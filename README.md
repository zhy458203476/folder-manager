# 文件夹管理器 (Folder Manager)

基于浏览器 File System Access API 的本地文件夹管理网页应用。

## 功能

- 选择本地文件夹（Chrome/Edge 最新版，`showDirectoryPicker`）
- 列表 / 网格两种视图浏览
- 按名称、大小、修改时间、类型排序
- 实时搜索过滤
- 新建文件夹、重命名、删除（右键菜单）
- 底部统计：条目数、文件数、总大小、类型分布
- 深浅主题切换，响应式适配手机

## 使用

直接打开 `index.html`（或通过 GitHub Pages 访问），点击「选择文件夹」授权后即可管理。

所有数据仅在浏览器本地处理，不会上传。

## 注意

- 需要 Chrome 105+ / Edge 105+（File System Access API）
- 重命名需要 Chrome 110+
- 需 HTTPS 环境（GitHub Pages 满足；本地 file:// 打开在 Chrome 中亦可用）
