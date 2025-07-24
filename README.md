# vanit--site
<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profumeria Vanité</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500&family=Open+Sans&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            font-family: 'Open Sans', sans-serif;
            color: #333;
            background-color: #fffaf7;
        }

        header {
            background-color: #f5e6e0;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            font-family: 'Playfair Display', serif;
            font-size: 2.8em;
            margin: 0;
            color: #b06c6c;
        }

        nav {
            background-color: #fff0eb;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: #b06c6c;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        section {
            padding: 40px 20px;
            max-width: 1000px;
            margin: auto;
        }

        h2 {
            color: #b06c6c;
            font-family: 'Playfair Display', serif;
            margin-bottom: 20px;
        }

        .hero {
            background: url('https://images.unsplash.com/photo-1613046836513-c1d59c4f1f69?auto=format&fit=crop&w=1500&q=80') no-repeat center center;
            background-size: cover;
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-shadow: 1px 1px 4px #000;
            font-size: 2em;
        }

        .social-icons a {
            margin: 0 10px;
            text-decoration: none;
            color: #b06c6c;
            font-size: 1.4em;
        }

        footer {
            background-color: #f5e6e0;
            padding: 20px;
            text-align: center;
            font-size: 0.9em;
        }

        @media (max-width: 768px) {
            .hero {
                font-size: 1.5em;
                padding: 20px;
                text-align: center;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>Profumeria Vanité</h1>
        <p>Dove ogni fragranza racconta una storia</p>
    </header>

    <nav>
        <a href="#chisiamo">Chi Siamo</a>
        <a href="#arab">Profumi Arabi</a>
        <a href="#prodotti">Altri Prodotti</a>
        <a href="#contatti">Contatti</a>
    </nav>

    <div class="hero">
        Scopri il fascino delle fragranze orientali ✨
    </div>

    <section id="chisiamo">
        <h2>Chi Siamo</h2>
        <p>Benvenuti alla Profumeria Vanité! Un luogo dove il profumo diventa emozione, eleganza e carattere.  
        Selezioniamo solo le migliori fragranze e prodotti beauty per offrire ai nostri clienti un'esperienza unica. Vieni a trovarci e lasciati coccolare!</p>
    </section>

    <section id="arab">
        <h2>Profumi Arabi</h2>
        <p>Intensi, seducenti e indelebili. I profumi arabi sono l'ultima novità da Vanité!  
        Scopri le fragranze che raccontano storie di spezie, deserti dorati e notti d’Oriente.  
        Vieni in negozio per provarli: è amore al primo spruzzo!</p>
    </section>

    <section id="prodotti">
        <h2>Altri Prodotti</h2>
        <p>Oltre ai profumi arabi, da Vanité trovi una selezione esclusiva di:</p>
        <ul>
            <li>Profumi di marca: Dior, Chanel, Gucci e molti altri</li>
            <li>Make-up professionale</li>
            <li>Skincare e trattamenti di bellezza</li>
            <li>Accessori e idee regalo</li>
        </ul>
    </section>

    <section id="contatti">
        <h2>Contattaci</h2>
        <p><strong>📍 Indirizzo:</strong> Via Monaco 2</p>
        <p><strong>📞 Cellulare:</strong> <a href="tel:+393807964750">380 79 64 750</a></p>
        <p><strong>📷 Seguici sui social:</strong></p>
        <div class="social-icons">
            <a href="https://www.instagram.com" target="_blank">Instagram</a> |
            <a href="https://www.facebook.com" target="_blank">Facebook</a>
        </div>
        <p><strong>🕒 Orari:</strong> Lun–Sab: 9:00 – 19:30</p>

        <div style="margin-top: 20px;">
            <iframe src="https://maps.google.com/maps?q=via%20monaco%202&t=&z=15&ie=UTF8&iwloc=&output=embed" width="100%" height="300" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
        </div>
    </section>

    <footer>
        © 2025 Profumeria Vanité – Tutti i diritti riservati
    </footer>

</body>
</html>
