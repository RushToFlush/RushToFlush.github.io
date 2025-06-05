<!DOCTYPE html>
<html lang="sv">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pennbutiken</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f2f2f2;
    }
    header {
      background: #005eb8;
      color: white;
      padding: 1rem 2rem;
      text-align: center;
    }
    .products {
      display: flex;
      justify-content: center;
      gap: 2rem;
      margin: 2rem;
      flex-wrap: wrap;
    }
    .product {
      background: white;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      padding: 1rem;
      max-width: 220px;
      text-align: center;
    }
    .product img {
      max-width: 100px;
      margin-bottom: 1rem;
    }
    footer {
      background: #005eb8;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
    .contact {
      text-align: center;
      margin: 2rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Välkommen till Pennbutiken!</h1>
    <p>De bästa pennorna för alla tillfällen</p>
  </header>

  <div class="products">
    <div class="product">
      <img src="https://images.unsplash.com/photo-1515378791036-0648a3ef77b2?auto=format&fit=crop&w=400&q=80" alt="Blå penna">
      <h2>Blå Kulspetspenna</h2>
      <p>Pris: 10 kr</p>
    </div>
    <div class="product">
      <img src="https://images.unsplash.com/photo-1512314889357-e157c22f938d?auto=format&fit=crop&w=400&q=80" alt="Röd penna">
      <h2>Röd Gelpenna</h2>
      <p>Pris: 15 kr</p>
    </div>
    <div class="product">
      <img src="https://images.unsplash.com/photo-1519125323398-675f0ddb6308?auto=format&fit=crop&w=400&q=80" alt="Svart penna">
      <h2>Svart Fineliner</h2>
      <p>Pris: 20 kr</p>
    </div>
  </div>

  <div class="contact">
    <h2>Kontakta oss</h2>
    <p>Mejla: info@pennbutiken.se</p>
  </div>

  <footer>
  
    &copy; 2025 Pennbutiken
  </footer>
</body>
</html>
