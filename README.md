# 刘毅的个人主页

https://5isolitude.github.io/

以个人介绍为主的简洁静态主页，包含学校、研究兴趣与联系方式。姓名、单位和邮箱沿用改版前公开主页；研究兴趣根据已有交流整理。不添加未经确认的职位、学历、论文或研究成果。

## 文件

- `index.html`：个人信息及页面内容。
- `assets/style.css`：桌面与手机布局。
- `assets/favicon.svg`：图标。
- `.nojekyll`：普通静态文件部署。

没有构建步骤、JavaScript、外部字体或运行时依赖。修改 HTML 即可更新内容。

## 预览与发布

在项目目录运行 `python3 -m http.server 4173 --bind 127.0.0.1`，打开 http://127.0.0.1:4173/。

继续使用本仓库现有 GitHub Pages 配置，提交到 main 后由 GitHub Pages 发布。
