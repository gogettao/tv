<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>GOG IPTV - Teste grátis IPTV + TV Box</title>
<style>
  body {
    font-family: Arial, sans-serif;
    background: #0b0c2a;
    color: #fff;
    margin: 0; padding: 0;
  }
  .container {
    max-width: 420px;
    margin: 40px auto;
    background: #13152f;
    padding: 30px 25px;
    border-radius: 10px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.7);
  }
  h1 {
    text-align: center;
    color: #26e07f;
  }
  p.subtitle {
    text-align: center;
    font-size: 1.1rem;
    margin-bottom: 25px;
  }
  ul {
    list-style: none;
    padding: 0;
    margin-bottom: 25px;
  }
  ul li {
    margin: 12px 0;
    padding-left: 20px;
    position: relative;
  }
  ul li::before {
    content: "✔";
    color: #26e07f;
    position: absolute;
    left: 0;
  }
  form {
    display: flex;
    flex-direction: column;
    gap: 15px;
  }
  input[type="text"], input[type="tel"] {
    padding: 12px 15px;
    border-radius: 6px;
    border: none;
    font-size: 1rem;
  }
  input[type="tel"] {
    font-family: 'Arial', sans-serif;
  }
  button {
    background: #26e07f;
    color: #000;
    border: none;
    padding: 15px;
    border-radius: 6px;
    font-weight: 700;
    font-size: 1.1rem;
    cursor: pointer;
    transition: background 0.3s ease;
  }
  button:hover {
    background: #1db75f;
  }
  .depoimentos, .faq {
    margin-top: 30px;
    font-size: 0.9rem;
  }
  .depoimentos p, .faq p {
    background: #202448;
    padding: 12px 15px;
    border-radius: 6px;
    margin-bottom: 10px;
  }
  footer {
    text-align: center;
    margin-top: 40px;
    font-size: 0.8rem;
    color: #444;
  }
</style>
</head>
<body>
<div class="container">
  <h1>GOG IPTV</h1>
  <p class="subtitle">Assista TV ao vivo, filmes, séries e esportes com IPTV e TV Box MXQ PRO ou Firestick!</p>
  <ul>
    <li>Mais de 5.000 canais nacionais e internacionais</li>
    <li>Suporta MXQ PRO, Firestick, Smart TV, celular e tablet</li>
    <li>Teste grátis por 24 horas sem compromisso</li>
    <li>Suporte técnico completo e instalação fácil</li>
    <li>Parcelamento no Pix e cartão de crédito</li>
  </ul>

  <form id="leadForm" action="https://formspree.io/f/{your_form_id}" method="POST">
    <input type="text" name="nome" placeholder="Seu nome completo" required />
    <input type="tel" name="whatsapp" placeholder="WhatsApp com DDD" required pattern="^\d{10,11}$" />
    <button type="submit">Quero testar grátis!</button>
  </form>

  <div class="depoimentos">
    <h3>O que dizem nossos clientes</h3>
    <p>"Excelente serviço, imagem perfeita e atendimento rápido!" - João S.</p>
    <p>"Comprei o Firestick junto com IPTV, vale cada centavo." - Marina T.</p>
  </div>

  <div class="faq">
    <h3>Dúvidas frequentes</h3>
    <p><b>Funciona na minha região?</b> Sim, atendimento para todo o Brasil.</p>
    <p><b>Preciso de internet rápida?</b> Recomendamos mínimo 10 Mbps para qualidade HD.</p>
    <p><b>É legal usar IPTV?</b> Nosso serviço possui canais autorizados e conteúdo legal.</p>
  </div>
</div>
<footer>© 2025 GOG IPTV - Todos os direitos reservados</footer>

<script>
  // Ajuste simples para enviar para WhatsApp via backend depois ou integração com CRM
  document.getElementById('leadForm').addEventListener('submit', function(e) {
    // Pode adicionar tracking, integração CRM aqui
  });
</script>
</body>
</html>
