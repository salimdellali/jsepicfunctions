# JsEpicFunctions
JavaScript Epic Functions to save time while programming

Tired of writing :
```javascript
document.getElementById("id");
document.getElementsByTagName("tag");
document.getElementsByClassName("className");
```
 Every time?
 
 Use querySelector() and querySelectorAll() functions by targeting elements as you target them using CSS (or jQuery) :
 ```javascript
document.querySelector("singleSelector");      //single element
document.querySelectorAll("multipleSelector"); //multiple elements
```
Want more comfort ? Declare these functions :
```javascript
/**
 * Epic Functions Down Below !
 */
function _(e){
  return document.querySelector(e);
}
function _a(e){
  return document.querySelectorAll(e);
}
```
Becauser it's better to use :
```javascript
let selector = _("singleSelector");
//or
let selectors = _a("multipleSelector");
```
Instead of :
```javascript
let selector = document.querySelector("singleSelector");
//or
let selectors = document.querySelectorAll("multipleSelector");
```
> By using these Epic Functions, you avoid writing - up to - 23 additional characters in each usage :wink:

:rocket:
