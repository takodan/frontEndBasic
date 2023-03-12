# Java Script
this note will write in chinese, may skip some coding fundamentals  
# 0312 JS control flow: conditional expressions; JavaScript 流程控制：判斷式
建立邏輯判斷與對應  
## block程式區塊
用`{}`包覆的一段程式碼稱為區塊  
## if, if...else, if...else if... else
```js
if(boolean1){
    //  如果boolean1為true，執行這段區塊 
}else if(boolean2){
    // 如果boolean2為true，執行這段區塊
}else{
    // 如果以以上均為false，執行這段區塊
}
```

&nbsp;  
&nbsp; 

# 0312 JS control flow: loop; JavaScript 流程控制：迴圈基礎
重複執行程式區塊
## while
```js
while(boolean){
    // 如果為true，執行這段區塊
    // 執行結束，跳到開頭再判斷是否為true
}
```
### for
```js
for(初始化; boolean; 每次執行){
    // 同while
}
```

&nbsp;  
&nbsp; 

# 0312 JS control flow: loop command ;JavaScript 流程控制：迴圈指令 
只能寫在迴圈中的特殊指令
## break
強制中斷迴圈
## continue
強制進入下一個迴圈