# Seitnur Zhiger
## Contacts
email:nukejanjiger81@gmail.com.  
telegram: https://t.me/ZhigerSeitnur.
## About me 
I want to take this course and become a front-end developer, I am ready to study and work hard for this. Worked as a teacher in college, I want to take this course and become a front-end developer, I am ready to study and work hard for this. worked as a teacher in a college, introduced network technologies.

## Skills
* HTML 
* CSS
* BOOTSTRAP
## Code examples
Factorial
``` javascript
 function factorial(n){
    if(n < 0 || n >= 13){
     throw new RangeError();
      }else if( n == 0 || n == 1 ){
     return 1;
     }else{
        for(let i = n - 1 ; i >= 1; i--){
            n = n * i;
            
        }
        return n;  
     }
    }
```
Palindrome
```javascript
function isPalindrome(line) {
    let toS = line.toString();
    let splitted = toS.split('');
    let reverse = [];
    for(let i = splitted.length -1; i >= 0; i--){
        reverse.push(splitted[i]); 
    }
    let toJoin = reverse.join('');
    if (toJoin == toS){
        return true;
    }
    else {
        return false;
    }
}
```
