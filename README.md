# 个人主页

基于 [hexiangnan/hexiangnan.github.io](https://github.com/hexiangnan/hexiangnan.github.io) 的模板改造而来，已清空所有个人信息，只保留 HTML/CSS 骨架。

## 如何修改

直接编辑根目录的 `index.html`：

- 顶部 `<title>` 和 `<meta>` —— 改成你的名字和关键词。
- `#news` —— 右侧 News 栏，每条新闻一个 `<b>日期</b>` + `<span class="easylink">内容</span>` 块。
- `#left` 第一个 `<table>` —— 个人信息卡片：照片、姓名、职位、单位、地址、邮箱。把 `./files/profile.svg` 替换成你自己的照片（建议放到 `./files/` 目录下）。
- `.box` —— 简短自我介绍。
- `Recent Tutorials` / `Selected Publications` —— 复制其中一个 `<table>` 块，按格式增加条目；PDF 路径建议放到 `./papers/` 子目录。
- `Invited Talks` / `Professional Services` / `Experiences` / `Education` / `Useful Links` —— 同上，按需增删。
- 底部 `Last update:` —— 改成最近更新日期。

## 样式

样式表在 `./files/style.css`，整体走老派学术主页风格（深蓝 #0a2245 主色、Georgia 字体、固定 927px 宽度）。如需调整配色或宽度直接改这个文件即可。

## 之前的版本

旧的 academicpages 模板已保存在 `backup-academicpages` 分支，需要的时候可以 `git checkout backup-academicpages` 找回。
