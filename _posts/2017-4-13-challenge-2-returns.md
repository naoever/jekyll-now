---
layout: post
title: 4-13-2017 Challenge 2 Returns
---

## Today I learned (#TIL):

- For statement
- meaning of 'saving the value' in the function

>PROGRAMMING CHALLENGE 2:
Write a function that takes an array of names and outputs a
string showing every unique pairing, in a format similar to:
"Amy and Bob, Amy and Cindy, Bob and Cindy" as one example.

This works on Chrome concole.

```javascript
var people = ["Mat", "Mark", "Luke", "John"];
var n = people.length;
var i, j;

for(i = 0; i < n; i++){
    for(j = i + 1; j < n; j++){
        console.log(people[i] + " and " +  people[j]);
    }
}
```



