## Question: What is the value of foo?

```var foo = 10 + '20'; ```
//foo is 1020

## What will be the output of the code below?

```console.log(0.1 + 0.2 == 0.3) ```
//returns false

## How would you make this work?

```add(2, 5);```
```add(2) (5);```

## Question: What value is returned from the following statement?

```"i'm a lasagna hog".split("").reverse().join(""); ```
//returns "goh angasal a m'i"

## Question: What is the value of window.foo?

```( window.foo || ( window.foo = "bar" ) ); ```
//"1020"

## Question: What is the outcome of the two alerts below?

```Javascript 
var foo = "Hello"; 
(function() { 
    var bar = " World"; 
    alert(foo + bar);
})(); 
alert(foo + bar);
//Hello World is the first outcome and the second outcome is bar comes back undefine because bar was defined inside the function and not outside like foo was. 
```

## Question: What is the value of foo.length?

```Javascript 
var foo = [];
foo.push(1);
foo.push(2); 
// the length is 2 so [1, 2]```

