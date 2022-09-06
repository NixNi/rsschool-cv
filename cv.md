# Nikita Nikiforov
#### Student
***
## My Contact Info:
**Phone**: +7-931-593-32-15  
**E-mail**: nsntmp@gmail.com  
**Telegram**: Warilinc  
**Github**: [NixNi](https://github.com/NixNi)  
**Discord**: Varakafa#4619
***
## About me:
I am 19 years old student of SUAI. I like to learn new things and I try to constantly develop. I can approach tasks outside the box, considering them from different angles.
***
## Skills
 - HTML5
 - CSS3
 - JavaScript
 - Git, GitHub
 - VSCode
***
## Code example
This function detecting a pangram. A pangram is a sentence that contains every single letter of the alphabet at least once.
```js
function isPangram(string){
  return 1===string.toUpperCase().split('').reduce(
  (acc,rec,index) => { 
  if ((rec>='A' && rec<='Z') && string.toUpperCase().indexOf(rec)===index) {acc+=1}
  return acc
  },
  0
  )/26
}
```
g



