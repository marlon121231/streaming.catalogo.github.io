<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Catálogo Streaming Global</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f4f4f4;
      margin: 0;
      padding: 20px;
    }

    h2 {
      text-align: center;
      margin-bottom: 20px;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(160px, 1fr));
      gap: 15px;
    }

    .producto {
      background: #fff;
      padding: 15px;
      border-radius: 12px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }

    .nombre {
      font-weight: bold;
      font-size: 16px;
      margin-bottom: 5px;
    }

    .btn {
      display: inline-block;
      padding: 6px 10px;
      font-size: 14px;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      text-decoration: none;
      text-align: center;
      margin-top: 10px;
    }

    /* Colores */
    .netflix { background-color: #e50914; }
    .disney { background-color: #113ccf; }
    .hbo { background-color: #ffc107; color: black; }
    .amazon { background-color: #25a244; }
    .vix { background-color: #ff7300; }
    .paramount { background-color: #0d9488; }
    .plex { background-color: #f97316; }
    .crunchyroll { background-color: #d97706; }
    .spotify { background-color: #1db954; }
    .youtube { background-color: #ff0000; }

    @media screen and (max-width: 400px) {
      .nombre { font-size: 14px; }
      .btn { font-size: 12px; padding: 5px 8px; }
    }
  </style>
</head>
<body>

  <h2>Catálogo de Plataformas</h2>

  <div class="grid">

    <div class="producto">
      <div class="nombre" style="color:#e50914;">Netflix</div>
      <p><b>1 Pantalla x 30 días:</b> $13.000<br><b>Calidad:</b> FullHD y 4K</p>
      <a class="btn netflix" href="https://wa.me/573053172425?text=Netflix">Comprar</a>
    </div>

    <div class="producto">
      <div class="nombre" style="color:#25a244;">Amazon Prime Video</div>
      <p><b>1 Pantalla:</b> $11.000<br><b>Cuenta Completa:</b> $20.000</p>
      <a class="btn amazon" href="https://wa.me/573053172425?text=Amazon%20Prime%20Video">Comprar</a>
    </div>

    <div class="producto">
      <div class="nombre" style="color:#1db954;">Spotify Premium</div>
      <p><b>1 Cuenta 30 Días:</b> $14.000</p>
      <a class="btn spotify" href="https://wa.me/573053172425?text=Spotify%20Premium">Comprar</a>
    </div>

    <div class="producto">
      <div class="nombre" style="color:#113ccf;">Disney+ Premium</div>
      <p><b>1 Pantalla + STAR + ESPN:</b> $16.000<br><b>Cuenta Completa:</b> $40.000</p>
      <a class="btn disney" href="https://wa.me/573053172425?text=Disney+%20Premium">Comprar</a>
    </div>

    <div class="producto">
      <div class="nombre" style="color:#ffc107;">HBO Max</div>
      <p><b>1 Pantalla:</b> $10.000 por 30 días</p>
      <a class="btn hbo" href="https://wa.me/573053172425?text=HBO%20Max">Comprar</a>
    </div>

    <div class="producto">
      <div class="nombre" style="color:#113ccf;">Disney+ Normal</div>
      <p><b>1 Pantalla:</b> $13.000<br><b>Cuenta Completa:</b> $40.000</p>
      <a class="btn disney" href="https://wa.me/573053172425?text=Disney+%20Normal">Comprar</a>
    </div>

    <div class="producto">
      <div class="nombre" style="color:#ff7300;">Vix Premium</div>
      <p><b>1 Pantalla:</b> $12.000<br><b>Cuenta Completa:</b> $20.000</p>
      <a class="btn vix" href="https://wa.me/573053172425?text=Vix%20Premium">Comprar</a>
    </div>

    <div class="producto">
      <div class="nombre" style="color:#0d9488;">Paramount</div>
      <p><b>1 Pantalla:</b> $10.000<br><b>Cuenta Completa:</b> $20.000</p>
      <a class="btn paramount" href="https://wa.me/573053172425?text=Paramount">Comprar</a>
    </div>

    <div class="producto">
      <div class="nombre" style="color:#f97316;">PLEX</div>
      <p><b>1 Pantalla:</b> $10.000<br><b>Cuenta Completa:</b> $18.000</p>
      <a class="btn plex" href="https://wa.me/573053172425?text=PLEX">Comprar</a>
    </div>

    <div class="producto">
      <div class="nombre" style="color:#d97706;">Crunchyroll</div>
      <p><b>1 Pantalla:</b> $10.000<br><b>Cuenta Completa:</b> $18.000</p>
      <a class="btn crunchyroll" href="https://wa.me/573053172425?text=Crunchyroll">Comprar</a>
    </div>

    <div class="producto">
      <div class="nombre" style="color:#ff0000;">YouTube Premium</div>
      <p><b>1 Cuenta 30 Días:</b> $13.000</p>
      <a class="btn youtube" href="https://wa.me/573053172425?text=YouTube%20Premium">Comprar</a>
    </div>

  </div>

</body>
</html>
