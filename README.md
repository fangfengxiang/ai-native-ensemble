# ai-native-ensemble

AI原生协作交付系统。

**Ensemble · 协奏** — 基于 AI Native 理念重塑软件交付工作流，构建人机协同的自动化端到端交付系统。

## 当前交付物

- [交互原型 HTML](prototype/index.html)：五个可切换章节，含需求澄清演示、产品规划交付物和轻量交付分流示例。
- [产品设计与讨论记录](docs/product-design.md)：已明确方向、设计建议、待确认问题。
- [参考资料](docs/references.md)：讨论中提供的来源及使用边界。
- [更新记录](CHANGELOG.md)。

当前为 V0.2 产品讨论原型，无后端或实际 AI 集成。聚焦开发交付平台，测试作为完整交付的一环。

## 打开原型

下载仓库后用浏览器直接打开 `prototype/index.html`，不需安装依赖。也可在仓库目录运行：

```sh
python3 -m http.server 8000
```

访问 `http://localhost:8000/prototype/`。GitHub 文件页面展示源码，并不是运行中的原型；本次未启用 GitHub Pages。

## 维护方式

原型和文档随产品讨论同步更新至 `main`。保留“已明确 / 建议 / 待确认”状态，不将候选方案写成已达成的决定。研发流程分析等待进一步业务背景。
