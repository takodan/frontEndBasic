# CSS
this note will write in chinese
## 0220 CSS 簡介、語法基礎教學
HTML: 處理網頁結構
CSS: 處理排版樣式
### 套用CSS樣式屬性
屬性名稱：屬性內容  
```html  
<!--粗體;紅字-->
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
```html
font-weight:normal
font-weight:bold <!--粗體-->
```
大小
```html
font-size:16px
font-size:2em <!--兩倍大-->
```
裝飾
```html
text-decoration:underline
text-decoration:line-through
```
對齊
```html
text-align:left
text-align:center
```

