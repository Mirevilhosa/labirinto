<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Quiz e Labirinto</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="quiz-container">
    <h1>Quiz</h1>
    <p>Qual é o meu filme favorito?</p>
    <button onclick="checkAnswer('certo')">Filme A</button>
    <button onclick="checkAnswer('errado')">Filme B</button>
    <button onclick="checkAnswer('errado')">Filme C</button>
    <div id="quizResult"></div>
  </div>

  <div class="maze-container">
    <h2>Labirinto - Use o dedo para se mover!</h2>
    <div id="maze" class="maze">
      <div class="maze-wall" style="top: 0; left: 0; width: 100px; height: 100px;"></div>
      <div class="maze-wall" style="top: 100px; left: 0; width: 100px; height: 100px;"></div>
      <div class="maze-wall" style="top: 200px; left: 0; width: 100px; height: 100px;"></div>
      <!-- Continue a desenhar mais paredes aqui -->
    </div>
    <div id="mazeMessage"></div>
  </div>

  <script src="script.js"></script>
</body>
</html>
