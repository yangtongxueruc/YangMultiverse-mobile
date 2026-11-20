# YangMultiverse — 多元宇宙微缩生态互动小游戏

包含四个独立 3D 微缩生态世界：**春日草原**、**沙漠绿洲**、**森林秘境**、**极地冰原**，已完整适配桌面端与移动端触控（双指捏合缩放、双指旋转视角、竖屏自适应视野与底部安全区操作栏），纯静态单文件实现，解压即可直接部署到 GitHub Pages。

## 快速发布到 GitHub Pages

1. 新建一个 GitHub 仓库（例如 `yangmultiverse`），或打开你现有的静态站点仓库。
2. 将压缩包内的 `index.html` 和 `.nojekyll` 直接上传（或 `git push`）到仓库根目录。
3. 在仓库页面进入 **Settings → Pages**，在 **Build and deployment** 中选择 **Deploy from a branch**，分支选 `main`、目录选 `/ (root)`，点击 **Save**。
4. 等待约 1 分钟即可通过 `https://<你的用户名>.github.io/<仓库名>/` 访问。

## 支持的 URL 参数（方便网站内嵌）

- `?world=meadow` / `desert` / `forest` / `arctic`：指定默认进入的世界
- `?pure=1`：纯净嵌入模式（隐藏顶部世界切换与控制栏）
- `?zoom=1.2`：设置初始画面缩放倍率（范围 `0.85`–`2.20`）
