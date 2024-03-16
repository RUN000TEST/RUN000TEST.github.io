<!DOCTYPE html>
<html>

<head>
    <link rel="stylesheet" href="style.css">
    <style>

    </style>
</head>

<body>

    <video autoplay muted loop id="video-background">
        <source src="startvid.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>

    <div id="startScreen" style="width: 750px; height: 500px;">
        <h1 style="font-size: 90px; color: brown; "><b>RUN</b></h1>
        <p style="font-size: 35px; color: rgb(3, 216, 223)" >
            Steuerung: <br>
            Links: A <br>
            Rechts: D <br>
        </p>
        <p>Für bestes Erlebnis in den Vollbildmodus wechseln</p>

        <div class="btn btn-two" onclick="startGame()">
            <span></span>
        </div>

    </div>

    <canvas id="Canvas01"></canvas>

    <audio id="bm" src="bm.mp3"></audio>
    <audio id="sp" src="sp.mp3"></audio>
    <audio id="hit" src="hit.mp3"></audio>
    <audio id="audioR" src="r.mp3"></audio>
    <audio id="wait" src="wait.mp3" autoplay></audio>

    <script>

        // JavaScript-Code hier einfügen

    </script>
</body>

</html>
