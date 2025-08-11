
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfólio - Vitor Eduardo</title>
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(135deg, #002b36, #003b46, #005f6b);
            color: white;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
        }

        /* HEADER */
        header {
            padding: 20px;
            background: linear-gradient(90deg, #005f6b, #008c9e);
            display: flex;
            justify-content: center;
            align-items: center;
            box-shadow: 0 2px 20px rgba(0,0,0,0.4);
        }
        .logo {
            font-size: 2rem;
            font-weight: 700;
            color: white;
            letter-spacing: 2px;
            background: linear-gradient(90deg, #00d9ff, #00ffa2);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        /* ABOUT */
        .about {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 30px;
            padding: 50px 20px;
            flex-wrap: wrap;
        }
        .about img {
            width: 180px;
            height: 180px;
            object-fit: cover;
            border-radius: 50%;
            border: 3px solid #00d9ff;
            box-shadow: 0 4px 20px rgba(0,0,0,0.4);
        }
        .about-text {
            max-width: 500px;
        }
        .about-text h2 {
            font-size: 1.8rem;
            margin-bottom: 10px;
            color: #00d9ff;
        }
        .about-text p {
            font-size: 1rem;
            opacity: 0.9;
            line-height: 1.5;
        }
        .about-buttons {
            margin-top: 15px;
        }
        .about-buttons a {
            display: inline-block;
            padding: 10px 20px;
            margin-right: 10px;
            background: #00d9ff;
            color: #002b36;
            text-decoration: none;
            border-radius: 25px;
            font-weight: 500;
            transition: 0.3s;
        }
        .about-buttons a:hover {
            background: #00a0c6;
        }

        /* PROJECTS */
        .projects {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 40px;
            gap: 25px;
            flex: 1;
        }
        .card {
            background-color: #004f59;
            border-radius: 15px;
            padding: 20px;
            width: 280px;
            cursor: pointer;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            box-shadow: 0 5px 15px rgba(0,0,0,0.3);
        }
        .card:hover {
            transform: translateY(-8px);
            box-shadow: 0 12px 25px rgba(0,0,0,0.5);
        }
        .card h2 {
            margin-bottom: 10px;
            font-size: 1.3rem;
            color: #00d9ff;
        }
        .card p {
            font-size: 0.95rem;
            line-height: 1.4;
            opacity: 0.85;
        }

        /* FOOTER */
        footer {
            padding: 20px;
            background-color: #002b36;
            text-align: center;
            font-size: 0.9rem;
            opacity: 0.8;
        }
        footer a {
            color: #00d9ff;
            text-decoration: none;
            margin: 0 8px;
        }
        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <!-- HEADER -->
    <header>
        <div class="logo">VITOR EDUARDO</div>
    </header>

    <!-- ABOUT -->
    <section class="about">
        <img src="sua-foto.jpg" alt="Foto de Vitor Eduardo">
        <div class="about-text">
            <h2>Sobre Mim</h2>
            <p>Sou um engenheiro apaixonado por projetos de controle e automação, com experiência no desenvolvimento de sistemas embarcados, veículos autônomos e integração de hardware e software. Meu foco está em criar soluções inovadoras que unam eficiência e tecnologia de ponta.</p>
            <div class="about-buttons">
                <a href="mailto:seuemail@exemplo.com">Contato</a>
                <a href="https://github.com/seuusuario" target="_blank">GitHub</a>
            </div>
        </div>
    </section>

    <!-- PROJECTS -->
    <section class="projects">
        <div class="card" onclick="window.open('https://github.com/seuusuario/projeto1','_blank')">
            <h2>Controle de Distância - Servo Motor</h2>
            <p>Controle preciso da distância de uma esfera sobre haste inclinável.</p>
        </div>
        <div class="card" onclick="window.open('https://github.com/seuusuario/projeto2','_blank')">
            <h2>Controle de Ângulo - Brushless</h2>
            <p>Controle de inclinação usando motores brushless nas extremidades.</p>
        </div>
        <div class="card" onclick="window.open('https://github.com/seuusuario/projeto3','_blank')">
            <h2>Controle de Nível de Água</h2>
            <p>Regulação automática do nível de um tanque de água.</p>
        </div>
        <div class="card" onclick="window.open('https://github.com/seuusuario/projeto4','_blank')">
            <h2>Barco Cooperativo com Drones</h2>
            <p>Coordenação de barco autônomo e drones para missões conjuntas.</p>
        </div>
    </section>

    <!-- FOOTER -->
    <footer>
        <p>© 2025 Vitor Eduardo | 
            <a href="mailto:seuemail@exemplo.com">E-mail</a> | 
            <a href="https://linkedin.com/in/seuusuario" target="_blank">LinkedIn</a> | 
            <a href="https://github.com/seuusuario" target="_blank">GitHub</a>
        </p>
    </footer>

</body>
</html>
