<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>La Sirène Cookie Shop</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #ffe6eb;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #f8c6d8;
            text-align: center;
            padding: 20px;
        }
        header img {
            width: 200px;
        }
        h1 {
            color: #d63384;
        }
        p {
            text-align: center;
            color: #555;
            font-size: 18px;
            margin: 20px;
        }
        .section {
            padding: 20px;
            text-align: center;
        }
        ol, ul {
            text-align: left;
            display: inline-block;
            margin: 20px auto;
        }
        img.cookie-img {
            width: 250px;
            margin-top: 20px;
            border-radius: 15px;
            transition: transform 0.3s ease;
        }
        img.cookie-img:hover {
            transform: scale(1.05);
        }
        a {
            color: #d63384;
            text-decoration: none;
            font-weight: bold;
        }
        a:hover {
            text-decoration: underline;
        }
        .contact-form {
            background-color: #fff;
            padding: 20px;
            border-radius: 10px;
            width: 300px;
            margin: 30px auto;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        input, button {
            width: 90%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        button {
            background-color: #d63384;
            color: white;
            border: none;
            cursor: pointer;
        }
        button:hover {
            background-color: #b0246d;
        }
        footer {
            background-color: #f8c6d8;
            text-align: center;
            padding: 10px;
            font-size: 14px;
            margin-top: 30px;
        }
        hr {
            border: none;
            border-top: 2px solid #d63384;
            margin: 20px auto;
            width: 80%;
        }
        span {
            color: #d63384;
            font-weight: bold;
        }
        /* Nouveau bouton commander */
        .order-button {
            display: inline-block;
            background-color: #d63384;
            color: white;
            padding: 12px 20px;
            margin: 20px 0;
            border-radius: 25px;
            font-size: 16px;
            transition: background-color 0.3s ease, transform 0.3s ease;
            text-decoration: none;
        }
        .order-button:hover {
            background-color: #b0246d;
            transform: scale(1.05);
        }
        /* Responsive Design */
        @media (max-width: 768px) {
            header img {
                width: 150px;
            }
            .contact-form, ol, ul {
                width: 90%;
            }
            .cookie-img {
                width: 90%;
            }
        }
    </style>
</head>
<body>

    <header>
        <img src="New design logo la sirene (5).png" alt="La Sirène Cookie Shop">
    </header>

    <p>Bienvenue chez <span>La Sirène Cookie Shop</span> ! Les cookies les plus délicieux de Sousse 🍪✨</p>

    <hr>

    <div class="section">
        <h1>Nos Délices</h1>
        <ol>
            <li>Cookies au chocolat</li>
            <li>Cookies aux fraises</li>
            <li>Cookies spéciaux Sirène</li>
        </ol>

        <h2>Autres Gourmandises</h2>
        <ul>
            <li>Boules de chocolat</li>
            <li>Mini cupcakes</li>
            <li>Fraises enrobées</li>
        </ul>

        <img src="https://via.placeholder.com/250" alt="Cookies délicieux" class="cookie-img">

        <br>

        <a href="https://www.instagram.com/la.sirene.cookie.shop" class="order-button" target="_blank">Commander Maintenant</a>

        <p><a href="https://www.instagram.com/la.sirene.cookie.shop" target="_blank">Découvrez notre Instagram !</a></p>
    </div>

    <hr>

    <div class="contact-form">
        <h2>Contactez-Nous</h2>
        <form action="#" method="post">
            <input type="text" name="nom" placeholder="Votre nom" required>
            <input type="email" name="email" placeholder="Votre email" required>
            <button type="submit">Envoyer</button>
        </form>
    </div>

    <footer>
        © 2025 La Sirène Cookie Shop | Cité Taamir, Sousse | 📞 22 065 148
    </footer>

</body>
</html>
**
