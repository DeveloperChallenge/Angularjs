# Angular 

## Project setup 

1. install angular (bower install angularjs --save)
1. install bootstrap (bower install bootstrap --save)
1. create index.html file (in the root folder)
1. add dummy html code and link those angular and bootstrap file to your html file 
1. run the project 

:thumbsup:


## Creating and app

1. create application folder in your root app dir.
1. create controller folder in /application
1. create Maincontroller.js file in /application/controller/
1. create app.js file in /application/

__Add following code in App.js__

~~~
angular.module("App",[]);
~~~

__Add following code in MainController.js file__
~~~
angular.module("App")

.controller("MainController",['$scope',function($scope){
    $scope.name = "This is my first angular App and  controller";
}]);

~~~

