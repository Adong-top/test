## hello  world
<!doctype html>
<html>
<head>
<meta charset="utf-8"/>
<meta name="viewport" content="width=device-width,initial-scale=1.0">
<link rel="stylesheet" href="http://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap.min.css">
<title>九宫格</title>
<style type="text/css">
html,body{
	height:100%;
	margin:0;
}
.div-box{
	position:relative;
	width:480px;
	height:100%;
	margin:0 auto;
}
.myDiv{
	float:left;
	width:150px;
	height:150px;
	
	background-color:yellow;
	margin-bottom:15px;
	margin-right:15px;
	border-radius:12px;
}

</style>
</head>
<body>
<div class="div-box">
	<div class="myDiv"></div>
	<div class="myDiv"></div>
	<div class="myDiv" style="margin-right:0"></div><br/>
	<div class="myDiv"></div>
	<div class="myDiv"></div>
	<div class="myDiv" style="margin-right:0"></div><br/>
	<div class="myDiv" style="margin-bottom:0"></div>
	<div class="myDiv" style="margin-bottom:0"></div>
	<div class="myDiv" style="margin-right:0;margin-bottom:0"></div>
</div>
</body>
</html>
