<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rennan Sena - Desenvolvedor FullStack</title>
    <link rel="icon" href="https://avatars.githubusercontent.com/u/SEU_USUARIO" type="image/x-icon">
    <!-- Você pode substituir o href acima pela URL de uma imagem de perfil sua, se quiser um favicon personalizado -->

    <style>
        /* Estilos CSS para a página */
        :root {
            --bg-color: #1a1a2e;
            --card-bg-color: #21213b;
            --text-color: #e0e0e0;
            --highlight-color: #8c8cd9;
            --subtitle-color: #b0b0f0;
            --border-color: #4a4a6e;
            --shadow-color: rgba(0, 0, 0, 0.4);
            --hover-shadow-color: rgba(0, 0, 0, 0.6);
        }

        body {
            font-family: 'Segoe UI', 'Roboto', 'Helvetica Neue', Arial, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-color);
            margin: 0;
            padding: 20px;
            line-height: 1.6;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            box-sizing: border-box;
        }

        .container {
            background-color: var(--card-bg-color);
            border-radius: 12px;
            box-shadow: 0 6px 12px var(--shadow-color);
            padding: 30px 40px;
            max-width: 900px;
            width: 100%;
            text-align: center;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .container:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 16px var(--hover-shadow-color);
        }

        header img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
            object-fit: cover;
            margin-bottom: 20px;
            border: 4px solid var(--highlight-color);
            box-shadow: 0 0 15px rgba(140, 140, 217, 0.5);
        }

        header h1 {
            color: var(--highlight-color);
            margin-bottom: 8px;
            font-size: 3em;
            letter-spacing: 1px;
        }

        header h3 {
            color: var(--subtitle-color);
            font-size: 1.5em;
            margin-top: 0;
            margin-bottom: 30px;
            font-weight: 300;
        }

        h2 {
            color: var(--highlight-color);
            margin-top: 35px;
            margin-bottom: 18px;
            font-size: 2.2em;
            border-bottom: 1px solid var(--border-color);
            padding-bottom: 8px;
            display: inline-block;
        }

        p {
            margin-bottom: 18px;
            text-align: left;
            font-size: 1.05em;
        }

        .about-me ul {
            list-style: none;
            padding: 0;
            text-align: left;
            margin-top: 20px;
        }

        .about-me li {
            background-color: #2a2a47;
            padding: 10px 15px;
            border-left: 3px solid var(--highlight-color);
            margin-bottom: 10px;
            border-radius: 5px;
            font-size: 1em;
        }

        .highlight {
            color: var(--subtitle-color);
            font-weight: bold;
        }

        .skills-grid {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
            margin-top: 30px;
        }

        .skills-grid img {
            width: 50px; /* Tamanho maior para os ícones */
            height: 50px;
            object-fit: contain;
            transition: transform 0.2s ease;
        }

        .skills-grid img:hover {
            transform: scale(1.1);
        }

        .contact-links {
            display: flex;
            justify-content: center;
            gap: 25px;
            margin-top: 30px;
            flex-wrap: wrap;
        }

        .contact-links a img {
            height: 40px; /* Tamanho dos badges */
        }

        footer {
            margin-top: 50px;
            font-size: 0.85em;
            color: #999;
            text-align: center;
        }

        /* Responsividade */
        @media (max-width: 768px) {
            .container {
                padding: 25px 20px;
            }
            header h1 {
                font-size: 2.5em;
            }
            header h3 {
                font-size: 1.2em;
            }
            h2 {
                font-size: 1.8em;
            }
            p, .about-me li {
                font-size: 0.95em;
            }
            .skills-grid img {
                width: 40px;
                height: 40px;
            }
            .contact-links a img {
                height: 35px;
            }
        }

        @media (max-width: 480px) {
            header h1 {
                font-size: 2em;
            }
            header h3 {
                font-size: 1em;
            }
            h2 {
                font-size: 1.5em;
            }
            .skills-grid {
                gap: 15px;
            }
            .skills-grid img {
                width: 35px;
                height: 35px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <!-- Substitua 'SEU_USUARIO' pelo seu nome de usuário GitHub para usar seu avatar como foto -->
            <img src="https://github.com/SEU_USUARIO.png?size=150" alt="Foto de Perfil de Rennan Sena">
            <h1>Rennan Sena</h1>
            <h3>Desenvolvedor(a) FullStack</h3>
        </header>

        <section class="about-me">
            <h2>Olá! 👋 Sobre Mim</h2>
            <p>
                Sou Rennan Sena, desenvolvedor(a) FullStack de 23 anos, com raízes no Nordeste brasileiro. Minha paixão pela tecnologia me impulsiona a estar sempre atualizado(a) e em constante aprendizado, buscando as melhores soluções e me aprimorando continuamente nas últimas tendências do mercado.
            </p>
            <ul>
                <li><span class="highlight">Formação Técnica:</span> Desenvolvimento de Sistemas pelo SENAI (Concluído em 21/06/2022).</li>
                <li><span class="highlight">Graduação:</span> Atualmente cursando o 5º período de Análise e Desenvolvimento de Sistemas na Estácio (Previsão de formatura em dezembro de 2025.2).</li>
                <li><span class="highlight">Experiência (Alares Internet):</span> Desde 01/2023, atuando na execução e controle de projetos de sistemas de informação, além de desenvolver, testar, implantar e documentar programas de computador.</li>
                <li><span class="highlight">Experiência (Enel):</span> Desde 10/2024, lidando com a gestão eficiente de processos de faturamento e cobrança.</li>
            </ul>
            <p>
                Tenho um alto senso de responsabilidade e uma grande vontade de aprender e progredir na carreira profissional.
            </p>
        </section>

        <section class="skills">
            <h2>🚀 Minhas Linguagens e Tecnologias</h2>
            <p>
                Possuo um <span class="highlight">forte domínio em SQL</span> e <span class="highlight">sólidos conhecimentos em Java</span>, linguagens que utilizo para desenvolver soluções robustas e eficientes. Tenho também <span class="highlight">boa proficiência em Python e PHP</span>, aplicadas tanto no backend quanto em scripts e automações. Além disso, domino o básico de <span class="highlight">HTML e CSS</span> para construção de interfaces web, complementando minhas habilidades com diversas outras tecnologias para desenvolvimento.
            </p>
            <div class="skills-grid">
                <img alt="HTML" title="HTML5" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/html5/html5-original.svg" />
                <img alt="CSS" title="CSS3" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/css3/css3-original.svg" />
                <img alt="JavaScript" title="JavaScript" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-original.svg" />
                <img alt="Bootstrap" title="Bootstrap" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/bootstrap/bootstrap-original.svg" />
                <img alt="PHP" title="PHP" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/php/php-original.svg" />
                <img alt="JQuery" title="JQuery" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/jquery/jquery-original.svg" />
                <img alt="Python" title="Python" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" />
                <img alt="Java" title="Java" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/java/java-original.svg" />
                <img alt="SQL" title="SQL" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mysql/mysql-original.svg" /> <!-- Ou outro ícone de SQL específico, se preferir -->
                <img alt="Git" title="Git" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg" />
            </div>
        </section>

        <section class="contact">
            <h2>�� Conecte-se Comigo!</h2>
            <p>Estou sempre aberto(a) a novas conexões e oportunidades. Sinta-se à vontade para me contatar:</p>
            <div class="contact-links">
                <a href="https://linkedin.com/in/SEU_LINKEDIN" >
                    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
                </a>
                <a href="mailto:Rennansenna10@gmail.com">
                    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
                </a>
                <!-- Adicione mais links aqui se tiver (ex: GitHub, Twitter, Portfolio) -->
                <a href="https://github.com/SEU_USUARIO" >
                    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
                </a>
            </div>
        </section>

        <footer>
            <p>&copy; 2024 Rennan Sena.
        </footer>
    </div>
</body>
</html>
