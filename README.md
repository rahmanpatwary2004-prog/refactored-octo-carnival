<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <title>Bar Francesconi | Caffetteria e Bistrot, Firenze</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Bar Francesconi, fondato nel 2014, è un bistrot e caffetteria a Firenze. Offriamo colazione, pranzo, dessert e servizio al tavolo. Voto 4.3/5.">
    
    <style>
        :root {
            --primary-color: #007bff; /* Azzurro (Blue) */
            --secondary-color: #ffc107; /* Giallo/Oro (Gold) */
            --dark-text: #333;
            --light-bg: #f8f9fa;
        }
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            color: var(--dark-text);
            background-color: #fff;
            line-height: 1.6;
        }
        /* Header e Navigazione */
        header {
            background-color: var(--primary-color);
            color: white;
            padding: 20px 0;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        header h1 {
            font-size: 2.5em;
            margin-bottom: 5px;
            text-transform: uppercase;
        }
        header p {
            font-size: 1.1em;
            color: var(--secondary-color);
            margin: 0;
        }
        nav {
            background-color: #343a40;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        nav a {
            display: inline-block;
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-transform: uppercase;
            font-weight: bold;
            transition: background-color 0.3s;
        }
        nav a:hover {
            background-color: #495057;
        }

        /* Contenuto Principale */
        .container {
            max-width: 1000px;
            margin: 20px auto;
            padding: 0 15px;
        }
        section {
            padding: 40px 0;
            border-bottom: 1px solid #e9ecef;
        }
        h2 {
            text-align: center;
            color: var(--primary-color);
            margin-bottom: 30px;
            font-size: 2em;
            border-bottom: 3px solid var(--secondary-color);
            display: block;
            width: fit-content;
            margin-left: auto;
            margin-right: auto;
            padding-bottom: 5px;
        }
        
        /* Contatti e Orari */
        #contact-hours { background-color: var(--light-bg); text-align: center; }
        .info-grid { display: flex; justify-content: space-around; flex-wrap: wrap; margin-top: 20px; }
        .info-card { background: white; padding: 20px; margin: 10px; border-radius: 8px; box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1); width: 45%; min-width: 280px; }
        .info-card h3 { color: var(--primary-color); font-size: 1.3em; border-bottom: 2px solid #ccc; padding-bottom: 10px; margin-bottom: 15px; }
        .hour-item { display: flex; justify-content: space-between; margin-bottom: 5px; font-size: 1em; }
        .closed { color: #dc3545; font-weight: bold; }

        /* Servizi e Feature Grid */
        #features-services { padding: 40px 0; }
        .feature-grid { display: flex; flex-wrap: wrap; justify-content: space-around; text-align: left; margin-top: 20px; }
        .feature-box { background: #fff; border: 1px solid #eee; padding: 15px; margin: 10px; width: 45%; min-width: 250px; border-radius: 6px; box-shadow: 0 1px 3px rgba(0,0,0,0.05); }
        .feature-box h4 { color: var(--dark-text); margin-top: 0; border-bottom: 1px dashed #ddd; padding-bottom: 5px; }
        .feature-list { list-style: none; padding: 0; }
        .feature-list li { padding: 5px 0; display: flex; align-items: center; font-size: 0.95em; }
        .check { color: #28a745; font-weight: bold; margin-right: 8px; }

        /* Sezione Menu Specifiche */
        #menu .menu-section {
            background: var(--light-bg);
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.05);
            margin-top: 25px;
        }
        #menu .menu-section h3 {
            color: var(--primary-color); 
            text-align: center;
            margin-bottom: 15px;
        }
        #menu ul {
            list-style: none;
            padding: 0;
            margin: 0;
        }
        #menu ul li {
            background: #fff;
            padding: 10px 15px;
            margin-bottom: 8px;
            border-radius: 5px;
            display: flex;
            justify-content: space-between;
            font-size: 1.1em;
            border-left: 4px solid var(--secondary-color);
        }
        #menu ul li strong {
            color: var(--primary-color);
        }
        .rating {
            font-size: 1.1em;
            font-weight: bold;
            color: var(--secondary-color);
            margin-top: 10px;
        }
        
        /* Footer */
        footer {
            background-color: #343a40;
            color: white;
            text-align: center;
            padding: 20px 0;
            font-size: 0.9em;
        }
        
        /* Media Query per Mobile */
        @media (max-width: 600px) {
            header h1 { font-size: 2em; }
            nav a { padding: 10px 12px; font-size: 0.85em; }
            .info-card, .feature-box { width: 100%; } 
            .info-grid, .feature-grid { flex-direction: column; align-items: center; }
        }
    </style>
