<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<title>oMensEmMemoRia</title>
<meta name="viewport" content="width=device-width, initial-scale=1">

<style>
body {
  margin: 0;
  background: #0f0f0f;
  color: white;
  font-family: Arial, sans-serif;
}

header {
  text-align: center;
  padding: 15px;
  background: #111;
  font-size: 22px;
  font-weight: bold;
}

.grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 12px;
  padding: 12px;
}

.card {
  text-decoration: none;
  color: white;
}

.card img {
  width: 100%;
  border-radius: 10px;
}

.card h3 {
  text-align: center;
  font-size: 14px;
  margin-top: 6px;
}

.filme {
  padding: 15px;
}

video {
  width: 100%;
  background: black;
  border-radius: 8px;
}

.voltar {
  display: block;
  margin-bottom: 10px;
  color: #0af;
  text-decoration: none;
}
</style>
</head>

<body>

<header>🎬 oMensEmMemoRia</header>

<!-- 🔹 TELA DE SELEÇÃO -->
<div class="grid">

  <a href="#filme1" class="card">
    <img src="https://upload.wikimedia.org/wikipedia/pt/6/6e/Harry_Potter_e_a_C%C3%A2mara_Secreta.jpg">
    <h3>Câmara Secreta</h3>
  </a>

  <a href="#filme2" class="card">
    <img src="https://upload.wikimedia.org/wikipedia/pt/4/4a/Harry_Potter_e_o_Prisioneiro_de_Azkaban.jpg">
    <h3>Prisioneiro de Azkaban</h3>
  </a>

  <a href="#filme3" class="card">
    <img src="https://upload.wikimedia.org/wikipedia/pt/7/7a/Harry_Potter_e_o_C%C3%A1lice_de_Fogo.jpg">
    <h3>Cálice de Fogo</h3>
  </a>

</div>

<!-- 🔹 FILME 1 -->
<div id="filme1" class="filme">
  <a href="#" class="voltar">⬅ Voltar</a>
  <h2>Harry Potter e a Câmara Secreta</h2>
  <video controls>
    <source src="https://commondatastorage.googleapis.com/gtv-videos-bucket/sample/BigBuckBunny.mp4" type="video/mp4">
  </video>
</div>

<!-- 🔹 FILME 2 -->
<div id="filme2" class="filme">
  <a href="#" class="voltar">⬅ Voltar</a>
  <h2>Harry Potter e o Prisioneiro de Azkaban</h2>
  <video controls>
    <source src="https://commondatastorage.googleapis.com/gtv-videos-bucket/sample/ElephantsDream.mp4" type="video/mp4">
  </video>
</div>

<!-- 🔹 FILME 3 -->
<div id="filme3" class="filme">
  <a href="#" class="voltar">⬅ Voltar</a>
  <h2>Harry Potter e o Cálice de Fogo</h2>
  <video controls>
    <source src="https://commondatastorage.googleapis.com/gtv-videos-bucket/sample/Sintel.mp4" type="video/mp4">
  </video>
</div>

</body>
</html>
