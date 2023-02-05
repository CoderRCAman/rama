Loop JS object
```javascript
	for (const property in object) {
	  console.log(`${property}: ${object[property]}`);
	}
```
Accept only positive whole numbers 
```javascript

onkeypress="return (event.charCode == 8 || event.charCode == 0 || event.charCode == 13) ? null : event.charCode >= 48 && event.charCode <= 57"

```
Get random number among two given ends min and max
```js
	min = Math.ceil(min);
    max = Math.floor(max);
    return Math.floor(Math.random() * (max - min + 1) + min);
```
