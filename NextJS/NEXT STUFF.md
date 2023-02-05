How to resolve 404 not found when using dynamic routes to access PUBLIC FOLDER
**ANS** : Basically it happens  because of prefixed slash which means doing something like 
```js
	images/random.png 
	//the above will not work 
	/images/random.png //will work
```
