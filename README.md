# HarmonyOS Python 场景覆盖率

基于通用开发场景的 GitHub 高 Star Python 项目依赖分析，并与
TasksDistributor 适配目录进行对照。

## 在线报告

https://ohos-python.github.io/python_test/

统一覆盖口径：三方库包名出现在 `tasks_all.csv`，或者 PyPI 近 30 天下载排名
位于 Top 5 万，即视为已经纳入适配目录。版本号和任务结果状态不参与判断。

## 下载文件

- [完整分析数据](site/ohos_python_scenario_coverage.json)
- [TasksDistributor 聚合表](site/tasks_all.csv)
- [Top 5 万未收录库清单](site/top5w_missing_adaptation.xlsx)

站点由 GitHub Actions 自动发布。报告入口文件位于 `site/index.html`。
