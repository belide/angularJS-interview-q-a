# angularJS-interview-q-a
Angular JS Interview Questions &amp; Answer

###1) What are the advantage of AngularJS?

There are following advantages of AngularJS:
* Data Binding 
* Customize & Extensible 
* Code Reusability 
* Compatibility 
		
###2) What is the role of ng-app, ng-init and ng-model directives?

  ng-app - Initialize the angular app.
	ng-init - Initialize the angular app data.
	ng-model - Bind the html elem

###3) What is $scope and $rootScope?
	$scope - A $scope is a JavaScript object which is used for communication between controller and view. 
			Basically, $scope binds a view (DOM element) to the model and functions defined in a controller.

	$rootScope - The $rootScope is the top-most scope. An app can have only one $rootScope which will be shared among
	all the components of an app. Hence it acts like a global variable. All other $scopes are children of the $rootScope. 
  
###4) What are the directives in angular JS ?
	AngularJS directives are a combination of AngularJS template markups (HTML attributes or elements, or CSS classes) 
	and supporting JavaScript code.The JavaScript directive code defines the template data and behaviors of the HTML elements.

###5) What are different ways to invoke a directive?
	Attribute ('A')		<span my-directive></span>
	Class('C') 		<span class="my-directive: expression;"></span>
	Element ('E')	 	<my-directive></my-directive>
	Comment	('M')		<!-- directive: my-directive expression -->

###6) What is difference between $scope and scope ?
	$scope - In case of DI, you inject the scope object with the dollar prefix i.e. $scope. The reason is the injected arguments must match to the names of injectable objects followed by dollar ($) prefix .
	scope - When the methods like directive linker function don’t receive arguments through dependency injection, you just pass the scope 		object without using dollar prefix i.e. scope. The reason is the passing arguments are received by its caller.

  
###7) What is difference between services and factory ?
	Service - It is just a function for the business layer of the application . It is act as a constauctor function and invoked 
	once at a run time with new keyword.
	factory - Factory give you the same capability of as .serice() , but it is more powerful and flexible . A factory is a design 		pattern . Factory create objetcs such as new class instances , returns object literals, return functions and closures or even just return a simply string.
