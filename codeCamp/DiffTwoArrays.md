# Diff Two Arrays 

## 需求
* 比较两个数组，然后返回一个新数组，该数组的元素为两个给定数组中所有独有的数组元素。换言之，返回两个数组的差异。  

* 这是一些对你有帮助的资源:

    * Comparison Operators
    * Array.slice()
    * Array.filter()
    * Array.indexOf()
    * Array.concat()

* 以下是需要满足的条件

  *  diff([1, 2, 3, 5], [1, 2, 3, 4, 5]) 应该返回一个数组。 
 
  *  ["diorite", "andesite", "grass", "dirt", "pink wool",     "dead shrub"], ["diorite", "andesite", "grass", "dirt",     "dead shrub"] 应该返回 ["pink wool"]。
  
  *  ["andesite", "grass", "dirt", "pink wool", "dead shrub"], ["diorite", "andesite", "grass", "dirt", "dead shrub"] 应该返回 ["diorite", "pink wool"]。 
 
  *  ["andesite", "grass", "dirt", "dead shrub"], ["andesite", "grass", "dirt", "dead shrub"] 应该返回 []。  

  *  [1, 2, 3, 5], [1, 2, 3, 4, 5] 应该返回 [4]。  

  *  [1, "calf", 3, "piglet"], [1, "calf", 3, 4] 应该返回 ["piglet", 4]。  

  *  [], ["snuffleupagus", "cookie monster", "elmo"] 应该返回 ["snuffleupagus", "cookie monster", "elmo"]。  

  *  [1, "calf", 3, "piglet"], [7, "filly"] 应该返回 [1, "calf", 3, "piglet", 7, "filly"]。  
  
## 方案  

### 第一种方法

```javascript
function diff(arr1, arr2) {
  var newArr = [];
  var newArr1 = [];
  var newArr2 = [];
  // Same, same; but different.

  for(var i=0;i<arr1.length;i++){
    if(arr2.indexOf(arr1[i])==-1){
      newArr1.push(arr1[i]);
    }
  }

  for(var j=0;j<arr2.length;j++){
    if(arr1.indexOf(arr2[j])==-1){
      newArr2.push(arr2[j]);
    }
  }
  
  newArr = newArr1.concat(newArr2);
  return newArr;
}

diff([1, 2, 3, 5], [1, 2, 3, 4, 5]);

```

## 第二张方法

```javascript
function diff(arr1, arr2) {
  var newArr = [];         
  var same=[];
  for(var i=0;i<arr1.length;i++){
    if(arr2.indexOf(arr1[i])!==-1){
      same.push(arr1[i]);                //找出相同的项放在一个数组中
    }
  }
  newArr=arr1.filter(function(v){
   return same.indexOf(v)==-1;           //找出第一个数组中不同的项
  }).concat(arr2.filter(function(v){
   return same.indexOf(v)==-1;           //找出第二个数组中不同的项
  }));
  return newArr;                         //返回
}
```
## 第三种方法

```javascript
function diff(arr1, arr2) {

      var newArr = [];

      var arr3=arr1.concat(arr2);//将arr1和arr2合并为arr3

      function isContain(value){

      //找出arr3中不存在于arr1和arr2中的元素

      return arr1.indexOf(value)==-1||arr2.indexOf(value)==-1;

   }

      newArr = arr3.filter(isContain);

      return newArr;

}

```
## 第四种方法

```javascript
function diff(arr1, arr2) { 
  return arr1.filter(function(v){
   return arr2.indexOf(v)==-1;        //第一个数组在第二个数组中不同的项
  }).concat(arr2.filter(function(v){
   return arr1.indexOf(v)==-1;
  }));                                //第二个数组在第一个数组中不同的项
}
```

