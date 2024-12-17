---
layout: standalone
title: "Merci"
author: "Guillaume"
last_modified_at: 2024-11-06T21:00:52-05:00
sitemap: false
---
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>{{ page.title }}</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
      background: url('/images/Brise-tes-chaines_edited.jpg') no-repeat center center fixed;
      background-size: cover;
      color: #fff;
    }
    .content-container {
      position: relative;
      max-width: 800px;
      margin: 0 auto;
      padding: 20px;
      background-color: rgba(0, 0, 0, 0.7);
      border-radius: 10px;
      text-align: center;
    }
    h1 {
      font-size: 2.5em;
      margin-bottom: 20px;
    }
    h3 {
      font-size: 1.5em;
      margin: 20px 0;
    }
    p {
      font-size: 1.2em;
      line-height: 1.5;
    }
    button {
      font-size: 1.2em;
      color: #fff;
      background-color: #5cb85c;
      border: none;
      border-radius: 5px;
      padding: 10px 20px;
      cursor: pointer;
      margin-top: 20px;
    }
    button:hover {
      background-color: #4cae4c;
    }
    .email-check {
      margin-top: 30px;
      font-size: 1.2em;
      color: #ffdf00;
    }
  </style>
  {% include head-custom.html %}
</head>
<body>
  <div class="content-container">
    <h1>Merci et Bravo pour votre décision !</h1>
    <p>Vous avez fait un grand pas aujourd’hui pour reprendre le contrôle de votre vie. Nous sommes ravis de vous accompagner dans cette transformation.</p>
    <p class="email-check">📩 <strong>Vérifiez vos emails</strong> pour confirmer votre inscription et accéder à votre contenu gratuit !</p>
    <h3>Rejoignez également notre communauté bienveillante et discrète</h3>
    <p>Accédez à un espace d'entraide avec des ressources exclusives et des échanges enrichissants pour avancer ensemble.</p>
    <button onclick="window.location.href='https://www.facebook.com/groups/lapresliaison'">
      👉 Rejoignez la Communauté
    </button>
    <p>Merci de nous faire confiance. Nous sommes là pour vous soutenir à chaque étape.</p>
  </div>
</body>


