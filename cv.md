# Vladislav Poroshkov
***

## Junior Frontend Developer
***

### Contact info

**Email:** v.perush@mail.ru

**Telegram:** @Just_Perush

[**LinkedIn**](https://www.linkedin.com/in/vladislav-poroshkov/)
****

### Skills

#### 
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
****

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

