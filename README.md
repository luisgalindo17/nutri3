<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Nutrición Infantil Tocatlán</title>
  <style>
    body {
      font-family: "Segoe UI", sans-serif;
      margin: 0;
      padding: 0;
      text-align: center;
      background-color: #f0f8ff;
      scroll-behavior: smooth;
    }

    header {
      background: url('https://tetlax.org.mx/wp-content/uploads/2023/06/0531-El-Tribunal-Va-a-la-Escuela-Tocatlan-1.jpg') no-repeat center center;
      background-size: cover;
      color: rgb(15, 15, 15);
      padding: 60px 0;
      text-align: center;
    }

    header h1 {
      font-size: 3em;
      font-weight: bold;
      text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.7);
    }

    nav ul {
      list-style: none;
      padding: 0;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      background-color: #005f73;
      margin: 0;
    }

    nav ul li {
      margin: 10px 15px;
    }

    nav ul li a {
      color: #fff;
      text-decoration: none;
      font-weight: bold;
      font-size: 1em;
    }

    main {
      padding: 20px;
    }

    section {
      margin-bottom: 30px;
      padding: 20px;
      border-radius: 10px;
      color: white;
      background-size: cover;
      background-position: center;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }

    section img {
      max-width: 100%;
      border-radius: 10px;
      margin-top: 15px;
    }

    footer {
      text-align: center;
      padding: 20px;
      background-color: #e0e0e0;
      color: #111;
      font-family: "Segoe UI", sans-serif;
    }

    .resultado {
      font-weight: bold;
      font-size: 18px;
      margin-top: 15px;
    }

    .bajo {
      color: red;
    }

    .saludable {
      color: green;
    }

    .alto {
      color: orange;
    }

    #imagenIMC img {
      width: 150px;
      margin-top: 10px;
    }

    #recomendacionIMC {
      font-style: italic;
      margin-top: 10px;
      color: #fff;
      max-width: 400px;
      margin-left: auto;
      margin-right: auto;
    }

    .galeria-img {
      display: flex;
      justify-content: space-between;
      flex-wrap: wrap;
      gap: 20px;
    }

    .solo-escritorio {
      display: none;
    }

    @media (min-width: 769px) {
      .solo-escritorio {
        display: block;
      }

      .solo-movil {
        display: none;
      }
    }

    @media (max-width: 768px) {
      .galeria-img {
        flex-direction: column;
        align-items: center;
      }

      .galeria-img img {
        width: 90%;
      }

      iframe {
        width: 100%;
        height: auto;
        aspect-ratio: 16/9;
      }

      .solo-escritorio {
        display: none;
      }

      .solo-movil {
        display: block;
      }

      #imagenIMC img {
        width: 100px;
      }
    }

    /* Fondo de cada sección */
    #tocatlan, #consejos, #video, #galeria, #recetas, #imc, #contacto, #sintomas {
      background: url('https://www.foxstextil.com.br/image/cache/catalog/Lisos/tecido-fustao-azul-bebe-1000x1000.jpg') no-repeat center center;
      background-size: cover;
    }

    /* NUEVO ESTILO PARA TEXTO DE IMÁGENES */
    .img-item {
      width: 30%;
      text-align: center;
    }

    .img-item img {
      width: 100%;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }

    .img-texto {
      color: black;
      font-size: 1em;
      margin-top: 10px;
    }

    @media (max-width: 768px) {
      .img-item {
        width: 90%;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>PÁGINA WEB DE NUTRICIÓN EN NIÑOS DE 1 - 4 AÑOS - TOCATLÁN</h1>
  </header>

  <nav>
    <ul>
      <li><a href="#tocatlan">Tocatlán</a></li>
      <li><a href="#consejos">Consejos</a></li>
      <li><a href="#video">Video</a></li>
      <li><a href="#sintomas">Síntomas</a></li>
      <li><a href="#recetas">Recetas</a></li>
      <li><a href="#imc">IMC</a></li>
      <li><a href="#contacto">Contacto</a></li>
    </ul>
  </nav>

  <main>
    <section id="tocatlan">
      <h2>Tocatlán y la Nutrición Infantil</h2>
      <p>Tocatlán es una comunidad con un alto índice de padres adolescentes. La falta de información ha generado un alto índice de desnutrición en niños de 1-4 años. Esta página busca ayudarte con información útil. Lo mejor siempre será acudir a un profesional.</p>
      <p class="solo-escritorio">Versión de escritorio.</p>
      <img src="https://noticierosenlinea.com/wp-content/uploads/2018/07/plato-del-buen-comer-mexico-800x800.png" alt="alimentación saludable" />
    </section>

    <section id="consejos">
      <h2>Consejos de Nutrición</h2>
      <ul>
        <li>Incluye frutas y verduras en cada comida.</li>
        <li>Ofrece proteínas magras como pollo o legumbres.</li>
        <li>Evita alimentos con azúcares añadidos y refrescos.</li>
        <li>Asegura una buena hidratación con agua.</li>
      </ul>
    </section>

    <section id="video">
      <h2>Video de Nutrición Infantil</h2>
      <iframe src="https://www.youtube.com/embed/04OcYjc2kh0" title="Video de ejemplo" frameborder="0" allowfullscreen></iframe>
    </section>

    <section id="sintomas">
      <h2>Algunos de los síntomas de desnutrición son:</h2>
      <div class="galeria-img">
        <div class="img-item">
          <img src="https://japaclip.com/es/files/woman-before-after-weight-loss.png" alt="Antes y después de pérdida de peso">
          <p class="img-texto">Pérdida de peso corporal</p>
        </div>
        <div class="img-item">
          <img src="https://images.freeimages.com/clg/istock/previews/9981/99812107-little-boy-having-stomach-ache.jpg?fmt=webp&h=350" alt="Dolor abdominal">
          <p class="img-texto">problemas digestivos</p>
        </div>
        <div class="img-item">
          <img src="https://media.istockphoto.com/id/1396923079/es/vector/ni%C3%B1a-sinti%C3%A9ndose-sola-apat%C3%ADa-depresi%C3%B3n-ni%C3%B1o-jugando-solo-con-juguete-de-oso.jpg?s=1024x1024&w=is&k=20&c=R1PQ02RVMk64R3nT5W7hK8tV5Ta-8XPFchGjKzwT6i0=" alt="Niña apática con peluche">
          <p class="img-texto">problemas psicológicos</p>
        </div>
      </div>
    </section>

    <section id="recetas">
      <h2>Recetas Saludables</h2>
      <article>
        <h3>Batido de Plátano y Espinaca</h3>
        <ul>
          <li>1 plátano maduro</li>
          <li>1 taza de espinaca fresca</li>
          <li>1/2 taza de yogur natural</li>
          <li>1/2 taza de leche o bebida vegetal</li>
        </ul>
        <p>Licuar todo hasta obtener una mezcla suave. Servir frío.</p>
      </article>
      <article>
        <h3>Tortitas de Avena y Manzana</h3>
        <ul>
          <li>1 taza de avena</li>
          <li>1 manzana rallada</li>
          <li>1 huevo</li>
          <li>Canela al gusto</li>
        </ul>
        <p>Mezclar y cocinar en sartén caliente hasta dorar.</p>
      </article>
    </section>

    <section id="imc">
      <h2>Calculadora de IMC Infantil (1 a 4 años)</h2>
      <p>Introduce el peso, la estatura y la edad del niño o niña para calcular su IMC:</p>
      <input type="number" id="edad" placeholder="Edad en años (1 a 4)">
      <input type="number" id="peso" placeholder="Peso en kg">
      <input type="number" id="altura" placeholder="Altura en metros"><br><br>
      <button onclick="calcularIMC()">Calcular IMC</button>
      <p id="resultadoIMC" class="resultado"></p>
      <div id="imagenIMC"></div>
      <p id="recomendacionIMC"></p>
    </section>

    <section id="contacto">
      <h2>Contacto</h2>
      <p>¿Tienes dudas o necesitas orientación?</p>
      <p><strong>Email:</strong> contacto@nutriciontocatlan.mx</p>
      <p><strong>Teléfono:</strong> +52 246 000 0000</p>
      <p><strong>Dirección:</strong> Tocatlán, Tlaxcala, México</p>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Página de Nutrición Tocatlán. Todos los derechos reservados.</p>
  </footer>

  <script>
    function calcularIMC() {
      const edad = parseInt(document.getElementById("edad").value);
      const peso = parseFloat(document.getElementById("peso").value);
      const altura = parseFloat(document.getElementById("altura").value);
      const resultado = document.getElementById("resultadoIMC");
      const imagen = document.getElementById("imagenIMC");
      const recomendacion = document.getElementById("recomendacionIMC");

      resultado.className = "resultado";
      imagen.innerHTML = "";
      recomendacion.textContent = "";

      if (!edad || edad < 1 || edad > 4 || !peso || !altura || altura === 0) {
        resultado.textContent = "Por favor, introduce valores válidos: edad entre 1 y 4 años, peso y altura.";
        return;
      }

      const imc = peso / (altura * altura);
      let mensaje = `El IMC es: ${imc.toFixed(2)}. `;
      let clase = "", imgSrc = "", consejo = "";  
      let rango = { bajo: 0, alto: 0 };

      switch (edad) {
        case 1: rango = { bajo: 14.5, alto: 18.0 }; break;
        case 2: rango = { bajo: 14.0, alto: 17.5 }; break;
        case 3: rango = { bajo: 13.8, alto: 17.0 }; break;
        case 4: rango = { bajo: 13.5, alto: 16.5 }; break;
      }

      if (imc < rango.bajo) {
        mensaje += "🔴 IMC por debajo del rango saludable.";
        clase = "bajo";
        imgSrc = "https://cdn-icons-png.flaticon.com/512/2920/2920063.png";
        consejo = "Tu niño/a puede necesitar más energía. Añade snacks saludables y consulta a un profesional.";
      } else if (imc > rango.alto) {
        mensaje += "🔴 IMC por encima del rango saludable.";
        clase = "alto";
        imgSrc = "https://cdn-icons-png.flaticon.com/512/2920/2920073.png";
        consejo = "Evita alimentos procesados, fomenta juegos activos y consulta con el pediatra.";
      } else {
        mensaje += "🟢 IMC dentro del rango saludable. ¡Muy bien!";
        clase = "saludable";
        imgSrc = "https://cdn-icons-png.flaticon.com/512/2920/2920054.png";
        consejo = "Tu niño/a está en un buen estado nutricional. Sigue ofreciendo comidas equilibradas.";
      }

      resultado.textContent = mensaje;
      resultado.classList.add(clase);
      imagen.innerHTML = `<img src="${imgSrc}" alt="Resultado IMC">`;
      recomendacion.textContent = consejo;
    }
  </script>
</body>
</html>
