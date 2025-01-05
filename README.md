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
                <li><a href="#contact">Kontakt</a></li>
            </ul>
        </nav>
    </header>

    <!-- Sekcja główna -->
    <section id="home">
        <h1>Witamy w MedSuit!</h1>
        <p>Profesjonalna odzież medyczna dla Ciebie.</p>
        <a href="#shop">Zobacz naszą ofertę</a>
    </section>

    <!-- Sklep -->
    <section id="shop">
        <h2>Sklep</h2>
        <div class="product">
            <img src="path_to_product_image.jpg" alt="Produkt">
            <h3>Bluzka medyczna</h3>
            <p>Cena: 99 zł</p>
            <button>Dodaj do koszyka</button>
        </div>
        <!-- Dodaj inne produkty -->
    </section>

    <!-- O nas -->
    <section id="about">
        <h2>O nas</h2>
        <p>MedSuit to firma, która oferuje wygodną i funkcjonalną odzież medyczną, idealną do pracy w służbie zdrowia.</p>
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
