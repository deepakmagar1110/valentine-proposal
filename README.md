<!DOCTYPE html>
<html>
<head>
  <title>For You ❤️</title>
</head>

<body style="background:#ffe6e6; text-align:center; font-family:Arial; padding-top:60px;">

  <h1>Hey Kajal ❤️</h1>

  <p>I tried finding the right words…</p>
  <p>But my heart already knows the answer.</p>

  <h2>You make my ordinary days feel special ✨</h2>

  <h1>Will you be my Valentine? 🌹</h1>

  <div style="margin-top:30px;">
    <button onclick="yesClick()" 
      style="padding:15px 30px; font-size:18px; background:#ff4d6d; color:white; border:none; border-radius:8px; cursor:pointer;">
      Yes 💖
    </button>

    <button onclick="noClick()" 
      style="padding:15px 30px; font-size:18px; margin-left:20px; background:#ccc; border:none; border-radius:8px; cursor:pointer;">
      No 🙈
    </button>
  </div>

  <p id="response" style="margin-top:40px; font-size:22px;"></p>

  <p style="margin-top:60px;">— Deepak</p>

  <script>
    function yesClick() {
      document.getElementById("response").innerHTML =
        "You just made me smile like an idiot 😍💖";
    }

    function noClick() {
      document.getElementById("response").innerHTML =
        "That’s okay… I’m still glad I asked 🌷";
    }
  </script>

</body>
</html>
