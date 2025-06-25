<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <title>Portfólio Lettycia</title>
  <style>
    /* Ativa rolagem suave ao clicar nos links do menu */
    html {
      scroll-behavior: smooth;
    }

    /* Estilo geral do corpo da página */
    body {
      font-family: Arial, sans-serif;
      background-color: #ffe6f0;
      margin: 0;
      padding: 0;
      color: #333;
    }

    /* Estilo do menu de navegação */
    nav {
      background-color: #ff80b3;
      padding: 15px;
      text-align: center;
    }

    /* Estilo dos links do menu */
    nav a {
      margin: 0 15px;
      color: white;
      text-decoration: none;
      font-weight: bold;
      font-size: 1.1em;
    }

    /* Efeito hover nos links do menu */
    nav a:hover {
      text-decoration: underline;
    }

    /* Estilo geral das seções */
    section {
      padding: 50px 20px;
      max-width: 900px;
      margin: 0 auto;
    }

    /* Estilo dos títulos */
    h1, h2 {
      text-align: center;
      color: #b30059;
    }

    /* Estilo da lista no portfólio */
    ul {
      max-width: 600px;
      margin: 0 auto;
      padding-left: 20px;
    }

    ul li {
      margin-bottom: 10px;
    }

    ul li a {
      color: #ff4d94;
      text-decoration: none;
    }

    ul li a:hover {
      text-decoration: underline;
    }

    /* Estilo dos inputs e textarea do formulário */
    form input, form textarea {
      width: 100%;
      padding: 8px;
      margin-top: 5px;
      margin-bottom: 15px;
      border: 1px solid #ccc;
      border-radius: 5px;
      font-size: 1em;
      font-family: Arial, sans-serif;
    }

    /* Estilo do botão enviar do formulário */
    form input[type="submit"] {
      background-color: #ff80b3;
      color: white;
      border: none;
      cursor: pointer;
      font-weight: bold;
      font-size: 1.1em;
      transition: background-color 0.3s ease;
    }

    /* Efeito hover do botão enviar */
    form input[type="submit"]:hover {
      background-color: #e066a0;
    }

    /* Estilo da imagem banner */
    .banner {
      display: block;
      max-width: 100%;
      height: auto;
      margin: 20px auto;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(255, 128, 179, 0.3);
    }

    /* Estilo do rodapé */
    footer {
      background-color: #ff80b3;
      color: white;
      text-align: center;
      padding: 15px 10px;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <!-- Cabeçalho com título e menu -->
  <header>
    <h1 id="inicio">Bem-vindo ao meu site 💖</h1>

    <!-- Menu de navegação com links para as seções -->
    <nav>
      <a href="#inicio">Início</a>
      <a href="#sobre">Sobre</a>
      <a href="#formacao">Formação</a>
      <a href="#portfolio">Portfólio</a>
      <a href="#contato">Contato</a>
    </nav>
  </header>

  <!-- Seção Sobre mim -->
  <section id="sobre">
    <h2>Sobre mim</h2>
    <p>Olá! Meu nome é Lettycia, sou uma pessoa jovem, criativa e determinada. Gosto de inovar e crescer profissionalmente e pessoalmente. Meus hobbies incluem desenhar, ouvir música e aprender novas línguas, como o espanhol e inglês.</p>
  </section>

  <!-- Seção Formação educacional -->
  <section id="formacao">
    <h2>Formação</h2>
    <p>Atualmente estou cursando Análise e Desenvolvimento de Sistemas e também estudo inglês e espanhol por fora. Estou sempre em busca de aprender mais para crescer na área de tecnologia e comércio interno e externo.</p>
  </section>

  <!-- Seção Portfólio com links para projetos -->
  <section id="portfolio">
    <h2>Portfólio</h2>
    <p>Veja abaixo alguns exemplos de sites e projetos que desenvolvi durante o curso:</p>
    <ul>
      <li><a href="https://lettyciasales.github.io/meuwebsite/" target="_blank" rel="noopener noreferrer">Projeto do site pessoal</a></li>
      <li><a href="#" target="_blank" rel="noopener noreferrer">Exercício prático de HTML e CSS</a></li>
    </ul>
  </section>

  <!-- Seção Contato com informações de contato -->
  <section id="contato">
    <h2>Contato</h2>

    <p>📞 Telefone: <a href="tel:+5551995045404">(54) 99504-5404</a></p>
    <p>📧 Email: <a href="mailto:lettycia.salees@gmail.com">Lettycia.salees@gmail.com</a></p>
    <p>💬 WhatsApp: <a href="https://wa.me/5551995045404" target="_blank" rel="noopener noreferrer">Clique para conversar</a></p>
    <p>🌐 Instagram: <a href="https://instagram.com/sales.letty" target="_blank" rel="noopener noreferrer">@sales.letty</a></p>
  </section>

  <!-- Conteúdo principal com imagem banner e texto -->
  <main>
    <img src="17826.webp" alt="Banner do site" class="banner" />
    <p style="text-align: center;">Este é um projeto feito para a disciplina de Ferramentas da Programação Web.</p>
  </main>

  <!-- Rodapé com créditos -->
  <footer>
    <p>Feito por Lettycia Abiaes Sales - 2025</p>
  </footer>

</body>
</html>
