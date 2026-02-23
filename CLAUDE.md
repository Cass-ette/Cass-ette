# Claude Code 工作记录

## 2025-02-14

### 完成的工作

1. **克隆仓库**
   - 以 SSH 方式克隆 `git@github.com:Cass-ette/Cass-ette.git`

2. **删除不可用的 workflow**
   - 删除 `.github/workflows/generate-stats.yml`

3. **添加 3D 贡献图**
   - 创建 `.github/workflows/3d-contrib.yml`
   - 使用 `yoshi389111/github-profile-3d-contrib@main`
   - 更新频率：每2小时
   - 支持 dark/light 主题切换
   - 修复权限问题：添加 `permissions: contents: write`

4. **更新 README.md**
   - 添加 3D 贡献图展示（使用 jsDelivr CDN 加速）
   - 深色主题：`profile-night-rainbow.svg`
   - 浅色主题：`profile-gitblock.svg`

5. **更新贪吃蛇 workflow**
   - 修改 `.github/workflows/snake.yml` 更新频率为每2小时

6. **更新 Git 全局配置**
   - `user.name` = `Cass-ette`
   - `user.email` = `1804534439@qq.com`

### 当前 Workflow 配置

| Workflow | 文件 | 更新频率 |
|----------|------|----------|
| 3D 贡献图 | `3d-contrib.yml` | 每2小时 |
| 贪吃蛇动画 | `snake.yml` | 每2小时 |

### 待办/后续
- 考虑是否使用 GitHub 隐私邮箱
- 如需添加语言统计卡片，使用动态 API：
  ```
  https://github-readme-stats.vercel.app/api/top-langs/?username=Cass-ette&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=FFFFFF
  ```
