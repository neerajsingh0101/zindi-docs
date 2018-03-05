
## How to populate today's date in `mm/dd/yyyy` format


```javascript
var currentDt = new Date();
var mm = currentDt.getMonth() + 1;
var dd = currentDt.getDate();
var yyyy = currentDt.getFullYear();
var formattedDate = mm + '/' + dd + '/' + yyyy;
return formattedDate;
```
