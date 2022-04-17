# Anton Sukhadolets

### Contact Info:
- tel: +48 792 302 263
- email: suhodoleca@gmail.com
- [Linkedin](https://www.linkedin.com/in/anton-suhodolec-276283a3/)

### Summary
I don't have commercial experience, but I try to get new knowledge every day. I do training web projects and read a lot of web documentation and articles.
In my learning I use such online resources as: 
- codecademy [link to my profile](https://www.codecademy.com/profiles/design6714341631)
- codewars [link to my profile](https://www.codewars.com/users/SuhodolecA)
- freecodecamp [link to my profile](https://www.freecodecamp.org/fccd05e9812-e2ea-4038-920a-15d1b3799051)
- frontendmentor [link to my profile](https://www.frontendmentor.io/profile/SuhodolecA)
- frameworks documetation, books

and others...

### Skills 
- HTML5
- CSS (including animations, flexbox, css grid and css variables, accessibility)
- JavaScript
- Chart.js
- jQuery
- React.js (basic)
- Sass/Scss
- LESS
- Git
- BEM methodology
- Gulp 4 (basic)
- Node.js (basic)
- Npm(basic)
- Figma

### Code example:

```
function smallEnough(a, limit){
 return a.every(elem => elem <= limit);
}
```
```
function filterHomogenous(arrays) {
  return arrays.filter(i => {
    return i.length === 1 || i.every(i => typeof i === 'number') && i.length !== 0 || i.every(i => typeof i === 'string') && i.length !== 0;
    })
}
```
```
const whosOnline = (friends) => {
  const resultObj = {};
  friends.forEach(i => {
    if (i.status === 'online' && i.lastActivity > 10) {
      if (resultObj.hasOwnProperty('away')) {
        resultObj.away.push(i.username);
      } else {
         resultObj.away = [i.username];
      }
    } else if (i.status === 'online' && i.lastActivity <= 10) {
      if (resultObj.hasOwnProperty('online')) {
        resultObj.online.push(i.username);
      } else {
        resultObj.online = [i.username];
      }
    } else {
      if (resultObj.hasOwnProperty('offline')) {
        resultObj.offline.push(i.username);
      } else {
        resultObj.offline = [i.username];
      }
       
    }
  })

  return resultObj;
}
```

### Experience:
Some training projects that I did:
- [Tip-calculator-app-challenge-hub](https://tip-calculator-app-challenge-hub.vercel.app/)
- [Time-tracking-dashboard](https://time-tracking-dashboard-umber.vercel.app/)
- [Image-gallery](https://image-gallery-liart.vercel.app/)
- [Analog-clock-js](https://analog-clock-js.vercel.app/)
- [More in my GitHub](https://github.com/SuhodolecA)

### Education:  
- October 2019 - February 2020 IT SPECIALISTS TRAINING CENTER SkillUP, FRONT-END DEVELOPING.
- 2012-2013 Institute for Advanced Qualifications and Retraining BNTU, Logistics, Logistician - economist.
- 2007-2012 Belarusian National Technical University, Instrument making, Electrician - engineer.
### Languages: 
- Russian - Native
- English - B1
- Polish - A2