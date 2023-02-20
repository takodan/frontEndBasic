# HTML
## this note will write in chinese
## 0216 HTML 簡介、語法基礎教學
### tag 標籤
開頭標籤：\<html>、\<body>
結束標籤：\<html>、\</body>  
```html
<head><title>標題文字</title></head>
```
### tag屬性
屬性名稱 = "屬性內容"  
```html
<div id= "title"> class= "head">Title</div>
```
### 無內文tag
```html
<img></img>、<hr></hr> 也可以寫成<img/>、<hr/>
```
### 註解
```html
<!--註解文字-->
```
### 基本結構例子
```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8"/>
        <title>網頁標題</title>
    <head>
    <body>
        這裡輸入內容
    <body>
</html>
```
### \!TIP\! 用shift+tab減少縮排
<br/>

***
## 0216 HTML 常用標籤介紹
### 標題
\<h1>、\<h2>、\<h3>...  
```html
<h1>這是文章標題</h1>
```
### 超連結
\<a>配合href屬性指定目標網址  
```html
<a href="https://example.com">Example</a>
```
### 圖片
\<img>配合src屬性指定檔案位置  
```html
<img src="檔案位置"></img> 也可以寫成<img src="檔案位置"/>
```
### 列表
無順序\<ul> 有順序\<ol> 每一列\<li>  
```html
<ul>
    <li>aaa</li>
    <li>bbb</li>
</ul>
```
### 表格
\<table>  
\<tr> 代表row  
\<td> 代表column
```html
<table>
    <tr>
        <td>1</td>
        <td>2</td>
        <td>3</td>
    </tr>
    <tr>
        <td>4</td>
        <td>5</td>
        <td>6</td>
    </tr>
</table>
```
表格會類似於這樣  
| 1 | 2 | 3 |  
| 4 | 5 | 6 |

### 參考資料
https://www.w3schools.com/tags/default.asp

    