# bahsa-color-file1

#code_1


<!DOCTYPE html> 
<html> 
<head> 
<title> 
Background Colors 
</title> 
</head> 
<body onLoad="f1()" onUnload="msg()"> 
<h1 align="center">7 Different & visibly distinct background colors</h1> 
</body> 
<script type="text/javascript"> 
function f1() 
{ 
document.bgColor="red"; 
window.setTimeout("f2()",1500); 
} 
function f2() 
{ 
document.bgColor="green"; 
window.setTimeout("f3()",1500); 
} 
function f3() 
{ 
document.bgColor="pink"; 
window.setTimeout("f4()",1500); 
} 
function f4() 
{ 
document.bgColor="orange"; 
window.setTimeout("f5()",1500); 
} 
function f5() 
{ 
document.bgColor="skyblue"; 
window.setTimeout("f6()",1500); 
} 
function f6() 
{ 
document.bgColor="voilet"; 
window.setTimeout("f7()",1500); 
} 
function f7() 
{ 
document.bgColor="aqua"; 
window.setTimeout("f1()",1500); 
} 
function msg() 
{ 
alert("Display of 7 different colors"); 
} 
</script> 
</html>
