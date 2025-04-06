<!DOCTYPE html>
<html lang="pt-br">
<head>
    <!-- Bootstrap 5 -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --tech-blue: #2A5C82;
            --edu-green: #4CAF50;
            --creative-purple: #7E57C2;
            --energy-orange: #FF9800;
            --dark-bg: #1A237E;
        }
        
        body {
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%);
        }
        
        .hero-section {
            background: var(--dark-bg);
            clip-path: polygon(0 0, 100% 0, 100% 90%, 0 100%);
            color: white;
        }
        
        .skill-badge {
            transition: transform 0.3s, box-shadow 0.3s;
        }
        
        .skill-badge:hover {
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
        }
        
        .project-card {
            border: none;
            transition: transform 0.3s;
            background: linear-gradient(145deg, #ffffff, #f8f9fa);
        }
        
        .project-card:hover {
            transform: scale(1.03);
        }
        
        .nav-pills .nav-link {
            border: 2px solid transparent;
            transition: all 0.3s;
        }
        
        .nav-pills .nav-link.active {
            border-color: var(--edu-green);
            background: transparent;
            color: var(--edu-green);
        }
    </style>
</head>
<body>

<div class="container-fluid px-0">
    <!-- Hero Section -->
    <section class="hero-section text-center py-5">
        <div class="container">
            <div class="avatar mb-4">
                <i class="fas fa-chalkboard-teacher fa-4x text-warning"></i>
            </div>
            <h1 class="display-4 fw-bold mb-3">Bruno Carvalho</h1>
            <p class="lead mb-4">Transformando educação através da tecnologia</p>
            
            <!-- Interactive Navigation -->
            <ul class="nav nav-pills justify-content-center gap-3 mb-4">
                <li class="nav-item">
                    <a class="nav-link active" href="#sobre"><i class="fas fa-user-graduate me-2"></i>Sobre</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#projetos"><i class="fas fa-laptop-code me-2"></i>Projetos</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#tecnologias"><i class="fas fa-microchip me-2"></i>Tecnologias</a>
                </li>
            </ul>
        </div>
    </section>

    <!-- Main Content -->
    <div class="container py-5">
        <!-- About Section -->
        <section id="sobre" class="mb-5">
            <div class="row g-4">
                <div class="col-lg-6">
                    <div class="card border-0 shadow-lg h-100">
                        <div class="card-body">
                            <h2 class="card-title mb-4"><i class="fas fa-brain text-primary me-2"></i>Metodologias</h2>
                            <ul class="list-unstyled">
                                <li class="mb-3">
                                    <h5><span class="badge bg-primary me-2">ABP</span> Aprendizagem Baseada em Projetos</h5>
                                    <small class="text-muted">Desenvolvimento de soluções reais</small>
                                </li>
                                <li class="mb-3">
                                    <h5><span class="badge bg-success me-2">🎮</span> Gamificação</h5>
                                    <small class="text-muted">Jogos educacionais personalizados</small>
                                </li>
                                <li>
                                    <h5><span class="badge bg-warning me-2">🔁</span> Aprendizado por Erros</h5>
                                    <small class="text-muted">Valorização do processo criativo</small>
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>
                
                <div class="col-lg-6">
                    <div class="card border-0 shadow-lg h-100">
                        <div class="card-body">
                            <h2 class="card-title mb-4"><i class="fas fa-flask text-danger me-2"></i>Áreas de Atuação</h2>
                            <div class="row">
                                <div class="col-md-6 mb-3">
                                    <div class="p-3 bg-light rounded">
                                        <h5>Geografia Digital</h5>
                                        <small class="text-muted">GIS e tecnologias espaciais</small>
                                    </div>
                                </div>
                                <div class="col-md-6 mb-3">
                                    <div class="p-3 bg-light rounded">
                                        <h5>Robótica Criativa</h5>
                                        <small class="text-muted">Protótipos com Arduino</small>
                                    </div>
                                </div>
                                <div class="col-md-6 mb-3">
                                    <div class="p-3 bg-light rounded">
                                        <h5>Desenvolvimento Web</h5>
                                        <small class="text-muted">Projetos full-stack</small>
                                    </div>
                                </div>
                                <div class="col-md-6">
                                    <div class="p-3 bg-light rounded">
                                        <h5>Realidade Virtual</h5>
                                        <small class="text-muted">Experiências imersivas</small>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Technologies Section -->
        <section id="tecnologias" class="mb-5">
            <h2 class="text-center mb-4"><i class="fas fa-tools me-2"></i>Tecnologias</h2>
            <div class="row g-3">
                <div class="col-6 col-md-3">
                    <div class="card project-card h-100">
                        <div class="card-body text-center">
                            <i class="fab fa-html5 fa-3x text-danger mb-3"></i>
                            <h5>HTML5</h5>
                            <small class="text-muted">Estrutura Web</small>
                        </div>
                    </div>
                </div>
                <div class="col-6 col-md-3">
                    <div class="card project-card h-100">
                        <div class="card-body text-center">
                            <i class="fab fa-js-square fa-3x text-warning mb-3"></i>
                            <h5>JavaScript</h5>
                            <small class="text-muted">Interatividade</small>
                        </div>
                    </div>
                </div>
                <div class="col-6 col-md-3">
                    <div class="card project-card h-100">
                        <div class="card-body text-center">
                            <i class="fab fa-python fa-3x text-primary mb-3"></i>
                            <h5>Python</h5>
                            <small class="text-muted">Automação & IA</small>
                        </div>
                    </div>
                </div>
                <div class="col-6 col-md-3">
                    <div class="card project-card h-100">
                        <div class="card-body text-center">
                            <i class="fas fa-robot fa-3x text-success mb-3"></i>
                            <h5>Robótica</h5>
                            <small class="text-muted">Arduino & IoT</small>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Projects Section -->
        <section id="projetos">
            <h2 class="text-center mb-4"><i class="fas fa-rocket me-2"></i>Projetos em Destaque</h2>
            <div class="row g-4">
                <div class="col-md-6">
                    <div class="card project-card h-100">
                        <div class="card-body">
                            <div class="d-flex align-items-center mb-3">
                                <i class="fas fa-tractor fa-2x text-success me-3"></i>
                                <h4 class="mb-0">Agrinho 2024</h4>
                            </div>
                            <p class="card-text">Plataforma de conexão campo-cidade com marketplace integrado</p>
                            <div class="tech-tags mb-3">
                                <span class="badge bg-primary">WebVR</span>
                                <span class="badge bg-success">GIS</span>
                                <span class="badge bg-warning">E-commerce</span>
                            </div>
                            <a href="https://lobosilencioso.github.io/agrinho_2024/" class="btn btn-outline-success">
                                <i class="fas fa-external-link-alt me-2"></i>Acessar Projeto
                            </a>
                        </div>
                    </div>
                </div>
                
                <div class="col-md-6">
                    <div class="card project-card h-100">
                        <div class="card-body">
                            <div class="d-flex align-items-center mb-3">
                                <i class="fas fa-vr-cardboard fa-2x text-primary me-3"></i>
                                <h4 class="mb-0">Paraná Faz Ciência</h4>
                            </div>
                            <p class="card-text">Experiência educativa em Realidade Virtual multiplataforma</p>
                            <div class="tech-tags mb-3">
                                <span class="badge bg-primary">A-Frame</span>
                                <span class="badge bg-danger">Three.js</span>
                                <span class="badge bg-warning">WebGL</span>
                            </div>
                            <a href="https://vrpfc.vercel.app/" class="btn btn-outline-primary">
                                <i class="fas fa-external-link-alt me-2"></i>Explorar VR
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </div>

    <!-- Footer -->
    <footer class="bg-dark text-white py-4">
        <div class="container text-center">
            <div class="social-links mb-3">
                <a href="https://www.linkedin.com/in/btcarval" class="text-white me-3">
                    <i class="fab fa-linkedin fa-2x"></i>
                </a>
                <a href="https://github.com/btcarval" class="text-white me-3">
                    <i class="fab fa-github fa-2x"></i>
                </a>
                <a href="mailto:seuemail@example.com" class="text-white">
                    <i class="fas fa-envelope fa-2x"></i>
                </a>
            </div>
            <p class="mb-0">🚀 Transformando a educação através da inovação tecnológica</p>
        </div>
    </footer>
</div>

<!-- Bootstrap JS -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
