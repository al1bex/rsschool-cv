# Alibek Tastan _a.k.a (**@al1bex**)_

## Contact Information
   * __Phone number__: `8(775)-721-68-65`
   * __E-mail__: `alibektastan04@gmail.com`
   * __Instagram__: `@al1bekkkk`

## About myself:
> Hello everyone who read the text. My name is, my name is chiki-chiki Slim Shady. OK, jokes aside. My name is Alibek, and I'm 17 yo. I recently moved to Almaty, for studying at International IT University. I love playing competitive games, walking, listen music and learn programming.

## Skills:
   * HTML5
   * CSS3
   * Native JavaScript(ES5, ES6)
   * C++ (Superficially)
   * Stand on hands (Professional)

## Code Example:
   _Written on JavaScript_

   ```
   h1.addEventListener('mouseenter', function () {
    this.style.color = 'red'
})

h1.addEventListener('mouseleave', function () {
    this.style.color = 'white'
})  
let link  = document.querySelector('a')

link.addEventListener('click', handleLinkClick)
function handleLinkClick(event) {
   link.textContent = link.textContent === 'Hide' ? 'Show' : 'Hide'
   event.preventDefault()

   let div = boxes[0]
   div.style.display = div.style.display === 'none' ?  'flex' : 'none'
}

const boxes = document.querySelectorAll('div')

for (let i = 0; i < boxes.length; i++) {
    boxes[i].addEventListener('click', function (event) {
        event.stopPropagation()
        console.log(event.target.id)
    })
}
 
const pars = document.querySelectorAll('p')

for (let i = 0; i < pars.length; i++) {
    pars[i].addEventListener('click', function(event) {
        console.log(event.target.textContent)
    })
}
   ```

## Courses: 
* HTML5 and CSS3 Basics (_Completed_)
* [JS Course by Udemy](https://www.udemy.com/course/modern-javascript-from-beginning) (_In progress_)
* RS School JS/Front-end. Stage 0 (_In progress_)