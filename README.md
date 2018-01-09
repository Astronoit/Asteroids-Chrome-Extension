<html>
  <head>
    <title>Asteroids</title>
  </head>
  <style>
* {
	margin: 0;
}
canvas {
	position: absolute;
	width: 100%;
	height: 100%;
	background: #262626;
}
#info {
	color: #FFF;
	font-family: "Lucida Sans Typewriter", "Lucida Console", Monaco, "Bitstream Vera Sans Mono", monospace;
	margin: 10px 10px 0;
	padding: 8px;
	background: #161616;
	position: absolute;
	z-index: 1;
}
#info h1 {
	font-size: 18px;
}
#info p {
	font-size: 11px;
}
  </style>
  <body>
<div id="info">
  <h1>Canvas Asteroids:</h1>
  <p>Use [A][S][W][D] or [&larr;][&uarr;][&darr;][&rarr;] to MOVE</p>
  <p>Use [SPACE] or [K] to SHOOT</p>
</div>

	  <canvas id="canvas"></canvas>
	  
 <script src="desc.js"></script>
