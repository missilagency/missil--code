<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>Landing Page</title>
    <link rel="missil landing page" href="missil landing page .css">
  </head>
  <body>
    <header>
      <nav>
        <ul>
          <li><a href="#">Início</a></li>
          <li><a href="#">Produtos</a></li>
          <li><a href="#">Contato</a></li>
        </ul>
      </nav>
    </header>
    <main>
      <h1>Seja bem-vindo à nossa Landing Page!</h1>
      <h2>Conheça nosso novo produto:</h2>
      <div class="product-info">
        <div class="product-image">
          <img src="product-image.jpg" alt="Produto X">
        </div>
        <div class="product-description">
          <h3>Produto X</h3>
          <p>O Produto X é a solução ideal para o seu problema.</p>
          <p>Veja como funciona:</p>
          <div class="product-video">
            <iframe width="560" height="315" src="https://www.youtube.com/embed/VIDEO_ID" frameborder="0" allowfullscreen></iframe>
          </div>
        </div>
      </div>
      <div class="contact-form">
        <h2>Entre em contato conosco</h2>
        <form action="#" method="post">
          <label for="name">Nome:</label>
          <input type="text" id="name" name="name" required>
          <label for="email">E-mail:</label>
          <input type="email" id="email" name="email" required>
          <label for="message">Mensagem:</label>
          <textarea id="message" name="message" required></textarea>
          <button type="submit" class="button">Enviar</button>
        </form>
      </div>
    </main>
    <footer>
      <p>Todos os direitos reservados.</p>
    </footer>
  </body>
</html>
