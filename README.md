<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FLEA World</title>
    <style>
        body {
            font-family: 'Calibri', sans-serif;
            background-color: #E0F7FA; /* bleu ciel clair */
            color: #333333; /* gris foncé */
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #B2EBF2; /* bleu ciel */
            padding: 20px;
            text-align: center;
            position: relative;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        header h1 {
            margin: 0;
            color: #00838F; /* bleu foncé */
            font-size: 2.5em;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #4DD0E1; /* bleu ciel moyen */
            padding: 10px;
        }
        nav a {
            color: #FFF;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }
        .container {
            padding: 20px;
            position: relative;
        }
        .section {
            margin-bottom: 30px;
        }
        .section h2 {
            color: #00838F;
            border-bottom: 2px solid #00838F;
            padding-bottom: 10px;
        }
        .blog, .forum {
            background-color: #FFF;
            padding: 20px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        footer {
            background-color: #333;
            color: #FFF;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .decorations {
            position: absolute;
            width: 30px;
            height: 30px;
        }
        .flower { top: 10px; left: 10px; }
        .butterfly { top: 10px; right: 10px; }
        .book { bottom: 20px; left: 20px; }
        .pencil { bottom: 20px; right: 20px; }
        .star { top: 50%; left: 50%; transform: translate(-50%, -50%); }
    </style>
</head>
<body>
    <header>
        <h1>FLEA World</h1>
        <img src="https://www.svgrepo.com/show/276918/flower.svg" alt="Flower" class="decorations flower">
        <img src="https://www.svgrepo.com/show/276765/butterfly.svg" alt="Butterfly" class="decorations butterfly">
    </header>
    <nav>
        <a href="#hobbies">Hobbies</a>
        <a href="#blog">Blog</a>
        <a href="#forum">Forum</a>
    </nav>
    <div class="container">
        <img src="https://www.svgrepo.com/show/354070/book.svg" alt="Book" class="decorations book">
        <img src="https://www.svgrepo.com/show/354090/pencil.svg" alt="Pencil" class="decorations pencil">
        <img src="https://www.svgrepo.com/show/275656/star.svg" alt="Star" class="decorations star">
        <section id="hobbies" class="section">
            <h2>Mes Passions</h2>
            <p>Plongée dans l'univers de la mode, la musique et la poésie, je trouve mon équilibre à travers ces passions. J'aime suivre les dernières tendances, découvrir de nouveaux sons et composer mes propres poèmes. Le bien-être et la confiance en soi sont des sujets qui me tiennent particulièrement à cœur, tout comme la sensibilisation à la dépression.</p>
        </section>
        <section id="blog" class="section blog">
            <h2>Blog</h2>
            <p>Bienvenue sur mon blog où je partage mes réflexions, mes expériences et mes conseils sur divers sujets tels que la mode, la musique, la poésie, le bien-être, la confiance en soi et la dépression.</p>
            <p><a href="#">Lire les articles</a></p>
        </section>
        <section id="forum" class="section forum">
            <h2>Forum</h2>
            <p>Rejoignez notre forum pour discuter de divers sujets liés à la mode, à la musique, à la poésie, au bien-être, à la confiance en soi et à la dépression. Partagez vos idées, vos expériences et soutenez-vous mutuellement.</p>
            <p><a href="#">Accéder au forum</a></p>
        </section>
    </div>
    <footer>
        &copy; 2024 FLEA World. Tous droits réservés.
    </footer>
</body>
</html>
