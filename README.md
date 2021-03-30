# typora-theme-Autumnus

+ 🔠 目录自动编号；
+ 🔍 显著区分各层级标题；
+ 📷 `![no-shadow](图片路径)`： 添加 `no-shadow` 可以为不想添加阴影的图片去掉阴影；
+ 🎴 `![normal](图片路径)`：为图片添加 `normal` 可以让图片去掉阴影，同时处于行内而非单独一行；
+ 📖导出为 PDF 时，可以添加 `<hr class="pb" />` 来添加分页符；
+ ✅Less 主题可以使用 `引用+六级标题` 来实现 注意，`引用+加粗的六级标题`来实现 信息。预览见 [更新日志](#update)
+ ⚡调整了代码块的光标颜色，以更加明显。
+ 🔧每个主题都提供了不同的字体样式。（[可选安装](#font)）

> 该主题主要测试于  Windows 和 Ubuntu，尚未经过 Mac 平台测试，但应能正常工作。如果出现任何显示错误，请联系我。

## 预览

主题预览可以查看此处：

<details>
  <summary>Alfluent</summary>
  <img src="https://i.loli.net/2021/03/17/cjY8tZfVwMiLqDC.png" alt="alfluent.png">
  </details>
  <details>
  <summary>Adark</summary>
  <img src="https://i.loli.net/2021/03/17/Mpr71zkiNHhbT8w.jpg" alt="adark"  />
  </details>
  <details>
  <summary>Autumnus</summary>
  <img src="https://i.loli.net/2021/03/17/XCx2LUzVS6DfJEj.jpg" alt="Autumnus" />
  </details>
  <details>
  <summary>Adfluent</summary>
   <img src="https://i.loli.net/2021/03/17/CgiI5UM7rbp1oz4.png" alt="adfluent.png" />
</details>
<br/>
<details>
  <summary>Less-light</summary>
<img src="https://i.loli.net/2021/03/31/q7oNCebh3zF4anZ.png" >
</details>
<details>
  <summary>Less-light-fluent</summary>
<img src="https://i.loli.net/2021/03/31/T6BIYZalUDRd8Gv.png" >
</details>
<details>
  <summary>Less-dark</summary>
<img src="https://i.loli.net/2021/03/31/PU76fXOnLWayh5k.png" >
</details>
<details>
  <summary>Less-dark-fluent</summary>
<img src="https://i.loli.net/2021/03/31/b9GrRM82Wu6B37O.png" >
</details>
## 安装

下载该主题后，打开 `偏好设置→外观→主题→打开主题文件夹`。之后将喜欢的主题文件夹下的 `css` 文件和 `assets` 文件夹复制到该文件夹下，重新进入 `偏好设置→外观→主题` 选择喜欢主题后，重启 Typora 即可。

> 不同主题名称的含义：
>
> + `Autumnus`系列：`Autumnus.css` 是该系列主题的根基，该系列主题都依赖该主题。`Adark.css` 是其暗黑主题。`Alfluent.css` 和 `Adfluent.css` 则分别是亮色主题和暗色主题的模糊样式。
> + `Autumnus-opt`、`Autumnus-less`、`Autumnus-QD` 系列主题的名称和上面的相同。

## 导出

所有的主题都只有亮色模式才可以导出，其他的样式无法导出或导出后会出现显示错误。即可以导出的主题包括：`Autumnus`、`Autumnus-opt`、`Autumnus-less`。

## 修改主题

现在可以更加方便的调整自己的主题了！更改主题的方式可以查看此处。

## <span id="update">更新日志</span>

+ 2021.3.31 `Autumnus` 和 `Less` 一样，现在拥有了新的引用样式，在引用内添加六级标题，或者讲六级标题加粗即可发现。同时，也为 `Less` 主题新增了打印主题，基本上显示的内容就是打印所看到的内容，但是该主题现在只是调增了显示内容，对于 Typora 的 UI 显示还未做进一步调整。

+ 2021.3.16 重新调整了 `Autumnus` 的样式，修改了代码样式。现在可以更方便的调整主题的样式了。现在的样式仍处于 `beta` 状态，可能会有部分样式和之前的样式不同。

+ 2021.2.24 `Autumnus`、`Opt`、`Less` 三个主题分别增加了暗亮两种的模糊主题。

+ 2021.1.26  `Less` 主题新增了引用样式。调整了二级标题的样式。

## <span id="font">关于字体</span>

每个主题所使用的的具体字体如下：
+ Autumnus
  + 黑体：Poppins 和 Noto Sans CJK SC
  + 宋体：EB Garamond 和 Noto Serif CJK SC
  + 楷体：EB Garamond 和 华文楷体
  + 代码：Cascadia Code

+ Less
  + 黑体：Raleway Medium 和 Noto Sans CJK SC
  + 宋体：Lora 和 Noto Serif CJK SC
  + 楷体：Lora 和 华文楷体
  + 代码：Cascadia Code

剩下的两个主题也和上面的字体使用情况相差无几。新增的 `Less-light-print` 主题中使用的字体如下：

  + 黑体：Noto Serif CJK SC
  + 宋体：Noto Serif CJK SC
  + 楷体：悠哉字体
  + 代码：Cascadia Code

需要注意：新增的 `Less-light-print` 主题并未提供回退字体！！！