<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <h1 style="font-size: 36px;">MÁXIMOS SOLUÇÕES - Soluções em Segurança Eletrônica</h1>
    <style>
        /* Reset e estilos globais */
        * {
            margin: auto;
            padding: auto;
            box-sizing: border-box;
            font-family: 'Arial', sans-serif;
        }
        
        body {
            background-color: #f5f5f5;
            color: #333;
            line-height: 1.6;
        }
        
        /* Cabeçalho */
        header {
            background-color: #1a1a2e;
            color: white;
            padding: 1rem 0;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
        }
        
        .header-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .logo {
            font-size: 1.8rem;
            font-weight: bold;
            color: #4cc9f0;
        }
        
        nav ul {
            display: flex;
            list-style: none;
        }
        
        nav ul li {
            margin-left: 1.5rem;
        }
        
        nav ul li a {
            color: white;
            text-decoration: none;
            transition: color 0.3s;
        }
        
        nav ul li a:hover {
            color: #4cc9f0;
        }
        
        /* Hero Section */
        .hero {
            background: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)), url('https://images.unsplash.com/photo-1558002038-1055907df827?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');
            background-size: cover;
            background-position: center;
            height: 100vh;
            display: flex;
            align-items: center;
            text-align: center;
            color: white;
            padding-top: 80px;
        }
        
        .hero-content h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
        }
        
        .hero-content p {
            font-size: 1.2rem;
            margin-bottom: 2rem;
            max-width: 700px;
            margin-left: auto;
            margin-right: auto;
        }
        
        .btn {
            display: inline-block;
            background-color: #4cc9f0;
            color: white;
            padding: 0.8rem 1.8rem;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
            transition: background-color 0.3s;
        }
        
        .btn:hover {
            background-color: #3aa8d8;
        }
        
        /* Serviços */
        .services {
            padding: 5rem 0;
            background-color: white;
        }
        
        .section-title {
            text-align: center;
            margin-bottom: 3rem;
        }
        
        .section-title h2 {
            font-size: 2.5rem;
            color: #1a1a2e;
        }
        
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }
        
        .service-card {
            background-color: #f9f9f9;
            padding: 2rem;
            border-radius: 8px;
            text-align: center;
            transition: transform 0.3s, box-shadow 0.3s;
        }
        
        .service-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
        }
        
        .service-card i {
            font-size: 3rem;
            color: #4cc9f0;
            margin-bottom: 1.5rem;
        }
        
        .service-card h3 {
            font-size: 1.5rem;
            margin-bottom: 1rem;
            color: #1a1a2e;
        }
        
        /* Sobre */
        .about {
            padding: 5rem 0;
            background-color: #f5f5f5;
        }
        
        .about-content {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 3rem;
            align-items: center;
        }
        
        .about-text h2 {
            font-size: 2.5rem;
            color: #1a1a2e;
            margin-bottom: 1.5rem;
        }
        
        .about-text p {
            margin-bottom: 1.5rem;
        }
        
        .about-image img {
            width: 100%;
            border-radius: 8px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }
        
        /* Contato */
        .contact {
            padding: 5rem 0;
            background-color: white;
        }
        
        .contact-form {
            max-width: 600px;
            margin: 0 auto;
            background-color: #f9f9f9;
            padding: 2rem;
            border-radius: 8px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }
        
        .form-group {
            margin-bottom: 1.5rem;
        }
        
        .form-group label {
            display: block;
            margin-bottom: 0.5rem;
            font-weight: bold;
        }
        
        .form-group input,
        .form-group textarea {
            width: 100%;
            padding: 0.8rem;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-size: 1rem;
        }
        
        .form-group textarea {
            height: 150px;
        }
        
        /* Rodapé */
        footer {
            background-color: #1a1a2e;
            color: white;
            padding: 2rem 0;
            text-align: center;
        }
        
        .footer-content {
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;
        }
        
        .footer-section {
            flex: 1;
            min-width: 250px;
            margin-bottom: 1.5rem;
        }
        
        .footer-section h3 {
            color: #4cc9f0;
            margin-bottom: 1rem;
        }
        
        .social-links a {
            color: white;
            margin-right: 1rem;
            font-size: 1.5rem;
            transition: color 0.3s;
        }
        
        .social-links a:hover {
            color: #4cc9f0;
        }
        
        .copyright {
            margin-top: 2rem;
            padding-top: 1rem;
            border-top: 1px solid #444;
        }
        
        /* Responsividade */
        @media (max-width: 768px) {
            .header-content {
                flex-direction: column;
                text-align: center;
            }
            
            nav ul {
                margin-top: 1rem;
            }
            
            .hero-content h1 {
                font-size: 2.5rem;
            }
            
            .about-content {
                grid-template-columns: 1fr;
            }
            
            .about-image {
                order: -1;
            }
        }
    </style>
    <!-- Ícones do Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <!-- Cabeçalho -->
    <header>
        <div class="container">
            <div class="header-content">
                <div class="logo">Máximus Soluções</div>
                <nav>
                    <ul>
                        <li><a href="#home">Início</a></li>
                        <li><a href="#services">Serviços</a></li>
                        <li><a href="#about">Sobre</a></li>
                        <li><a href="#contact">Contato</a></li>
                    </ul>
                </nav>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <div class="container">
            <div class="hero-content">
                <div>
                    <h1>Proteção Inteligente para seu Patrimônio</h1>
                    <p>Soluções completas em segurança eletrônica, controle de acesso, cancelas, portões automatizados, manutenção em notebooks, desktops, reparo de celulares smartphones, manutenção em sistema de telefonia em geral (Pabx), infraestrutura de rede e cabeamento estruturado com tecnologia de ponta para sua tranquilidade.</p>
                    <a href="#contact" class="btn">Solicitar Orçamento</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Serviços -->
    <section class="services" id="services">
        <div class="container">
            <div class="section-title">
                <h2>Nossos Serviços</h2>
            </div>
            <div class="services-grid">
                <div class="service-card">
                    <i class="fas fa-camera"></i>
                    <h3>Sistemas de CFTV</h3>
                    <p>Câmeras de alta definição com gravação em nuvem e monitoramento remoto via smartphone.</p>
                </div>
                <div class="service-card">
                    <i class="fas fa-lock"></i>
                    <h3>Alarmes</h3>
                    <p>Sistemas de alarme residencial e comercial com sensores de movimento e botão de pânico.</p>
                </div>
                <div class="service-card">
                    <i class="fas fa-fingerprint"></i>
                    <h3>Controle de Acesso</h3>
                    <p>Soluções modernas com biometria, cartões de proximidade e controle remoto de acessos.</p>
                </div>
                <div class="service-card">
                    <i class="fas fa-phone"></i>
                    <h3>Celular Smartphone.</h3>
                    <p>Reparo em celulares smartphones .</p>
                </div> 
                <div class="service-card">
                    <i class="fas fa-network-wired"></i>
                    <h3>Notebooks e Desktops.</h3>
                    <p>O diagnóstico de notebooks e desktops envolve a identificação de problemas de hardware e software para determinar a causa de mau funcionamento e encontrar soluções .</p>
                </div> 
                <div class="service-card">
                    <i class="fas fa-lightbulb"></i>
                    <h3>Automação Residencial</h3>
                    <p>Integração de sistemas de segurança com automação de portões automatizados e cancelas para maior comodidade e eficiência.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Sobre -->
    <section class="about" id="about">
        <div class="container">
            <div class="about-content">
                <div class="about-text">
                    <h2>Sobre a Máximus Soluções</h2>
                    <p>Com experiência no mercado de segurança eletrônica, automação, controle de acesso, telefonia, infraestrutura de rede e cabeamento estruturado a Máximus Soluções se consolidou como referência em soluções inteligentes de proteção patrimonial.</p>
                    <p>Nossa equipe de especialistas está sempre atualizada com as mais recentes tecnologias para oferecer aos nossos clientes sistemas eficientes e personalizados para cada necessidade.</p>
                    <p>Valorizamos a transparência, a qualidade dos produtos e a excelência no atendimento, garantindo a satisfação e a tranquilidade de quem confia em nossos serviços.</p>
                </div>
                <div class="about-image">
                    <img src="https://images.unsplash.com/photo-1600880292203-757bb62b4baf?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Equipe SecureTech">
                </div>
            </div>
        </div>
    </section>

    <!-- Contato -->
    <section class="contact" id="contact">
        <div class="container">
            <div class="section-title">
                <h2>Entre em Contato</h2>
            </div>
            <div class="contact-form">
                <form>
                    <div class="form-group">
                        <label for="name">Nome</label>
                        <input type="text" id="name" name="name" required>
                    </div>
                    <div class="form-group">
                        <label for="email">E-mail</label>
                        <input type="email" id="email" name="email" required>
                    </div>
                    <div class="form-group">
                        <label for="phone">Telefone</label>
                        <input type="tel" id="phone" name="phone">
                    </div>
                    <div class="form-group">
                        <label for="message">Mensagem</label>
                        <textarea id="message" name="message" required></textarea>
                    </div>
                    <button type="submit" class="btn">Enviar Mensagem</button>
                </form>
            </div>
        </div>
    </section>

    <!-- Rodapé -->
    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="footer-section">
                    <h3>Máximus Soluções</h3>
                    <p>Soluções inteligentes para residências empresas e condomínios.</p>
                </div>
                <div class="footer-section">
                    <h3>Contato</h3>
                    <p><i class="fas fa-phone"></i> (21) 96436-6431</p>
                    <p><i class="fas fa-phone"></i> (21) 97923-2476</p>
                    <p><i class="fas fa-envelope"></i> maximussolucoess@gmail.com</p>
                    <p><i class="fas fa-map-marker-alt"></i> </p>
                </div>
                <div class="footer-section">
                    <h3>Redes Sociais</h3>
                    <div class="social-links">
                        <a href="#"><i class="fab fa-facebook"></i></a>
                        <a href="#"><i class="fab fa-instagram"></i></a>
                        <a href="#"><i class="fab fa-linkedin"></i></a>
                        <a href="#"><i class="fab fa-youtube"></i></a>
                    </div>
                </div>
            </div>
            <div class="copyright">
                <p>&copy; 2025 Máximus Soluções. Todos os direitos reservados.</p>
            </div>
        </div>
    </footer>
</body>
</html>
