<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Portfólio - Vitor Eduardo</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, Helvetica, sans-serif;
    }
    body {
      background-color: #f4f4f4;
      color: #333;
      line-height: 1.6;
    }
    header {
      background: #222;
      color: #fff;
      padding: 20px 0;
      text-align: center;
    }
    header h1 {
      font-size: 2rem;
    }
    header p {
      font-size: 1.2rem;
      color: #ccc;
    }
    main {
      max-width: 1000px;
      margin: 30px auto;
      padding: 0 20px;
    }
    section {
      margin-bottom: 40px;
    }
    h2 {
      color: #444;
      margin-bottom: 10px;
      border-bottom: 2px solid #ddd;
      padding-bottom: 5px;
    }
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .card {
      background: #fff;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0px 2px 5px rgba(0,0,0,0.1);
      transition: transform 0.2s ease;
    }
    .card:hover {
      transform: scale(1.03);
    }
    .card h3 {
      margin-bottom: 10px;
    }
    .card p {
      font-size: 0.95rem;
      color: #666;
      margin-bottom: 10px;
    }
    .card a {
      display: inline-block;
      background: #0077cc;
      color: white;
      padding: 8px 12px;
      border-radius: 4px;
      text-decoration: none;
      font-size: 0.9rem;
    }
    .card a:hover {
      background: #005fa3;
    }
    footer {
      text-align: center;
      padding: 15px;
      font-size: 0.9rem;
      color: #555;
      background: #eee;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Vitor Eduardo</h1>
    <p>Portfólio de Projetos</p>
  </header>

  <main>
    <section>
      <h2>Sobre Mim</h2>
      <p>Sou desenvolvedor apaixonado por tecnologia e inovação. Aqui estão alguns dos meus projetos, desde aplicações web até automações e experimentos com código.</p>
    </section>

    <section>
      <h2>Projetos</h2>
      <div class="projects">
        <div class="card">
          <h3>Projeto 1</h3>
          <p>Descrição breve do projeto. Pode incluir tecnologias utilizadas e objetivo.</p>
          <a href="https://github.com/seu_usuario/projeto1" target="_blank">Ver no GitHub</a>
        </div>
        <div class="card">
          <h3>Projeto 2</h3>
          <p>Descrição breve do projeto. Pode incluir tecnologias utilizadas e objetivo.</p>
          <a href="https://github.com/seu_usuario/projeto2" target="_blank">Ver no GitHub</a>
        </div>
        <div class="card">
          <h3>Projeto 3</h3>
          <p>Descrição breve do projeto. Pode incluir tecnologias utilizadas e objetivo.</p>
          <a href="https://github.com/seu_usuario/projeto3" target="_blank">Ver no GitHub</a>
        </div>
      </div>
    </section>
  </main>

  <footer>
    &copy; 2025 Vitor Eduardo - Todos os direitos reservados.
  </footer>

</body>
</html>
