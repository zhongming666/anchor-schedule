# 主播排班总表（在线版）

单页 HTML 工具：自动按"2+2 模式"给主播排班，每天每人播满 4 小时、不超 2 小时连续、不出现断播。

- 数据保存在浏览器 localStorage（每个域名独立）
- 顶栏有「导出/导入数据」按钮可迁移数据
- 开始日期、天数、主播列表均可调整

## 本地使用

直接双击 `index.html` 即可在浏览器打开。

## 在线访问

GitHub Pages 提供静态托管：https://<用户名>.github.io/anchor-schedule/

## 部署方式

- 本仓库 `main` 分支的根目录由 GitHub Pages 自动部署
- 入口文件为 `index.html`
- 文件中包含 `.nojekyll`，禁用 Jekyll 模板引擎