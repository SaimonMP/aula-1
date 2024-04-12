# aula-1
html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Game Zone - Sua Loja de Games</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
        nav {
            background-color: #444;
            padding: 10px 0;
            text-align: center;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 10px;
        }
        section {
            padding: 20px;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        h2 {
            color: #333;
        }
        p {
            color: #555;
        }
        ul {
            list-style-type: none;
            padding: 0;
        }
        li {
            margin-bottom: 5px;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
        }
        .produto {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            margin-top: 20px;
        }
        .produto img {
            width: 200px;
            height: 200px;
            margin-bottom: 10px;
        }
        .produto h3 {
            margin-top: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Game Zone</h1>
        <p>Sua Loja de Games</p>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#sobre">Sobre</a>
        <a href="#produtos">Produtos</a>
        <a href="#contato">Contato</a>
    </nav>
    <div class="container">
        <section id="home">
            <h2>Bem-Vindo à Game Zone</h2>
            <p>Encontre os melhores jogos e consoles na nossa loja!</p>
        </section>
        <section id="sobre">
            <h2>Sobre Nós</h2>
            <p>Game Zone é uma loja de games fundada por Saimon e Mario. Estamos comprometidos em fornecer os melhores produtos e serviços para os amantes de jogos.</p>
        </section>
        <section id="produtos">
            <h2>Nossos Produtos</h2>
            <div class="produto">
                <div>
                    <img src="https://via.placeholder.com/200" alt="Jogo para PC">
                    <h3>Jogo para PC</h3>
                    <p>R$ 99,99</p>
                </div>
                <div>
                    <img src="https://via.placeholder.com/200" alt="Jogo para PlayStation">
                    <h3>Jogo para PlayStation</h3>
                    <p>R$ 129,99</p>
                </div>
                <div>
                    <img src="https://via.placeholder.com/200" alt="Jogo para Xbox">
                    <h3>Jogo para Xbox</h3>
                    <p>R$ 129,99</p>
                </div>
                <div>
                    <img src="https://via.placeholder.com/200" alt="Jogo para Nintendo Switch">
                    <h3>Jogo para Nintendo Switch</h3>
                    <p>R$ 149,99</p>
                </div>
                <div>
                    <img src="https://via.placeholder.com/200" alt="Console">
                    <h3>Console</h3>
                    <p>A partir de R$ 999,99</p>
                </div>
                <div>
                    <img src="https://via.placeholder.com/200" alt="Acessório">
                    <h3>Acessório</h3>
                    <p>A partir de R$ 49,99</p>
                </div>
            </div>
        </section>
        <section id="contato">
            <h2>Entre em Contato</h2>
            <p>Estamos sempre prontos para ajudá-lo. Entre em contato conosco se tiver alguma dúvida ou sugestão.</p>
            <p>Email: contato@gamezone.com</p>
            <p>Telefone: (XX) XXXX-XXXX</p>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Game Zone. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
