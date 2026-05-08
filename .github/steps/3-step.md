## 步骤 3: 配置你的网站

干得漂亮！你的首页已经更新完成 ✨

接下来，我们为网站添加一些配置，让它看起来更美观。

### 📖 理论: Jekyll 与 \_config.yml

Jekyll 使用一个名为 `_config.yml` 的配置文件，统一管理网站设置。
例如：网站主题、标题、作者信息、网站描述、GitHub 用户名等。这些内容都会影响 GitHub Pages 最终生成的网站效果。具体可参考[Jekyll 官方文档](https://jekyllrb.com/docs/configuration/?utm_source=chatgpt.com)。

本次练习中，我们将使用一个适合博客场景的主题：`minima`。

### ⌨️ 实操环节: 配置网站

1. 打开 `main` 分支下的 `_config.yml` 文件。
1. 点击右上角的编辑按钮，进入文件编辑模式。
1. 添加下面这行配置，为网站启用 `minima` 主题：

   ```yml
   theme: minima
   ```

1. （可选）你还可以修改其他配置项，例如 `title:`, `author:`, `description:`

   <details>
   <summary>示例 </summary><br/>

   ```yml
   theme: minima
   title: {{ login }} 的个人博客
   description: 在这里记录我的学习、项目与生活
   author: {{ login }}
   ```

   </details>

1. 提交修改到 `main` 分支。
1. 提交完成后，Mona 会继续为你准备下一步练习内容。


<details>
<summary>Hav遇到问题? 🤷</summary><br/>

- 确认你正在编辑 `main` 分支下的 `_config.yml` 文件。
- 请仔细检查 YAML 格式。注意缩进和冒号！

</details>
