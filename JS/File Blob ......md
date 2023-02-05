to convert a blob file back to file just use File constructor 
```javascript
var file = new File([myBlob], "name");
```
Update file using js 
```JS
	const dataTransfer = new DataTransfer();
	dataTransfer.items.add(file);
```