# Node Globals

This repo showcases hat if you forget a `var` keyword in Node.js, it'll leak the variable into a global variable, accessible from other files and modules too! Just like it would in the browser!

## Why?

Why did I even bother doing this? I write [CoffeeScript](http://coffeescript.org/), which [ensures all variables are locally scoped](http://coffeescript.org/#lexical-scope), so I never realised this behavour actually occurs within node, so was surprised when it did. Perhaps my fault? Maybe. But at least, using CoffeeScript means I never have to worry about this, perhaps time to give CoffeeScript a go?

## Run

```
node one.js
```