<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ChillOwl - Il Tuo Hub per la Gestione del Tempo</title>
    <style>
        /* Stili CSS per il layout */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            color: #333;
            line-height: 1.6;
        }
        header {
            background-color: #d4a34e; /* Giallo ocra */
            color: white;
            padding: 20px;
            text-align: center;
            position: relative;
            margin-bottom: 20px;
        }
        header h1 {
            margin-bottom: 10px;
            font-size: 2em;
        }
        header p {
            font-size: 1.2em;
        }
        header a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s;
        }
        header a:hover {
            color: #e0b456; /* Giallo chiaro */
        }
        nav {
            background-color: #8b5d2e; /* Marrone scuro */
            color: white;
            padding: 10px;
            text-align: center;
            margin-bottom: 20px;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 10px;
            font-weight: bold;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #e0b456; /* Giallo chiaro */
        }
        section {
            padding: 20px;
            margin: 20px;
            background-color: #fff;
            border-radius: 5px;
            box-shadow: 0px 0px 10px 0px rgba(0,0,0,0.1); /* Ombra leggera */
        }
        section h2 {
            margin-bottom: 15px;
            color: #d4a34e; /* Giallo ocra */
        }
        section p {
            margin-bottom: 15px;
        }
        section ul {
            list-style-type: none;
            padding: 0;
        }
        section ul li {
            margin-bottom: 10px;
            padding-left: 20px;
            position: relative;
        }
        section ul li:before {
            content: "\2022"; /* Aggiungi il carattere del bullet */
            color: #d4a34e; /* Giallo ocra */
            font-size: 1.2em;
            position: absolute;
            left: 0;
        }
        footer {
            background-color: #8b5d2e; /* Marrone scuro */
            color: white;
            text-align: center;
            padding: 10px;
        }
        footer p {
            margin: 5px 0;
        }
        .advertisement {
            text-align: center;
            background-color: #f9f9f9;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 5px;
        }
        .advertisement img {
            max-width: 100%;
            border-radius: 5px;
            box-shadow: 0px 0px 10px 0px rgba(0,0,0,0.1); /* Ombra leggera */
        }
    </style>
</head>
<body>
    <header>
        <h1 id="headerText">Benvenuto su ChillOwl</h1>
        <p>Il Tuo Hub per la Gestione del Tempo</p>
        <a href="https://discord.gg/VmrRC5V2" target="_blank">Unisciti al nostro Discord</a>
    </header>
    <nav>
        <a href="#about">Informazioni</a>
        <a href="#tips">Consigli</a>
        <a href="#advertise">Pubblicità</a>
        <a href="#contact">Contatti</a>
    </nav>
    <section id="about">
        <h2>Informazioni su ChillOwl</h2>
        <p>ChillOwl è il tuo spazio sicuro per scambiare consigli e suggerimenti sulla gestione del tempo e delle routine quotidiane.</p>
        <p>Unisciti al nostro canale Discord per connetterti con persone simili a te e migliorare le tue abilità nella gestione del tempo!</p>
    </section>
    <section id="tips">
        <h2>Consigli sulla Gestione del Tempo</h2>
        <p>Ecco alcuni suggerimenti utili per ottimizzare la tua routine giornaliera:</p>
        <ul>
            <li>Imposta obiettivi specifici per ogni giorno</li>
            <li>Classifica le attività in base all'importanza e all'urgenza</li>
            <li>Fai delle pause regolari per evitare il burnout</li>
            <li>Utilizza strumenti e tecniche di gestione del tempo</li>
            <li>Mantieni l'organizzazione e ordina il tuo spazio di lavoro</li>
        </ul>
    </section>
    <section id="advertise">
        <h2>Pubblicità su ChillOwl</h2>
        <div class="advertisement">
            <h3>Pubblicità</h3>
            <p>Spazio pubblicitario disponibile! Contattaci per promuovere il tuo prodotto o servizio.</p>
            <img src="https://via.placeholder.com/400x200" alt="Pubblicità">
        </div>
    </section>
    <section id="contact">
        <h2>Contatti</h2>
        <p>Hai domande o suggerimenti? Contattaci!</p>
        <p>Email: <span id="email">infochillowlspace@gmail.com</span></p>
        <p>Telefono: <span id="phoneNumber">3923740588</span></p>
    </section>
    <footer>
        <p>&copy; 2024 ChillOwl. Tutti i diritti riservati. - Contatti: <span id="footerEmail">infochillowlspace@gmail.com</span> | Tel: <span id="footerPhoneNumber">3923740588</span></p>
    </footer>

    <script>
        // Aggiungere qui gli script JavaScript

        // Cambia il numero di telefono casualmente
        const phoneNumber = document.getElementById("phoneNumber");
        const footerPhoneNumber = document.getElementById("footerPhoneNumber");
        phoneNumber.textContent = "3923740588";
        footerPhoneNumber.textContent = "3923740588";

        // Cambia l'email casualmente
        const email = document.getElementById("email");
        const footerEmail = document.getElementById("footerEmail");
        email.textContent = "infochillowlspace@gmail.com";
        footerEmail.textContent = "infochillowlspace@gmail.com";
    </script>
</body>
</html>
