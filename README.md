# Style Guide
Style guide for all of Spleefies' repos.
## General
Indentation: 2 spaces.

Variable names: `camelCase`.

Strings: For empty strings and strings with one character, use single quotes (`''`). Otherwise, use double quotes (`""`)\
Exception: when a string contains double quotes, you are allowed to use single quotes. e.g. `'This is a "style guide".'` 

## JavaScript
No semicolons should be used.

The variable name of a HTML element should have the element's name in it. 
```js
const submitButton = document.querySelector("#submit")
const popupDiv = document.getElementById("popup")
```

## TypeScript
Types should be capitalised. 
```ts
type Data
type UserData
```

## Any Questions? 
[Create an issue](https://github.com/Spleefies/style-guide/issues/new).