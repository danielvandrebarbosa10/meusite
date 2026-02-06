<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Meu Primeiro Site</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        body {
            margin: 0;
            font-family: "Times New Roman", serif;
            background-color: #f4f4f4;
            color: #333;
        }

        header {
            background-color: #2c3e50;
            color: white;
            padding: 30px 20px;
            text-align: center;
        }

        main {
            max-width: 800px;
            margin: 40px auto;
            padding: 0 20px;
        }

        section {
            margin-bottom: 30px;
        }

        h2 {
            color: #2c3e50;
        }

        footer {
            background-color: #ddd;
            text-align: center;
            padding: 15px;
            font-size: 0.9em;
        }

        a {
            color: #2980b9;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <header>
        <h1>Meu Site</h1>
        <p>Um site simples em HTML</p>
    </header>

    <main>
        <section>
            <h2>Sobre</h2>
            <p>
                Este é um site básico feito apenas com HTML e CSS.
                Ele pode ser publicado no GitHub Pages ou Netlify sem nenhuma configuração extra.
            </p>
        </section>

        <section>
            <h2>Objetivo</h2>
            <p>
                Usar este site como base para estudos, portfólio ou projetos acadêmicos.
            </p>
        </section>

        <section>
            <h2>Contato</h2>
            <p>
                Email: <a href="mailto:seuemail@email.com">seuemail@email.com</a>
            </p>
        </section>
    </main>

    <footer>
        © 2026 — Criado por você
    </footer>

</body>
</html>