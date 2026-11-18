# 后会友期性格测试 v5.2

单文件静态测试网页，入口文件为仓库根目录的 `index.html`。

## EdgeOne Pages 部署设置

- 部署方式：Import Git Repository
- 仓库：`wang133224/-houhuiyouqi-quiz`
- 生产分支：`main`
- 框架：Other / Static HTML
- Build command：留空
- Output directory：`./`（仓库根目录）
- 环境变量：无需配置

九张人物头像已直接内嵌在 HTML 中，无需额外图片资源。每次向 `main` 推送提交，可由 EdgeOne Git 集成触发重新部署。


## v5.2.1 更新

- 移除普通结果页和隐藏款结果页的分享/复制链接按钮。
- 保留 20 道题、9 张内嵌人物头像和单人物结果展示。
