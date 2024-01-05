<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>¿Cogmos?</title>
  <style>
    body {
      background-color: #f0f0f0; /* Color de fondo */
    }

    #noBtn {
      visibility: visible;
      position: absolute;
    }
  </style>
</head>
<body>

<h1 id="titulo">¿Cogmos?</h1>
<button id="siBtn" onclick="seleccionarOpcion('sí')">Sí</button>
<button id="noBtn" onclick="moverNo()">No</button>

<p id="contador">Contador: 0</p>

<script>
  let contadorClicks = 0;

  function cambiarColor() {
    const colores = ['#FF5733', '#33FF57', '#5733FF', '#FF33A1', '#33A1FF'];
    const colorAleatorio = colores[Math.floor(Math.random() * colores.length)];
    document.getElementById('titulo').style.color = colorAleatorio;
  }

  function mostrarFrase() {
    alert('Te Amo Ferxhi');
  }

  function moverNo() {
    const noBtn = document.getElementById('noBtn');
    const newX = Math.floor(Math.random() * (window.innerWidth - 50));
    const newY = Math.floor(Math.random() * (window.innerHeight - 50));
    noBtn.style.left = newX + 'px';
    noBtn.style.top = newY + 'px';
  }

  function seleccionarOpcion(opcion) {
    if (opcion === 'sí') {
      contadorClicks++;
      document.getElementById('contador').innerText = 'Contador: ' + contadorClicks;
      cambiarColor();
      mostrarFrase();
      moverNo();
    } else {
      alert('Has seleccionado: No');
    }
  }
</script>

</body>
</html>
