<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Мой питомец</title>
<style>
body {
  font-family: sans-serif;
  text-align: center;
  background: #f2f2f2;
}
.pet {
  font-size: 100px;
}
button {
  font-size: 18px;
  margin: 10px;
  padding: 10px 20px;
}
</style>
</head>
<body>

<h1>🐶 Мой питомец</h1>
<div class="pet">🐶</div>
<p id="status">Голоден 😢</p>

<button onclick="feed()">🍖 Покормить</button>
<button onclick="play()">🎾 Поиграть</button>

<script>
function feed() {
  document.getElementById("status").innerText = "Сыт 😊";
}

function play() {
  document.getElementById("status").innerText = "Счастлив 😄";
}
</script>

</body>
</html>
