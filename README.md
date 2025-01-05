<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MedSuit - Sklep z odzieżą medyczną</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Nagłówek -->
    <header>
        <nav>
            <ul>
                <li><a href="#home">Strona Główna</a></li>
                <li><a href="#shop">Sklep</a></li>
                <li><a href="#about">O Nas</a></li>
                <li><a href="#blog">Blog</a></li>
                <li><a href="#contact">Kontakt</a></li>
            </ul>
        </nav>
    </header>

    <!-- Strona Główna -->
    <section id="home">
        <h1>Witamy w MedSuit!</h1>
        <p>Profesjonalna odzież medyczna dla Ciebie.</p>
        <div class="hero-image">
            <img src="https://images.pexels.com/photos/4373527/pexels-photo-4373527.jpeg" alt="Odzież medyczna">
        </div>
        <a href="#shop" class="cta-button">Zobacz naszą ofertę</a>
    </section>

    <!-- Sklep -->
    <section id="shop">
        <h2>Sklep</h2>
        <div class="product">
            <img src="https://images.pexels.com/photos/4373527/pexels-photo-4373527.jpeg" alt="Produkt 1">
            <h3>Bluzka medyczna</h3>
            <p>Cena: 99 zł</p>
            <button>Dodaj do koszyka</button>
        </div>
        <div class="product">
            <img src="https://images.pexels.com/photos/4373528/pexels-photo-4373528.jpeg" alt="Produkt 2">
            <h3>Fartuch medyczny</h3>
            <p>Cena: 129 zł</p>
            <button>Dodaj do koszyka</button>
        </div>
        <!-- Dodaj inne produkty -->
    </section>

    <!-- O nas -->
    <section id="about">
        <h2>O nas</h2>
        <p>MedSuit to firma, która oferuje wygodną i funkcjonalną odzież medyczną, idealną do pracy w służbie zdrowia.</p>
        <div class="about-image">
            <img src="https://images.pexels.com/photos/4171732/pexels-photo-4171732.jpeg" alt="Nasza odzież medyczna">
        </div>
    </section>

    <!-- Blog -->
    <section id="blog">
        <h2>Blog</h2>
        <article class="blog-post">
            <h3>Jak wybrać odpowiednią odzież medyczną?</h3>
            <p>Wybór odpowiedniego stroju medycznego ma kluczowe znaczenie dla komfortu i efektywności pracy w służbie zdrowia...</p>
            <a href="#">Czytaj więcej</a>
        </article>
        <article class="blog-post">
            <h3>Dlaczego warto inwestować w profesjonalną odzież medyczną?</h3>
            <p>Odzież medyczna wysokiej jakości wpływa na wygodę, bezpieczeństwo oraz profesjonalny wizerunek pracowników medycznych...</p>
            <a href="#">Czytaj więcej</a>
        </article>
    </section>

    <!-- Formularz kontaktowy -->
    <section id="contact">
        <h2>Skontaktuj się z nami</h2>
        <form action="submit_form.php" method="POST">
            <label for="name">Imię:</label>
            <input type="text" id="name" name="name">
            
            <label for="email">E-mail:</label>
            <input type="email" id="email" name="email">

            <label for="message">Wiadomość:</label>
            <textarea id="message" name="message"></textarea>

            <button type="submit">Wyślij</button>
        </form>
        <a href="https://www.instagram.com/med_suit_pl" target="_blank">Nasze Instagram</a>
    </section>

    <footer>
        <p>&copy; 2025 MedSuit - Wszelkie prawa zastrzeżone</p>
    </footer>
</body>
</html>

/* Prosty CSS */
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f8f8f8;
}

header {
    background-color: #009688;
    color: white;
    padding: 10px 0;
    text-align: center;
}

header nav ul {
    list-style: none;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin: 0 15px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
}

section {
    padding: 20px;
    margin: 20px;
    background-color: white;
    border-radius: 8px;
}

.hero-image img {
    width: 100%;
    height: auto;
    border-radius: 8px;
}

.product img {
    width: 100%;
    height: auto;
    border-radius: 8px;
}

.about-image img {
    width: 100%;
    height: auto;
    border-radius: 8px;
}

.cta-button {
    background-color: #009688;
    color: white;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
    font-weight: bold;
}

.blog-post {
    background-color: #f0f0f0;
    padding: 15px;
    border-radius: 8px;
    margin-bottom: 20px;
}

.blog-post a {
    text-decoration: none;
    color: #009688;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}

/* Responsywność */
@media (max-width: 768px) {
    header nav ul li {
        display: block;
        margin: 10px 0;
    }

    .product, .blog-post {
        margin-bottom: 20px;
    }
}
