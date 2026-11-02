# 更新记录

## V0.3.1 — 2026-11-03

- 修复 Pages 工作流重跑时报 `Multiple artifacts named "github-pages"` 的问题。
- artifact 名称加入 workflow run ID 与 run attempt，并在上传和部署步骤使用同一个名称，确保每次重跑只匹配本次 HTML 包。

## V0.3 — 2026-11-03

- 参考 linklet-admin 的 GitHub Pages 部署工作流，将纯 HTML 原型目录直接上传发布。
- 去掉 Node 安装、构建和复制步骤；main 更新自动部署，也可手动触发。
- README 增加在线演示入口与部署说明。
- 采用 GitHub Actions 的 Pages artifact / deploy 工作流：https://github.com/fangfengxiang/linklet-admin/blob/main/.github/workflows/deploy.yml

## V0.2 — 2026-11-02

- 将既有 V0.1 原型纳入 ai-native-ensemble 仓库，更新 Ensemble 品牌展示。
- 补充产品规划、三类交付物、产品主导轻量交付及可切换示例。
- 记录已知研发流程，明确等待进一步补充，未展开问题分析。
- 建立产品讨论 Markdown 与参考资料清单。
- 取消 Tab 切换时平滑滚动与 scrollIntoView 的重复纵向滚动；仅在标签超出可视范围时调整导航横向位置。
- 此优化不代表已定位所有预览卡顿原因。完成 JS 语法和静态结构检查，未进行真实浏览器性能测量。

## V0.1 — 2026-11-02（此前原型）

五个主题章节、需求澄清与产品决策演示、备注和工单导出。此次仓库初始化以 V0.2 收录。
