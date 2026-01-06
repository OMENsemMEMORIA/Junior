<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<title>Filmes no Rave</title>
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
  font-size: 20px;
}

.movie {
  padding: 15px;
}

.movie img {
  width: 100%;
  max-height: 380px;
  object-fit: cover;
  border-radius: 10px;
  margin-bottom: 10px;
}

.movie h3 {
  margin: 8px 0;
}

video {
  width: 100%;
  height: 220px;
  border-radius: 8px;
  background: black;
}
</style>
</head>

<body>

<header>🎬 Harry Potter — Teste no Rave</header>

<div class="movie">
  <img src="https://upload.wikimedia.org/wikipedia/pt/6/6e/Harry_Potter_e_a_C%C3%A2mara_Secreta.jpg">
  <h3>Harry Potter e a Câmara Secreta</h3>
  <video controls>
    <source src="https://commondatastorage.googleapis.com/gtv-videos-bucket/sample/BigBuckBunny.mp4" type="video/mp4">
  </video>
</div>

<div class="movie">
  <img src="https://upload.wikimedia.org/wikipedia/pt/4/4a/Harry_Potter_e_o_Prisioneiro_de_Azkaban.jpg">
  <h3>Harry Potter e o Prisioneiro de Azkaban</h3>
  <video controls>
    <source src="https://commondatastorage.googleapis.com/gtv-videos-bucket/sample/ElephantsDream.mp4" type="video/mp4">
  </video>
</div>

<div class="movie">
  <img src="https://upload.wikimedia.org/wikipedia/pt/7/7a/Harry_Potter_e_o_C%C3%A1lice_de_Fogo.jpg">
  <h3>Harry Potter e o Cálice de Fogo</h3>
  <video controls>
    <source src="https://commondatastorage.googleapis.com/gtv-videos-bucket/sample/Sintel.mp4" type="video/mp4">
  </video>
</div>

</body>
</html>
