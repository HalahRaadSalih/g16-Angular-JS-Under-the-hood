## Angular JS Under the hood

This repo is for angularjs concepts and what's going on under the hood. 

### Questions

- what is a digest cycle?
- what is $watch? 
- what does apply do?
- what is the difference between `$scope.$digest` and `$scope.$apply`?
	-  `$scope.$digest()`it fires the updates/changes (digest cycle)from within what scope it was called. 
	-  `scope.$apply()` goes all the way to the rootscope and fire their changes.
- what is the `$rootscope`?
	- it is the father of all others scopes per app. Every app has one rootscope and every controller has scope. 


###Notes:

 - scope is an object.
 - pass data between controllers? using services, don't say rootscope. 
