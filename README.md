# 印昱橙 — 室内设计师个人简历

在线简历网站，单文件 HTML，打开即用，也可通过 GitHub Pages 部署为在线页面。

## 快速使用

### 本地打开
双击 `index.html` 即可在浏览器中查看。

### 部署到 GitHub Pages（免费在线访问）

1. 在 GitHub 新建一个仓库（如 `resume`）
2. 将本文件夹上传到仓库（或通过 Git 推送）
3. 进入仓库 **Settings → Pages**
4. **Source** 选择 `main` 分支，根目录 `/ (root)`，点击 **Save**
5. 等待几秒，页面会显示访问地址：
   ```
   https://你的用户名.github.io/resume/
   ```
6. 如果需要自定义域名，在 **Custom domain** 中填入并配置 DNS 即可

### 替代方案：一键部署到 Vercel / Netlify

直接将整个文件夹拖入 [Vercel](https://vercel.com) 或 [Netlify](https://netlify.com) 即可部署，同样免费。

## 文件说明

| 文件 | 说明 |
|---|---|
| `index.html` | 主文件，包含所有 HTML / CSS / JS |
| `个人照片.jpg` | Hero 头像 |
| `龙山豪庭截图.png` | 项目截图 1 |
| `尚海荟截图.png` | 项目截图 2 |
| `明湖苑截图.png` | 项目截图 3 |

> 如不需要截图展示，可删除三张截图并将 `index.html` 中 `<img>` 的 fallback（`img-placeholder`）样式设为默认可见。

## 功能

- 6 大板块：Hero / 关于我 / 作品项目 / 经历履历 / 技能背书 / 联系合作
- 锚点导航栏 + 滚动高亮
- 滚动入场动效、数字递增动画、技能进度条
- 移动端响应式适配
- 一键下载 A4 简历 PDF（调用浏览器打印）

## 自定义

- 修改个人信息：编辑 `index.html` 中对应板块的 HTML 内容
- 修改配色：编辑 `:root` 中的 CSS 变量
- 替换照片：替换 `个人照片.jpg`
- 替换项目截图：替换三张截图 PNG 文件
