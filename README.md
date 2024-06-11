<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mon Portfolio Futuriste</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #121212;
            color: #e0e0e0;
        }
        header {
            background: linear-gradient(90deg, #1f4037, #99f2c8);
            color: #fff;
            text-align: center;
            padding: 1em 0;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        .container {
            width: 90%;
            margin: 2em auto;
            max-width: 1200px;
        }
        .bio, .portfolio {
            background: rgba(255, 255, 255, 0.1);
            border-radius: 10px;
            padding: 1.5em;
            margin-bottom: 2em;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
        }
        .portfolio ul {
            list-style: none;
            padding: 0;
        }
        .portfolio li {
            background: rgba(0, 0, 0, 0.2);
            margin: 1em 0;
            padding: 1em;
            border-radius: 10px;
            transition: transform 0.3s, background 0.3s;
        }
        .portfolio li:hover {
            transform: scale(1.05);
            background: rgba(0, 0, 0, 0.3);
        }
        footer {
            text-align: center;
            padding: 1em 0;
            background: #1f1f1f;
            color: #aaa;
        }
        footer p {
            margin: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Mon Portfolio Futuriste</h1>
    </header>
    
    <div class="container">
        <section class="bio">
            <h2>À propos de moi</h2>
            <p>Je m'appelle [Ton Nom] et je suis passionné par la programmation. J'adore explorer les nouvelles technologies et créer des solutions innovantes pour résoudre des problèmes complexes. Voici quelques-uns des projets sur lesquels j'ai travaillé.</p>
        </section>

        <section class="portfolio">
            <h2>Mes Projets</h2>
            <ul>
                <li>
                    <h3>Projet 1 : [Nom du Projet]</h3>
                    <p>Description du projet 1, les technologies utilisées et les objectifs atteints.</p>
                </li>
                <li>
                    <h3>Projet 2 : [Nom du Projet]</h3>
                    <p>Descriptiondu projet 2, les technologies utilisées et les objectifs atteints.</p>
                </li>
                <li>
                    <h3>Projet 3 : [Nom du Projet]</h3>
                    <p>Description du projet 3, les technologies utilisées et les objectifs atteints.</p>
                </li>
            </ul>
        </section>
    </div>
    
    <footer>
        <p>&copy; 2024 [Ton Nom]. Tous droits réservés.</p>
    </footer>
</body>
</html>

