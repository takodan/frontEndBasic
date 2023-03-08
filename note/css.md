# CSS
this note will write in chinese
## 0220 CSS 簡介、語法基礎教學
HTML: 處理網頁結構
CSS: 處理排版樣式
### 套用CSS樣式屬性
屬性名稱：屬性內容 
### \! TIP \! CSS comment:`/* comment */`
```css  
/* 粗體;紅字 */
<div style="font-weight:bold;color:red">標題</div>
```
顯示為:<div style="font-weight:bold;color:red">標題</div>

### 乾淨標籤:無預設樣式的標籤
有預設樣式
```html
<h3>預設粗體、放大、增加行距</h3>
```
無預設樣式
```html
<div>一般文字</div>
<span>一般文字</span>
```
### 標籤顯示模式
決定標籤顯示放式  
行內 inline  
```html
<span></span>
<a></a>
<img/>
````
區塊 block(自動換行)
```html
<div></div>
<h1></h1>
<ul></ul>
<table></table>
```
隱藏模式 none(不直接顯示)  
透過CSS的display屬性設定  
### 文字相關
顏色
```html
color:red
color:#0000ff
```
粗細
```css
font-weight:normal
font-weight:bold /* 粗體 */
```
大小
```css
font-size:16px
font-size:2em /* 兩倍大 */
```
裝飾
```css
text-decoration:underline
text-decoration:line-through
```
對齊
```css
text-align:left
text-align:center
```

&nbsp;  
&nbsp;  

## 0220 CSS Box Model 區塊模型
一個tag一個box  
### padding 區塊填塞
區塊的內容和邊框距離
```css
/* 距離10px */
<div style="padding:10px">Hello</div>
<div style="padding-top:10px">Hello</div>
<div style="padding-right:10px">Hello</div>
<div style="padding-bottom:10px">Hello</div>
<div style="padding-left:10px">Hello</div>
```
### border 區塊邊框
邊框的樣式
```css
/* 預設0px等於無邊框 */
<div style="border:0px">Hello</div>
/* 實線紅色 */
<div style="border:3px solid red">Hello</div>
/* 需線藍色 */
<div style="border:1px dashed blue">Hello</div>
```

### margin 外邊距
相鄰區塊的距離
```css
/* Line1下外邊距10px */
<div style="margin-bottom:10px">Line1</div>
<div>Line2</div>
/* Line2上外邊距10px，兩個結果是一樣的 */
<div>Line1</div>
<div style="margin-top:10px">Line2</div>
```

### background color
```css
/* 設定整個box背景藍色World紅色 */
<div style="background-color:blue">
    Hello
    <span style="background-color:red">World</span>
</div>
```

### 區塊的width和height
#### width
預設和父標籤等寬  
width:500px  
width:50%  
#### height
預設隨內容大小縮放  
height:300px
height:100%  
### \! TIP \! 只有block區塊才能設定，例如 \<div>

&nbsp;  
&nbsp; 

## 0308 CSS Selector
用來決定CSS樣式的適用標籤，藉此區分CSS樣式和HTML標籤  
### class 選擇器
在head底下設立style標籤，再透過class屬性套用CSS到標籤上  
`.attributeName`  
`class="attributeName"`

### id 選擇器
類似於class選擇器，只是符號不同  
`#attributeName`  
`id="attributeName"`

### 標籤名稱選擇器
直接以標籤名稱套用CSS樣式
`body{background-color:#808080}`

```html
<html>
    <head>
        ...
        <style>
            .style-red{color:red}
            #title{
                margin:10px;
                font-size:20px
            }
            body{background-color:#808080}
        </style>
    </head>
    <body>
        /*  背景會是灰色#808080  */
        <div class="style-red">這串字就會是紅色</div>
        <div id ="title">這串字就會是title的樣式</div>
    <body>
</html>
```

### CSS樣式檔案
將CSS樣式設定成獨立檔案，在head內引入  
```html
<link rel="stylesheet" type="text/css" href="filePath"/>
```