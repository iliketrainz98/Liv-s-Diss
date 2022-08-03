## Liv's Dissertation Survey

<html>
<body>

<script>
<!--
/*
Random link button- By JavaScript Kit (http://javascriptkit.com)
Over 300+ free scripts!a
This credit MUST stay intact for use
*/

//specify random links below. You can have as many as you want
var randomlinks=new Array()

randomlinks[0]="https://sps.onlinesurveys.ac.uk/harrisdissertationsurveyc"
randomlinks[1]="https://sps.onlinesurveys.ac.uk/harrisdissertationt"

function randomlink(){
window.location=randomlinks[Math.floor(Math.random()*randomlinks.length)]
}
//-->
</script>
<form method="post">
<p><input type="button" name="B1" value="Begin Survey" onclick="randomlink()"></p> </form>

<!--Uncomment below to use a regular text link instead
<a href="javascript:randomlink()">Random Link</a>
-->

</body>
</html>

