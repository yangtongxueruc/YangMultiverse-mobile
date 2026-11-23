# YangMultiverse

交互式 Three.js 3D 黏土/毛毡绘本风多元宇宙微缩生态沙盘，包含 5 个独立宇宙：

- `meadow` — 🌿 春日草原（小羊与金渐层猫）
- `desert` — 🏜 沙漠绿洲（迷你羊驼与耳廓狐）
- `forest` — 🌲 森林秘境（红松鼠与小熊猫）
- `arctic` — ❄ 极地冰原（企鹅与北极熊）
- `coral` — 🐚 珊瑚浅海（寄居蟹与海獭，含橘子海日落、热带太阳雨与蓝眼泪水母夜）

## GitHub Pages 部署步骤

1. 将压缩包解压后的全部文件（`index.html`、`.nojekyll`、`README.md`）上传到 GitHub 仓库根目录并推送至 `main` 分支。
2. 进入仓库 **Settings → Pages**，在 **Build and deployment** 中将 **Source** 设为 **Deploy from a branch**，分支选择 `main`、目录选择 `/ (root)` 并保存。
3. 等待约 1 分钟即可通过 `https://<你的用户名>.github.io/<仓库名>/` 访问。

## 支持的 URL 参数

- `?world=meadow|desert|forest|arctic|coral`：指定默认进入的宇宙
- `?pure=1`：纯净嵌入模式（隐藏外围 UI，适合个人网站 `<iframe>` 嵌入）
- `?zoom=0.85..2.2`：自定义初始镜头缩放倍率
