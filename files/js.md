# JavaScript教學

----

## 前置:開發軟體介紹

---

### Adobe Brackets

![](https://upload.wikimedia.org/wikipedia/commons/b/b0/Adobe_Brackets_v0.0.x_icon.png)
* 由HTML、CSS和JavaScript編寫的HTML編輯器
* 可即時預覽網頁
* 跨平台(Windows、macOS、Linux)

----

# JavaScript

----

## 基本介紹
* **JavaScript**，通常縮寫為**JS**
* 它被世界上的絕大多數網站所使用，也被現代的網頁瀏覽器所支援

----

## 如何在網頁中導入JS
* 加入`<script>`標籤
  * 直接使用
  * 連結檔案

---

### 直接使用

```html
<script>
    (JS程式碼)
</script>
```

---

### 連結檔案

```html
<script src="example.js"></script>
```
* *src*：檔案來源(source)

**注意：** 採用此種方式，`<script>`標籤內的任何文字將會失效

----

## 程式語法

----

### console.log("hello world")

* 用來在主控台顯示文字用的函數

```js
console.log("hello world");
```

---

### 彈窗提示：alert()
* 直接地顯示訊息

```js
alert("hello world");
```

---

### 彈窗輸入：prompt()
* 提示使用者輸入文字

```js
prompt("type in something");
```

----

### 宣告變數：var
* 記憶某些訊息(例如使用者輸入的文字)

```js
var x = 10;
var y = 0.5;
var message = "Hi!";
```

----

### 條件判斷：if
* 當程式需要進行判斷時，就會使用到if語句

---

#### if的基本語法
```js
if (條件式){
  ...
}
else if (條件式){
  ...
}
else {
  ...
}
```
* 基本上該語法幾乎類於C/C++

---

#### 條件式
```
A 條件運算子 B
```

常見的條件運算子：
* `>` (大於)
* `<` (小於)
* `>=` (大於等於)
* `<=` (小於等於)
* `==` (等於)

---

#### 條件式
* 成立：*真(true)*
* 不成立：*假(false)*

---
#### if程式練習
試做一判斷A和B數字大小的程式

----

### 副程式(函式)的使用:function
* 大程式中，可以再切分出許多小程式
* 通常每個小程式各只負責一個任務
* 又可稱為副程式

---

#### function的基本語法
```js
function 名稱(傳入變數1, 傳入變數2...){
    程式碼...
    return 值;
}
```

---

##### 使用語法範例
```js
函式名稱(變數A, 變數B...);
```

---

#### function程式練習
利用`function`，將前面if練習程式中的判斷部分，
製作成一個函式來使用。

----

## 實作:猜拳
* `alert()` 顯示訊息
* `prompt()` 讓使用者出拳
* 結合前面所學的JS語法

---

### 玩家出拳:提示使用者選擇

---

### 電腦出拳:隨機數的使用(Math.random)
```js
var computer = Math.random();
```
* `Math.random()`：隨機從0~1之間取一小數

---

#### 隨機數範圍分配
* 剪刀: *0.00~0.33*
* 石頭: *0.34~0.66*
* 布: *0.67~1.00*

共3種

* 顯示電腦出拳

---

### 判斷勝負
  1. 可從是否平手開始
  1. 接著再分別對剪刀、石頭、布進行判斷
  1. 判斷為玩家或電腦勝利

<!--##### 小試身手
請嘗試將判斷勝負的程式寫成一個函式-->

----

## 發布至網際網路

----

### Git簡介
Git是一個版本控制軟體，我們可以使用git方便進行專案的管理與追蹤，
如檔案變更、紀錄等。

---

### Github簡介
Git會需要儲存庫，來進行檔案的儲存，
而Github就提供了線上的儲存庫代管服務，
類似於雲端硬碟的概念。

---

### Github Pages(github.io)簡介
由於JS主要依賴於網頁來執行，因此會需要建立網站。

而Github Pages是利用儲存庫裡的檔案，建立網站的功能。

---

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
在瀏覽器輸入自己網站的網址(儲存庫名稱)，看到自己的網站，完成！

----

# 學習資源
<div style="margin:0px auto;text-align:center;">
<img src="./files/javascript_qrcode.png"><br>本教學簡報</div>

* [實作範例網頁](rock-paper-scissors.html)
* [教學講義](https://fanlan1210.github.io/website-tutorial/javascript)
