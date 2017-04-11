---
layout: post
title: 4-10-2017 Day Three
---

## Today I learned (#TIL):

- How to write function.
- Some markdown syntax to edit this blog.
- Challenge 1

>PROGRAMMING CHALLENGE 1:
Write a function that answers the question,
"How many UNIQUE pairings would we have if everyone in our
group did one pair programming session with everyone else?"

inputs: the number of the people in the group
outputs: the nuber of the unique parings

I know the formula for getting the number of league match games.
x (x-1) +2 = games

So, I want to make calculator with it first.

If we have four people in the group, the number of shaking hands would be,

```javascript
function shakeHands() {
  var pairs ;
  pairs = 4 * (4 - 1) / 2
    document.write(pairs);
}
shakeHands(); 
```


## My next goals:

- Making another Challenge 1 solution with more programming way of thinking.
