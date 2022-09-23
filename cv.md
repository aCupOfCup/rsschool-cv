# Zaparenko Dmitry Evgenievich
<ins>_Contacts:_</ins>
* E-mail: dmi1ryD@yandex.com
* LinkedIn: [https://www.linkedin.com/in/dimitry-z/](https://www.linkedin.com/in/dimitry-z/)
* Facebook: [https://www.facebook.com/](https://www.facebook.com/)
* Discord(RS-School server): Dmitry Zaparenko (@M-Dimonka)
* Github:
	* First account - [https://github.com/Di-mentos](https://github.com/Di-mentos)  
	* Second account(RS-School repos) - [https://github.com/M-Dimonka](https://github.com/M-Dimonka)

*********

<ins>_Goals:_</ins>  
 1. To develop as a Frontend-developer, finding ways to make the sites more attractive and interactive for user  
 2. To learn how to make complex web-applications using different technologies
 
*********

<ins>_Main skills:_</ins>
 * HTML5/CSS3 (transformation and animation of elements, using filters, gradients)
 * Semantical-HTML
 * Responsive layouts
 * Flexbox
 * BEM-methodology
 * SASS/SCSS
 * Javascript basics(data types, arrays, OOP approach, DOM, closures, callbacks, prototypes)
 * Basics of Three.js, SVG
 * Basics of React(SPA-conception, JSX, components, state management, FLUX, UI/BLL program architecture levels)
 * Photoshop, Figma
 * Git, Github
 * Sublime Text 3, VS Code, Brackets
 
*********

<ins>_Code example:_</ins>

**A task from Codewars:** If we list all the natural numbers below 10 that are multiples of 3 or 5, we get 3, 5, 6 and 9. The sum of these multiples is 23.  
Finish the solution so that it returns the sum of all the multiples of 3 or 5 below the number passed in. Additionally, if the number is negative, return 0 (for languages that do have them).  
**Solution:**
```
function solution(number){
  var sum = 0;
  if(number<0){
    return 0;
  }
  else{
    for(var i=1; i<number; i++){
      if(i%3 == 0 || i%5==0){
        sum+=i;
      }
    }
  }
  return sum;
}
```

*********
