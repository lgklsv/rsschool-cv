# Oleg Kolosov

### Junior Frontend Developer

## Contact information:
**Email**: kolosov20011@gmail.com  |  **Telegram**: [helgiology](https://t.me/helgiology) | **Discord**: lgklsv#8630 | 

## Work experience:
**FuckRKN1** (Open source project) <sup>jul. 2022</sup>

Implemented a feature that switches a language on the page with only one html file. It works throughout the whole website remembering the current language.

[GitHub link](https://github.com/nezavisimost/fuckrkn1.org) | [Visit website](https://fuckrkn1.org/#ru)

## Skills:
- HTML
- CSS(SASS/SCSS)
- JavaScript(Fundamentals, ES6+, OOP, Asynchronous JavaScript, DOM)
- Git/GitHub
- Figma
- Module Bundlers(Parcel)

## Code example:
A function which increments a string, to create a new string.
- If the string already ends with a number, the number should be incremented by 1.
- If the string does not end with a number. the number 1 should be appended to the new string.

Examples:
`foo -> foo1`
`foobar23 -> foobar24`
`foo0042 -> foo0043`
`foo9 -> foo10`
`foo099 -> foo100`
``` javascript
function incrementString (strng) {
    const regex = /[0-9]+$/;
    if(strng.match(regex)) {
        const check = strng.match(regex)
        const lengthArr = check[0].length;
        const number =  +check[0] + 1;
        const numLength = Array.from(number).length;
        if(numLength != lengthArr){
            const padded = String(number).padStart((lengthArr - numLength), '0' );
            return strng.replace(regex, padded);
        }
        return strng.replace(regex, number)
    } 
    else {
        const resArr = Array.from(strng);
        resArr.push('1');
        return resArr.join('');
    } 
}
```

## Education/courses:
- [The Complete JavaScript Course 2022: From Zero to Expert!](https://www.udemy.com/course/the-complete-javascript-course/)
- [Harvard CS50x](https://cs50.harvard.edu/x/2022/)
- [Git & GitHub - The Practical Guide](https://www.udemy.com/course/git-github-practical-guide/)
- [FreeCodeCamp](https://www.freecodecamp.org/learn) (Responsive Web Design, JavaScript Algorithms and Data Structures, Front End Development Libraries)
- [RS School JavaScript/Front-end ](https://rs.school/js/)(ongoing)

## Languages:
- English (intermediate/upper-intermediate)
- Russian (native)
- German (A2 - B1)
