# faq-rh
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Perguntas de Recursos Humanos</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f4f7fb;
      margin: 0;
      padding: 0;
      color: #333;
    }
    header {
      background: #2b6cb0;
      color: #fff;
      padding: 20px;
      text-align: center;
      font-size: 24px;
      font-weight: bold;
    }
    .container {
      max-width: 900px;
      margin: 20px auto;
      padding: 20px;
      background: #fff;
      border-radius: 12px;
      box-shadow: 0 3px 10px rgba(0,0,0,0.1);
    }
    h2 {
      color: #2b6cb0;
    }
    .faq {
      margin-top: 20px;
    }
    .faq-item {
      background: #e9f1ff;
      padding: 15px;
      border-radius: 10px;
      margin-bottom: 10px;
      cursor: pointer;
      border-left: 5px solid #2b6cb0;
    }
    .faq-item:hover {
      background: #dce9ff;
    }
    .answer {
      display: none;
      padding: 10px 15px;
      background: #f8faff;
      border-radius: 8px;
      margin-top: 8px;
      border-left: 4px solid #4a90e2;
    }
  </style>
</head>
<body>
  <header>
    Perguntas Frequentes de Recursos Humanos
  </header>

  <div class="container">
    <h2>FAQ – Dúvidas Comuns</h2>
    <p>Clique em uma pergunta para visualizar a resposta.</p>

    <div class="faq">

      <div class="faq-item" onclick="toggleAnswer(1)">
        📌 Como envio meu currículo?
      </div>
      <div class="answer" id="answer1">
        Você pode enviar seu currículo pelo e-mail oficial do RH ou pelo formulário disponível no site da empresa.
      </div>

      <div class="faq-item" onclick="toggleAnswer(2)">
        📌 Como acompanho meu processo seletivo?
      </div>
      <div class="answer" id="answer2">
        O acompanhamento pode ser feito via WhatsApp automático, e-mail ou pelo portal do candidato.
      </div>

    </div>
  </div>

  <script>
    function toggleAnswer(id) {
      const answer = document.getElementById("answer" + id);
      answer.style.display = answer.style.display === "block" ? "none" : "block";
    }
  </script>
</body>
</html>
