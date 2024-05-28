# FUTYSTA
 Portfólio de Jogos, Blog sobre Jogos, Tutoriais, Contato, e Links para Redes Sociais.
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Site de Jogos</title>
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #0d0d0d;
            color: #e0e0e0;
        }
        header, nav, section, footer {
            margin: 20px;
            padding: 20px;
            border-radius: 10px;
            background: linear-gradient(135deg, #1f1f1f, #292929);
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
        }
        header {
            text-align: center;
        }
        nav {
            text-align: center;
        }
        nav a {
            color: #00bfff;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
            text-transform: uppercase;
        }
        nav a:hover {
            color: #00ffff;
        }
        section {
            margin-bottom: 20px;
        }
        footer {
            text-align: center;
        }
        .content {
            max-width: 800px;
            margin: auto;
        }
        h1, h2 {
            color: #00bfff;
        }
        .portfolio-item, .blog-post, .tutorial {
            background-color: #1a1a1a;
            padding: 15px;
            margin-bottom: 10px;
            border-radius: 5px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        .portfolio-item:hover, .blog-post:hover, .tutorial:hover {
            background-color: #333;
        }
        .social-links a {
            color: #00bfff;
            margin: 0 10px;
            text-decoration: none;
            font-size: 1.5em;
        }
        .social-links a:hover {
            color: #00ffff;
        }
        .form-control {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: none;
            border-radius: 5px;
            background-color: #1a1a1a;
            color: #e0e0e0;
        }
        .form-control::placeholder {
            color: #888;
        }
        .submit-btn {
            background-color: #00bfff;
            color: #0d0d0d;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-weight: bold;
        }
        .submit-btn:hover {
            background-color: #00ffff;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bem-vindo ao Meu Site de Jogos</h1>
    </header>
    <nav>
        <a href="#sobre-mim">Sobre Mim</a>
        <a href="#portfolio">Portfólio de Jogos</a>
        <a href="#blog">Blog sobre Jogos</a>
        <a href="#tutoriais">Tutoriais</a>
        <a href="#contato">Contato</a>
    </nav>
    <div class="content">
        <section id="sobre-mim">
            <h2>Sobre Mim</h2>
            <p>Olá! Meu nome é [Seu Nome] e sou apaixonado por jogos. Desenvolvo jogos e escrevo sobre o mundo dos jogos. Adoro compartilhar minhas experiências e conhecimentos com outros entusiastas.</p>
        </section>
        <section id="portfolio">
            <h2>Portfólio de Jogos</h2>
            <div class="portfolio-item">
                <h3>Jogo 1</h3>
                <p>Descrição do jogo 1. Detalhes sobre o desenvolvimento, mecânicas e desafios.</p>
            </div>
            <div class="portfolio-item">
                <h3>Jogo 2</h3>
                <p>Descrição do jogo 2. Detalhes sobre o desenvolvimento, mecânicas e desafios.</p>
            </div>
        </section>
        <section id="blog">
            <h2>Blog sobre Jogos</h2>
            <div class="blog-post">
                <h3>Postagem 1</h3>
                <p>Texto da postagem 1 sobre novidades, análises ou experiências no mundo dos jogos.</p>
            </div>
            <div class="blog-post">
                <h3>Postagem 2</h3>
                <p>Texto da postagem 2 sobre novidades, análises ou experiências no mundo dos jogos.</p>
            </div>
        </section>
        <section id="tutoriais">
            <h2>Tutoriais</h2>
            <div class="tutorial">
                <h3>Tutorial 1</h3>
                <p>Descrição do tutorial 1. Instruções passo a passo para ajudar outros desenvolvedores de jogos.</p>
            </div>
            <div class="tutorial">
                <h3>Tutorial 2</h3>
                <p>Descrição do tutorial 2. Instruções passo a passo para ajudar outros desenvolvedores de jogos.</p>
            </div>
        </section>
        <section id="contato">
            <h2>Contato</h2>
            <form action="https://example.com/form-submit" method="post">
                <input type="text" name="nome" class="form-control" placeholder="Seu Nome" required>
                <input type="email" name="email" class="form-control" placeholder="Seu Email" required>
                <textarea name="mensagem" class="form-control" rows="5" placeholder="Sua Mensagem" required></textarea>
                <button type="submit" class="submit-btn">Enviar</button>
            </form>
        </section>
        <footer>
            <p>Siga-me nas redes sociais:</p>
            <div class="social-links">
                <a href="https://twitter.com/seuusuario" target="_blank">Twitter</a>
                <a href="https://www.facebook.com/seuusuario" target="_blank">Facebook</a>
                <a href="https://www.instagram.com/seuusuario" target="_blank">Instagram</a>
                <a href="https://www.linkedin.com/in/seuusuario" target="_blank">LinkedIn</a>
            </div>
        </footer>
    </div>
</body>
</html>
