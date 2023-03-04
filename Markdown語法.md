#### 文件參考自https://markdown.tw/
* [標題](#1)  
* [分隔線](#2)  
* [連結](#3)  
* [強調](#4)  
* [程式碼](#5)  
* [圖片](#6)  
* [空格](#7)  
<h1 id="1">標題</h1>  
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
<h1 id="2">分隔線</h1>  
你可以在一行中用三個或以上的星號、減號、底線來建立一個分隔線，行內不能有其他東西。你也可以在星號中間插入空白。下面每種寫法都可以建立分隔線:
```* * *  

***  

*****  

- - -
```  
<h1 id="3">連結</h1>  
連結的文字都是用 [方括號] 來標記。
要建立一個行內形式的連結，只要在方塊括號後面馬上接著括號並插入網址連結即可，如果你還想要加上連結的title文字，只要在網址後面，用雙引號把title文字包起來即可，例如：
```
This is [an example](http://example.com/ "Title") inline link.

[This link](http://example.net/) has no title attribute.
```
<h1 id="4">強調</h1>
Markdown使用星號和底線作為標記強調字詞的符號，被或包圍的字詞會被轉成用<em>標籤包圍，用兩個*或_包起來的話，則會被轉成<strong>，例如：
```
*single asterisks*

_single underscores_

**double asterisks**

__double underscores__
```
em:
_single underscores_

strong:
__double underscores__
 
<h1 id="5">程式碼</h1>  
如果要標記一小段行內程式碼，你可以用反引號把它包起來（`），例如：
Use the `printf()` function.
也可以連續用三個反引用來一整段程式碼

<h1 id="6">圖片</h1>  
一個驚嘆號!
接著一個方括號，裡面放上圖片的替代文字
接著一個普通括號，裡面放上圖片的網址，最後還可以用引號包住並加上 選擇性的’title’文字。
```
![Alt text](/path/to/img.jpg)

![Alt text](/path/to/img.jpg "Optional title")
```
<h1 id="7">空格</h1>  
```
插入一個空格 (non-breaking space)
　　　　&nbsp;    或    &#160;     或      &#xA0;

插入兩個空格 (en space)
　　　　&ensp;     或    &#8194;   或      &#x2002;

插入四個空格 (em space)
　　　　&emsp;    或    &#8195;   或      &#x2003;
```
