<!DOCTYPE html>
<html>
<h1 id="titolo"> CHI INTERROGO OGGI? </h1>
<body style="background:yellow">
<script>
var studenti=["sara","daniel","beniamino"];
function alunni(){
var x=Math.floor(Math.random()*3);
document.getElementById("ciao").innerHTML= studenti[x];
}
</script>
<input type="button" value="interroga!!!" onclick="alunni()"/>
<text id="ciao"/>
</body>
</html> 

