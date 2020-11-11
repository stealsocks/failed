<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1" />
 <title>Groove</title>
  <link rel="stylesheet" href="groovebrown.css">
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


  <script src="groove.js">



</body>
</html>
