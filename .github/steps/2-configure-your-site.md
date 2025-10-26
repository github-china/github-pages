<!--
  <<< Author notes: Step 2 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
  Historic note: previous version checked for empty pull request, changed to the correct theme `minima`.
-->

## Step 2: 配置你的网站

_你已经成功启用了 GitHub Pages! :tada:_

接下来我们将在一个名为 `my-pages` 的分支上进行操作，这个分支我已经为你创建好了，用来帮助你完善网站的外观。 :sparkles:

Jekyll 使用一个名为 `_config.yml` 的配置文件，用来存放网站的相关设置，包括主题、站点名称、GitHub 用户名等。
你可以在仓库的 **Code** 标签页中找到 `_config.yml` 文件。

接下来我们将使用一个适合博客的主题。在本次课程中，我们选择使用名为 **“minima”** 的主题。

### :keyboard: 实操环节: 配置你的网站

1. 打开 `my-pages` 分支，找到 `_config.yml` 文件。
2. 在文件右上角，点击编辑图标进入编辑模式。
3. 为了使用 **minima** 主题，我们在 `_config.yml` 文件里添加下面的内容

   ```yml
   theme: minima
   ```
4. （可选）你还可以修改 `title:`、`author:` 和 `description:` 等配置项，用来个性化你的网站。
5. 提交（Commit）你的修改。
6. （可选）你可以创建一个 Pull Request，以便查看整个课程中你所做的所有更改。
   打开 **Pull Requests** 标签页，点击 **New pull request**，然后将 `base` 设为 `main`，`compare` 设为 `my-pages`。
7. 等待大约 20 秒后刷新本页面，[GitHub Actions](https://docs.github.com/en/actions) 会自动识别你已完成此操作，并进入下一步。