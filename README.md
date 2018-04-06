# -
自适应屏幕大小并可在手机上显示的九宫格
##HTML代码
```
<!DOCTYPE html>
<html>
<head>
	<title>自适应九宫格</title>
	<meta charset="utf-8">
	<!--vw:viewport width
		vh:viewport height-->
	<!-- <style type="text/css">
		.content{
			height: 96vw;
			background-color: grey;
			align-self: center;
		}
		.content div{
			margin: 1%;
			width: 30%;
			height: 30%;
			background-color: orange;
			float: left;
			border-radius: 20%;
		}
	</style> -->
	<link rel="stylesheet" type="text/css" href="自适应九宫格.css">
</head>
<body>
	<div class="content">
		<div></div>
		<div></div>
		<div></div>
		<div></div>
		<div></div>
		<div></div>
		<div></div>
		<div></div>
		<div></div>
	</div>
</body>
</html>
```

##CSS代码
```
.content{
	width: 96%;
	/*vw:viewport width
	vh:viewport height*/
	height: 96vw;
	background-color: white;
	align-self: center;
}
.content div{
	margin: 1%;
	width: 30%;
	height: 30%;
	background-color: orange;
	float: left;
	border-radius: 20%;
	/*padding-left:31%;
	padding-bottom: 31%;
	margin:auto;
	border-radius: 20%;
	background: orange;
	float:left;*/
}
```