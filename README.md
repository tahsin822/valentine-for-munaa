<!DOCTYPE html>
<html>
<head>
<title>For My Valentine 💖</title>
<style>
body { text-align:center; font-family:Arial; background:pink; padding-top:100px; }
button { padding:15px 30px; font-size:20px; margin:20px; border-radius:20px; border:none; cursor:pointer; }
#noBtn { position:absolute; }
</style>
</head>
<body>

<h1>Will You Be My Valentine? 💖</h1>

<button onclick="showLove()">YES 💕</button>
<button id="noBtn" onmouseover="moveButton()">NO 😜</button>

<p id="message"></p>

<script>
function showLove() {
  document.getElementById("message").innerHTML = "YAYYYYY 💖 I KNEW IT 😭✨";
}

function moveButton() {
  var btn = document.getElementById("noBtn");
  btn.style.left = Math.random()*window.innerWidth + "px";
  btn.style.top = Math.random()*window.innerHeight + "px";
}
</script>

</body>
</html>
