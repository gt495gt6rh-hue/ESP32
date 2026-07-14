# ESP32
<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8">
<title>LED Steuerung</title>
</head>

<body style="text-align:center;margin-top:100px;">

<h1>LED Steuerung</h1>

<button onclick="ledOn()">
LED EIN
</button>

<script>
function ledOn() {
    fetch("http://192.168.178.45/led/on");
}
</script>

</body>
</html>
