# Sum All Numbers in a Range

## 需求

* 我们会传递给你一个包含两个数字的数组。返回这两个数字和它们之间所有数字的和。
  
  最小的数字并非总在最前面。
  
* 这是一些对你有帮助的资源:
  
  * Math.max()
  * Math.min()
  * Array.reduce()

* 以下是需满足的条件  
  
  * sumAll([1, 4]) 应该返回一个数字。
  * sumAll([1, 4]) 应该返回 10。
  * sumAll([4, 1]) 应该返回 10。
  * sumAll([5, 10]) 应该返回 45。
  * sumAll([10, 5]) 应该返回 45。
  
## 方案

### 第一种方法

```javascript
function sumAll(arr) {
  
  var a = arr[0]>arr[1]?arr[0]:arr[1];
  console.log(a);
  var b = arr[0]<arr[1]?arr[0]:arr[1];
  console.log(b);
  var c = a - b;
  console.log(c);
  var d = 0 ;
  for(var i=0; i < c+1; i++){
    d = d + (i+b);
  }
  return d;
}

sumAll([1, 4]);
```
> 近似写法
```javascript
function sumAll(arr) {
  var result=0;
  a_start=Math.min(arr[0],arr[1]);
  a_end=Math.max(arr[0],arr[1]);
  while(a_start<=a_end){
    result+=a_start;
    a_start++;
  }
  return result;
}

sumAll([1, 4]);
```
### 第二种方法

```javascript
/*利用reduce来进行求和*/
function sumAll(arr) {
   var arryA=[];
   var max=Math.max.apply(null,arr);
   var min=Math.min.apply(null,arr);
   var sum=0;
   var sumFun=function(max,min){
      for(var i=0;i<(max-min+1);i++){
         arryA.push(min+i);
      }
      console.log(arryA);
      var value=arryA.reduce(function(previousValue,currentValue){
         return previousValue+currentValue;
      });
      return value;
   };
   sum=sumFun(max,min);
   return sum;
}
```

### 第三种写法

```javascript
function sumAll(arr) {
  return (arr[0] + arr[1])*(Math.abs(arr[0] - arr[1]) + 1)/2;
}
//论数学之美
```