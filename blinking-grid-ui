<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>6 Color Blink Page</title>

<style>
body {
    margin: 0;
    height: 100vh;
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-template-rows: repeat(2, 1fr);
}

/* Box styling */
.box {
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 30px;
    font-weight: bold;
    color: white;
}

/* Default colors */
.box1 { background-color: #FF5733; }
.box2 { background-color: #33FF57; }
.box3 { background-color: #3357FF; }
.box4 { background-color: #FF33A8; }
.box5 { background-color: #33FFF6; color: black; }
.box6 { background-color: #A833FF; }

/* 🔥 Blinking animation */
@keyframes blinkColors {
    0%   { background-color: #FF5733; }
    20%  { background-color: #33FF57; }
    40%  { background-color: #3357FF; }
    60%  { background-color: #FF33A8; }
    80%  { background-color: #33FFF6; color: black; }
    100% { background-color: #A833FF; }
}

/* Apply animation on hover */
.box:hover {
    animation: blinkColors 1s infinite;
}
</style>

</head>

<body>

<div class="box box1">1</div>
<div class="box box2">2</div>
<div class="box box3">3</div>
<div class="box box4">4</div>
<div class="box box5">5</div>
<div class="box box6">6</div>

</body>
</html>
