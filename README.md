<!doctype html>
<html>
<head>
<style>
h1
{
color:green;
}
h2{
font-family:impact;
}
body{
text-align:center;
}
</stle>
</head>
<body>
<h1>JAVASCRIPT PROGRAM</h1>
<p>javascript program to generate random integer between 1 to 10,the user is then prompted to input a guess number.if the user input matches with guess number,the program will display a message"Matched"otherwise display a message "Not matched"</p>
<script type="text/javascript">

const num=Math.ceil(Math.random()*10);
console.log(num);
const gnum=prompt('Guess the number between 1 and 10 inclusive');
if(gnum==num)document.write("good work")
else
document.write("not matched")
</script>
<h2>display variables</h2>
<p id="demo"></p>
<script>
var x=5;
var y=6;
var z=x+y;
document.getElementById("demo").innerHTML="the value of z is:"+z;
</script>
<p><mark style="background-color:burlywood">TOPIC:JAVA CORE</mark></p>
<h1>JAVASCRIPT</H1>
<H2>javascript:program to get the website URL?</h2>
<p><b>click on below button to get current URL</b></p>
<button onclick="GetURL()">GetURL</button>
<p id="url"></P>
<script>
function GetURL(){
var gfg=document.URL;
document.getElementById("url").innerHTML=gfg;

}
</script>
<h2>the javascript typeof</h2>
<p id="kk"></p>
<script>
document.getElementById("kk").innerHTML=typeof"john"+"<br>"+
                                        typeof 3.14+"<br>"+
										typeof true+"<br>"+
										typeof false+"<br>"+
										typeof x;
	</script>
<p style="color:green">AREA F THE CIRCLE</p>
<script>
 let pi=3.14159265358979323846;
 function findarea(r){
 
 return(pi*r*r);
 }
 let r,Area;
 r=5;
 
 Area=findArea(r);
 
 document.write("Area of Circle is:"+Area);
 </script>
 
 </body>
 </html>
