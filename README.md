<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nexora - E-Commerce futuriste</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: linear-gradient(to bottom right, #000000, #0d0d0d);
            color: #ffffff;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
            overflow: hidden;
        }
        header {
            width: 100%;
            background: rgba(0, 0, 0, 0.8);
            padding: 1rem;
            text-align: center;
            position: fixed;
            top: 0;
        }
        header h1 {
            color: #00d4ff;
            font-size: 2.5rem;
            margin: 0;
        }
        .logo-container {
            text-align: center;
            margin: 6rem 0 2rem 0;
        }
        .logo-container img {
            max-width: 150px;
            height: auto;
        }
        .logo-container p {
            font-size: 1.2rem;
            margin-top: 1rem;
            color: #ccc;
        }
        main {
            padding-top: 6rem;
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 2rem;
        }
        .product {
            background: #1a1a1a;
            border-radius: 8px;
            padding: 1.5rem;
            text-align: center;
            width: 300px;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.5);
            transition: transform 0.3s, box-shadow 0.3s;
        }
        .product:hover {
            transform: translateY(-10px);
            box-shadow: 0px 8px 20px rgba(0, 0, 0, 0.8);
        }
        .product img {
            width: 100%;
            height: auto;
            border-radius: 4px;
        }
        .product h2 {
            margin: 1rem 0 0.5rem;
            font-size: 1.5rem;
            color: #00d4ff;
        }
        .product p {
            margin: 0.5rem 0;
            font-size: 1rem;
        }
        .product button {
            background: #00d4ff;
            color: #000;
            border: none;
            padding: 0.5rem 1rem;
            border-radius: 4px;
            cursor: pointer;
            transition: background 0.3s;
        }
        .product button:hover {
            background: #0088cc;
        }
        footer {
            width: 100%;
            background: rgba(0, 0, 0, 0.8);
            padding: 1rem;
            text-align: center;
            position: fixed;
            bottom: 0;
        }
        footer p {
            margin: 0;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bienvenue chez Nexora</h1>
    </header>
    <div class="logo-container">
        <img src="/mnt/data/logo.png" alt="Logo Nexora">
        <p>La technologie d'exception, où innovation et sérénité se rencontrent.</p>
    </div>
    <main>
        <!-- Produits ici -->
        <div class="product">
            <img src="https://via.placeholder.com/300" alt="Image du produit">
            <h2>Produit 1</h2>
            <p>Conception futuriste pour les besoins modernes.</p>
            <button>Ajouter au panier</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/300" alt="Image du produit">
            <h2>Produit 2</h2>
            <p>L'innovation haute technologie à son meilleur.</p>
            <button>Ajouter au panier</button>
        </div>
    </main>
    <footer>
        <p>© 2025 Nexora. Tous droits réservés.</p>
    </footer>
</body>
</html>
