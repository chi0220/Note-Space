### 文件參考自https://markdown.tw/

# 標題
## Setext
```
This is an H1
=============

This is an H2
-------------
```
## Atx
```
# This is an H1

## This is an H2

###### This is an H6
```
# 分隔線
你可以在一行中用三個或以上的星號、減號、底線來建立一個分隔線，行內不能有其他東西。你也可以在星號中間插入空白。下面每種寫法都可以建立分隔線：
```
* * *

***

*****

- - -
```
# 連結
連結的文字都是用 [方括號] 來標記。
要建立一個行內形式的連結，只要在方塊括號後面馬上接著括號並插入網址連結即可，如果你還想要加上連結的title文字，只要在網址後面，用雙引號把title文字包起來即可，例如：
```
This is [an example](http://example.com/ "Title") inline link.

[This link](http://example.net/) has no title attribute.
```
# 強調
Markdown使用星號（*）和底線（_）作為標記強調字詞的符號，被*或_包圍的字詞會被轉成用<em>標籤包圍，用兩個*或_包起來的話，則會被轉成<strong>，例如：
```
  *single asterisks*

_single underscores_

**double asterisks**

__double underscores__
```
__double underscores__
