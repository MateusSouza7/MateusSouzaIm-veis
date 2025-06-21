<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Mateus Souza - Corretor de Imóveis</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { font-family: Arial, sans-serif; line-height: 1.6; background: #f4f4f4; color: #333; }
    header { background: #2c3e50; color: white; padding: 2rem 1rem; text-align: center; }
    header h1 { font-size: 2.5rem; }
    header p { font-size: 1.2rem; margin-top: 0.5rem; }

    section { padding: 2rem 1rem; max-width: 1000px; margin: auto; }

    .cta { text-align: center; margin: 2rem 0; }
    .cta a {
      background: #3498db; color: white; padding: 0.8rem 1.5rem;
      text-decoration: none; border-radius: 5px; font-size: 1.1rem;
    }
    .cta a:hover { background: #2980b9; }

    .financiamento {
      background: #ecf0f1; padding: 1.5rem; border-radius: 8px;
      margin-top: 2rem;
    }

    .galeria {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 1.5rem;
      margin-top: 2rem;
    }

    .imovel {
      background: white; border-radius: 8px; overflow: hidden;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }

    .imovel img {Allyson - RND 02 - Noite IA
      width: 100%; height: 180px; object-fit: cover;
    }

    .imovel .detalhes {
      padding: 1rem;
    }

    .imovel .detalhes h3 {
      margin-bottom: 0.5rem;
    }

    form {
      background: white; padding: 2rem; border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1); margin-top: 2rem;
    }

    footer {
      background: #2c3e50; color: white; text-align: center;
      padding: 1rem; margin-top: 3rem;
    }

    /* WhatsApp Button */
    .whatsapp-button {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background-color: #25d366;
      color: white;
      border-radius: 50%;
      width: 60px;
      height: 60px;
      display: flex;
      align-items: center;
      justify-content: center;
      text-decoration: none;
      font-size: 30px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
      z-index: 1000;
    }

    .whatsapp-button:hover {
      background-color: #1ebd5a;
    }
  </style>
</head>
<body>

  <header>
    <h1>Mateus Souza</h1>
    <p>Te ajudo a realizar o sonho da casa própria</p>
  </header>

  <section class="cta">
    <p>Consulte nossas opções disponíveis</p>
    <a href="#galeria">Ver Imóveis</a>
  </section>

  <section class="financiamento">
    <h2>Financiamento Facilitado</h2>
    <p>Aprenda a financiar seu primeiro imóvel contando com uma ajudinha do governo.</p>
  </section>

  <section id="galeria">
    <h2>Imóveis Disponíveis</h2>
    <div class="galeria">
      <div class="imovel">
        <img src="https://source.unsplash.com/400x300/?house" alt="Casa 1">
        <div class="detalhes">
          <h3>Casa em bairro tranquilo</h3>
          <p>3 quartos, 2 banheiros, garagem – R$ 350.000</p>
        </div>
      </div>
      <div class="imovel">
        <img src="https://source.unsplash.com/400x300/?apartment" alt="Apartamento 1">
        <div class="detalhes">
          <h3>Apartamento moderno</h3>
          <p>2 quartos, 1 suíte, elevador – R$ 280.000</p>
        </div>
      </div>
      <div class="imovel">
        <img src="https://source.unsplash.com/400x300/?real-estate" alt="Casa 2">
        <div class="detalhes">
          <h3>Casa com quintal grande</h3>
          <p>4 quartos, varanda, churrasqueira – R$ 420.000</p>
        </div>
      </div>
    </div>
  </section>

  <section id="contato">
    <h2>Entre em Contato</h2>
    <!-- Substitua a URL do action pelo SEU Google Forms -->
    <iframe src="https://docs.google.com/forms/d/e/1FAIpQLSfD5vSZYuKfWWOSeuHxxEXEMPLO/viewform?embedded=true" width="100%" height="600" frameborder="0" marginheight="0" marginwidth="0">Carregando…</iframe>
  </section>

  <footer>
    <p>&copy; 2025 Mateus Souza - Corretor de Imóveis</p>
  </footer>

  <!-- Botão Flutuante do WhatsApp -->
  <a href="https://wa.me/55SEUNUMEROAQUI" class="whatsapp-button" target="_blank" title="Fale comigo no WhatsApp">
    &#x1F4AC;
  </a>

</body>
</html>
