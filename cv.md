# MIkhail Popov
### Frontend / Javascript developer
---
## Contacts
##### Email: *[mvpdev@bk.ru](mailto:mvpdev@bk.ru)*
##### Telegram: *[@mipospb](https://t.me/mipospb)*

##### Github: *[mvpd3v](https://github.com/mvpd3v)*
---
## About me
*I want to become a software engineer and specialize in building modern interfaces in web applications. I love technology, the web, science fiction and industrial music. Every day I try to acquire skills and absorb knowledge that help me achieve my goal. My strengths are: curiosity experimentation, perseverance and quick assimilation of new information.*

---
## Skills
* *HTML, Pug*
* *CSS, SASS / SCSS, BEM, Tailwind, Bootstrap*
* *Javascript (ES6), React (begginer)*
* *Git*
* *VS Code, Webstorm*
* *Figma, Photoshop*

---
## Code examples

##### Array Deep Count
```Javascript
const deepCount = (arr) => {
  return arr.reduce((a, b) => {
    return a + (Array.isArray(b) ? deepCount(b) : 0)
  }, arr.length)
}
```
#####  Pair of gloves
```Javascript
const numberOfPairs = (gloves) => {
  let map = new Map();
  let arr = [];
  for (g of gloves) {
    if (!map.has(g)) map.set(g, 0);
    let count = map.get(g)
    map.set(g, count + 1)
  }
  Array.from(map.entries()).map(e => Math.floor(e[1] / 2)).forEach(e => {
    if (e > 0) arr.push(e)
  })
  return arr.reduce((a, i) => a + i, 0);
}
```
---
## Education
* University College Orenburg State University
  - *Technician-programmer*
* Self study
  - [Google](https://www.google.com/)
  - [Github](https://github.com/)
  - [Youtube](https://www.youtube.com/)
  - [MDN](https://developer.mozilla.org/en-US/docs/Learn)
  - [learn.javascript.ru](https://learn.javascript.ru/)
  - [Doka](https://doka.guide/)
  - [WebReference](https://webref.ru/)
  - [Codepen](https://codepen.io/)

---
## English
* A1