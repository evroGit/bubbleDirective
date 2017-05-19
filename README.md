## "bubbleDirective" is a small AngularJs directive to show colored pop-up bubbles and squares..
Use "bubble" directive to make your site more sympathetic

## Demo site
[http://ngsite.square7.de](http://ngsite.square7.de)

```
<bubble number="10" box-height="900" rounding="0" start-color="blue" end-color="blue"></bubble>
```
Attributes:
- number      (optional)    Number of showing bubbles  The value has to be an integer. Default value - "10"
- box-height  (optional)    Takeoff height for bubbles (optional). Default value - 1100px)
- rounding    (optional)    Rounding corners. Default value - 0 ("bubble" are quadratic)
- start-color (optional)    Start color. Default value - "gray".
                            There are 7 predefined colors:
                            "red", "green", "blue", "yellow", "black",  "gray", "white"
- end-color   (optional)    End color. Default value - "gray".

To install: put bubble-directive source link into <body>-tag of index.html
```
<script src="bubbleDirective.js"></script>
```
Put bubble module 'bubbleDirective' in your angular module dependencies array, f.e.:
```
var app = angular.module('myApp', ['ngRoute',...,'bubbleDirective'])
```
