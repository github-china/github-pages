<!--
  <<< Author notes: Step 4 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
  Historic note: previous version checked the file path. Previous version checked the front matter formatting.
-->

## Step 4: 发布一篇文章

_你的主页看起来很棒! :cowboy_hat_face:_

GitHub Pages 使用的是 **Jekyll**。在 Jekyll 中，博客需要遵守约定的文件命名格式和 “frontmatter”（文件头部信息）。
文件必须命名为 `_posts/YYYY-MM-DD-title.md`， 并且文件开头必须包含 `title` 和 `date` 两个字段。

**什么是 frontmatter？** Jekyll 文件使用的格式叫 **YAML frontmatter**，它位于文件顶部，看起来像这样：

```yml
---
title: "Welcome to my blog"
date: 2019-01-20
---
```

关于 frontmatter 的更多配置说明，可以查看 [Jekyll 官方文档](https://jekyllrb.com/docs/frontmatter/)。

### :keyboard: 实操环节：创建一篇博客文章

1. 切换到 `my-pages` 分支。
2. 点击 **Add file（添加文件）** 下拉菜单，选择 **Create new file（新建文件）**。
3. 将文件命名为 `_posts/YYYY-MM-DD-title.md`。
4. 把 `YYYY-MM-DD` 替换为今天的日期，并将 `title` 修改为你想要的博客标题。

   > 注意：如果修改了标题，请确保单词之间用短横线（`-`）连接。
   > 如果日期格式不正确，网站会构建失败，并提示错误。
   > 详细说明请参阅：[Page build failed: Invalid post date](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/troubleshooting-jekyll-build-errors-for-github-pages-sites)。
5. 在文件顶部输入以下内容：

   ```yaml
   ---
   title: "YOUR-TITLE"
   date: YYYY-MM-DD
   ---
   ```
6. 将 `YOUR-TITLE` 替换为你文章的标题。
7. 将 `YYYY-MM-DD` 替换为今天的日期。
8. 在下面写一段简单的文章内容（可以随时回来修改）。
9. 将更改提交（Commit）到当前分支。
10. 等待大约 20 秒后刷新本页面。[GitHub Actions](https://docs.github.com/en/actions) 会自动检测到更新，并进入下一步。