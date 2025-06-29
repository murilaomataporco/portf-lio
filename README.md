<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>Portfólio de Fotos</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    body {
      font-family: sans-serif;
      margin: 0;
      background: #f5f5f5;
    }
    header {
      background: #222;
      color: #fff;
      padding: 2rem 1rem;
      text-align: center;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 1.5rem;
      padding: 2rem;
      max-width: 1100px;
      margin: 0 auto;
    }
    .photo-item {
      background: #fff;
      border-radius: 6px;
      box-shadow: 0 2px 8px #0002;
      overflow: hidden;
      text-align: center;
      transition: transform 0.2s;
    }
    .photo-item:hover {
      transform: scale(1.03);
    }
    .photo-item img {
      width: 100%;
      height: 220px;
      object-fit: cover;
      display: block;
    }
    .caption {
      padding: 1rem;
      font-weight: bold;
    }
    @media (max-width: 600px) {
      .gallery {
        padding: 1rem;
        gap: 1rem;
      }
      .photo-item img {
        height: 140px;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Meu Portfólio de Fotos</h1>
    <p>Algumas das minhas melhores imagens</p>
  </header>
  <section class="gallery">
    <div class="photo-item">
      <img src="foto1.jpg" alt="Descrição da foto 1">
      <div class="caption">Descrição da Foto 1</div>
    </div>
    <div class="photo-item">
      <img src="foto2.jpg" alt="Descrição da foto 2">
      <div class="caption">Descrição da Foto 2</div>
    </div>
    <div class="photo-item">
      <img src="foto3.jpg" alt="Descrição da foto 3">
      <div class="caption">Descrição da Foto 3</div>
    </div>
    <!-- Adicione mais fotos conforme necessário -->
  </section>
</body>
</html>
