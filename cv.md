# Timur Yagudin
![avatar](./img/banner.jpg)
## My contacts
+ discord: t1murius
+ telegram: [@t1murius](https://t.me/t1murius)
+ GitHub: [timurius](https://github.com/timurius/)
+ Gmail: timur.yagudin.08@gmail.com
+ number: +995 591 21 80 56

## Brief Self-Introduction
I'am a beginner frontend developer and now I`m taking frontend courses on RS school to be able to find a job in the future. I already have experience in using html, css, js and a little bit React. Hope that I will complete this course successfully!
## Code examples
A few examples of my code taken from [codewars](https://www.codewars.com/):
### [Where my anagrams at?](https://www.codewars.com/kata/523a86aa4230ebb5420001e1)
```
function anagrams(word, words) {
  return words.filter( item => Array.from(word).sort().join() == Array.from(item).sort().join() )
}
```
### [Pete, the baker](https://www.codewars.com/kata/525c65e51bf619685c000059)
```
function cakes(recipe, available) {
  let res = [];
  for(let key in recipe){
    if( !(key in available) ) return 0;
    
    res.push( Math.floor(available[key] / recipe[key]) );
    
  }
  return res.sort( (a, b) => a - b )[0];
}
```
### [Detect Pangram](https://www.codewars.com/kata/545cedaa9943f7fe7b000048)
```
function isPangram(string){
  let alphabet = "ABCDEFGHIJKLMNOPQRSTUVWXYZ";
  let res = new Set();
  string = string.toUpperCase();
  Array.from(string).forEach(value => alphabet.includes(value) ? res.add(value) : '');
  return Array.from(res).sort().join("") == alphabet;
}
```
## Work experience
I\`ve already worked on one small [project](http://portfolio.bulat.one/) and I think it\`s pretty solid for a first project.
## Education
I still study at school, but I have completed [itstep](https://itstep.org/) main course in Belarus. After that, I`ve been self-studying using docs (such as [MDN](https://developer.mozilla.org/) and others), forums ([Stack Overflow ](https://stackoverflow.com/), [Reddit](https://www.reddit.com/), etc.), and other websites on the internet ([The Modern JavaScript Tutorial](https://javascript.info/), [W3Schools](https://www.w3schools.com/)).
## English level
According to [this website](https://test-english.com/level-test/) I have B1+ approximate level of grammar in English. But I don't have much experience communicating in English in real life. 
