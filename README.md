<!DOCTYPE html>
<html>
<h1 id="titolo"> CHI INTERROGO OGGI? </h1>
<body style="background:yellow">
<script>
var studenti=["sara","daniel","beniamino","davide","alberto","laura","limor","andre","raphael","rimini","jordan","tommaso","dalia","joshua","yoel"];
function alunni(){
var x=Math.floor(Math.random()*15);
document.getElementById("interrogo").innerHTML= studenti[x];
}
</script>
<input type="button" value="interroga!!!" onclick="alunni()"/>
<text id="interrogo"/>
</body>
</html> 

