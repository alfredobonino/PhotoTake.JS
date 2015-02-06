# PhotoTake.JS
This is a javascript library(1,4kb) for take photo with your webcam simply.

This library use localStorage.

Example:

<html>

<body

<head>

<meta http-equiv="Content-Type" content="text/html; charset=ISO-8859-1">
<script type="text/javascript" src="phototake.js"></script>
<script type="text/javascript">
localStorage.setItem("phototake-width", "680");
localStorage.setItem("phototake-height", "480");
</script>
<video id="phototake-video" width="600" height="400" autoplay></video>
<canvas id="phototake-canvas" width="680" height="480"></canvas>
<center><br><button id="phototake">Take</button></center>
</head>
</body>
</html>

