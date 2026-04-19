<!DOCTYPE html>
<html>
<head>
  <title>My Game</title>
  <style>
    body {
      margin: 0;
      text-align: center;
      background: #70c5ce;
      font-family: Arial;
    }
    canvas {
      background: #fff;
      display: block;
      margin: 20px auto;
      border: 2px solid black;
    }
    #score {
      font-size: 24px;
      color: #000;
    }
  </style>
</head>
<body>

<h1>My Game 🎮</h1>

<!-- 🔹 Ad Space Top -->
<div id="ad-top">
  <!-- AdSense code yaha paste karna -->
</div>

<div id="score">Score: 0</div>
<canvas id="gameCanvas" width="400" height="500"></canvas>

<!-- 🔹 Ad Space Bottom -->
<div id="ad-bottom">
  <!-- AdSense code yaha paste karna -->
</div>

<script>
let canvas = document.getElementById("gameCanvas");
let ctx = canvas.getContext("2d");

let bird = { x: 50, y: 150, size: 20, gravity: 0.6, lift: -10, velocity: 0 };
let pipes = [];
let score = 0;

document.addEventListener("keydown", () => {
  bird.velocity = bird.lift;
});

function drawBird() {
  ctx.fillStyle = "yellow";
  ctx.fillRect(bird.x, bird.y, bird.size, bird.size);
}

function drawPipes() {
  ctx.fillStyle = "green";
  pipes.forEach(pipe => {
    ctx.fillRect(pipe.x, 0, 50, pipe.top);
    ctx.fillRect(pipe.x, pipe.bottom, 50, canvas.height);
  });
}

function updatePipes() {
  if (Math.random() < 0.02) {
    let top = Math.random() * 200 + 50;
    let gap = 120;
    pipes.push({ x: canvas.width, top: top, bottom: top + gap });
  }

  pipes.forEach(pipe => {
    pipe.x -= 2;

    // collision
    if (
      bird.x < pipe.x + 50 &&
      bird.x + bird.size > pipe.x &&
      (bird.y < pipe.top || bird.y + bird.size > pipe.bottom)
    ) {
      alert("Game Over! Score: " + score);
      document.location.reload();
    }

    // score
    if (pipe.x === bird.x) {
      score++;
      document.getElementById("score").innerText = "Score: " + score;
    }
  });

  pipes = pipes.filter(pipe => pipe.x > -50);
}

function updateBird() {
  bird.velocity += bird.gravity;
  bird.y += bird.velocity;

  if (bird.y > canvas.height || bird.y < 0) {
    alert("Game Over! Score: " + score);
    document.location.reload();
  }
}

function gameLoop() {
  ctx.clearRect(0, 0, canvas.width, canvas.height);

  drawBird();
  drawPipes();
  updateBird();
  updatePipes();

  requestAnimationFrame(gameLoop);
}

gameLoop();
</script>

</body>
</html>
