# Codewars Challenges

## JavaScript

```javascript

// Multiply

function multiply(a, b){
  return a * b
}

// Reversed Strings

/* Complete the solution so that it reverses the string passed into it. */

function solution(str){
  // add code here
  return str.split('').reverse().join('')
}

// Odd Or Even

/* Given a list of integers, determine whether the sum of its elements is odd or even.
Give your answer as a string matching "odd" or "even".
If the input array is empty consider it as: [0] (array with a zero).*/

function OddOrEven(array) {
  // add code here
}

// String ends with
/* Complete the solution so that it returns true if the first argument(string) passed in ends with the 2nd argument (also a string). */

function solution(str, end){
  // add code here
  return str.endsWith(end) // returns boolean value
}

// Century from Year

/* The first century spans from the year 1 up to and including the year 100, the second century - from the year 101 up to and including the year 200, etc.

Given a year, return the century it is in. */

function century(year) {
  // add code here
  if(year > 100 && year < 1600>){
    return 16
  } else if (year < 100){
    return 1
  }

  return Math.ceil(year / 100)
}

// Convert a string to a number!

/* We need a function that can transform a string into a number. What ways of achieving this do you know? */

var stringToNumber = function(str){
  // add code here
  let newStr = parseInt(str)
  return newStr
}

// Friend or Foe?
/* Make a program that filters a list of strings and returns a list with only your friends name in it.
If a name has exactly 4 letters in it, you can be sure that it has to be a friend of yours! Otherwise, you can be sure he's not...*/

function friend(friends){
  // add code here
  const result = friends.filter(friend => friend.length === 4)
  return result
}

// Disemvowel Trolls

/* A common way to deal with this situation is to remove all of the vowels from the trolls' comments, neutralizing the threat.
Your task is to write a function that takes a string and return a new string with all vowels removed. */

function disemvowel(str){
  // add code here
  let regex = /[aeiou]/ig
  return str.replace(regex, '')
}

// Convert boolean values to strings 'Yes' or 'No'

/* Complete the method that takes a boolean value and return a "Yes" string for true, or a "No" string for false.
 */

function boolToWord(boolean){
  // add code here
  // use ternary operator rather than if/else
  return bool ? 'Yes' : 'No'
}

// Needle in the Haystack

/* Write a function findNeedle() that takes an array full of junk but containing one "needle".
After your function finds the needle it should return a message (as a string) that says:

"found the needle at position " plus the index it found the needle */

function findNeedle(haystack){
  // add code here
  let needleIndex = haystack.indexOf('needle')
  if(needleIndex != -1){
    return `found the needle at position ${needleIndex}`
  }
  }
}

```
