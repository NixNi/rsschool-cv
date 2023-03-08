# Nikita Nikiforov
## Junior Frontend Developer
***
## My Contact Info:
Phone: +7-931-593-32-15  
E-mail: nsntmp@gmail.com  
Telegram: Warilinc  
## About me:
I decide to learn development because I like to create new things that will help people. I try to constantly learn new things and develop. My strength is to approach tasks outside the box, considering them from different angles.
## Skills
 - HTML5, CSS3, SCSS  
 - JavaScript, TypeScript  
 - React  
 - Git, GitHub  
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