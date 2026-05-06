# Prova<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>ENIAC - O Primeiro Computador</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>ENIAC</h1>
    <p>O primeiro computador eletrônico da história</p>
</header>

<nav>
    <ul>
        <li><a href="#historia">História</a></li>
        <li><a href="#caracteristicas">Características</a></li>
        <li><a href="#curiosidades">Curiosidades</a></li>
    </ul>
</nav>

<main>
    <section id="historia">
        <h2>História</h2>
        <p>O ENIAC foi criado em 1945 e revolucionou a computação.</p>
    </section>

    <section id="caracteristicas">
        <h2>Características</h2>
        <ul>
            <li>Pesava mais de 30 toneladas</li>
            <li>Usava válvulas eletrônicas</li>
            <li>Consumía muita energia</li>
        </ul>
    </section>

    <section id="curiosidades">
        <h2>Curiosidades</h2>
        <p>O ENIAC ocupava uma sala inteira!</p>
    </section>
</main>

<footer>
    <p>Desenvolvido por Leonardo</p>
</footer>

</body>
</html>
/* Reset básico */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Corpo */
body {
    font-family: Arial, sans-serif;
    background: #0a0a0a;
    color: #e0e0e0;
}

/* Cabeçalho */
header {
    background: linear-gradient(90deg, #111, #222);
    text-align: center;
    padding: 30px;
    border-bottom: 3px solid #00ffcc;
}

header h1 {
    font-size: 3em;
    color: #00ffcc;
}

header p {
    color: #aaa;
}

/* Menu */
nav {
    background: #111;
}

nav ul {
    display: flex;
    justify-content: center;
    list-style: none;
}

nav li {
    margin: 10px;
}

nav a {
    text-decoration: none;
    color: #00ffcc;
    padding: 10px 15px;
    border: 1px solid #00ffcc;
    transition: 0.3s;
}

nav a:hover {
    background: #00ffcc;
    color: #000;
}

/* Conteúdo */
main {
    padding: 20px;
}

section {
    margin-bottom: 30px;
    padding: 20px;
    border-left: 4px solid #00ffcc;
    background: #111;
    border-radius: 5px;
}

section h2 {
    margin-bottom: 10px;
    color: #00ffcc;
}

/* Lista */
ul {
    margin-left: 20px;
}

/* Rodapé */
footer {
    text-align: center;
    padding: 15px;
    background: #111;
    border-top: 2px solid #00ffcc;
    margin-top: 20px;
}
