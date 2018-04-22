# Roman Numeral Converter

## 需求

*  将给定的数字转换成罗马数字。

   所有返回的 罗马数字 都应该是大写形式。

*  这是一些对你有帮助的资源:

    * Roman Numerals
    * Array.splice()
    * Array.indexOf()
    * Array.join()
    
*  以下是需满足的条件：

    * convert(2) 应该返回 "II"。
    * convert(3) 应该返回 "III"。
    * convert(4) 应该返回 "IV"。
    * convert(5) 应该返回 "V"。
    * convert(9) 应该返回 "IX"。
    * convert(12) 应该返回 "XII"。
    * convert(16) 应该返回 "XVI"。
    * convert(29) 应该返回 "XXIX"。
    * convert(44) 应该返回 "XLIV"。
    * convert(45) 应该返回 "XLV"。
    * convert(68) 应该返回 "LXVIII"。
    * convert(83) 应该返回 "LXXXIII"。
    * convert(97) 应该返回 "XCVII"。
    * convert(99) 应该返回 "XCIX"。
    * convert(500) 应该返回 "D"。
    * convert(501) 应该返回 "DI"。
    * convert(649) 应该返回 "DCXLIX"。
    * convert(798) 应该返回 "DCCXCVIII"。
    * convert(891) 应该返回 "DCCCXCI"。
    * convert(1000) 应该返回 "M"。
    * convert(1004) 应该返回 "MIV"。
    * convert(1006) 应该返回 "MVI"。
    * convert(1023) 应该返回 "MXXIII"。
    * convert(2014) 应该返回 "MMXIV"。
    * convert(3999) 应该返回 "MMMCMXCIX"。

## 方案 

### 第一种写法

```javascript
function convert(num) {  
    var numArr = [1, 4, 5, 9, 10, 40, 50, 90, 100, 400, 500, 900, 1000];  
    var strArr = ["I", "IV", "V", "IX", "X", "XL", "L", "XC", "C", "CD", "D", "CM", "M"];  
    var result = "";  
    while (num > 0) {  
        var i = numArr.length;  
        while (i >= 0) {  
            if (num >= numArr[i]) {  
                result += strArr[i];  
                num -= numArr[i];  
            } else {  
                i--;  
            }  
        }  
    }  
    return result;  
} 
```