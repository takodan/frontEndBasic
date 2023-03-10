# Java Script
this note will write in chinese, may skip some coding fundamentals
# 0310 JS intro; JavaScript 簡介、快速開始
製作動態網頁的基礎  
## script 標籤
在html程式碼寫在`<script>`中  
```html
<script>
    console.log("Hello JavaScript");
</script>
```
## \! TIPS \! 注意大小寫
## \! TIPS \! 可以在網頁開發人工具debug

&nbsp;  
&nbsp; 

# 0310 JS data type; JavaScript 資料、資料型態
## 註解 comment
```js
// 單行註解

/* 
多行
註解 
*/
```
## 資料 data
程式基本運作單位  
## 資料型態 data type
1. 數字number：1 2 3.14  
2. 字串string："Hello" '接受單引號'  
3. 布林boolean：true false //均為小寫  
4. 空值null：undefined null //均為小寫  
5. 物件object：//暫時跳過  
## \* FYI \* undefined(未定義)和null(空)定義上為兩種不同的形態，但意義類似
## \* FYI \* 另有BigInt(因過大無法使用number表示的數)和Symbol兩種型態，但可能較少使用

# 0301 JS variable; JavaScript 變數、常數
## 變數 variable
可命名、存放資料的空間  
## 宣告變數 assign variable
```js
let x;
x=1 // assign
let variableName="data";
```
## 常數 constant
不可變動資料的變數
```js
const variableName="data";
variableName="newData"; // error
```
## \* FYI \* 宣告常數一定要給直否則會error
```js
const x; // error
const y=undefined; //ok
```
