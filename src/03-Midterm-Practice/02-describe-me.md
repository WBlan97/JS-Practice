# Describe Me - A Lesson on Data Types

![Cute bunch of 4 kittens](./../assets/images/cute-kittens.jpg)

Let's pause for a second and make sure that we understand how data are another way to describe our reality. Different types of data and data structures offer us different ways to carry out this descriptive work.

In small groups of 3-4 people, work through the following sections that ask you to describe the above image of kittens with different types of data primitives and data structures.

<p class="warning">
  Be sure to render your variables to the page in a separate codeblock, so you know the code is working.
</p>

## 1. String

```js
let descriptionCat = "Here are four cute kittens that are all different colors."
```

## 2. Array

Create a variable that is assigned to an Array that has 4 or more values to describe this image.

```js
let cuteArray = ["farLeft", "tabby", "headDown", "leaning"]
```

## 3. Object

Create a variable that is assigned 1 object with at least 4 key-value pairs.
```js
let Timmy = {
Hair: "Orange",
eyeColor: "Blue",
ageMonth: 3,
temperament: "Restful",
}
```

## 4. Array of Objects

```js
let cuteArrayObject = [
{
Hair: "Orange",
eyeColor: "Blue",
ageMonth: 3,
temperament: "Angry",
}, 
{
Hair: "Brown",
eyeColor: "Blue",
ageMonth: 4,
temperament: "solemn",
}]


```

```js
/**
 * logNames
**/
const logNames = (collection) => {
console.log(collection)
}
```







## Helpful Transformative Methods in JS

We should remember a few useful methods, when working with the above types of data. Let's practice some of them together:

### Strings

```js
/**
 * Strings:
 * concatenation, .charAt(), .slice(), .slice()
**/

```

```js
descriptionCat.slice(2,10)
descriptionCat.split(".")
```
### Arrays

```js
/**
 * Arrays:
 * Using index position, .push(), for loops, .map()
**/
cuteArray[0]
cuteArray.push("TopRight")
for (let Kitty in cuteArray){
console.log(")
}

let newKittyArray = cuteArray.map(
(kitty) => {
  if(kitty == "farLeft"){
  let newName = "cute" + kitty
  return newName
  }
}
)
```
### Objects

```js
/**
 * Objects:
 * Accessing values with keys; Adding new properties (key-value pairs)
**/
Timmy["Hair"]
```

### Array of Objects

```javascript
/**
 * Array of Objects:
 * Looping through and accessing properties with keys;
 * Adding new props;
 * Difference between .map() and for loops
**/
```

```javascript
let newKittyCollection = kittenCollection.map(
  
)
```

## Practice with Functions
<!-- Write a new function  -->
```js
/**
 * 1. File formats
 * 2. PropName: String, used to access specific property in object.
 **/

const writeKittyProperties = (animalCollection, propName) => {
let newCollection = []
for (const animal of animalCollection){
newCollection.push(animal[propName])
}
return newCollection
}
```

```js
let kittynames = writeKittyProperties(kittenCollection, "name")
console.log(kittyNames)
```

