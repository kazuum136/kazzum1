# kazzum1
Kazuum est une marque de vêtements indépendante qui allie style et identité. Chaque pièce est pensée pour affirmer ta singularité.
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Kazuum - Marque de vêtements</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Arial', sans-serif;
    }

    body {
      background-color: #fff;
      color: #111;
      line-height: 1.6;
    }

    header {
      background-color: #000;
      color: #fff;
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
    }

    header h1 {
      font-size: 28px;
      letter-spacing: 2px;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      margin-left: 20px;
      font-weight: bold;
    }

    section {
      padding: 80px 40px;
    }

    #accueil {
      background: #f5f5f5;
      text-align: center;
    }

    #accueil h2 {
      font-size: 36px;
      margin-bottom: 20px;
    }

    #accueil p {
      font-size: 18px;
      margin-bottom: 30px;
    }

    #accueil a {
      display: inline-block;
      background: #000;
      color: #fff;
      padding: 12px 24px;
      text-decoration: none;
      border-radius: 4px;
    }

    #produits {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .produit {
      border: 1px solid #ccc;
      padding: 20px;
      text-align: center;
    }

    .produit img {
      width: 100%;
      height: auto;
      margin-bottom: 10px;
    }

    form {
      max-width: 500px;
      margin: auto;
      display: flex;
      flex-direction: column;
    }

    form input,
    form textarea {
      padding: 12px;
      margin: 10px 0;
      border: 1px solid #ccc;
      border-radius: 4px;
    }

    form button {
      background: #000;
      color: #fff;
      padding: 12px;
      border: none;
      cursor: pointer;
    }

    footer {
      background: #000;
      color: #fff;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Kazuum</h1>
    <nav>
      <a href="#accueil">Accueil</a>
      <a href="#apropos">À propos</a>
      <a href="#produits">Produits</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="accueil">
    <h2>Bienvenue chez Kazuum</h2>
    <p>Exprime ton style avec notre collection de vêtements uniques.</p>
    <a href="#produits">Voir nos produits</a>
  </section>

  <section id="apropos">
    <h2>À propos de Kazuum</h2>
    <p>Kazuum est une marque de vêtements indépendante qui allie style et identité. Chaque pièce est pensée pour affirmer ta singularité.</p>
  </section>

  <section id="produits">
    <h2>Nos Produits</h2>
    <div class="produit">
      <img src="https://via.placeholder.com/300x400" alt="Produit 1">
      <h3>T-shirt Kazuum</h3>
      <p>non Disponible.</p>
    </div>
    <div class="produit">
      <img src="https://via.placeholder.com/300x400" alt="Produit 2">
      <h3>sweat Kazuum</h3>
      <p>non Disponible.</p>
    </div>
    <div class="produit">
      <img src="https://via.placeholder.com/300x400" alt="Produit 3">
      <h3>Casquette Kazuum</h3>
      <p>non Disponible.</p>
    </div>
  </section>

  <section id="contact">
    <h2>Contacte-nous</h2>
    <form action="https://formspree.io/f/xzzvkdql" method="POST">
      <input type="hidden" name="_subject" value="Message du site Kazuum" />
      <input type="text" name="name" placeholder="Ton nom" required />
      <input type="email" name="email" placeholder="Ton e‑mail" required />
      <textarea name="message" rows="5" placeholder="Ton message" required></textarea>
      <button type="submit">Envoyer</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Kazuum. Tous droits réservés.</p>
  </footer>

</body>
</html>
