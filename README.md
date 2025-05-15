# portfolio-fotografia
├── index.html
├── style.css
├── script.js
├── /galeria/
│   ├── natureza.html
│   ├── urbana.html
│   └── retratos.html
├── /imagens/
│   ├── natureza1.jpg
│   ├── urbana1.jpg
│   └── retrato1.jpg
└── README.md
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfólio Fotográfico - Lucas K.</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Lucas K. Fotografia</h1>
    <nav>
      <a href="galeria/natureza.html">Natureza</a>
      <a href="galeria/urbana.html">Urbana</a>
      <a href="galeria/retratos.html">Retratos</a>
    </nav>
  </header>

  <main>
    <h2>Bem-vindo(a) ao meu portfólio</h2>
    <p>Aqui compartilho minha paixão por capturar momentos únicos através da lente.</p>
    <p><a href="#contato">Fale comigo</a></p>
  </main>

  <footer id="contato">
    <h3>Contato</h3>
    <p>Email: lucaskerche11@gmail.com</p>
    <p>Instagram: @lucask_fotos</p>
    <p>&copy; 2025 - Lucas Kerche</p>
  </footer>
</body>
</html>
body {
  font-family: 'Segoe UI', sans-serif;
  margin: 0;
  background: #111;
  color: #eee;
}

header {
  background: black;
  padding: 1em;
  text-align: center;
}

nav a {
  margin: 0 10px;
  color: #ccc;
  text-decoration: none;
}

main {
  padding: 20px;
  text-align: center;
}

footer {
  background: #222;
  padding: 1em;
  text-align: center;
}
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Natureza | Portfólio Lucas K.</title>
  <link rel="stylesheet" href="../style.css">
</head>
<body>
  <header>
    <h1>Fotos de Natureza</h1>
    <a href="../index.html">Voltar</a>
  </header>
  <main>
    <img src="../imagens/natureza1.jpg" alt="Paisagem com montanhas" width="300">
    <img src="../imagens/natureza2.jpg" alt="Floresta com névoa" width="300">
    <!-- Adicione mais fotos -->
  </main>
</body>
</html>
