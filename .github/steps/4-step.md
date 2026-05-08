## 步骤 4: 发布第一篇博客文章

你的首页现在看起来不错！ 🤠

### 📖 理论: Jekyll 博客文章与 Front Matter

在 Jekyll 中，文章需要遵循特定的文件命名规则，系统才能正确识别并生成文章页面。文件必须以 `_posts/YYYY-MM-DD-title.md` 命名，并且必须在 **front matter** 中包含 `title` 和 `date` 字段。

什么是 **Front matter**：Jekyll 要求在每篇文章顶部包含一段特殊配置，称为 **Front Matter（头部配置）**。它本质上是一段 YAML 配置，用于告诉 Jekyll：文章标题、发布时间，以及页面布局等信息。


示例如下：

```yaml
---
title: "Welcome to my blog"
date: 2025-05-15
---
```

> [!NOTE]
> 更多内容可参考 [Jekyll frontmatter 文档](https://jekyllrb.com/docs/front-matter/).


### ⌨️ 实操环节: 创建博客文章

1. 切换到仓库的 `main` 分支。
1. 点击 `Add file（添加文件）` 下拉菜单，然后选择 `Create new file（创建新文件）`。
1. 按照 `_posts/YYYY-MM-DD-title.md` 的格式创建文件。
1. 将 `YYYY-MM-DD` 替换为今天的日期，并根据需要修改文章标题。
   > 修改标题时请注意，单词之间用短横线（-）连接。
   > 如果日期格式不正确，Jekyll 将无法构建网站，并提示错误。更多说明可参考 [Page build failed: Invalid post date](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/troubleshooting-jekyll-build-errors-for-github-pages-sites)。

1. 在文章顶部添加以下内容

   ```yaml
   ---
   title: "YOUR-TITLE"
   date: YYYY-MM-DD
   ---
   ```

   1. 将 `YOUR-TITLE` 替换为你的文章标题
   1. 将 `YYYY-MM-DD` 替换为今天的日期
1. 在下面写一点博客正文内容。不需要写很多，简单记录几句话即可，后续随时都可以继续修改。
1. 提交修改到 `main` 分支。
1. 提交完成后，Mona 会自动为你准备下一步练习。

<details>
<summary>遇到问题? 🤷</summary><br/>

- Double-check your file name and date format.
- Make sure your frontmatter is at the very top of the file and formatted correctly.

</details>
