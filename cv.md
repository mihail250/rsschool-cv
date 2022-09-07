## Mihail Melihow

Contact information:


Phone: 89537472536


E-mail: mmelihow@gmail.com


Telegram: @mihailmelihow


----
**Briefly About Myself:**

My goal is to do every day what i love and most passionate about. How i want to achive it? By learning new skills , and asking myself do i like it or not. And now i satisfied by learning programming. Also healphy food, and sports are the my best friends in this journey.

----
**Skills and Proficiency:**

HTML5, CSS3
JavaScript Basics
Git, GitHub
VS Code
Python Basics

----
 **Code example:**
 
 *Implement function check(str, bracketsConfig), that for given brackets sequence will return true if it is correct and false otherwise
In the second param there is bracketsConfig - the array of pairs open-closed brackets. Each subarray includes only 2 elements - opening and closing bracket
```
module.exports = function check(str, bracketsConfig) {

  let objects = {};
  for (i = 0; i < bracketsConfig.length; i++) {
    objects[bracketsConfig[i][1]] = bracketsConfig[i][0];
  }


   
  let opens = [];
  let closes = [];
  for (i = 0; i < bracketsConfig.length; i++ ) {
  opens.push(bracketsConfig[i][0])
  closes.push(bracketsConfig[i][1])
  }

    
    let same = str.split('|').length-1;
    if (same % 2 > 0) {
    return false
  }
   
  let stack = [];
  for (i = 0; i < str.length; i++){
    
    if (  stack.length !== 0 && objects[str[i]] === stack[stack.length-1] )  {
      stack.pop() 
      
       
    } else if (  opens.includes(str[i])) {
      stack.push(str[i]) 
    } else {
      return false
    }
    
    

  }
  return stack.length === 0 ? true : false ;
}
```
----
**Courses:**

generation python - for beginners
rsschool JS/ FrontEnd 

----
**Languages:**

English - Intermediate (listening and reading slills - strong upper intermediate, speaking and writing - pre intermediate)

Russian - Native
