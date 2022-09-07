# Anatoliy Komarov CV
****
### Contacts:
****
* **Location:** Minsk, Belarus
* **Phone:** +375 29 709-60-78
* **Email:** admin@komaroff.biz
* **GitHub:** komarofff
****
### About me

****
### Skills:
****
*	HTML5
*	CSS3 GRID + FLEX
*	Bootstrap
*	TailWind
*	SCSS
*	GULP
*	JavaScript
*	PHP
*	MYSQL
*	Laravel
*	Wordpress
*	Vue.js
*	Git
*	Figma
*	Photoshop
****
### Portfolio:
[[Portfolio link](https://komarofff.github.io/front-end/)](https://komarofff.github.io/front-end/)
****
### Code example:
****
```
function isValidWalk(walk) {
  console.log(walk)
  //insert brilliant code here
  let pairs = {
    'n':'s',
    's':'n',
    'w':'e',
    'e':'w'
  }
 const chunkSize = 5;
 let subarray = [];
for (let i = 0; i <Math.ceil(walk.length/chunkSize); i++){
    subarray[i] = walk.slice((i*chunkSize), (i*chunkSize) + chunkSize);
}
let reverseWay = subarray.map(el => el.map(val => pairs[val]))   
console.log('reverseWay=',reverseWay[0].reverse())
     console.log('subarray=',subarray[1])
  if(walk.length != 10){
    return false
  }
  if(walk.length == 10 && (JSON.stringify(reverseWay[0].reverse()) == JSON.stringify(subarray[1])) ){   
      return true
  }else{return false}
  return false
  
}
```
****
### Experience
****
FRONT-END DEVELOPER  in  VASTERRA  (VASTERRA. COM)     05.01-2021 - JUNE 2022  
****
### Courses
*  2017    **MYFREEDOM**
Front-end developer. PHP, MYSQL, HTML, CSS, JavaScript, Laravel
* 2021   **BELHARD Academy**
Front-end developer. HTML5, CSS3 (GRID+FLEX), JavaScript, Vue.js
****
### Languages
* English A2-B1
* Polish  C1
****
****
