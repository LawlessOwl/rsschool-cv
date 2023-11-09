<img src="https://www.stratege.ru/sites/default/files/games/boxart/img/401b83a367da230e170f100d23f383e1.png" alt="my avatar" width="100"/>

# **Maxim Kaschei** 


## Contact Information
### -*Linkedin : (https://www.linkedin.com/in/maksim-kaschei-00058524a/)*
### -*discord : lawlessowl*

---

## Self-introduction
### **I’m front-end developer specializing on JavaScript development and HTML with SCSS layout, I have a 1,5 year of experience in solving problems** </br>
### **My goal for this year it’s improve my development skill, start work with React and find good team with who I can work and grow up like a developer.**

---

## Skills
- JavaScript
- HTML5
- CSS
- SCSS
- React

---

## Code Examples

### My solution for [RGB To Hex Conversion task on codewars](https://www.codewars.com/kata/513e08acc600c94f01000001)
```
let rgb = (r, g, b) => {
    let convers = (color) => {
      if (color > 255) {
        return 'FF'
      } else if (color < 0) {
        return '00'
      } else {
        return color.toString(16).padStart(2,"0").toUpperCase()
      } 
  }
    return convers(r) + convers(g) + convers(b)
}
```

### My solutioon for [Matrix Multiplier task on codewars](https://www.codewars.com/kata/573248f48e531896770001f9)
```
const getMatrixProduct = (a, b) => {
  let firstMatrixRow = a.length
  let firstMatrixCol = a[0].length
  let secondMatrixRow = b.length
  let secondMatrixCol = b[0].length
  let result = []
  if (firstMatrixCol != secondMatrixRow) {
    return null
  } else {
    for (let i = 0; i < firstMatrixRow; i++) {
    result[i] = []
  }
  for (let j = 0; j < secondMatrixCol; j++) {
    for (let i = 0; i < firstMatrixRow; i++) {
      let c = 0;
      for (let k = 0; k < secondMatrixRow; k++) {
        c += a[i][k]*b[k][j];
        result[i][j] = c
      }
    }
  }
  return result;
  }
};
```

---

## Work expirience

### [Agency Landing page](https://github.com/LawlessOwl/agency.github.io)
***This project is a web-site for photographers team, this landing I make with HTML and SCSS, all animation I make on SCSS and for elements position I use Flexbox.***
[Deployment](https://lawlessowl.github.io/agency.github.io/)

---

## Education

### ***Grodno State College of Technique, Technologies and Design (2014-2017)***
- Electromechanic
- Computer's operator

---

## English Language

### ***English skill - B1***