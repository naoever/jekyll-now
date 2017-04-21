---
layout: post
title: 4-21-2017 Slice function
---

## Slice function

The slice() method returns the selected elements in an array, as a new array object. 

The slice() method selects the elements starting at the given start argument, and ends at, but does not include, the given end argument. (W3C)

- Samples

Slice can return the part of the string.

```javascript
function print(str){
  document.write(str + "<br />");
}

document.write("<p>");

var str_obj = new String("Thank you");

print(str_obj);

print("slice(0, 1) --> " + str_obj.slice(0, 1));
print("slice(0, 2) --> " + str_obj.slice(0, 2));
print("slice(0, 5) --> " + str_obj.slice(0, 5));
print("slice(3, 7) --> " + str_obj.slice(3, 7));
print("slice(0) --> " + str_obj.slice(0));
print("slice(6) --> " + str_obj.slice(6));
print("slice(-9, -4) --> " + str_obj.slice(-9, -4));
print("slice(-8, 4) --> " + str_obj.slice(-8, 4));
print("slice(5, 0) --> " + str_obj.slice(5, 0));

document.write("</p>");
```

```javascript
var array = ['a', 'b', 'c', 'd'];

var s1 = array.slice(1, 2);
var s2 = array.slice(1, 3);

console.log(array); // ['a', 'b', 'c', 'd']
console.log(s1);    // ['b']
console.log(s2);    // ['b', 'c']
'''

