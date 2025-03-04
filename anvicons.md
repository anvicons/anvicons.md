<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ANVICONS - Demolări de orice tip</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px 0;
        }
        header h1 {
            margin: 0;
            font-size: 36px;
        }
        nav {
            background-color: #444;
            overflow: hidden;
        }
        nav a {
            color: white;
            text-align: center;
            padding: 14px 20px;
            display: inline-block;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        .section {
            padding: 20px;
            margin: 20px 0;
        }
        .section h2 {
            color: #333;
        }
        .services ul {
            list-style-type: none;
            padding: 0;
        }
        .services li {
            background-color: #e2e2e2;
            margin: 10px 0;
            padding: 10px;
            border-radius: 5px;
        }
        .gallery img {
            max-width: 100%;
            height: auto;
            display: block;
            margin: 10px 0;
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
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .contact-form button {
            background-color: #333;
            color: white;
            padding: 10px 15px;
            border: none;
            cursor: pointer;
            border-radius: 5px;
        }
        .contact-form button:hover {
            background-color: #555;
        }
    </style>
</head>
<body>

    <header>
        <h1>ANVICONS - Demolări de orice tip</h1>
    </header>

    <nav>
        <a href="#despre">Despre Noi</a>
        <a href="#servicii">Servicii</a>
        <a href="#proiecte">Proiecte Finalizate</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="despre" class="section">
        <h2>Cine Suntem</h2>
        <p>ANVICONS este o companie de încredere, specializată în demolări de orice tip. Oferim soluții eficiente și sigure pentru demolarea clădirilor rezidențiale, comerciale, industriale și a altor structuri complexe. Echipa noastră dispune de echipamente moderne și respectă toate reglementările de siguranță și protecția mediului.</p>
    </section>

    <section id="servicii" class="section services">
        <h2>Serviciile Noastre</h2>
        <ul>
            <li><strong>Demolări clădiri rezidențiale</strong> - Demolăm case și apartamente cu siguranță și rapiditate.</li>
            <li><strong>Demolări clădiri comerciale</strong> - Oferim soluții eficiente pentru demolarea spațiilor comerciale.</li>
            <li><strong>Demolări industriale</strong> - Specializați în demolarea fabricilor și depozitelor.</li>
            <li><strong>Demolări interioare</strong> - Îndepărtăm pereți, podele și alte structuri interioare.</li>
            <li><strong>Dărâmarea infrastructurilor</strong> - Demolăm drumuri, poduri și alte structuri de infrastructură.</li>
            <li><strong>Reciclarea materialelor</strong> - Procesăm și reciclăm materialele provenite din demolări.</li>
        </ul>
    </section>

    <section id="proiecte" class="section gallery">
        <h2>Proiecte Finalizate</h2>
        <p>În această secțiune, găsești câteva dintre proiectele noastre finalizate. Fiecare proiect reflectă angajamentul nostru pentru calitate și siguranță.</p>
        <img src="https://via.placeholder.com/600x400" alt="Proiect Demolare 1">
        <img src="https://via.placeholder.com/600x400" alt="Proiect Demolare 2">
        <img src="https://via.placeholder.com/600x400" alt="Proiect Demolare 3">
    </section>

    <section id="contact" class="section contact-form">
        <h2>Contactează-ne</h2>
        <p>Pentru mai multe informații sau pentru a solicita o ofertă personalizată, completează formularul de mai jos:</p>
        <form>
            <input type="text" name="nume" placeholder="Numele tău" required>
            <input type="email" name="email" placeholder="Email" required>
            <input type="tel" name="telefon" placeholder="Telefon" required>
            <textarea name="mesaj" rows="4" placeholder="Mesajul tău" required></textarea>
            <button type="submit">Trimite mesajul</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 ANVICONS. Toate drepturile rezervate.</p>
    </footer>

</body>
</html>
