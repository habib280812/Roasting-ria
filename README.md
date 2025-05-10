# Roasting-ria
<!DOCTYPE html>
<html lang="ms">
<head>
  <meta charset="UTF-8">
  <title>Roasting Super untuk Ria Qistina</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: linear-gradient(to right, #ff99cc, #66ccff);
      color: #fff;
      text-align: center;
      padding: 50px;
    }
    .card {
      background-color: rgba(0, 0, 0, 0.6);
      border-radius: 20px;
      padding: 30px;
      max-width: 600px;
      margin: auto;
      box-shadow: 0 4px 15px rgba(0,0,0,0.3);
    }
    h1 {
      font-size: 2em;
      margin-bottom: 20px;
    }
    #roast {
      font-size: 1.5em;
      margin: 30px 0;
    }
    button {
      padding: 10px 20px;
      font-size: 1em;
      background-color: #ff6699;
      border: none;
      border-radius: 10px;
      cursor: pointer;
      color: white;
      transition: background-color 0.3s;
    }
    button:hover {
      background-color: #cc3366;
    }
  </style>
</head>
<body>
  <div class="card">
    <h1>Roasting Super untuk Ria Qistina (Abe Ji)</h1>
    <div id="roast">Tekan butang untuk mula roast!</div>
    <button onclick="generateRoast()">Roast </button>
  </div>

  <script>
    const roasts = [
      "Ria Qistina pakai kalkulator pun salah kira, matematik level alien!"
      "Kalau Ria masuk MasterChef, dapur yang stress bukan dia!",
      "Dia ingat 'Google' tu boyfriend dia – semua benda tanya Google!",
      "Ria cakap dia busy, tapi busy scroll TikTok sampai pagi!",
      "Kalau dia masuk debat, mikrofon pun give up nak dengar!",
      "Ria Qistina study 5 minit, rehat 5 jam – balance katanya!",
      "Dia posing satu jam, tapi gambar masih macam CCTV tangkap!",
      "Ria kata dia queen, tapi mahkota pun lari!",
    ];

    function generateRoast() {
      const roast = roasts[Math.floor(Math.random() * roasts.length)];
      document.getElementById("roast").textContent = roast;
    }
  </script>
</body>
</html>
