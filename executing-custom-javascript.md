## Executing custom JavaScript

Zindid allows you to execute custom JavaScript in order to get things done which might be hard to do purely using 
extension or step editor.

Here is an example when based on text certain action needed to be taken.

If the text is “Care coordinators” then find a particular element, click on it. Then find another element and then click on 
that element.

``` javascript
if ("${text}" == "Care Coordinators") {
  var selector = ".btn-group > .btn > :nth-child(1)";
  document.querySelector(selector).click();
  selector = "#nav > div.switcher.pull-left > ul > li.active > a"
  document.querySelector(selector).click();
}
```
