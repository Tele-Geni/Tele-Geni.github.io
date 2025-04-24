# 我的个人博客

这是一个使用 Jekyll 和 GitHub Pages 搭建的个人博客，使用 Chirpy 主题。

## 本地开发

1. 安装 Ruby 和 Bundler
2. 安装依赖：
   ```bash
   bundle install
   ```
3. 启动本地服务器：
   ```bash
   bundle exec jekyll serve
   ```
4. 访问 `http://localhost:4000`

## 自动部署

博客已经配置了 GitHub Actions，当你推送代码到 master 分支时，会自动构建和部署。

## 写作新文章

1. 在 `_posts` 目录下创建新的 Markdown 文件
2. 文件名格式为：`YYYY-MM-DD-title.md`
3. 在文件开头添加 YAML 头信息，例如：
   ```yaml
   ---
   layout: post
   title: 文章标题
   date: YYYY-MM-DD HH:MM:SS +/-TTTT
   categories: [分类1, 分类2]
   tags: [标签1, 标签2]
   ---
   ```
4. 使用 Markdown 语法编写内容

## 博客功能

- 文章分类和标签
- 时间线归档
- 搜索功能
- 评论系统（使用 Giscus）
- 响应式设计
- 自动部署

## 自定义域名

博客使用自定义域名 `telegeni.site`，通过 GitHub Pages 提供服务。

## 主题和自定义

- 当前使用 Chirpy 主题
- 可以通过修改 `_config.yml` 进行配置
- 可以自定义 CSS 和布局文件 