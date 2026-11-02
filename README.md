# ai-native-ensemble

AI原生协作交付系统。

**Ensemble · 协奏** — 基于 AI Native 理念重塑软件交付工作流，构建人机协同的自动化端到端交付系统。

## 当前交付物

- [在线原型演示](https://fangfengxiang.github.io/ai-native-ensemble/)
- [交互原型 HTML 源码](prototype/index.html)
- [产品设计与讨论记录](docs/product-design.md)
- [参考资料](docs/references.md)
- [演示站点部署说明](docs/deployment.md)
- [更新记录](CHANGELOG.md)

V0.4 产品讨论原型，六个章节，独立展示业务需求与交付流程、产品岗位流程，以及产品主导轻量交付。没有后端或实际 AI 集成。定位是开发交付平台，测试作为完整交付的一环。

## 本地打开

直接用浏览器打开 `prototype/index.html`，无需安装依赖。或在仓库目录运行：

```sh
python3 -m http.server 8000
```

访问 `http://localhost:8000/prototype/`。

## 发布

GitHub Actions 将 `prototype/` 目录直接发布到 GitHub Pages。每次 main 分支更新后自动部署，Actions 也支持手动运行。无需构建步骤或依赖安装。演示站点是公开的。

原型和产品讨论文档持续更新至 `main`。保留“已明确 / 建议 / 待确认”状态；研发流程分析等待进一步业务背景。
