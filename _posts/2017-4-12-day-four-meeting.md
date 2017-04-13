---
layout: post
title: 4-10-2017 Day Four: What would computer think?
---

## Today I learned (#TIL):

### on 1st Virtual meeting
- Using browser console for quick check (I've been using this browser function only for checking the source! amazing.)

- Pair programming: from freecodecamp - Repeat a string repeat a string
https://www.freecodecamp.com/challenges/repeat-a-string-repeat-a-string

We used new function (Liz has never used that) repeat.
We had some errors in the process. Through that I found some clues on what to do with the bug.
In this case, we had errors because;
repeat function rules (doesn't work for negative number)
line orders

```javascript
function repeatStringNumTimes(str, num) {
//inputs: a string, how many times to repeat the string
//outputs: a new edited string, original string multiplied by num
  //steps to need to happen: how do we get the string to repeat itself.
  // repeat after me
 
  
   if (num < 0) {
     return "";
   }
  var newString = str.repeat(num);
  return newString;
  
}

repeatStringNumTimes("abc", -2);
```

- for statement and while statement

- Think like in the computer's shoes. 


### for myself

- reviewing for statement and while statement
- Trying 


## My next goals:

- Back to the Challenge 1, 2 with the mindset I've learnd at today's meeting.
