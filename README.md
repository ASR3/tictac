<html>
<head>
<title>Form Event</title>
<script language="javascript">
var a
function tictac(t)
{
if(a==1){
t.value="x"
a=0
t.blur()
}
else
{
t.value="o"
a=1
t.blur()
}
}
function pqr(fnm){
fnm.t1.focus;fnm.t1.value=""
fnm.t2.focus;fnm.t2.value=""
fnm.t3.focus;fnm.t3.value=""
fnm.t4.focus;fnm.t4.value=""
fnm.t5.focus;fnm.t5.value=""
fnm.t6.focus;fnm.t6.value=""
fnm.t7.focus;fnm.t7.value=""
fnm.t8.focus;fnm.t8.value=""
fnm.t9.focus;fnm.t9.value=""
}
</script>
</head>
<body>
<form>
<br><center>
<<<<<< TIC TAC TOE >>>>>>
<br><br>
<input type="text" name="t1" size=3 onfocus="tictac(this)">
<input type="text" name="t2" size=3 onfocus="tictac(this)">
<input type="text" name="t3" size=3 onfocus="tictac(this)">
<br>
<input type="text" name="t4" size=3 onfocus="tictac(this)">
<input type="text" name="t5" size=3 onfocus="tictac(this)">
<input type="text" name="t6" size=3 onfocus="tictac(this)">
<br>
<input type="text" name="t7" size=3 onfocus="tictac(this)">
<input type="text" name="t8" size=3 onfocus="tictac(this)">
<input type="text" name="t9" size=3 onfocus="tictac(this)">
<br><br>
<input type="button" value="Reset" onclick="pqr(form)">
</center>
</form>
</body>
</html>

