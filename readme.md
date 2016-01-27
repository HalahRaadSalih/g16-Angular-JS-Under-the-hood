## Angular JS Under the hood

This repo is for angularjs concepts and what's going on under the hood. 

### Questions

- what is a digest cycle?
- what is $watch? 
- what does apply do?
- what is the difference between `$scope.$digest` and `$scope.$apply`?
	-  `$scope.$digest()`it fires all watchers from the scope it was called from. 
	-  `scope.$apply()` goes all the way to the rootscope and fire their changes.
- what is the `$rootscope`?
	- it is the father of all others scopes per app. Every app has one rootscope and every controller has scope. 


###Notes:

 - Scope is an object.
 - pass data between controllers? using services, don't say rootscope. 
 -  don't user the variables with $$ because they're meant to be private for angularJS.
 -  `$scope.$$watchers` is a list of watchers. 
 -  What are directives? a way to let/teach html to perform some functionality. They live inside your html. Examples of directives? ng-model, ng-repat ..etc. You can make your own custom directives. 
 
