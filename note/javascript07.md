# Java Script
this note will write in chinese, may skip some coding fundamentals  
# 0316 JavaScript Event Handling 事件處理
網頁互動
## 常見事件種類mouse
1. onclick
2. onmouseover
3. onmouseout
4. onmousedown
5. onmouseup
## 事件處理流程
1. 在哪個標籤上發生
2. 事件的種類
3. 事件對應的函式
```html
<div eventName= "functionName();">content</div>
<script>
    function functionName(){
        // code
    }
</script>

<!-- or use "this" represent the element -->
<div eventName= "functionName(this);">content</div>
<script>
    function functionName(elem){
        elem.innerHTML= "new content";
    }
</script>

<!-- multiple event -->
<div
    eName1= "fName1(this);"
    eName2= "fName2(this);"
>content</div>
<script>
    function fName1(this){
        elem.innerHTML= "new content";
    }
    function fName2(this){
        elem.innerHTML= "new content";
    }
</script>
```