# **Hasenov Magzhan**


## **Contacts:**

**E-mail:** mak.khas01@gmail.com <br>
**Phone:** +7 (775) 796 3210 <br>
**Discord:** Maka#2223 <br>


## **Briefly about myself**:

I was born in 09.30.2001 in the country of Kazakhstan, in the city of Astana. At the moment I am studying in the second year of the Master's degree program "Information Systems". I have no work experience, but I have a very great desire to learn programming. Since I was a teenager, I have been very interested in programming because it looks like a constructor of your capabilities and ideas. I perceive programming environments as a canvas, and a programmer as an artist drawing an amazing world. And it always fascinated me, the way pieces of code come to life in front of the user, I always wanted to do it myself. For this reason, I started to study programming on my own, and I think I have reached a good level, but still in order to improve my skills I entered RS School. I hope with the help of this school I will be able to create my "own world" in the future.


## **Programming languages and Frameworks:**

### *Basics:*

![JavaScript](https://img.shields.io/badge/-JavaScript-090909?style=for-the-badge&logo=Javascript&logoColor=yellow)
![CSS3](https://img.shields.io/badge/-CSS-090909?style=for-the-badge&logo=CSS3&logoColor=blue)
![Node.JS](https://img.shields.io/badge/-Node.JS-090909?style=for-the-badge&logo=Node.js&logoColor=green)
![Express](https://img.shields.io/badge/-Express-090909?style=for-the-badge&logo=Express&logoColor=green)
![Python](https://img.shields.io/badge/-Python-090909?style=for-the-badge&logo=Python&logoColor=blue)
![MongoDB](https://img.shields.io/badge/-MongoDB-090909?style=for-the-badge&logo=MongoDB&logoColor=green)

### *Beginner:*

![React](https://img.shields.io/badge/-React-090909?style=for-the-badge&logo=React&logoColor=blue)
![Vue](https://img.shields.io/badge/-Vue-090909?style=for-the-badge&logo=Vue.js)
![SQL](https://img.shields.io/badge/-SQL-090909?style=for-the-badge&logo=mysql)


## **Code example:**

**Detect Pangram KATA from CODEWARS:** Given a string, detect whether or not it is a pangram. Return True if it is, False if not. Ignore numbers and punctuation.

```JavaScript
function isPangram(string){
  const alphabet = ["a", "b", "c", "d", "e", "f", "g", "h", "i", "j",
                  "k", "l", "m", "n", "o", "p", "q", "r", "s", "t", "u",
                  "v", "w", "x", "y", "z"];

  var split_string = [];

  for (i in string){
    if(string[i] === " " || string[i] === "." || typeof string[i] === "number"){
      /* pass */
    } else {
      split_string.push(string[i].toLowerCase())
    }
  };

  for (var j = 0; j < alphabet.length; j++) {
    if (split_string.indexOf(alphabet[j]) < 0) {
      return false;
    }
  };

  return true;

};
```


## **Education:**


### *Master's degree:*

- Turan-Astana University program: "Information Systems" (in progress)

### *Courses:*

- HTML and CSS course on the [Stepik](https://stepik.org) (completed)
- RS School Course "JS / Front-End Stage 0" (in progress)

## **Languages:**

- Kazakh - Native
- Russian - Intermediate / Upper-intermediate (2nd language)
- English - Pre intermediate (A2)