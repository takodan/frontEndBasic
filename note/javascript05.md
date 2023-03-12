# Java Script
this note will write in chinese, may skip some coding fundamentals  
# 0312 JS object; JavaScript 物件基礎
用來封裝其他資料的容器
## \* FYI \* similar to python dictionary
## 建立、使用物件
```js
let obj= new Object(); // 建立名為obj的物件
obj.x= 3; // 建立物件成員(propertie), 非函式成員也叫屬性
obj.y= 4;
obj.foo= function(){}; //function也可以是properties, 函式成員也叫方法(methods)

result= obj.x+ obj.y //3+ 4
```

## 在物件的方法(methods)使用this
```js
let obj2= new Object();
obj2.x= 3;
obj2.y= 4;
obj2.bar= function(){
    console.log(this.x,this.y); // this refers to obj2
};
```

## JSON(JS物件表示法)
建立物件的簡單寫法
```js
let obj3= {}; // 空白物件
let obj4= {
    x:3,
    y:4,
    show:function(){
        console.log(this.x,this.y);
    }
};
```

&nbsp;  
&nbsp;  

# 0312 JavaScript Array 陣列物件
按照順序放其他資料的容器
## \* FYI \* similar to python list
## 建立、使用陣列
```js
let arr= new Array();
// as same as
let arr2= [];

//add data into array
arr.push(3);
arr.push(4);

// get data
arr[0]; // 3
arr[1]; // 4

// array length
console.log(arr.length); // 2

//add data when create array
arr3= [3, 4];
arr3.push(6);
console.log(arr3); //[3, 4, 6]
```