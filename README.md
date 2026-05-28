# 胡兴宇的个人主页

基于 [hexiangnan/hexiangnan.github.io](https://github.com/hexiangnan/hexiangnan.github.io) 的模板改造，内容来源于个人简历。

线上地址：https://xingyuHuxingyu.github.io

## 文件结构

- `index.html` —— 主页内容
- `files/style.css` —— 样式表（深蓝 #0a2245 主色、Georgia 字体、固定 927px 宽度）
- `files/profile.jpg` —— 个人照片（244×370，从简历中提取）
- `files/pdf.gif` —— 论文条目的 PDF 小图标
- `.nojekyll` —— 让 GitHub Pages 直接把 HTML 当静态文件服务

## 如何更新内容

直接编辑 `index.html`：

- `<title>` / `<meta>` —— 标题和 SEO 关键词
- `#news` —— 右侧 News 栏，每条新闻一个 `<b>日期</b>` + `<span class="easylink">内容</span>` 块
- `#left` 第一个 `<table>` —— 个人卡片（照片、姓名、职位、单位、邮箱、GitHub）
- `.box` —— 自我介绍
- `Publications` —— 论文条目（目前只列第一作者，新论文按现有 `<table>` 格式增加）
- `Awards & Honors` / `Industry Experience` / `Education` / `Skills & Languages` —— 按需增删
- 底部 `Last update:` —— 最近更新日期

## 备份

之前 academicpages 模板的内容保存在 [`backup-academicpages`](https://github.com/xingyuHuxingyu/Huxingyu.github.io/tree/backup-academicpages) 分支。
