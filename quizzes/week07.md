# Advanced Front-End Frameworks


**1.** Describe the two ways to bind Data in Vue?
<!-- enter you answer in the space below -->
```
The first way is to use v-bind, which is shortened with ':' behind a tag. :src=""
The second way is to use {{}} which is when you call a variable between tags. <div>{{}}</div>
```
**2.** The `SPA` acronym stands for what?
<!-- enter you answer in the space below -->
```
single-page application
```
**3.** What are some of the advantages/uses of a `SPA` over a traditional one?
<!-- enter you answer in the space below -->
```
The main use is organization. Keeping one page separate from others, but using/reusing components on those pages keeps things organized and allows for saving time on coding.
```
**4.** What does the `onMounted` method in Vue do?
<!-- enter you answer in the space below -->
```
onMounted says that when this page loads, run whatever code is in this method. Mainly used for fetching data required for the page.
```
**5.** What is the `v-model` attribute in Vue for, and when might you use it?
<!-- enter you answer in the space below -->
```
v-model (i think) creates an object with the attributes you've inputed on it, typically using 'editable'. You'd want to use this when editing an object or creating one.
```
**6.** The `v:on` (`@`) directive can be used for what?
<!-- enter you answer in the space below -->
```
Used for @click and @submit for running functions or code
```
**7.** Which Vue attributes(directives) could you use to conditionally render elements on a page?
<!-- enter you answer in the space below -->
```
v-if, v-else, v-show are the three I can think of. Basically saying v-if this is true, render this, else, render that. v-show doesn't even load the thing I think.
```
**8.** What is the purpose of the `key` attribute when using `v-for` on an element?
<!-- enter you answer in the space below -->
```
key is just basically an index for the array it's iterating through. I'm even pretty sure you can use :key.index instead of :key.id.
```
**9.** What is the `<slot>` element and what is it used for?
<!-- enter you answer in the space below -->
```
slot is what's used in components to insert new code in a template.
```