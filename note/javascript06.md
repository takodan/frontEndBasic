# Java Script
this note will write in chinese, may skip some coding fundamentals  
# 0313 JavaScript HTML DOM 核心觀念
根據HTML Tag 建立 JS Object，稱為 HTML Element  
HTML Element串接在一起稱為HTML Document Object Model( DOM)
## 繪製網頁
HTMLcode> HTML DOM in JS> Web page
## window object
代表整個網頁
```js
console.log(windows); // 全部取得變數

window.innerWidth; // 頁面寬度
window.innerHeight // 頁面高度

window.prompt("彈出可輸入視窗訊息","輸入預設值");
window.alert("彈出此警告訊息");

// screen object
window.screen
window.screen.width // 整個螢幕寬度
window.screen.height // 整個螢幕高度
```
## document object
代表網頁主畫面，是window的一個屬性
```js
window.document
// as same as
document

document.title // HTML title tag
document.body // HTML body tag
```

# 0315 JavaScript HTML DOM 網頁畫面操作演練
## 利用id取得、操作標籤
```html
<div id="content">string</div>
<script>
    let divElement= document.querySelector("#content")
    divElement.innerHTML= "new string";
    divElement.className= "welcome";
    divElement.style.color= "blue";
    divElement.style.display= "none";
    divElement.style.fontSize= 30px;
</script>
```
## 點擊按鈕
```html
<button onclick= "change()">點我</button>
<script>
    function change(){
        // run this when click 點我
    }
</script>
```



