<!DOCTYPE html>
<html>
<head>
  <title>Mascotas Rescatadas</title>
  <style>
    * { margin: 0; padding: 0; }
    body { font-family: 'Segoe UI', Arial; }
    .slide { 
      min-height: 100vh; 
      display: flex; 
      flex-direction: column; 
      justify-content: center; 
      align-items: center; 
      text-align: center; 
      padding: 40px;
      color: white;
      position: relative;
    }
    .slide::before {
      content: '';
      position: absolute;
      top: 0; left: 0; right: 0; bottom: 0;
      background-size: cover;
      background-position: center;
      filter: brightness(0.4);
      z-index: -1;
    }
    h1 { font-size: 3.5em; margin-bottom: 20px; text-shadow: 2px 2px 8px rgba(0,0,0,0.8); }
    h2 { font-size: 2.5em; margin-bottom: 20px; text-shadow: 2px 2px 8px rgba(0,0,0,0.8); }
    p { font-size: 1.3em; max-width: 700px; line-height: 1.7; text-shadow: 1px 1px 6px rgba(0,0,0,0.8); }
    
    .slide1::before { background-image: url('URL_DE_TU_FOTO_1'); }
    .slide2::before { background-image: url('URL_DE_TU_FOTO_2'); }
    .slide3::before { background-image: url('URL_DE_TU_FOTO_3'); }
    .slide4::before { background-image: url('URL_DE_TU_FOTO_4'); }
    .slide5 { background: linear-gradient(135deg, #6366F1, #8B5CF6); }
  </style>
</head>
<body>
  <div class="slide slide1">
    <h1>Mascotas Rescatadas</h1>
    <p>Una segunda oportunidad para los que más lo necesitan</p>
  </div>

  <div class="slide slide2">
    <h2>¿Por qué rescatar?</h2>
    <p>Millones de animales viven en la calle o sufren maltrato. Rescatar o adoptar les da una nueva vida llena de amor, cuidados y seguridad.</p>
  </div>

  <div class="slide slide3">
    <h2>Beneficios de adoptar</h2>
    <p>Salvas una vida, reduces el abandono, y ganas un compañero fiel y agradecido. Las mascotas rescatadas suelen ser las más leales y cariñosas.</p>
  </div>

  <div class="slide slide4">
    <h2>¿Cómo puedes ayudar?</h2>
    <p>Adopta en lugar de comprar, apadrina, dona a refugios, o difunde casos de adopción. Cada acción cuenta para cambiar su historia.</p>
  </div>

  <div class="slide slide5">
    <h2>Gracias 🙏</h2>
    <p>Juntos podemos darles el hogar que merecen</p>
  </div>
</body>
</html>
