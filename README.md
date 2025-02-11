<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Meu Site</title>
    <link rel="stylesheet" href="styles.css"> <!-- Se você quiser adicionar um arquivo CSS -->
</head>
<body>

    <header>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Sobre</a></li>
                <li><a href="#">Serviços</a></li>
                <li><a href="#">Contato</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="introducao">
            <h1>Bem-vindo ao meu site!</h1>
            <p>Este é um exemplo de página inicial usando HTML.</p>
        </section>

        <section id="sobre">
            <h2>Sobre</h2>
            <p>Aqui você pode adicionar informações sobre você ou seu projeto.</p>
        </section>

        <section id="servicos">
            <h2>Serviços</h2>
            <p>Descreva os serviços que você oferece.</p>
        </section>

        <section id="contato">
            <h2>Contato</h2>
            <form action="#" method="post">
                <label for="nome">Nome:</label>
                <input type="text" id="nome" name="nome" required>
                <label for="email">E-mail:</label>
                <input type="email" id="email" name="email" required>
                <label for="mensagem">Mensagem:</label>
                <textarea id="mensagem" name="mensagem" required></textarea>
                <button type="submit">Enviar</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Meu Site. Todos os direitos reservados.</p>
    </footer>

</body>
</html>
