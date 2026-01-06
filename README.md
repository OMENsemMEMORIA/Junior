<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<title>oMensEmMemoRia</title>
<meta name="viewport" content="width=device-width, initial-scale=1">

<style>
body {
  background: #0f0f0f;
  color: #fff;
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

header {
  text-align: center;
  padding: 15px;
  background: #111;
  font-size: 22px;
  font-weight: bold;
}

.container {
  padding: 10px;
}

.card {
  background: #1a1a1a;
  margin-bottom: 15px;
  border-radius: 8px;
  overflow: hidden;
}

.card img {
  width: 100%;
  display: block;
}

.card h3 {
  margin: 10px;
  font-size: 18px;
}

.card video {
  width: 100%;
  height: auto;
  background: black;
}
</style>
</head>

<body>

<header>oMensEmMemoRia 🎬</header>

<div class="container">

  <!-- CARD 1 -->
  <div class="card">
    <img src="https://upload.wikimedia.org/wikipedia/pt/6/6e/Harry_Potter_e_a_C%C3%A2mara_Secreta.jpg" alt="Harry Potter e a Câmara Secreta">
    <h3>Harry Potter e a Câmara Secreta</h3>
    <video controls>
      <source src="https://commondatastorage.googleapis.com/gtv-videos-bucket/sample/BigBuckBunny.mp4" type="video/mp4">
    </video>
  </div>

  <!-- CARD 2 -->
  <div class="card">
    <img src="https://upload.wikimedia.org/wikipedia/pt/4/4a/Harry_Potter_e_o_Prisioneiro_de_Azkaban.jpg" alt="Harry Potter e o Prisioneiro de Azkaban">
    <h3>Harry Potter e o Prisioneiro de Azkaban</h3>
    <video controls>
      <source src="https://commondatastorage.googleapis.com/gtv-videos-bucket/sample/ElephantsDream.mp4" type="video/mp4">
    </video>
  </div>

  <!-- CARD 3 -->
  <div class="card">
    <img src="https://upload.wikimedia.org/wikipedia/pt/7/7a/Harry_Potter_e_o_C%C3%A1lice_de_Fogo.jpg" alt="Harry Potter e o Cálice de Fogo">
    <h3>Harry Potter e o Cálice de Fogo</h3>
    <video controls>
      <source src="https://commondatastorage.googleapis.com/gtv-videos-bucket/sample/Sintel.mp4" type="video/mp4">
    </video>
  </div>

</div>

</body>
</html>
