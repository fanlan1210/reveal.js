## 軟體介紹:Adobe Brackets
* 由HTML,CSS和JavaScript編寫的HTML編輯器
* 可即時預覽網頁
* 跨平台(Windows,Mac OS,Linux)

----

# HTML

----

## 對HTML的基本認識

**HTML**，全名HyperText Markup Language，中文譯為超文本標記語言，為形成網頁的最基本骨架。
* 目前主要使用HTML5
* 其實它並不算是程式語言，而是標記語言

---

### 標籤
起始標籤(start tag)
```
<p>
```

結束標籤(end tag)
```
</p>
```

少部分的標籤會單獨存在
```
<br >
<br />
```

----

## 基本結構

----

我們可以將HTML網頁的結構，想像成一個人
```none
html
  - head
  - body
```
*	head(頭):主要負責記錄屬性和連結檔案
*	body(身體):使用者可看到的內容，主要位於這裡

----

## 網頁內容

----

### 文字排印(Typography)

`<h1>` ~ `<h6>` : 標題(heading)

`<p>` : 段落(paragraph)

---

### 圖片
```
<img src="#">
```
* *src* : 來源(source)，必須是直接連結至檔案本身

----

# CSS

----

## 什麼是CSS
* CSS，全名Cascading Style Sheets，中文為層疊樣式表
* 為HTML網頁添加樣式(如顏色、大小、背景等等)
* 如果網頁是一個人，HTML是它的內在，CSS就是它的外表
* 目前主要使用CSS3

----

## 如何套用CSS
使用CSS主要有3種方式，在此先介紹常用的其中2種

----

### 標籤內套用
```
<p style=”...”> .....
```

---

### 連結檔案套用
```html
<head>
    <link rel="stylesheet" type="text/css" href="theme.css">
</head>
```
`<link>`為連結檔案的標籤

* *rel* 為連結關係，這裡選擇"樣式表"(stylesheet)

* *type* 為類型，由於是css文本，所以填入"text/css"

* *href* 內填入連結位址

----

## CSS內容

---

```
CSS語法:
	選擇器(selector) {
		屬性(property) : 值(value);
}
```
* 選擇器: 在這裡我們填入標籤名(如h1)

----

### 文字樣式
* color: 文字/前景 顏色
* font-size: 文字大小，單位習慣用"像素"(px,pixel)
* font-align:文字對齊

---

### 設定背景
* background-color: 背景顏色
* background-image: 背景圖片
* background-size:調整背景大小

----

# Github

----

### git 簡介
git是一個版本控制軟體，我們可以使用git方便進行專案的管理與追蹤
如檔案變更、紀錄等。

---

### Github簡介
git會需要儲存庫，來進行檔案的儲存。
而Github就提供了線上的儲存庫代管服務，
類似於雲端硬碟的概念

---

### Github Pages(github.io)簡介
Github Pages是利用儲存庫裡的檔案，建立網站的功能。

----

## 儲存庫

----

### 建立專案儲存庫(repository)
儲存庫(repository)在這裡是指在儲存上的的資料結構，
可以暫時想像成一個儲存空間。

* 使用網站的新增功能，建立一個儲存庫(記得勾選用README初始化)
* 儲存庫名字填"*使用者名稱.github.io*"

---

### 上傳檔案至儲存庫
* 在儲存庫裡，使用上傳檔案功能，將自己的網頁檔案上傳上去
* 記得在commit時，簡單寫個描述

----

## 網站發佈
在瀏覽器輸入自己網站的網址(儲存庫名稱)，看到自己的網站，完成!

----

## 學習資源
<div style="margin:0px auto;text-align:center;">
<img src="./files/web-tutorial_qrcode.png"><br>本教學簡報</div>

[教學講義](https://github.com/fanlan1210/website-tutorial)
[網頁模板](https://html5up.net)