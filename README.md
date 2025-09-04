# BOCA.DICE
<!--
Licencia MIT
Copyright (c) 2025 TuNombre

Por la presente se concede permiso, sin cargo, a cualquier persona que obtenga una copia
de este código y los archivos asociados, para usar, copiar, modificar, fusionar, publicar, distribuir, sublicenciar y/o vender copias del código,
siempre y cuando se dé crédito al autor original.

EL CÓDIGO SE ENTREGA "TAL CUAL", SIN GARANTÍA DE NINGÚN TIPO, EXPRESA O IMPLÍCITA, INCLUYENDO PERO NO LIMITADO A GARANTÍAS DE COMERCIALIZACIÓN,
IDONEIDAD PARA UN PROPÓSITO PARTICULAR Y NO INFRACCIÓN. EN NINGÚN CASO LOS AUTORES SERÁN RESPONSABLES DE NINGUNA RECLAMACIÓN, DAÑOS U OTRA RESPONSABILIDAD,
YA SEA EN UNA ACCIÓN DE CONTRATO, AGRAVIO O CUALQUIER OTRA FORMA, QUE SURJA DEL USO O DE OTRO TIPO DEL CÓDIGO.
-->
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Boca Dice</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #0033a0; /* Azul Boca */
      color: #ffcc00;      /* Amarillo Boca */
    }

    header {
      background: #002b80;
      text-align: center;
      padding: 1.5rem;
      border-bottom: 5px solid #ffcc00;
    }

    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }

    header p {
      margin: 0.5rem 0 0;
      font-size: 1.2rem;
    }

    main {
      max-width: 1000px;
      margin: 2rem auto;
      padding: 0 1rem;
    }

    section {
      margin-bottom: 3rem;
    }

    section h2 {
      border-bottom: 3px solid #ffcc00;
      padding-bottom: 0.5rem;
    }

    /* Noticias */
    .noticia {
      background: white;
      color: #333;
      border-radius: 12px;
      padding: 1rem;
      margin-bottom: 1.5rem;
      box-shadow: 0 3px 6px rgba(0,0,0,0.2);
    }

    .noticia img {
      max-width: 100%;
      border-radius: 10px;
      margin-bottom: 0.5rem;
    }

    /* Partidos */
    .partidos {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1rem;
    }

    .partido {
      background: white;
      color: #0033a0;
      border-radius: 10px;
      padding: 1rem;
      text-align: center;
      box-shadow: 0 3px 6px rgba(0,0,0,0.2);
    }

    footer {
      background: #002b80;
      color: #ffcc00;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>BOCA DICE</h1>
    <p>Noticias y próximos partidos del Xeneize</p>
  </header>

  <main>
    <!-- Sección de noticias -->
    <section>
      <h2>Noticias</h2>
      <div class="noticia">
        <img src="https://upload.wikimedia.org/wikipedia/commons/f/f1/Escudo_del_Club_Atl%C3%A9tico_Boca_Juniors_2012.png" alt="Escudo de Boca">
        <h3>Boca entrena pensando en Atlético Tucumán</h3>
        <p>El equipo se prepara para su próximo partido en la Bombonera. El DT analiza variantes en el mediocampo.</p>
      </div>
      <div class="noticia">
        <h3>Refuerzo en la defensa</h3>
        <p>Boca oficializó la llegada de un nuevo central para reforzar el plantel de cara al torneo internacional.</p>
      </div>
    </section>

    <!-- Sección de próximos partidos -->
    <section>
      <h2>Próximos 5 partidos</h2>
      <div class="partidos">
        <div class="partido">
          <h3>Boca vs Atlético Tucumán</h3>
          <p>Domingo 7 de septiembre, 21:00</p>
        </div>
        <div class="partido">
          <h3>San Lorenzo vs Boca</h3>
          <p>Miércoles 10 de septiembre, 19:30</p>
        </div>
        <div class="partido">
          <h3>Boca vs Talleres</h3>
          <p>Sábado 13 de septiembre, 20:00</p>
        </div>
        <div class="partido">
          <h3>Racing vs Boca</h3>
          <p>Miércoles 17 de septiembre, 21:30</p>
        </div>
        <div class="partido">
          <h3>Boca vs Independiente</h3>
          <p>Domingo 21 de septiembre, 18:00</p>
        </div>
      </div>
    </section>
  </main>

  <footer>
    <p>© 2025 Boca Dice - Sitio de noticias no oficial</p>
  </footer>
</body>
</html>
