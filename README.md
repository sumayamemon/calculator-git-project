<!doctype html>
<html>
<head>
<style>
body{
	background-color: skyblue;}			
*{
	box-sizing:border-box;
	-webkit- box-sizing:border-box;
	-moz- box-sizing:border-box;}
.wrap{
	width:400px;
	margin:auto;
	height:auto;
	background:black;
	padding:15px;}
.body{
	width:100%;
	padding:10px;
	font-size:22px;
	font-weight:bold;
	margin-top:20px;
	border-radius:5px;}	

.button{
	width:89px;
	padding:10px;
	font-size:22px;
	font-weight:bold;
	margin-top:20px;
	border-radius:5px;}	

#del{
	width:100%;
	height:50px;
        font-size:22px;
	margin-top:2opx;
	border-radius:5px;
        font-weight:bold;}
}
</style>
<meta charset="utf-8">
<title>calculator</title>
</head>
<body>
<div class=" wrap">
<form name="cal">
<input type="text" name="display" class="body" >
<br><br>
<input type="button" value="9" onClick="cal.display.value+='9'" class="button">
<input type="button" value="8" onClick="cal.display.value+='8'" class="button">
<input type="button" value="7" onClick="cal.display.value+='7'" class="button">
<input type="button" value="+" onClick="cal.display.value+='+'" class="button">
<br><br>
<input type="button" value="6" onClick="cal.display.value+='6'" class="button">
<input type="button" value="5" onClick="cal.display.value+='5'" class="button">
<input type="button" value="4" onClick="cal.display.value+='4'" class="button">
<input type="button" value="-" onClick="cal.display.value+='-'" class="button">
<br><br>
<input type="button" value="3" onClick="cal.display.value+='3'" class="button">
<input type="button" value="2" onClick="cal.display.value+='2'" class="button" >
<input type="button" value="1" onClick="cal.display.value+='1'" class="button">
<input type="button" value="*" onClick="cal.display.value+='*'" class="button">
<br><br>
<input type="button" value="0" onClick="cal.display.value+='0'" class="button">
<input type="button" value="/" onClick="cal.display.value+='/'" class="button">
<input type="button" value="%" onClick="cal.display.value+='%'" class="button">
<input type="button" value="=" onClick="cal.display.value= eval (cal.display.value)" class="button">
<br><br>
<input type="button" value="DELETE" onClick="cal.display.value=''" id="del">
</form>
</div>
</body>
</html>
