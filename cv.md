# **Dundzer Nikita**
### Junior Frontend Developer
---  
### Contact Information:
**Phone:** +375(44)584-69-48;  
**E-mail:** nikita456nikita@yandex.ru;  
**Telegram:** @nabiraunamerok;  

---  
### About Myself:
I started programming at the age of 17 when he entered the IT University of BSUIR in Minsk.  
At first, programming seemed very difficult and I began to think that it was not mine, but  
then I joined the learning process and everything began to work out. in the 2nd year, I really  
enjoyed doing layout and frontend programming in general. For myself, I was engaged in photography  
and editing these photos in programs such as Adobe Photoshop and Lightroom. Also in the 3rd year  
I liked Java and in the future I think that I will master it too. In my free time I play guitar, drums.  

---  
### Skills:
**&#183;** HTML5, CSS3  
**&#183;** SCSS, SASS  
**&#183;** JavaScript, Java Basic, C++, TypeScript  
**&#183;** Git, GitHub  
**&#183;** VS Code, Intelij IDEA, WebStorm  
**&#183;** Adobe Photoshop, Adobe Lightroom  

---
### Code example:
**Kids With the Greatest Number of Candies from LEETCODE:**  
_There are n kids with candies. You are given an integer array candies, where each candies[i]_  
_represents the number of candies the ith kid has, and an integer extraCandies, denoting_  
_the number of extra candies that you have. Return a boolean array result of length n, where_  
_result[i] is true if, after giving the ith kid all the extraCandies, they will have the greatest_  
_number of candies among all the kids, or false otherwise. Note that multiple kids can have the_  
_greatest number of candies._  

```
@param {number[]} candies  
@param {number} extraCandies  
@return {boolean[]}  

var kidsWithCandies = function(candies, extraCandies) {  
    result = [];  
    for (let i = 0; i < candies.length; i++){  
        candies[i] += extraCandies;  
        if (candies[i] === Math.max.apply(null, candies)) result.push(true);  
        else result.push(false);  
        candies[i] -= extraCandies;  
    }  
    return result;  
};  
```
---
### Courses: 
**&#183;** JavaScript Manual on [learnjavascript.ru](learnjavascript.ru) (completed);  
**&#183;** RS Schools Course «JavaScript/Front-end. Stage 1» (in progress);  

---
### Languages:
**&#183;** English - Intermediate;  
**&#183;** Russian - Native;  