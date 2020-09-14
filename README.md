# Autumnus-L & Autumnus-D

复刻了 `typora-theme-autumnus` 的亮色模式和暗夜模式，使用 `less` 编写，缩小了文件的大小。

## 安装

把 `css` 文件复制到主题文件夹下，重启程序后选择对应的主题即可。

## 修改主题

直接修改 `css` 文件或者修改 `less` 文件后重新生成 `css`。

## 一些 Tips

+ 默认情况下会对图片添加阴影效果。要消除阴影效果，只需要在导入图片时，修改其 `alt` 属性即可。

  ```markdown
  ![](img-file) //默认样式
  ![no-shadow](img-file) //消除阴影效果
  ![normal](img-file) //使图片和文字处于同一行，适于小图片。
  ```

+ 导出为 PDF 之前，可以通过添加 `<hr class=“pb”>` 来添加分页符。

+ 请不要删除 `light` 文件，`dark` 样式依赖该文件。