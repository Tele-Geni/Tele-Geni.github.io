# 我的个人博客

这是一个使用 Jekyll 和 GitHub Pages 搭建的个人博客。

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

## 部署

1. 将代码推送到 GitHub 仓库
2. 在仓库设置中启用 GitHub Pages
3. 选择 main 分支作为源
4. 等待几分钟，你的博客就会在 `https://<username>.github.io/<repository>` 上线

## 写作新文章

1. 在 `_posts` 目录下创建新的 Markdown 文件
2. 文件名格式为：`YYYY-MM-DD-title.md`
3. 在文件开头添加 YAML 头信息
4. 使用 Markdown 语法编写内容

## 主题和自定义

- 当前使用 minima 主题
- 可以通过修改 `_config.yml` 进行配置
- 可以自定义 CSS 和布局文件 