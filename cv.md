# Vladislav Poroshkov


## Junior Frontend Developer


### Contact info

**Email:** v.perush@mail.ru

**Telegram:** @Just_Perush

**Discord:** Just_Perush#6585

[**LinkedIn**](https://www.linkedin.com/in/vladislav-poroshkov/)

***

### About

I came here to refresh my knowledge, consolidate my javascript development skills, and get a lot of relevant knowledge in the Front-end.


### Skills

- **HTML5**
- **Style Sheets:** CSS, SASS, SCSS
    - Adaptive, responsive markup
        - Mobile-first
        - Desktop-first
- **Programming languages:** JavaScript (ES6+), Node.js (Basic), Python
- **Libraries:** React (Basic), Axios
- **Package managers:** NPM, Yarn
- **Bundlers:** Vite, Webpack
- **Version Control Systems**: git
- **Dev environment:** WebStorm


***

### Code example

**Task:** Transform any string to ASCII. In the resulting number replace all the numbers `7` with the number `1`.
Function should return the difference of two numbers.

```javascript
function calcASCIIDifference(stringToCalc) {
    const total1 = stringToCalc.split('')
        .map(currentValue => currentValue.charCodeAt(0)).join('')
    const total2 = total1.split('')
        .map(currentValue => currentValue === '7' ? '1' : currentValue).join('')
    return total1 - total2
}

console.log(calcASCIIDifference('ABC'))
```
***

### Projects
1. [AxitProject](https://github.com/JustPerush/AxitProject) - First markup project. **Technologies:** HTML+CSS.
2. [Dashboard](https://github.com/JustPerush/Dashboard) - Second markup project with adaptive markup and Sass CSS extension. **Technologies:** HTML+SCSS, Gulp.
3. [Softarex Test Project](https://github.com/JustPerush/softarex-test-project) - Test project for Softarex Technologies. **Technologies:** HTML+SCSS, JavaScript, React, Vite, ESLint.

***

### Education and courses

1. [Belarusian State University of Informatics and Radioelectronics](https://www.bsuir.by/), Faculty of Computer Systems and Networks (2019-2023). Systems engineer, Bachelor degree.
2. [TeachMeSkills](https://teachmeskills.by/) (2021-2022). Frontend Development Course.
3. Rolling Scopes School Course "JavaScript/Front-end. Stage 0" (in progress)

***

### Languages 

- English - Intermediate
- Russian - Native
- Belarusian - Intermediate
