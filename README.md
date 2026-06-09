# 个人主页

这个仓库基于 AcadHomepage / Minimal Mistakes 风格的 Jekyll 模板整理，用于部署到 GitHub Pages。

## 需要修改的文件

- `_config.yml`: 网站标题、描述、仓库名、作者姓名、邮箱、GitHub、Google Scholar、ORCID 等。
- `_pages/about.md`: 首页正文，包括简介、学历、论文专利、荣誉奖项、学术会议、工作实习。
- `images/`: 头像、favicon、机构 logo、论文配图等静态资源。
- `_data/navigation.yml`: 顶部导航。

## 部署到 GitHub Pages

1. 在 GitHub 创建仓库：`USERNAME/USERNAME.github.io`。
2. 修改 `_config.yml` 中的 `repository` 为 `USERNAME/USERNAME.github.io`，并填写个人信息。
3. 推送到 GitHub：

```bash
git init
git add .
git commit -m "Initialize homepage"
git branch -M main
git remote add origin https://github.com/USERNAME/USERNAME.github.io.git
git push -u origin main
```

4. 在仓库 `Settings -> Pages` 中选择 `Deploy from a branch`，分支选择 `main`，目录选择 `/root`。
5. 部署完成后访问 `https://USERNAME.github.io`。

## Google Scholar 引用统计

默认未启用自动抓取。需要时可以恢复或新增 GitHub Actions，并在仓库 `Settings -> Secrets and variables -> Actions` 中添加 `GOOGLE_SCHOLAR_ID`。

## 本地预览

本机需要安装 Ruby 和 Bundler：

```bash
bundle install
bundle exec jekyll serve
```

然后访问 `http://127.0.0.1:4000`。
