# Try Fix TextView中英文排版不对齐的情况

## TextView在显示中文时所遵循的原则

1. 标点符号不能显示在一行的行首和行尾，如果一个标点符号刚好在一行的行尾，该标点符号就会连同前一个字符跳到下一行显示。

2. 如果遇到双符号，例如：“《》”，“（）”等符号，如果一行显示不完全就会在下一行显示。

3. 英文字符串和数字如果在一行显示不全，则会自动换到下一行显示。


## 思路

在设置TextView的内容之前，对内容进行处理，使内容不会出现上述case。

## 源码分析
