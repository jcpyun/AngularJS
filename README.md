# AngularJS
I really think that REACT is better but... Oh well... 


$python -m SimpleHTTPServer

<html ng-app> to initialize

   <h1>Hello {{ name }}!</h1>
    <input type= 'text' ng-model='name'>
#####################
if statement:

<span ng-if='name'>{{name}}</span>
<span ng-if='!name'>WOW</span>
#####################
Custom class (DIRECTIVE)

<h1 class= "old-class" ng-class=
    "{
        'new-class': name==='john',
        'new-class2': name=='wow',
      }"
        >Hello 
</h1>
########################
Creating Angular app
dirctory:
-js
    -app
        -app.module.js:  This is just declaring stuff
            'use strict';
            angular.module('jcpapp',[]);
            and then in index.html:
            <html ng-app="jcpapp">
            and then I added
            <script src= './js/app/app.module.js'></script>
            <script src= './js/app/app.config.js'></script>
        -app.config.js:  This extends the module.