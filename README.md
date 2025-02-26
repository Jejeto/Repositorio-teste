<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Exercícios Bootstrap</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <div class="container mt-5">
        <!-- Exercício 1: Sistema de Grid -->
        <div class="row">
            <div class="col-md-4 purpl text-white p-3">Coluna 1</div>
            <div class="col-md-4 bg-success text-white p-3">Coluna 2</div>
            <div class="col-md-4 bg-danger text-white p-3">Coluna 3</div>
        </div>
       
        <!-- Exercício 2: Botões Estilizados -->
        <div class="mt-3">
            <button class="btn btn-primary">Primário</button>
            <button class="btn btn-success">Sucesso</button>
            <button class="btn btn-danger">Perigo</button>
            <button class="btn btn-primary btn-lg">Grande</button>
            <button class="btn btn-primary btn-sm">Pequeno</button>
        </div>

        <!-- Exercício 3: Navbar -->
        <nav class="navbar navbar-expand-lg navbar-light bg-light mt-3">
            <div class="container-fluid">
                <a class="navbar-brand" href="#">Navbar</a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav">
                        <li class="nav-item"><a class="nav-link" href="#">Início</a></li>
                        <li class="nav-item"><a class="nav-link" href="#">Sobre</a></li>
                        <li class="nav-item"><a class="nav-link" href="#">Contato</a></li>
                        <li class="nav-item dropdown">
                            <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown">Serviços</a>
                            <ul class="dropdown-menu">
                                <li><a class="dropdown-item" href="#">Web Design</a></li>
                                <li><a class="dropdown-item" href="#">SEO</a></li>
                            </ul>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>

        <!-- Exercício 4: Cards de Perfil -->
        <div class="card mt-4" style="width: 18rem;">
            <img src="https://via.placeholder.com/150" class="card-img-top" alt="Perfil">
            <div class="card-body">
                <h5 class="card-title">Nome do Usuário</h5>
                <p class="card-text">Cargo do Usuário</p>
                <p class="card-text">Breve descrição do usuário.</p>
                <a href="#" class="btn btn-primary">Ver Perfil</a>
            </div>
        </div>

        <!-- Exercício 5: Formulário de Contato -->
        <form class="mt-4">
            <div class="mb-3">
                <label for="nome" class="form-label">Nome</label>
                <input type="text" class="form-control" id="nome">
            </div>
            <div class="mb-3">
                <label for="email" class="form-label">Email</label>
                <input type="email" class="form-control" id="email">
            </div>
            <div class="mb-3">
                <label for="mensagem" class="form-label">Mensagem</label>
                <textarea class="form-control" id="mensagem" rows="3"></textarea>
            </div>
            <button type="submit" class="btn btn-primary">Enviar</button>
        </form>

        <!-- Exercício 6: Carrossel de Imagens -->
        <div id="carouselExample" class="carousel slide mt-5" data-bs-ride="carousel">
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <img src="https://via.placeholder.com/800x400" class="d-block w-100" alt="Slide 1">
                </div>
                <div class="carousel-item">
                    <img src="https://via.placeholder.com/800x400" class="d-block w-100" alt="Slide 2">
                </div>
                <div class="carousel-item">
                    <img src="https://via.placeholder.com/800x400" class="d-block w-100" alt="Slide 3">
                </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
            </button>
        </div>

        <!-- Exercício 7: Modal -->
        <button type="button" class="btn btn-warning mt-4" data-bs-toggle="modal" data-bs-target="#exampleModal">Abrir Modal</button>
        <div class="modal fade" id="exampleModal" tabindex="-1">
            <div class="modal-dialog">
                <div class="modal-content">
                    <div class="modal-header">
                        <h5 class="modal-title">Título do Modal</h5>
                        <button type="button" class="btn-close" data-bs-dismiss="modal"></button>
                    </div>
                    <div class="modal-body">
                        Conteúdo do modal.
                    </div>
                    <div class="modal-footer">
                        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Fechar</button>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
