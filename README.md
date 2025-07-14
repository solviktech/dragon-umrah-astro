# Dragon Umrah Astro

这是 Dragon Umrah 的 Astro 网站项目。

## 本地开发

```bash
# 安装依赖
npm install

# 启动开发服务器
npm run dev

# 构建生产版本
npm run build

# 预览构建结果
npm run preview
```

## 部署到 GitHub Pages

### 方法 1：使用 GitHub Actions（推荐）

1. 将代码推送到 GitHub 仓库
2. 在仓库设置中启用 GitHub Pages：
   - 进入 Settings > Pages
   - Source 选择 "GitHub Actions"
3. 推送代码到 master 分支，GitHub Actions 会自动构建并部署

### 方法 2：手动部署

```bash
# 使用 gh-pages 包部署
npm run deploy
```

### 访问网站

部署成功后，网站将在以下地址可用：
```
https://[你的用户名].github.io/dragon-umrah-astro/
```

## 注意事项

- 项目已配置 `base: '/dragon-umrah-astro/'`，适合 GitHub Pages 部署
- `.nojekyll` 文件确保 `_astro` 目录不被 GitHub Pages 忽略
- 所有静态资源路径都已正确配置
