<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Heartbeat Heart</title>
  <style>
    body {
      margin: 0;
      background: black;
      overflow: hidden;
    }
    canvas {
      display: block;
    }
  </style>
</head>
<body>
<canvas id="canvas"></canvas>

<script>
  const canvas = document.getElementById("canvas");
  const ctx = canvas.getContext("2d");

  canvas.width = window.innerWidth;
  canvas.height = window.innerHeight;

  function heart(t) {
    const x = 16 * Math.pow(Math.sin(t), 3);
    const y = - (13 * Math.cos(t) - 5 * Math.cos(2 * t)
                - 2 * Math.cos(3 * t) - Math.cos(4 * t));
    return {x, y};
  }

  const particles = [];
  const particleCount = 400;

  for (let i = 0; i < particleCount; i++) {
    const t = Math.random() * Math.PI * 2;
    const pos = heart(t);
    particles.push({
      x: pos.x * 10 + canvas.width / 2,
      y: pos.y * 10 + canvas.height / 2,
      baseSize: Math.random() * 1.5 + 1,
      opacity: Math.random() * 0.5 + 0.5,
    });
  }

  let beat = 0;
  function animate() {
    ctx.clearRect(0, 0, canvas.width, canvas.height);
    
    beat += 0.08;
    const scale = 1 + Math.sin(beat) * 0.3;  // Nhịp đập: tăng/giảm size đồng bộ

    for (let p of particles) {
      const size = p.baseSize * scale;
      ctx.beginPath();
      ctx.arc(p.x, p.y, size, 0, Math.PI * 2);
      ctx.fillStyle = `rgba(255, 0, 150, ${p.opacity})`;
      ctx.shadowBlur = 15;
      ctx.shadowColor = "deeppink";
      ctx.fill();
    }

    requestAnimationFrame(animate);
  }

  animate();
</script>
</body>
</html>
