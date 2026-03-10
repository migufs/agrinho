# agrinho
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Agro forte, futuro sustentável: equilíbrio entre produção e meio ambiente.">
    <title>Agro Forte - Futuro Sustentável</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Agro Forte, Futuro Sustentável</h1>
            <nav>
                <ul>
                    <li><a href="#sobre">Sobre</a></li>
                    <li><a href="#sustentabilidade">Sustentabilidade</a></li>
                    <li><a href="#tecnologia">Tecnologia</a></li>
                    <li><a href="#contato">Contato</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="sobre">
        <div class="container">
            <h2>O que é o Agro Forte?</h2>
            <p>O Agro Forte é um movimento que busca o equilíbrio entre a produção agrícola e a preservação do meio ambiente. Nosso objetivo é promover práticas sustentáveis que garantam a produção de alimentos de qualidade, ao mesmo tempo em que protegemos os recursos naturais para as futuras gerações.</p>
        </div>
    </section>

    <section id="sustentabilidade" class="bg-green">
        <div class="container">
            <h2>Sustentabilidade no Agro</h2>
            <p>A sustentabilidade no agronegócio é fundamental para garantir que a produção de alimentos não prejudique o meio ambiente. Investimos em tecnologias e práticas agrícolas que respeitam a natureza, preservando os solos, a água e a biodiversidade.</p>
        </div>
    </section>

    <section id="tecnologia">
        <div class="container">
            <h2>Tecnologia a favor do Agro Sustentável</h2>
            <p>A tecnologia é uma aliada essencial para o desenvolvimento do agro sustentável. Usamos soluções inovadoras para melhorar a eficiência da produção, reduzir desperdícios e promover a agricultura de baixo impacto ambiental.</p>
        </div>
    </section>

    <footer id="contato">
        <div class="container">
            <h2>Entre em Contato</h2>
            <p>Email: contato@agroforte.com.br</p>
            <p>Telefone: (11) 98765-4321</p>
        </div>
    </footer>
</body>
</html>

/* Reset de margens e padding */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Corpo do site */
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
}

/* Cabeçalho */
header {
    background-color: #4CAF50;
    color: white;
    padding: 20px 0;
}

header .container {
    width: 80%;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header h1 {
    font-size: 2.5rem;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
}

nav a {
    color: white;
    text-decoration: none;
    font-size: 1.1rem;
    transition: color 0.3s ease;
}

nav a:hover {
    color: #ddd;
}

/* Seções */
section {
    padding: 40px 0;
}

.bg-green {
    background-color: #e8f5e9;
}

.container {
    width: 80%;
    margin: 0 auto;
}

h2 {
    font-size: 2rem;
    color: #4CAF50;
    margin-bottom: 20px;
}

p {
    font-size: 1.1rem;
    color: #666;
    line-height: 1.8;
}

/* Rodapé */
footer {
    background-color: #333;
    color: white;
    padding: 20px 0;
    text-align: center;
}

footer h2 {
    margin-bottom: 10px;
}

footer p {
    font-size: 1rem;
}

/* Responsividade */
@media (max-width: 768px) {
    header .container {
        flex-direction: column;
        align-items: center;
    }

    nav ul {
        flex-direction: column;
        gap: 15px;
    }

    .container {
        width: 90%;
    }
}
