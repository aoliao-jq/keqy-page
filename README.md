# 企业认证说明页 · 静态页面模板

单文件静态页面（`index.html` + 徽章图 `badge.png`），手机端布局，用于练习/内部演示。

> 声明：本仓库仅为**页面结构与版式的学习/演示用途**，与任何第三方认证服务的官方页面无关，也不代表任何企业获得认证。徽章等图片素材版权归原权利人所有，请勿用于对外宣传或资质背书。

## 在线访问

把 `USER` / `REPO` / `BRANCH` 换成实际值即可：

- statically.io：`https://cdn.statically.io/gh/USER/REPO/BRANCH/index.html`
- 备用（raw.githack）：`https://raw.githack.com/USER/REPO/BRANCH/index.html`

页面内徽章使用相对路径 `badge.png`，与 `index.html` 同目录，所以在上述地址下也能正常加载。

## 本地预览

直接双击 `index.html`，或在目录里 `python -m http.server 8080` 后访问 `http://localhost:8080`。

## 注意

statically.io 按 URL 永久缓存，改完文件后同一地址可能仍拿到旧内容；需要立即生效时在链接后加个版本参数（如 `index.html?v=2`，query 不同即视为新 URL），或把分支换成 commit SHA。
