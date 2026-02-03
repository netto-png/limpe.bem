<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Limpe Bem: Produtos de limpeza com economia, qualidade e limpeza de verdade. Lava-roupas, alvejantes, desinfetantes e mais. Compre no varejo ou atacado.">
    <meta name="keywords" content="Limpe Bem, produtos de limpeza, lava-roupas, alvejantes, desinfetantes, detergentes, amaciantes, limpeza doméstica, limpeza profissional">
    <title>Limpe Bem - Limpeza que Rende Mais</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        body { font-family: Arial, sans-serif; background-color: #f8f9fa; color: #333; }
        .navbar { background-color: #007bff; }
        .hero { background: linear-gradient(to right, #007bff, #28a745); color: white; padding: 100px 0; text-align: center; }
        .section { padding: 60px 0; }
        .product-card { border: none; box-shadow: 0 4px 8px rgba(0,0,0,0.1); transition: transform 0.3s; }
        .product-card:hover { transform: scale(1.05); }
        .whatsapp-float { position: fixed; bottom: 20px; right: 20px; background-color: #25d366; color: white; border-radius: 50%; width: 60px; height: 60px; display: flex; align-items: center; justify-content: center; font-size: 24px; box-shadow: 0 4px 8px rgba(0,0,0,0.3); z-index: 1000; }
        .whatsapp-float:hover { background-color: #128c7e; }
        .testimonial { background-color: #e9ecef; padding: 20px; border-radius: 10px; margin: 10px 0; }
        footer { background-color: #007bff; color: white; text-align: center; padding: 20px 0; }
    </style>
</head>
<body>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark">
        <div class="container">
            <a class="navbar-brand" href="#home"><i class="fas fa-broom"></i> Limpe Bem</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="#produtos">Produtos</a></li>
                    <li class="nav-item"><a class="nav-link" href="#sobre">Sobre</a></li>
                    <li class="nav-item"><a class="nav-link" href="#promocoes">Promoções</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contato">Contato</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Home Section -->
    <section id="home" class="hero">
        <div class="container">
            <h1>Limpe Bem: Economia, Qualidade e Limpeza de Verdade</h1>
            <p>Produtos que limpam de verdade e cabem no seu bolso.</p>
            <a href="#produtos" class="btn btn-light btn-lg me-2"><i class="fas fa-eye"></i> Ver Produtos</a>
            <a href="https://wa.me/5511999999999?text=Olá,%20gostaria%20de%20comprar%20produtos%20da%20Limpe%20Bem" class="btn btn-warning btn-lg"><i class="fab fa-whatsapp"></i> Comprar Agora</a>
            <div class="row mt-4">
                <div class="col-md-4"><h5>Produtos Mais Vendidos</h5><p>Descubra os favoritos dos clientes.</p></div>
                <div class="col-md-4"><h5>Promoções da Semana</h5><p>Descontos imperdíveis.</p></div>
                <div class="col-md-4"><h5>Vantagens</h5><p>Preço competitivo, qualidade garantida, rendimento superior.</p></div>
            </div>
            <div class="mt-4">
                <span class="badge bg-success">Compra Segura</span>
                <span class="badge bg-info">Produtos Testados</span>
                <span class="badge bg-warning">Atendimento Rápido</span>
            </div>
        </div>
    </section>

    <!-- Produtos Section -->
    <section id="produtos" class="section">
        <div class="container">
            <h2 class="text-center mb-4">Nossos Produtos</h2>
            <div class="row">
                <!-- Exemplo de Produto -->
                <div class="col-md-4 mb-4">
                    <div class="card product-card">
                        <img src="https://via.placeholder.com/300x200?text=Lava-Roupas" class="card-img-top" alt="Lava-Roupas">
                        <div class="card-body">
                            <h5 class="card-title">Lava-Roupas Concentrado</h5>
                            <p class="card-text">Limpeza profunda e econômica. Benefícios: Remove manchas difíceis, rende mais.</p>
                            <p><strong>R$ 15,00 (Varejo) / R$ 12,00 (Atacado)</strong></p>
                            <a href="https://wa.me/5511999999999?text=Quero%20comprar%20Lava-Roupas" class="btn btn-primary"><i class="fab fa-whatsapp"></i> Comprar</a>
                        </div>
                    </div>
                </div>
                <!-- Repita para outros produtos: Alvejantes, Desinfetantes, etc. -->
                <div class="col-md-4 mb-4">
                    <div class="card product-card">
                        <img src="https://via.placeholder.com/300x200?text=Alvejante" class="card-img-top" alt="Alvejante">
                        <div class="card-body">
                            <h5 class="card-title">Alvejante Poderoso</h5>
                            <p class="card-text">Branqueia e desinfeta. Benefícios: Higiene total, sem resíduos.</p>
                            <p><strong>R$ 8,00 (Varejo) / R$ 6,50 (Atacado)</strong></p>
                            <a href="https://wa.me/5511999999999?text=Quero%20comprar%20Alvejante" class="btn btn-primary"><i class="fab fa-whatsapp"></i> Comprar</a>
                        </div>
                    </div>
                </div>
                <!-- Adicione mais produtos conforme necessário -->
            </div>
        </div>
    </section>

    <!-- Sobre Section -->
    <section id="sobre" class="section bg-light">
        <div class="container">
            <h2 class="text-center mb-4">Sobre a Limpe Bem</h2>
            <p>A Limpe Bem nasceu com o compromisso de oferecer produtos de limpeza de alta qualidade, acessíveis e eficazes. Somos uma loja confiável para donas de casa, pequenos comércios e empresas de limpeza. Nossa história é de dedicação à economia e à limpeza real, com atendimento honesto e próximo. Escolhemos produtos testados e aprovados, garantindo que você tenha o melhor para sua casa ou negócio.</p>
        </div>
    </section>

    <!-- Promoções Section -->
    <section id="promocoes" class="section">
        <div class="container">
            <h2 class="text-center mb-4">Promoções Especiais</h2>
            <div class="row">
                <div class="col-md-6">
                    <h5>Ofertas da Semana</h5>
                    <p>Kit Lava-Roupas + Amaciante por R$ 20,00 (10% off).</p>
                </div>
                <div class="col-md-6">
                    <h5>Descontos por Quantidade</h5>
                    <p>Compre 10 unidades e ganhe 15% de desconto.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contato Section -->
    <section id="contato" class="section bg-light">
        <div class="container">
            <h2 class="text-center mb-4">Entre em Contato</h2>
            <div class="row">
                <div class="col-md-6">
                    <h5>Informações</h5>
                    <p><i class="fas fa-phone"></i> Telefone: (11) 99999-9999</p>
                    <p><i class="fas fa-map-marker-alt"></i> Endereço: Rua da Limpeza, 123 - São Paulo, SP</p>
                    <p><i class="fas fa-clock"></i> Horário: Seg-Sex 8h-18h</p>
                    <a href="https://wa.me/5511999999999" class="btn btn-success btn-lg"><i class="fab fa-whatsapp"></i> Falar no WhatsApp</a>
                </div>
                <div class="col-md-6">
                    <form>
                        <div class="mb-3">
                            <label for="nome" class="form-label">Nome</label>
                            <input type="text" class="form-control" id="nome">
                        </div>
                        <div class="mb-3">
                            <label for="telefone" class="form-label">Telefone</label>
                            <input type="tel" class="form-control" id="telefone">
                        </div>
                        <div class="mb-3">
                            <label for="mensagem" class="form-label">Mensagem</label>
                            <textarea class="form-control" id="mensagem" rows="3"></textarea>
                        </div>
                        <button type="submit" class="btn btn-primary">Enviar</button>
                    </form>
                </div>
            </div>
            <div class="mt-4">
                <h5>Depoimentos</h5>
                <div class="testimonial">
                    <p>"Produtos incríveis! Limpa tudo e economiza." - Maria S.</p>
                </div>
                <div class="testimonial">
                    <p>"Atendimento rápido e confiável." - João P.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2023 Limpe Bem. Todos os direitos reservados. <a href="#" class="text-white">Política de Troca</a></p>
    </footer>

    <!-- WhatsApp Float Button -->
    <a href="https://wa.me/5511999999999?text=Olá,%20gostaria%20de%20saber%20mais%20sobre%20os%20produtos" class="whatsapp-float">
        <i class="fab fa-whatsapp"></i>
    </a>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
    <script>
        // Simples validação de formulário
        document.querySelector('form').addEventListener('submit', function(e) {
            e.preventDefault();
            alert('Mensagem enviada! Entraremos em contato em breve.');
        });
    </script>
</body>
</html>
