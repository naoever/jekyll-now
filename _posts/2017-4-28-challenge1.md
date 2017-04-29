---
layout: post
title: 4-28-2017 Challenge 1 memo
---

```javascript
for (int i = 0; i < length; i++) {
    for (int j = i + 1; j < length; j++) {
    }
}
```


```javascript
function pairwise(list) {
  if (list.length < 2) { return []; }
  var first = list[0],
      rest  = list.slice(1),
      pairs = rest.map(function (x) { return [first, x]; });
  return pairs.concat(pairwise(rest));
}
```

```javascript
var alpha = [ "a", "b", "c", "d", "e", "f", "h", "i", "j" ];

for(var n=1;n<7;n++){ 
  console.log(
    n,                                 // number of items
    pairwise(alpha.slice(0,n)).length, // how many pairs from function?
    n*(n-1)/2                          // double check with formula above
  ); 
} 
```
