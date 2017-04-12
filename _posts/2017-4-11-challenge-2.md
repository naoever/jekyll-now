---
layout: post
title: 4-11-2017 Challenge 2
---

## Today I learned (#TIL):

- Still struggling with Challenge 1
- Find some samples for Challenge 2 solution

>PROGRAMMING CHALLENGE 2:
If you finish challenge #1 above, here's an alternate version:
Write a function that takes an array of names and outputs a
string showing every unique pairing, in a format similar to:
"Amy and Bob, Amy and Cindy, Bob and Cindy" as one example.



```javascript
var people = ["Mat", "Mark", "Luke", "John"];
var n = people.length;
var i, j;

for(i = 0; i < n; i++){
    for(j = i + 1; j < n; j++){
        console.log(people[i] + ", " +  people[j]);
    }
}
```