</head>
<body>

    <header>
        <h1>Bar Francesconi</h1>
        <p>Caffetteria & Bistrot | Firenze, Italia</p>
    </header>

    <nav>
        <a href="#about">Chi Siamo</a>
        <a href="#menu">Menu & Aggiornamenti</a>
        <a href="#features-services">Servizi</a>
        <a href="#contact-hours">Contatti & Orari</a>
    </nav>

    <div class="container">
        
        <section id="about">
            <h2 style="text-align: center;">Benvenuti al Bar Francesconi</h2>
            
            <div style="text-align: center; margin-bottom: 30px;">
                <img src="bar_francesconi_display.jpg" alt="Vista del bancone e dei prodotti freschi del Bar Francesconi" style="max-width: 100%; height: auto; border-radius: 8px; box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);">
            </div>
            <p style="text-align: center; font-size: 1.2em; font-weight: bold; color: var(--primary-color);">Fondata il 25 Marzo 2014 | Categoria: Caffetteria e Bistrot</p>
            <p>Siamo un accogliente bistrot situato in **Via del Ponte Sospeso 38R, Firenze**. Dal 2014, Bar Francesconi è il luogo ideale per la tua colazione, pranzo o una pausa caffè di alta qualità.</p>
            <p>Siamo molto orgogliosi della nostra valutazione di **4.3 su 5 stelle** e del **100% di raccomandazione** da parte dei clienti.</p>
            <div class="rating">⭐️⭐️⭐️⭐️ (4.3 / 5) | 100% Consigliato</div>
            <p>La nostra atmosfera è **casuale e tranquilla**, perfetta per gruppi o per chi pranza da solo.</p>
        </section>

        <section id="menu">
            <h2 style="text-align: center;">Menu, Offerte e Dettagli</h2>
            
            <div class="menu-section">
                <h3 style="color: #d9534f;">🍽️ Menù del Pranzo del Giorno (Aggiorna qui!)</h3>
                <p style="text-align: center; font-style: italic;">(Aggiornamento per Oggi: Lunedì, 15 Dicembre 2025)</p>
                <div style="max-width: 500px; margin: 0 auto;">
                    <ul id="daily-menu-list">
                        <li><span>Primo Piatto: Lasagne al Forno</span> <strong>€8.50</strong></li>
                        <li><span>Secondo Piatto: Pollo alla Cacciatora</span> <strong>€9.00</strong></li>
                        <li><span>Contorno: Insalata Mista Fresca</span> <strong>€4.00</strong></li>
                        <li><span>Dolce del Giorno: Tiramisù Classico</span> <strong>€4.50</strong></li>
                        </ul>
                </div>
                <p style="text-align: center; margin-top: 15px; color: #555;">**Fascia di Prezzo:** €1 – €10 (Molto Accessibile)</p>
            </div>

            <div class="menu-section" style="margin-top: 20px;">
                <h3 style="color: var(--primary-color);">🍴 Opzioni di Ristorazione & Offerte</h3>
                <ul style="max-width: 500px; margin: 0 auto;">
                    <li><span>Disponibile per:</span> <strong>Colazione, Pranzo, Dessert</strong></li>
                    <li><span>Servizio Offerto:</span> <strong>Servizio al Tavolo</strong></li>
                    <li><span>Offerte Principali:</span> <strong>Caffè, Aperitivi, Cibo Sano</strong></li>
                    <li><span>Bevande Alcoliche:</span> <strong>Birra, Cocktail, Vino, Liquori</strong> disponibili</li>
                </ul>
            </div>
        </section>
        
        <section id="features-services" style="background-color: var(--light-bg);">
            <h2 style="text-align: center;">Servizi e Funzionalità</h2>
            
            <div class="feature-grid">
                
                <div class="feature-box">
                    <h4>Opzioni di Servizio</h4>
                    <ul class="feature-list">
                        <li><span class="check">✔</span> Dine-in (Consumo in loco)</li>
                        <li><span class="check">✔</span> Takeaway (Da asporto)</li>
                        <li><span class="check">✔</span> Accetta Prenotazioni</li>
                    </ul>
                </div>

                <div class="feature-box">
                    <h4>Accessibilità & Pagamenti</h4>
                    <ul class="feature-list">
                        <li><span class="check">✔</span> Accessibile ai Disabili (Ingresso, Bagno, Posti)</li>
                        <li><span class="check">✔</span> Carte di Credito / Debito accettate</li>
                        <li><span class="check">✔</span> Pagamenti Mobile NFC</li>
                    </ul>
                </div>

                <div class="feature-box">
                    <h4>Comodità</h4>
                    <ul class="feature-list">
                        <li><span class="check">✔</span> Parcheggio gratuito in strada</li>
                        <li><span class="check">✔</span> Adatto ai Bambini</li>
                        <li><span class="check">✔</span> Cani Ammessi</li>
                        <li><span class="check">✔</span> Bar in loco / Toilette</li>
                    </ul>
                </div>
            </div>
        </section>


        <section id="contact-hours" style="border-bottom: none;">
            <h2 style="text-align: center;">Contatti e Orari di Apertura</h2>
            
            <div class="info-grid">
                
                <div class="info-card">
                    <h3>Contatti</h3>
                    <p><strong>Indirizzo:</strong> Via del Ponte Sospeso 38R, Firenze, Italia, 50142</p>
                    <p><strong>Telefono (Mobile):</strong> 055 700110</p>
                    <p><strong>Email:</strong> barfrancesconi@hotmail.it</p>
                    <a href="tel:055700110" style="display: block; margin-top: 10px; color: var(--primary-color); text-decoration: none;">☎️ Chiamaci Ora</a>
                </div>
                
                <div class="info-card">
                    <h3>Orari di Apertura</h3>
                    <div style="text-align: left; padding: 0 10px;">
                        <div class="hour-item"><span>Lunedì:</span><span>06:00 – 20:00</span></div>
                        <div class="hour-item"><span>Martedì:</span><span>06:00 – 20:00</span></div>
                        <div class="hour-item"><span>Mercoledì:</span><span>06:00 – 20:00</span></div>
                        <div class="hour-item"><span>Giovedì:</span><span>06:00 – 20:00</span></div>
                        <div class="hour-item"><span>Venerdì:</span><span>06:00 – 20:00</span></div>
                        <div class="hour-item"><span>Sabato:</span><span>06:00 – 20:00</span></div>
                        <div class="hour-item"><span style="font-weight: bold;">Domenica:</span><span class="closed">Chiuso</span></div>
                        <p style="margin-top: 15px;">**Nota:** Apre 06:00 e chiude 20:00.</p>
                    </div>
                </div>
                
            </div>
        </section>

    </div>

    <footer>
        <p>© 2025 Bar Francesconi, Firenze. Creato per fornire un servizio migliore.</p>
        <p>Data di Creazione: Marzo 25, 2014</p>
    </footer>

</body>
</html>
