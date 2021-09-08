# Hi, my name is Yury Vinogradov


## Feel free to reach me out:
### 📞 Phone: +972 53 277-85-26
### ✉️ Email: yuvinogradov@gmail.com
### 🌐 LinkedIn: [Yury Vinogradov](https://www.linkedin.com/in/vngrd/)
#
### I'm a passionate frontend developer with experience in creating apps with React and Redux.
### I'm keen on solving katas on [Codewars](https://www.codewars.com/users/yuvinogradov). 
### In the future, I want to learn the backend and try myself as a fullstack developer.

#
### Main Skills
![ReactJs](https://img.shields.io/badge/-React-090909?style=for-the-badge&logo=React)
![Redux](https://img.shields.io/badge/-Redux-090909?style=for-the-badge&logo=Redux)
![JavaScript](https://img.shields.io/badge/-JavaScript-090909?style=for-the-badge&logo=JavaScript)
![TypeScript](https://img.shields.io/badge/-TypeScript-090909?style=for-the-badge&logo=TypeScript)
![API](https://img.shields.io/badge/-REST&#032;API-090909?style=for-the-badge)
# ![HTML](https://img.shields.io/badge/-HTML-090909?style=for-the-badge&logo=html5) ![CSS](https://img.shields.io/badge/-CSS-090909?style=for-the-badge&logo=css3) ![Material UI](https://img.shields.io/badge/-Material&#032;UI-090909?style=for-the-badge) ![CSS Modules](https://img.shields.io/badge/-CSS&#032;Modules-090909?style=for-the-badge) ![Styled Components](https://img.shields.io/badge/-Styled&#032;Components-090909?style=for-the-badge) ![STORYBOOK](https://img.shields.io/badge/-StoryBook-090909?style=for-the-badge) ![UNIT-TESTS](https://img.shields.io/badge/-Unit&#032;Tests-090909?style=for-the-badge)

### Code example:
(My solution of [Reverse or rotate?](https://www.codewars.com/kata/56b5afb4ed1f6d5fb0000991)  Kata on Codewars) :  

    function revrot(str, sz) {
        if( sz <= 0 || str === "" || sz > str.length) return ""
        
        filter = new RegExp(".{1," + sz + "}","g")
        console.log(filter)

        return  str.match(filter)
            .filter(s=> s.length === sz)
            .map(s => {
                    if (s.split('').reduce((acc, val) => acc+= val**3, 0) % 2 === 0 )  {
                        return s.split('').reverse().join('')
                    } else {
                        const arr = s.split('')
                        const leftChar = arr.shift()
                        arr.push(leftChar)
                        return arr.join('')
                    }
            }).join('')
    }

## Projects: 
**Carpooling marketplace.** (current project).  
Stack: React, JavaScript, Material UI, Firebase, AWS.   
  
**Cooperative purchasing.**  
Stack: React, Redux, TypeScript, Redux thunk, Axios, Formik.  
Developed product page and products list page, order page, reusable components, fixed bugs.  

**Memory cards web application.**  
Stack: React, Redux, TypeScript, Axios, Material UI.  
Developed user profile page, registration and login pages, pagination component, reusable modal components.  
  
**Food order aggregator web app.**  
Stack: React, Redux, TypeScript. 
Developed a food search, registration and authorization, added a user profile edit page.
  

## Education  
**React Frontend Developer, 2020**. IT-Incubator (640 hours, online).  
React, Redux, JavaScript, TypeScript.

**Bachelor of Electronic Engineering (1997 – 2002)**. Moscow State University of Electronic Technology, 
## Languages
English (fluent), Hebrew (intermediate), Russian (native)
