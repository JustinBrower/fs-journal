# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
let, var, const
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
a function runs a set of code only when called
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single responsibility function
open-closed principle
liskov substitution principle
interface segregation
dependency inversion
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
Index 2. arrays count form 0.
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
you.["You"].push(them)
Pretty much this and if this didnt work id make a find loop
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
if(2 >= 1){
  console.log('Two is indeed greater than one')
} else{
  console.log('What has this world come to')
}
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
the first part is the variable, the second is the "for" part, and the third is what happens if the "for" part is true.
normally i++ 
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
Document Object Model. index.html.
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
bool
number
bigint
string
symbol
null
undefined
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
parameters are the names of whats passed through, the argument is the value
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
primitive types always have a value, while reference types can not have a value
```