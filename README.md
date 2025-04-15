<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cabinet de Gestion de Copropriété Lynco Propriété</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #c0392b;
            color: white;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        section {
            padding: 40px 10%;
            background: url('https://cdn.pixabay.com/photo/2016/11/29/05/08/architecture-1867187_1280.jpg') no-repeat center center;
            background-size: cover;
            color: #000;
            text-align: center;
        }
        h2 {
            color: #c0392b;
        }
        .services {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            margin-top: 40px;
        }
        .service {
            background-color: rgba(253, 222, 222, 0.9);
            padding: 20px;
            width: 30%;
            margin: 10px;
            border-radius: 8px;
        }
        footer {
            background-color: #c0392b;
            color: white;
            text-align: center;
            padding: 20px;
        }
        .cta {
            background-color: #e74c3c;
            color: white;
            padding: 15px;
            font-size: 18px;
            border: none;
            cursor: pointer;
            border-radius: 5px;
            margin-top: 30px;
        }
        .cta:hover {
            background-color: #a93226;
        }
        form {
            margin-top: 40px;
            text-align: left;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
            background-color: rgba(255,255,255,0.9);
            padding: 20px;
            border-radius: 8px;
        }
        input, textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        button[type="submit"] {
            background-color: #e74c3c;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button[type="submit"]:hover {
            background-color: #c0392b;
        }
    </style>
</head>
<body>

<header>
    <h1>Cabinet de Gestion de Copropriété Lynco Propriété</h1>
    <p>Nous facilitons la gestion de votre patrimoine immobilier à Djibouti.</p>
</header>

<section>
    <h2>Nos Services</h2>
    <div class="services">
        <div class="service">
            <h3>Gestion Administrative</h3>
            <p>Rédaction des procès-verbaux, préparation des assemblées générales et gestion des contrats.</p>
        </div>
        <div class="service">
            <h3>Gestion Financière</h3>
            <p>Suivi des charges de copropriété, collecte des paiements, gestion des comptes bancaires.</p>
        </div>
        <div class="service">
            <h3>Maintenance et Entretien</h3>
            <p>Coordination des réparations et entretien des parties communes pour assurer le bon état de l'immeuble.</p>
        </div>
    </div>

    <h2>Pourquoi Choisir Notre Cabinet ?</h2>
    <p><strong>Professionnalisme, transparence, réactivité et expertise locale.</strong> Nous sommes dédiés à une gestion efficace de votre copropriété.</p>

    <button class="cta">Contactez-nous dès maintenant !</button>

    <form action="#" method="post">
        <h2>Demande de Tarifs</h2>
        <p>Remplissez ce formulaire pour recevoir nos tarifs personnalisés selon vos besoins.</p>

        <label for="nom">Nom :</label>
        <input type="text" id="nom" name="nom" required>

        <label for="email">Email :</label>
        <input type="email" id="email" name="email" required>

        <label for="message">Détaillez votre demande :</label>
        <textarea id="message" name="message" rows="5" placeholder="Ex. Nombre d'immeubles, nombre de lots, services souhaités..." required></textarea>

        <button type="submit">Demander un devis</button>
    </form>
</section>

<footer>
    <p>&copy; 2025 Lynco Propriété. Tous droits réservés.</p>
    <p>Téléphone : +253 77844613 | Email : cabinet@lyncopropriete.com</p>
</footer>

</body>
</html>
