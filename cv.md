# rsschool-cv
 ### Shchetinin Mikhail
 #### Aims:
  My aim it to become a good strong developer in one year period.
        Because I’m new to this area, 
        I want to learn basic technologies of front end development, main tools and approaches.
          As web development is one the perspective area of software development, 
          I’d like to understend how to build web application using modern aproaches and frameworks.
 #### Skills:
 JavaScript, React, HTML, CSS
 #### CODEWARS exemple:
```javascript

function getCard() {
    let arr = []
    function getRandomIntInclusive(min, max, letter) {
        min = Math.ceil(min);
        max = Math.floor(max);
        return (letter + (Math.floor(Math.random() * (max - min + 1)) + min))
    }
    function generate(min, max, letter, count) {
        for (i = 0; i < count; i++) {
            let res = getRandomIntInclusive(min, max, letter)
            if (!arr.includes(res)) arr.push(res)
            else i--
        }
    }
    generate(1, 15, "B", 5)
    generate(16, 30, "I", 5)
    generate(31, 45, "N", 4)
    generate(46, 60, "G", 5)
    generate(61, 75, "O", 5)
    return (arr)
} 

```
 #### English: 
 self-education
 #### Email: sh_chetinin@mail.ru