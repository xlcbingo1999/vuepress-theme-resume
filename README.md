## 🐈 介绍

### npm 启动指令

1. npm i
2. npm run dev


### 样式覆盖

创建 .vuepress/styles/palette.styl 文件

```css
/* font */
$fontSize = 13px
$fontWeight = 400

/* colors */
$accentColor = #4688F1
$textColor = #161F28
$borderColor = #eaecef
```

### 常见问题

> 如何导出为 pdf?

chrome 页面中右键 -> 打印 -> 另存为 pdf。

注意：打印-更多设置-取消勾选页眉和页脚。否则会有标题和日期。

> 导出的 pdf 如何控制只有 1 页？

方法一：.vuepress/styles/palette.styl 修改基准字体大小 $fontSize <br>
方法二：chrome 打印 -> 更多设置 -> 缩放

