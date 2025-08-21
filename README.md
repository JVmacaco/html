
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>José Vinicius - Chef de Cozinha</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    body {
      background-color: #fff8f0;
      color: #333;
      line-height: 1.6;
    }

    .container {
      max-width: 1000px;
      margin: 0 auto;
      padding: 0 20px;
    }

    header {
      background-color: #8B4513;
      color: white;
      padding: 20px 0;
      text-align: center;
    }

    h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
    }

    h2 {
      font-size: 2rem;
      color: #8B4513;
      margin: 30px 0 20px;
      text-align: center;
    }

    h3 {
      font-size: 1.5rem;
      color: #8B4513;
      margin: 15px 0;
    }

    p {
      margin-bottom: 15px;
    }

    .tagline {
      font-style: italic;
      color: #f0f0f0;
    }

    section {
      margin: 40px 0;
      padding: 30px;
      background: white;
      border-radius: 8px;
      box-shadow: 0 3px 10px rgba(0, 0, 0, 0.1);
    }

    .about {
      display: flex;
      flex-wrap: wrap;
      gap: 30px;
      align-items: center;
    }

    .about-text {
      flex: 1;
      min-width: 300px;
    }

    .about-image {
      flex: 1;
      min-width: 300px;
      height: 300px;
      background-color: #f4f4f4;
      border-radius: 8px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: #8B4513;
      font-size: 5rem;
    }

    .dishes {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }

    .dish {
      background: #fff8f0;
      padding: 20px;
      border-radius: 8px;
      text-align: center;
      border: 1px solid #e0d0c0;
    }

    .dish-image {
      height: 180px;
      background-color: #f4f4f4;
      border-radius: 8px;
      margin-bottom: 15px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: #8B4513;
      font-size: 3rem;
    }

    .specialties {
      display: flex;
      flex-wrap: wrap;
      gap: 15px;
      justify-content: center;
      margin-top: 20px;
    }

    .specialty {
      background: #8B4513;
      color: white;
      padding: 10px 20px;
      border-radius: 20px;
      font-size: 0.9rem;
    }

    .contact {
      display: flex;
      flex-wrap: wrap;
      gap: 15px;
      justify-content: center;
      margin-top: 20px;
    }

    .contact a {
      color: #8B4513;
      text-decoration: none;
      padding: 10px 20px;
      border: 1px solid #8B4513;
      border-radius: 4px;
      transition: all 0.3s;
    }

    .contact a:hover {
      background: #8B4513;
      color: white;
    }

    footer {
      text-align: center;
      margin-top: 50px;
      padding: 30px;
      background: #8B4513;
      color: white;
    }

    @media (max-width: 768px) {
      h1 {
        font-size: 2rem;
      }

      h2 {
        font-size: 1.7rem;
      }

      section {
        padding: 20px;
      }
    }
  </style>
</head>
<body>
  <header>
    <div class="container">
      <h1>José Vinicius</h1>
      <p class="tagline">Chef de Cozinha & Especialista em Gastronomia Regional</p>
    </div>
  </header>

  <div class="container">
    <!-- Sobre Mim -->
    <section id="about">
      <h2>Sobre Mim</h2>
      <div class="about">
        <div class="about-text">
          <p>Olá! Sou José Vinicius, um apaixonado por gastronomia com mais de 10 anos de experiência na cozinha. Minha especialidade é a culinária regional brasileira com toques contemporâneos.</p>
          <p>Formado pela Escola de Gastronomia de São Paulo, trabalhei em restaurantes premiados antes de seguir minha jornada como chef independente.</p>
          <p>Acredito que cozinhar é uma forma de expressão artística que une tradição, inovação e, acima de tudo, amor.</p>
        </div>
        <div class="about-image">
          <i class="fas fa-chef-hat"></i>
        </div>
      </div>
    </section>

    <!-- Especialidades -->
    <section id="specialties">
      <h2>Especialidades</h2>
      <div class="specialties">
        <span class="specialty">Culinária Regional Brasileira</span>
        <span class="specialty">Pratos com Toque Contemporâneo</span>
        <span class="specialty">Sobremesas Artesanais</span>
        <span class="specialty">Massas Frescas</span>
        <span class="specialty">Pratos Vegetarianos</span>
        <span class="specialty">Carnes Nobres</span>
      </div>
    </section>

    <!-- Pratos -->
    <section id="dishes">
      <h2>Pratos Destacados</h2>
      <div class="dishes">
        <div class="dish">
          <div class="dish-image">
            <i class="fas fa-drumstick-bite"></i>
          </div>
          <h3>Frango à Passarinho com Polenta Cremosa</h3>
          <p>Clássico da culinária mineira com minha assinatura especial de temperos.</p>
        </div>

        <div class="dish">
          <div class="dish-image">
            <i class="fas fa-fish"></i>
          </div>
          <h3>Moqueca Capixaba com Toque Contemporary</h3>
          <p>Receita tradicional com um toque especial de gengibre e coentro.</p>
        </div>

        <div class="dish">
          <div class="dish-image">
            <i class="fas fa-cheese"></i>
          </div>
          <h3>Risoto de Queijo Brie com Frutas Vermelhas</h3>
          <p>Combinação surpreendente de sabores doces e salgados.</p>
        </div>
      </div>
    </section>

    <!-- Contato -->
    <section id="contact">
      <h2>Contato</h2>
      <p>Interessado em meu trabalho? Vamos conversar sobre eventos, consultorias ou experiências gastronômicas!</p>
      <div class="contact">
        <a href="mailto:jose.vinicius@exemplo.com"><i class="fas fa-envelope"></i> Email</a>
        <a href="https://instagram.com/jose.vinicius.chef" target="_blank"><i class="fab fa-instagram"></i> Instagram</a>
        <a href="tel:+5511999999999"><i class="fas fa-phone"></i> Telefone</a>
      </div>
    </section>
  </div>

  <footer>
    <div class="container">
      <p>© 2023 José Vinicius - Chef de Cozinha</p>
    </div>
  </footer>
</body>
</html>
```
