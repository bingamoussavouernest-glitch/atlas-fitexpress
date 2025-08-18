# atlas-fitexpress
Tunnel de vente Fit Express - ATLAS FORMATION 
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Programme FitExpress - ATLAS FORMATION</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f5f5f5;
      color: #333;
    }
    header {
      background: #1e3c72;
      background: linear-gradient(to right, #2a5298, #1e3c72);
      color: white;
      text-align: center;
      padding: 20px;
    }
    header img {
      max-height: 60px;
      margin-bottom: 10px;
    }
    h1 {
      margin: 10px 0;
    }
    .container {
      max-width: 900px;
      margin: 40px auto;
      padding: 20px;
      background: white;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    }
    .price {
      font-size: 22px;
      font-weight: bold;
      color: #2a5298;
      margin: 15px 0;
    }
    form {
      margin-top: 20px;
      display: flex;
      flex-direction: column;
      gap: 12px;
    }
    input, button {
      padding: 12px;
      font-size: 16px;
      border-radius: 8px;
      border: 1px solid #ccc;
    }
    button {
      background: #2a5298;
      color: white;
      border: none;
      cursor: pointer;
    }
    button:hover {
      background: #1e3c72;
    }
    .btn-whatsapp {
      display: block;
      text-align: center;
      margin-top: 20px;
      padding: 12px;
      background: #25D366;
      color: white;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
    }
  </style>
</head>
<body>

  <header>
    <!-- Mets ici ton logo -->
    <img src="logo.png" alt="Logo ATLAS FORMATION">
    <h1>Programme FitExpress</h1>
    <p>Par ATLAS FORMATION</p>
  </header>

  <div class="container">
    <h2>Rejoignez le Programme FitExpress</h2>
    <p>Un programme conçu pour les personnes au rythme effréné qui veulent rester en forme sans perdre de temps.</p>
    
    <p class="price">Prix : 20 000 FCFA</p>

    <form action="https://formspree.io/f/mwkzjzno" method="POST">
      <input type="text" name="prenom" placeholder="Prénom" required>
      <input type="text" name="nom" placeholder="Nom" required>
      <input type="email" name="email" placeholder="Email" required>
      <input type="tel" name="telephone" placeholder="Téléphone" required>
      <button type="submit">Je m'inscris</button>
    </form>

    <a class="btn-whatsapp" 
       href="https://wa.me/242065814431?text=Bonjour%2C%20je%20veux%20m%27inscrire%20au%20Programme%20FitExpress" 
       target="_blank">
       📲 Rejoignez-nous sur WhatsApp
    </a>
  </div>

</body>
</html>
