# 薄肌计划（PWA）· 部署仓库

这个仓库里**只有构建产物**，由源仓库的 `npm run deploy`（`app/scripts/deploy-pages.mjs`）自动推送。
请不要手工改这里的文件 —— 下一次发布会整个覆盖。

- 站点：https://nianzhechao.github.io/foodAndWorkout_deploy/
- 源仓库：应用本体、需求 / 设计 / 进度文档、验收测试都在那边
- GitHub Pages 设置：Source = Deploy from a branch，分支 `main`，目录 `/ (root)`

产物是纯静态文件，装到主屏后离线可用（Service Worker）；使用者的记录只存在各自设备的浏览器里，服务器不留数据。
