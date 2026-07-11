# ancodeb

一个面向 GitHub Pages 的 Jekyll 中文个人博客，视觉方向是编辑杂志感。

## 本地预览

如果本机已安装 Ruby 和 Bundler：

```bash
bundle install
bundle exec jekyll serve
```

然后访问 `http://localhost:4000`。

## 部署到 GitHub Pages

1. 将本目录推送到 GitHub 仓库。
2. 在仓库 `Settings` -> `Pages` 中选择从分支部署。
3. 选择 `main` 分支和根目录 `/`。
4. 等待 GitHub Pages 构建完成。

## 修改内容

- 站点信息：编辑 `_config.yml`。
- 首页内容：编辑 `index.html`。
- 关于页面：编辑 `about.md`。
- 新文章：在 `_posts/` 中添加 `YYYY-MM-DD-title.md` 文件。
