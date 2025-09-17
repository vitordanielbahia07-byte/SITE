<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Entre em Contato</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" integrity="sha512-SnH5WK+bZxgPHs44uWIX+LLJAJ9/2eT0uR5U1aFmNAG+c8M5k5J8/7d5b8J8p3w8B9W8D9wG8wF5k5T5p8g==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap');

        :root {
            --primary-color: #3b82f6;
            --secondary-color: #1d4ed8;
            --text-color-primary: #1f2937;
            --text-color-secondary: #6b7280;
            --bg-color-light: #f9fafb;
            --bg-color-white: #ffffff;
            --border-color: #e5e7eb;0,
            --shadow-color: rgba(0, 0, 0, 0.05);
        }

        * {
            box-sizing: border-box;
        }

        body {
            font-family: 'Poppins', sans-serif;
            background-color: var(--bg-color-light);
            color: var(--text-color-primary);
            margin: 0;
            padding: 2rem;
            display: flex;
            justify-content: center;
        }

        .container {
            max-width: 1200px;
            width: 100%;
        }

        .header {
            text-align: center;
            margin-bottom: 2rem;
        }

        .header-tag {
            background-color: #e0e7ff;
            color: var(--primary-color);
            padding: 0.25rem 0.75rem;
            border-radius: 9999px;
            font-size: 0.875rem;
            font-weight: 500;
        }

        .header-title {
            font-size: 2.5rem;
            font-weight: 700;
            color: var(--text-color-primary);
            margin-top: 1rem;
            margin-bottom: 0.5rem;
        }

        .header-subtitle {
            font-size: 1rem;
            color: var(--text-color-secondary);
            max-width: 600px;
            margin: 0 auto;
        }

        .main-content {
            display: flex;
            gap: 2rem;
        }

        .info-column {
            flex: 1;
            display: flex;
            flex-direction: column;
            gap: 1.5rem;
        }

        .form-column {
            flex: 1;
        }

        .info-card,
        .form-card {
            background-color: var(--bg-color-white);
            padding: 2rem;
            border-radius: 0.75rem;
            box-shadow: 0 4px 6px -1px var(--shadow-color);
            border: 1px solid var(--border-color);
        }

        .info-header,
        .form-header {
            display: flex;
            align-items: center;
            gap: 1rem;
            margin-bottom: 1.5rem;
        }

        .info-header .icon,
        .form-header .icon {
            background-color: #dbeafe;
            color: var(--primary-color);
            padding: 0.75rem;
            border-radius: 0.5rem;
            font-size: 1.25rem;
        }

        .info-header h2,
        .form-header h2 {
            font-size: 1.25rem;
            font-weight: 600;
            margin: 0;
        }

        .info-body h3 {
            font-size: 1rem;
            font-weight: 600;
            margin-bottom: 0.25rem;
        }

        .info-body p {
            margin: 0;
            color: var(--text-color-secondary);
            font-size: 0.875rem;
        }

        .info-body-links {
            display: flex;
            flex-direction: column;
            gap: 0.5rem;
        }

        .quick-link {
            display: flex;
            align-items: center;
            gap: 1rem;
            color: var(--text-color-primary);
            text-decoration: none;
            font-weight: 500;
            padding: 0.75rem 1rem;
            border-radius: 0.5rem;
            transition: background-color 0.3s;
        }

        .quick-link:hover {
            background-color: #f3f4f6;
        }

        .quick-link .icon {
            color: var(--primary-color);
            font-size: 1rem;
        }

        form {
            display: flex;
            flex-direction: column;
            gap: 1.5rem;
        }

        .form-row {
            display: flex;
            gap: 1.5rem;
        }

        .form-group {
            flex: 1;
            display: flex;
            flex-direction: column;
        }

        label {
            font-weight: 500;
            margin-bottom: 0.5rem;
        }

        input,
        select,
        textarea {
            width: 100%;
            padding: 0.75rem 1rem;
            border: 1px solid var(--border-color);
            border-radius: 0.5rem;
            font-family: inherit;
            font-size: 0.875rem;
            color: var(--text-color-primary);
            background-color: #f9fafb;
        }

        input::placeholder,
        textarea::placeholder {
            color: #9ca3af;
        }

        input:focus,
        select:focus,
        textarea:focus {
            outline: none;
            border-color: var(--primary-color);
            box-shadow: 0 0 0 3px #dbeafe;
        }

        textarea {
            resize: vertical;
        }

        .submit-button {
            background-color: var(--primary-color);
            color: var(--bg-color-white);
            padding: 0.75rem 1.5rem;
            border: none;
            border-radius: 0.5rem;
            font-size: 1rem;
            font-weight: 600;
            cursor: pointer;
            transition: background-color 0.3s;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 0.5rem;
        }

        .submit-button:hover {
            background-color: var(--secondary-color);
        }

        @media (max-width: 992px) {
            .main-content {
                flex-direction: column;
            }
            .form-row {
                flex-direction: column;
                gap: 0;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header class="header">
            <span class="header-tag">Fale Conosco</span>
            <h1 class="header-title">Entre em Contato</h1>
            <p class="header-subtitle">Estamos aqui para esclarecer suas dúvidas e ajudá-lo a conhecer melhor nossa instituição. Entre em contato conosco!</p>
        </header>

        <main class="main-content">
            <div class="info-column">
                <div class="info-card">
                    <div class="info-header">
                        <i class="fas fa-phone-alt icon"></i>
                        <h2>Informações de Contato</h2>
                    </div>
                    <div class="info-body">
                        <h3>Telefone</h3>
                        <p>(11) 3456-7890</p>
                        <p>(11) 9 8765-4321</p>
                    </div>
                </div>

                <div class="info-card">
                    <div class="info-header">
                        <i class="fas fa-envelope icon"></i>
                        <h2>E-mail</h2>
                    </div>
                    <div class="info-body">
                        <p>contato@edutech.edu.br</p>
                        <p>secretaria@edutech.edu.br</p>
                    </div>
                </div>

                <div class="info-card">
                    <div class="info-header">
                        <i class="fas fa-map-marker-alt icon"></i>
                        <h2>Endereço</h2>
                    </div>
                    <div class="info-body">
                        <p>Rua da Educação, 123</p>
                        <p>Centro - São Paulo, SP</p>
                        <p>CEP: 01234-567</p>
                    </div>
                </div>

                <div class="info-card">
                    <div class="info-header">
                        <i class="fas fa-clock icon"></i>
                        <h2>Horário de Funcionamento</h2>
                    </div>
                    <div class="info-body">
                        <p>Segunda a Sexta: 7:00 - 22:00</p>
                        <p>Sábado: 8:00 - 12:00</p>
                        <p>Domingo: Fechado</p>
                    </div>
                </div>

                <div class="info-card">
                    <div class="info-header">
                        <i class="fas fa-link icon"></i>
                        <h2>Acesso Rápido</h2>
                    </div>
                    <div class="info-body-links">
                        <a href="#" class="quick-link"><i class="fas fa-user icon"></i> Portal do Aluno</a>
                        <a href="#" class="quick-link"><i class="fas fa-chalkboard-user icon"></i> Portal do Professor</a>
                        <a href="#" class="quick-link"><i class="fas fa-comment-dots icon"></i> FAQ: Perguntas Frequentes</a>
                    </div>
                </div>
            </div>

            <div class="form-column">
                <div class="form-card">
                    <div class="form-header">
                        <i class="fas fa-paper-plane icon"></i>
                        <h2>Envie sua Mensagem</h2>
                    </div>
                    <form action="#">
                        <div class="form-row">
                            <div class="form-group">
                                <label for="nome">Nome Completo *</label>
                                <input type="text" id="nome" placeholder="Seu nome completo">
                            </div>
                            <div class="form-group">
                                <label for="telefone">Telefone</label>
                                <input type="text" id="telefone" placeholder="(11) 9 9999-9999">
                            </div>
                        </div>
                        <div class="form-group">
                            <label for="email">E-mail *</label>
                            <input type="email" id="email" placeholder="seu@email.com">
                        </div>
                        <div class="form-group">
                            <label for="assunto">Assunto</label>
                            <select id="assunto">
                                <option>Informações Gerais</option>
                                <option>Matrículas</option>
                                <option>Cursos</option>
                                <option>Outros</option>
                            </select>
                        </div>
                        <div class="form-group">
                            <label for="mensagem">Mensagem *</label>
                            <textarea id="mensagem" rows="6" placeholder="Descreva como podemos ajudá-lo..."></textarea>
                        </div>
                        <button type="submit" class="submit-button">
                            <i class="fas fa-paper-plane"></i> Enviar Mensagem
                        </button>
                    </form>
                </div>
            </div>
        </main>
    </div>
</body>
</html>0
