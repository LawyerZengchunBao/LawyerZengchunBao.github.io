# 包增春律师个人网站

这是一个 Quarto + GitHub Pages 网站模板。

## 使用方式

1. 将本文件夹内所有文件复制到 GitHub repository 本地文件夹中。
2. 在 RStudio Terminal 中运行：

```bash
quarto render
```

3. 提交并推送到 GitHub：

```bash
git add .
git commit -m "Build lawyer personal website"
git push
```

4. 在 GitHub repository 设置中打开：

Settings → Pages → Deploy from a branch → main → /docs

如果 `quarto render` 无法运行，请安装 Quarto CLI：
https://quarto.org/docs/get-started/

## 需要替换或确认的地方

- `contact.qmd` 中的电话、邮箱、地址是否适合公开。
- `img/portrait.jpg` 和 `img/media_interview.jpg` 是否使用最终高清版本。
- 如需添加微信二维码，可放入 `img/` 文件夹，再在 `contact.qmd` 中引用。
