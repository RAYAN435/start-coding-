<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Start Coding</title>
    <style>
        /* Styles généraux */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(to right, #6a11cb, #2575fc);
            color: #fff;
        }
        header {
            text-align: center;
            padding: 80px 20px;
            background: rgba(0,0,0,0.3);
        }
        header h1 {
            font-size: 3em;
            margin-bottom: 20px;
        }
        header p {
            font-size: 1.3em;
            line-height: 1.5;
        }
        section {
            padding: 60px 20px;
            max-width: 1000px;
            margin: auto;
        }
        h2 {
            text-align: center;
            margin-bottom: 40px;
            font-size: 2.2em;
        }
        .card {
            background: rgba(255,255,255,0.1);
            padding: 20px;
            border-radius: 12px;
            margin-bottom: 20px;
        }
        .card:hover {
            background: rgba(255,255,255,0.2);
        }
        #interactive {
            text-align: center;
            margin-top: 40px;
        }
        input[type="text"] {
            padding: 10px;
            width: 300px;
            border-radius: 6px;
            border: none;
            margin-right: 10px;
        }
        button {
            padding: 10px 20px;
            border: none;
            border-radius: 6px;
            background-color: #ff7f50;
            color: white;
            font-size: 1em;
            cursor: pointer;
        }
        button:hover {
            background-color: #ff6347;
        }
        #response {
            margin-top: 20px;
            font-size: 1.2em;
        }
        footer {
            text-align: center;
            padding: 40px 20px;
            background: rgba(0,0,0,0.3);
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Start Coding</h1>
        <p>Transforme tes idées en projets concrets. Apprends à coder facilement, crée des applications, des sites web et bien plus encore. Ton aventure de développeur commence ici !</p>
    </header>

    <!-- À propos -->
    <section id="about">
        <h2>Pourquoi Start Coding ?</h2>
        <div class="card">
            <p>Que tu sois débutant ou passionné de technologie, Start Coding te guide pas à pas dans l’apprentissage du code. Découvre des langages comme HTML, CSS, JavaScript, Python et bien plus, à travers des tutoriels interactifs et des projets concrets.</p>
        </div>
        <div class="card">
            <p>Chaque exercice et projet est conçu pour te faire progresser rapidement, tout en gardant le plaisir d’apprendre. Rejoins une communauté dynamique et partage tes créations avec d’autres passionnés !</p>
        </div>
    </section>

    <!-- Projets et Défis -->
    <section id="projects">
        <h2>Projets et Défis</h2>
        <div class="card">
            <p>Crée ton premier site web en HTML/CSS</p>
        </div>
        <div class="card">
            <p>Développe une mini-application avec JavaScript</p>
        </div>
        <div class="card">
            <p>Automatise des tâches avec Python</p>
        </div>
    </section>

    <!-- Script interactif -->
    <section id="interactive">
        <h2>Parle avec Start Coding !</h2>
        <p>Écris ton prénom et découvre un message motivant :</p>
        <input type="text" id="name" placeholder="Ton prénom">
        <button onclick="respond()">Découvrir</button>
        <div id="response"></div>
    </section>

    <!-- Footer -->
    <footer>
        &copy; 2025 Start Coding. Tous droits réservés.
    </footer>

    <!-- Script JS -->
    <script>
        function respond() {
            const name = document.getElementById('name').value.trim();
            const response = document.getElementById('response');
            if(name === '') {
                response.textContent = "Entre ton prénom pour recevoir un message motivant !";
                return;
            }

            const messages = [
                Super, ${name} ! Aujourd'hui est le jour parfait pour coder ton premier projet !,
                ${name}, chaque ligne de code que tu écris te rapproche de tes rêves !,
                Allez ${name} ! Plonge dans le code et crée quelque chose d'incroyable !,
                Ton aventure commence maintenant, ${name}. Le monde du code t’attend !,
                Continue comme ça, ${name} ! Chaque erreur est une opportunité d’apprendre.
            ];

            const randomIndex = Math.floor(Math.random() * messages.length);
            response.textContent = messages[randomIndex];
        }
    </script>

</body>
</html>
