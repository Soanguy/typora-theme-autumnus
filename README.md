# typora-theme-autumnus

根据默认主题和 han.css 改动的 Typora 主题。

建议安装的字体：思源黑体、思源宋体、更纱黑体（term sc），苍耳今楷05。

`更新日志`：

2020-08-15—— `MODIFY`  

+ 更新了缺省字体中的楷体（未启用，全局样式名为 `--quota-font`）。
+ 调整了部分元素颜色、间距。
+ 增加了目录自动编码，默认只显示到四级标题。（将代码 `.md-toc-h5,.md-toc-h6 {display: none;}` 注释掉即可）。
+ 增加了大纲目录自动编码。
+ 三到六级标题的区分更加明显。
+ 调整了图片的样式。

2020-08-12 —— `UPDATE`  

+ 添加了更多的缺省字体，参考 `font.css`。
+ 修改了引用的显示样式和打印样式。
+ 修改了 UI 界面部分的颜色配合问题。
+ 修改了表格样式，使之更加明显。
+ 修复了部分显示错误。

`已知问题`：

- [x] 在引用中，光标显示会滞后一格（删除了引用首字下沉导致的光标异常）。
- [ ] 在选中一段长文字后，尤其是当前文字超过一段，选中背景色会在行末存续 1s 左右。

`待完成部分`：

- [x] 目录样式优化。
- [x] 黑夜模式（已创建，[typora-theme-autumnus_dark](https://github.com/Soanguy/typora-theme-autumnus_dark)）

样式预览：

![](typora-theme-review/ui.png)

![](typora-theme-review/review.png)

附：样式修改参考

<img src="typora-theme-review/Snipaste_2020-08-12_14-26-49.png" style="zoom:60%;" />

<img src="typora-theme-review/Snipaste_2020-08-12_14-30-45.png" style="zoom:60%;" />

<img src="typora-theme-review/Snipaste_2020-08-12_14-32-56.png" style="zoom:60%;" />

<img src="typora-theme-review/Snipaste_2020-08-12_14-38-01.png" style="zoom:60%;" />