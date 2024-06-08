<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Page Personnelle</title>
    <style>
        body {
            font-family: 'Calibri', sans-serif;
            background-color: #F5F5DC; /* beige */
            color: #000000; /* noir */
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #FFC0CB; /* rose bonbon */
            padding: 20px;
            text-align: center;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        header h1 {
            margin: 0;
            color: #4B0082; /* indigo pour un contraste mystérieux */
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #A52A2A; /* marron */
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
        }
        .section {
            margin-bottom: 30px;
        }
        .section h2 {
            color: #4B0082;
            border-bottom: 2px solid #4B0082;
            padding-bottom: 10px;
        }
        .blog, .forum {
            background-color: #FFF;
            padding: 20px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        footer {
            background-color: #000;
            color: #FFF;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bienvenue sur ma page personnelle</h1>
    </header>
    <nav>
        <a href="#hobbies">Hobbies</a>
        <a href="#blog">Blog</a>
        <a href="#forum">Forum</a>
    </nav>
    <div class="container">
        <section id="hobbies" class="section">
            <h2>Mes Hobbies et Intérêts</h2>
            <p>Je suis passionné(e) par la mode, la musique et la poésie. J'aime explorer de nouvelles tendances, découvrir de nouveaux artistes et écrire mes propres poèmes. Le bien-être et la confiance en soi sont des sujets qui me tiennent à cœur, tout comme la sensibilisation à la dépression.</p>
        </section>
        <section id="blog" class="section blog">
            <h2>Blog</h2>
            <p>Bienvenue sur mon blog où je partage mes pensées, mes expériences et mes conseils sur divers sujets, y compris la mode, la musique, la poésie, le bien-être, la confiance en soi et la dépression.</p>
            <p><a href="#">Lire les articles</a></p>
        </section>
        <section id="forum" class="section forum">
            <h2>Forum</h2>
            <p>Rejoignez notre forum pour discuter de divers sujets liés à la mode, à la musique, à la poésie, au bien-être, à la confiance en soi et à la dépression. Partagez vos idées, vos expériences et soutenez-vous mutuellement.</p>
            <p><a href="#">Accéder au forum</a></p>
        </section>
    </div>
    <footer>
        &copy; 2024 Ma Page Personnelle. Tous droits réservés.
    </footer>
</body>
</html>
