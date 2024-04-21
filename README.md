!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Meu Jogo</title>
  <style>
    /* Adicione estilos CSS aqui */
  </style>
</head>
<body>
  <canvas id="gameCanvas" width="800" height="600"></canvas>

  <script>
    // Adicione o código JavaScript do seu jogo aqui
    // Por exemplo:
    const canvas = document.getElementById('gameCanvas');
    const ctx = canvas.getContext('2d');

    // Desenhar um retângulo vermelho
    ctx.fillStyle = 'red';
    ctx.fillRect(50, 50, 100, 100);
  </script>
</body>
</html>
