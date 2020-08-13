# Eis2016
Hello,this is the sixth not fifth  setup of the project.
First off, thank you for taking the time to contribute! :+1: :tada: 

即缩进四个空格，也做为实现类似`<pre>`预格式化文本(Preformatted Text)的功能。
```javascript
function test(){
	console.log("Hello world!");
}
 
(function(){
    var box = function(){
        return box.fn.init();
    };

    box.prototype = box.fn = {
        init : function(){
            console.log('box.init()');

			return this;
        },

		add : function(str){
			alert("add", str);

			return this;
		},

		remove : function(str){
			alert("remove", str);

			return this;
		}
    };
    
    box.fn.init.prototype = box.fn;
    
    window.box =box;
})();

var testBox = box();
testBox.add("jQuery").remove("jQuery");
```

#### JS代码
```javascript
function test() {
	console.log("Hello world!");
}
```
