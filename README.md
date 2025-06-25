<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Portfólio Lettycia</title>
  <style>
    /* Ativa rolagem suave ao clicar nos links do menu */
    html {
      scroll-behavior: smooth;
    }

    body {
      font-family: Arial, sans-serif;
      background-color: #ffe6f0;
      margin: 0;
      padding: 0;
    }

    nav {
      background-color: #ff80b3;
      padding: 15px;
      text-align: center;
    }

    nav a {
      margin: 0 15px;
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    section {
      padding: 50px;
    }

    form input, form textarea {
      width: 100%;
      padding: 8px;
      margin-top: 5px;
      margin-bottom: 15px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    form input[type="submit"] {
      background-color: #ff80b3;
      color: white;
      border: none;
      cursor: pointer;
    }

    form input[type="submit"]:hover {
      background-color: #e066a0;
    }
  </style>
</head>
<body>

  <header>
    <!-- Título principal do site -->
    <h1 id="inicio" style="text-align: center;">Bem-vinda ao meu site 💖</h1>

    <!-- Menu de navegação -->
    <nav>
      <a href="#inicio">Início</a>
      <a href="#sobre">Sobre</a>
      <a href="#formacao">Formação</a>
      <a href="#portfolio">Portfólio</a>
      <a href="#contato">Contato</a>
    </nav>
  </header>

  <!-- Seção sobre mim -->
  <section id="sobre">
    <h2>Sobre mim</h2>
    <p>Olá! Meu nome é Lettycia, sou uma pessoa jovem, criativa e determinada. Gosto de inovar, amo ser compreendida e valorizada. Meus hobbies incluem desenhar, ouvir música e aprender novas línguas, como o espanhol.</p>
  </section>

  <!-- Seção de formação educacional -->
  <section id="formacao">
    <h2>Formação</h2>
    <p>Atualmente estou cursando Análise e Desenvolvimento de Sistemas e também estudo inglês e espanhol por fora. Estou sempre em busca de aprender mais para crescer na área de tecnologia.</p>
  </section>

  <!-- Seção de portfólio com links de exemplo -->
  <section id="portfolio">
    <h2>Portfólio</h2>
    <p>Veja abaixo alguns exemplos de sites e projetos que desenvolvi durante o curso:</p>
    <ul>
      <li><a href="https://lettyciasales.github.io/meuwebsite/" target="_blank">Projeto do site pessoal</a></li>
      <li><a href="#">Exercício prático de HTML e CSS</a></li>
    </ul>
  </section>

  <!-- Seção de contato com formulário visual -->
  <section id="contato">
    <h2>Contato</h2>
    <form>
      <!-- Campo nome -->
      <label>Nome:</label>
      <input type="text" name="nome">

      <!-- Campo e-mail -->
      <label>Email:</label>
      <input type="email" name="email">

      <!-- Campo mensagem -->
      <label>Mensagem:</label>
      <textarea name="mensagem" rows="4"></textarea>

      <input type="submit" value="Enviar">
    </form>
  </section>

</body>
</html>
