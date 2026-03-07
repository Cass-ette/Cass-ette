# Claude Code 工作记录

## 2026-03-01

### 完成的工作

1. **优化 Featured Project 卡片**
   - 原 inline style HTML 在 GitHub 上无法渲染，改为 shields.io badge
   - 添加 BlueLotus_XSSReceiver (🛡️) 和 ArknightsMaaRemoter- (🎮) 到精选项目
   - treasure 使用 💰 emoji（财富管理项目）

2. **修复 jsDelivr CDN 缓存问题**
   - 3D 贡献图 URL 添加 `@main` 分支标识，确保获取最新版本

3. **Workflow 降频**
   - `3d-contrib.yml` 和 `snake.yml` 从每 2 小时改为每 12 小时
   - 删除 3D 贡献图的 `push` 触发器，避免推送冲突

4. **更新 Git 全局配置**
   - `user.name` = `Cass-ette`
   - `user.email` = `54059865+Cass-ette@users.noreply.github.com`（GitHub 隐私邮箱）

5. **远程仓库改回 SSH**
   - `git@github.com:Cass-ette/Cass-ette.git`

### 说明
- README.md 和 README.zh.md 已同步更新

---

## 2025-02-14

### 完成的工作

1. **克隆仓库**
   - 以 SSH 方式克隆 `git@github.com:Cass-ette/Cass-ette.git`

2. **删除不可用的 workflow**
   - 删除 `.github/workflows/generate-stats.yml`

3. **添加 3D 贡献图**
   - 创建 `.github/workflows/3d-contrib.yml`
   - 使用 `yoshi389111/github-profile-3d-contrib@main`
   - 支持 dark/light 主题切换
   - 修复权限问题：添加 `permissions: contents: write`

4. **更新 README.md**
   - 添加 3D 贡献图展示（使用 jsDelivr CDN 加速）
   - 深色主题：`profile-night-rainbow.svg`
   - 浅色主题：`profile-gitblock.svg`

5. **更新贪吃蛇 workflow**

6. **更新 Git 全局配置**
   - `user.name` = `Cass-ette`
   - `user.email` = `1804534439@qq.com`

### 当前 Workflow 配置

| Workflow | 文件 | 更新频率 |
|----------|------|----------|
| 3D 贡献图 | `3d-contrib.yml` | 每12小时 |
| 贪吃蛇动画 | `snake.yml` | 每12小时 |

### 待办/后续
- 如需添加语言统计卡片，使用动态 API：
  ```
  https://github-readme-stats.vercel.app/api/top-langs/?username=Cass-ette&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=FFFFFF
  ```
