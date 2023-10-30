
HTML:
```html
<!DOCTYPE html>
<html>
<head>
  <title>Meu Site de Futebol</title>
  <link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
  <header>
    <h1>Meu Site de Futebol</h1>
  </header>

  <nav>
    <ul>
      <li><a href="#">Início</a></li>
      <li><a href="#">Notícias</a></li>
      <li><a href="#">Times</a></li>
      <li><a href="#">Jogadores</a></li>
      <li><a href="#">Contato</a></li>
    </ul>
  </nav>

  <section>
    <h2>Últimas Notícias</h2>
    <article>
      <h3>Título da Notícia</h3>
      <p>Conteúdo da notícia...</p>
    </article>
    <article>
      <h3>Título da Notícia</h3>
      <p>Conteúdo da notícia...</p>
    </article>
  </section>

  <footer>
    <p>&copy; 2021 Meu Site de Futebol. Todos os direitos reservados.</p>
  </footer>
</body>
</html>
```

CSS (style.css):
```css
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

header {
  background-color: #333;
  color: #fff;
  padding: 20px;
}

nav ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  background-color: #f2f2f2;
}

nav ul li {
  display: inline;
}

nav ul li a {
  display: block;
  padding: 10px;
  text-decoration: none;
  color: #333;
}

nav ul li a:hover {
  background-color: #ddd;
}

section {
  padding: 20px;
}

footer {
  background-color: #333;
  color: #fff;
  padding: 10px;
  text-align: center;
}
```
