<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1" />
 
  <style>#test {
  color: gray;
}

#hold {height:50px;
width: 90%;
margin-left:10%}

#nums{
  margin: auto;
  width: 65%;
  border: 3px inset black;
  padding: 10px;
background:black;
border-radius:25px
}

.button {padding:5px 20px;
border:1px hidden;
color:white;
background-color:#572c04}

.button * {font-size:120%}

.holder {min-width:6.6%;
height:30px;
float: left;
text-align: center;
padding-top:10px;
margin-top: 15px;
margin-left: 1px;
border: 2px solid black;
}

.holder2 {min-width:4.9%;
height:30px;
float: left;
text-align: center;
padding-top:10px;
margin-top: 15px;
margin-left: 1px;
border: 2px solid black;
}


.holder * {padding:35%}

.holder2 * {padding:40%}

h1 {font-family: monaco,Consolas,Lucida Console,monospace;
color:white;
background-color:#572c04
}

body {background:#fcdaa7;
font-family: monaco,Consolas,Lucida Console,monospace;
color:black;
margin-left:0%;
width:110%;
margin-top:0%}

#metronome {
height:20%;
width:69%;
display: none;
margin-left:auto;
margin-right:auto;
margin-top:0%;
border: 1px solid black;
background-color:black;
color:white;
overflow:hidden}

.header {border: 3px solid black;
background-color:#572c04;
color:white}

#startBtn, #stopBtn{padding:10px 30px;
border:1px hidden;
border-radius:25px;
color:white;
background-color:#572c04}

.collapsible {
  background-color:#572c04;
  color: white;
  cursor: pointer;
  padding: 18px;
  width: 70%;
  border: 1px solid black;
  text-align: center;
  font-size: 15px;
  margin-bottom:0px;
  font-family: monaco,Consolas,Lucida Console,monospace;
}

.active, .collapsible:hover {
  background-color:#572c04;
}



#metro {margin:0px}

.collapsible:after {
  content: '\02795'; /* Unicode character for "plus" sign (+) */
  font-size: 20px;
  color: white;
  float: right;
  margin-left: 5px;
  font-weight: 800
}

.active:after {
  content: "\2796"; /* Unicode character for "minus" sign (-) */
}
</style>
</head>
<body>

<div class="header">  <h1 align="center"><big><big><b>Groove</big></big></h1>
<p align="center">The Strumming Pattern Generator</b></p></div>
<br><br>
<p align="center">Choose timing: <select id="timing"></p>
<option value="4/4"> 4/4
<option value="3/4"> 3/4
</select>
<br>
<button class="button" onclick="diagram()" id="strums"><b>Set</b> </button>

<br><br>

<div id="nums"><br><br>
<div id="hold"></div>


<br>
<br>




<br><br>
</div>
<br>
<p align="center">Number of strums: <input type=text id="input" size=3> </input><br>
<button class="button" onclick="strums()" id="strums"><b>Set</b> </button></p><br><br><br><br>

<p id="metro" align=center><button type="button" class="collapsible"><b><big><big>Metronome</big></big></button>
  <div id=metronome>
<p align=center>BPM:<input type="text" id="bpm" value="90" size=5></p>
<p align=center><button name="button" class="button" id="startBtn">Start</button>
  <button name="button" id="stopBtn" class="button" >Stop</button></p></div>
</p>
 <script src="groove.js" type="text/javascript"></script>
</body>
</html>
