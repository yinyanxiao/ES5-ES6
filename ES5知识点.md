## 变量
### ES5中定义变量需要注意的是：
+ 用var来申明变量
+ 变量名要有语义
+ 命名要规范，驼峰命名
+ 变量名一般以字母、下划线、$符开头
+ 区分大小写
### 数据类型
+ 数字(number)、字符串(string)、布尔(Boolean)、Null、Object、Undefined
#### 数据类型的检测
+ typeof(返回值是检测出的类型，只可以检测原始类型)
+ instanceof(返回值是true/false 一般用于引用类型)
```html
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Document</title>
</head>
<body>
	<script>
		var str = "hello";
		var num1 = 10;
		var num2 = NaN;/*返回值是number*/
		var num3 = Infinity;/*返回值是number*/
		var bool = true;
		var nu = null
		var und;
		var obj = {};
		var reg = / /;
		var date = new Date();
		var arr = [];
		console.log(typeof num3)
		console.log(arr instanceof Object);
	</script>
</body>
</html>
```
#### 原始类型和引用类型的区别


#### 

