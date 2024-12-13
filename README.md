<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Pâtisserie artisanale Mister Cake - Gâteaux & Macarons faits maison.">
    <title>Mister Cake - Gâteaux & Macarons</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        header {
            background-color: #ff6f61; /* Un rouge doux pour attirer l'attention */
            padding: 20px 0;
            text-align: center;
            color: #fff;
        }
        header h1 {
            margin: 0;
            font-size: 3rem;
            letter-spacing: 2px;
        }
        header nav {
            margin-top: 10px;
        }
        header nav a {
            color: #fff;
            text-decoration: none;
            padding: 10px 20px;
            margin: 0 15px;
            background-color: #ff9a8b;
            border-radius: 5px;
            font-weight: bold;
        }
        header nav a:hover {
            background-color: #ff6f61;
        }
        section {
            padding: 40px 20px;
            text-align: center;
        }
        .gallery {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }
        .gallery img {
            width: 300px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .product {
            display: inline-block;
            text-align: left;
            margin: 20px;
            width: calc(33% - 40px);
            background-color: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .product h3 {
            font-size: 1.5rem;
            margin-top: 0;
            color: #ff6f61;
        }
        .product p {
            font-size: 1rem;
        }
        .product strong {
            color: #ff6f61;
        }
        .contact {
            background-color: #ff9a8b;
            padding: 40px;
            color: #fff;
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #333;
            color: #fff;
        }
    </style>
</head>
<body>

<header>
    <h1>Mister Cake</h1>
    <nav>
        <a href="#presentation">Présentation</a>
        <a href="#menu">Menu</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section id="presentation">
    <h2>Bienvenue chez Mister Cake !</h2>
    <p>Découvrez l'univers sucré de Mister Cake : des gâteaux gourmands et des macarons irrésistibles, faits maison avec des ingrédients de qualité. Chaque création est une véritable œuvre d'art qui ravira vos papilles.</p>
</section>

<section id="gallery">
    <h2>Nos Délices</h2>
    <div class="gallery">
        <img src="https://via.placeholder.com/300x200?text=Gâteau+Chocolat" alt="Gâteau au Chocolat">
        <img src="https://via.placeholder.com/300x200?text=Macaron+Vanille" alt="Macaron à la Vanille">
        <img src="https://via.placeholder.com/300x200?text=Gâteau+Fraisier" alt="Gâteau Fraisier">
    </div>
</section>

<section id="menu">
    <h2>Nos Produits</h2>
    <div class="product">
        <h3>Gâteau au Chocolat</h3>
        <p>Un gâteau moelleux au chocolat, garni de ganache fondante. L'indispensable pour tous les amoureux du chocolat.</p>
        <p><strong>Prix : 20€</strong></p>
    </div>
    <div class="product">
        <h3>Macarons à la Vanille</h3>
        <p>Des macarons légers et croquants à l'extérieur, avec une ganache à la vanille parfaitement parfumée.</p>
        <p><strong>Prix : 12€ (6 macarons)</strong></p>
    </div>
    <div class="product">
        <h3>Gâteau Fraisier</h3>
        <p>Un gâteau frais et fruité, avec des fraises juteuses et une crème légère à la vanille. Le choix parfait pour l'été !</p>
        <p><strong>Prix : 25€</strong></p>
    </div>
</section>

<section id="contact" class="contact">
    <h2>Passer Commande ou Nous Contacter</h2>
    <p>Vous souhaitez un gâteau personnalisé ou passer commande pour un événement spécial ? Contactez-nous directement par téléphone ou email.</p>
    <p><strong>Téléphone : +221 777 037 546</strong></p>
    <p><strong>Email : contact@mistercake.com</strong></p>
    <p>Adresse : Malika Plage, Dakar, Sénégal</p>
    <p>Suivez-nous sur TikTok : <strong>@chefAbou</strong></p>
</section>

<footer>
    <p>&copy; 2024 Mister Cake - Tous droits réservés</p>
</footer>

</body>
</html>
