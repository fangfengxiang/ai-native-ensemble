# 演示站点发布

演示地址：https://fangfengxiang.github.io/ai-native-ensemble/

仓库使用 GitHub Actions 把纯静态原型发布到 GitHub Pages，工作流位于 `.github/workflows/deploy.yml`。

- main 有提交时自动部署；支持 Actions 手动运行。
- 直接上传 `prototype/` 作为 Pages artifact，目录中的 `index.html` 即站点首页。
- 不安装依赖、不构建、不复制额外文件。
- 只发布 HTML 原型；Markdown 产品设计文档不会进入站点。
- artifact 名称按 workflow run 和 attempt 唯一生成，避免重跑失败任务时与上一次尝试的 artifact 重名。
- 本仓库为公开仓库，因此演示网站可公开访问。

首次启用 Pages 时，在仓库 Settings → Pages → Build and deployment 中将 Source 设为 **GitHub Actions**。随后到 Actions 查看 Deploy 工作流结果及实际发布 URL。
