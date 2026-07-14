<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>LED Steuerung</title>

<style>
body{
    font-family:Arial,sans-serif;
    background:#222;
    color:white;
    display:flex;
    justify-content:center;
    align-items:center;
    height:100vh;
    margin:0;
}

button{
    font-size:30px;
    padding:25px 60px;
    border:none;
    border-radius:15px;
    background:#00c853;
    color:white;
    cursor:pointer;
}

button:hover{
    background:#00a844;
}
</style>
</head>

<body>

<button onclick="ledOn()">LED EIN</button>

<script>
function ledOn(){
    fetch("http://DEINE_ESP_IP/led/on");
}
</script>

</body>
</html>
