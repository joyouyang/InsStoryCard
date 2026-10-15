# InsStoryCard

Cookmoji 的 10 个 Instagram Story 手机界面 demo，展示同一张原图如何变成一套表情包，以及不同的 Story 发布玩法。

- 照片、视频、Create、Layout 和 Hands-free 五种创作形式。
- 可体验投票、提问、情绪滑杆、Frames 显影与 Add Yours 接力。
- 每个方案附制作方式、配乐和滤镜建议。

这是静态网页，index.html 可直接打开，无需安装依赖或构建。图片已内嵌在页面中；图标等界面资源由 CDN 提供。

GitHub Pages 使用 main 分支根目录发布，更新 index.html 后自动重新部署。

音乐仅为选曲建议，未嵌入歌曲录音；Hands-free 方案为动作分镜，发布前需补拍。所有互动仅在 demo 中演示，不向 Instagram 发送或发布内容。

## brownout-stories.html

第二版：模拟手机上的 Story 查看器，10 条 The Great Brownout Story 按一个人一天发的顺序排列，图片在 `assets/`。地址：https://joyouyang.github.io/InsStoryCard/brownout-stories.html

## brownout-stories-2.html

第二组 10 条：每条都把原图和贴纸放进同一画面，目标是朋友一眼看出贴纸来自这张照片。复用 `assets/`。地址：https://joyouyang.github.io/InsStoryCard/brownout-stories-2.html

## brownout-stories-3.html

第三页，三组切换：翻面实验台（速度 × 1/4/6/9 张 × 5 种特效，三条推荐组合，实验台可任意改）、入口卡 4/6/9 张三条、用后端生产产物（角色描述、画风卡、标题、逐张设计、底稿提示词与模型原文、失败记录）讲制作过程的 10 条。画面里的文字是示例，字段名是真的。复用 `assets/`。地址：https://joyouyang.github.io/InsStoryCard/brownout-stories-3.html
