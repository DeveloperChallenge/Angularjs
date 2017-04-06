# Angular 

## Project setup 

* install angular (bower install angularjs --save)
* install bootstrap (bower install bootstrap --save)
* create index.html file (in the root folder)
* add dummy html code and link those angular and bootstrap file to your html file 
* run the project 

:thumbsup:


## Creating and app

* create application folder in your root app dir.
* create controller folder in /application
* create Maincontroller.js file in /application/controller/
* create app.js file in /application/

** Add following code in App.js ** 

~~~
angular.module("App",[]);
~~~

*** Add following code in MainController.js file ***
~~~
angular.module("App")

.controller("MainController",['$scope',function($scope){
    $scope.name = "This is my first angular App and  controller";
}]);

~~~

