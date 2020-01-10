# JsEpicFunctions
JavaScript epic functions to save time while programming

Tired of writing
```javascript
document.getElementById("id");
document.getElementsByTagName("tag");
document.getElementsByClassName("className");
```
 Every time?
 
 Use querySelector and querySelectorAll methods by targetting elements as you target them using CSS (or as in jQuery)
 ```javascript
document.document.querySelector("selector"); //single element
document.document.querySelectorAll("selector"); /:multiple elements
```
Want more comfort ?

Declare these functions
```javascript
function _(e){
  return document.document.querySelector(e);
}
function _a(e){
  return document.document.querySelectorAll(e);
}
```
Becauser it's better to use
```javascript
let selector = _("selector");
//or
let selectors = _a("selectors");
```
Than
```javascript
let selector = document.document.querySelector("selector");
//or
let selectors = document.document.querySelectorAll("selectors");
```
