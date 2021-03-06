<!DOCTYPE html>

<head>
    <meta charset="utf-8">
    <title>Ricardo Macedo Arquitetura</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">

    <!-- Slick slider -->
    <link rel="stylesheet" href="assets\util\slick\slick.css">

    <!-- AOS Animation -->
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">

</head>
<html>

<body>

    <!-- Nav Bar -
Menu de navegação do site -->
    <nav class="site-nav">
        <button class="hamburguer">Menu</button>
        <ul class="nav-ul">
            <li><a href="" class="sobre-nos-link">Sobre Nós</a></li>
            <li><a href="" class="depoimentos-link">Depoimentos</a></li>
            <li><a href="" class="projetos-link">Projetos</a></li>
            <li><a href="" class="contato-link">Entre em Contato</a></li>
        </ul>
    </nav>

    <!-- Slider -
Carrossel de projetos -->
    <h1 class="titulo">Ricardo Macedo Arquitetura</h1>
    <div class="slider">
        <div class="slider-projeto projeto-1"><a href="" class="legenda">Legenda 1</a></div>
        <div class="slider-projeto projeto-2"><a href="" class="legenda">Legenda 2</a></div>
        <div class="slider-projeto projeto-3"><a href="" class="legenda">Legenda 3</a></div>
    </div>

    <!-- Sobre Nós -->
    <div class="sobre-nos">
        <div class="wrapper">
            <section>
                <div class="sobre-nos-card card">
                    <h1>Sobre Nós</h1>
                </div>
                <p data-aos="fade-right" data-aos-duration="2000" class="sobre-nos-p">Formado pela Faculdade de Belas
                    Artes de São Paulo, atua há 28 anos no mercado.
                    Inicialmente,
                    dedicou-se à area de alimentação (restaurantes, praças de alimentação, cozinhas e refeitórios
                    industriais) realizando projetos junto às grandes cadeias americanas de fast food que na época,
                    ingressavam no país. Ao longo de sua carreira, voltou-se para a elaboração e execução de projetos e
                    obras com elevado grau de complexidade, envolvendo áreas residenciais, comerciais e corporativas.
                </p>
            </section>
            <section>
                <div class="missao-card card">
                    <h1>Nossa Missão</h1>
                </div>
                <p data-aos="fade-left" data-aos-duration="2000" class="missao-p">Contando sempre com equipe de obra
                    especializada. Alinhando-se à arquitetura
                    sustentável esteve em
                    BedZed ao sul de Londres para estudar o conceito Green Building, projeto arquitetônico desenvolvido
                    de acordo com normas de preservação e conservação de meio ambiente, através de economia e
                    reutilização de água, energia e reciclagem de materiais.Para realizar um aprofundamento em seu
                    mestrado, esteve em Chicago visitando obras de arquitetos como Mies van der Rohe e Frank Lloyd
                    Wright.
                </p>
            </section>
        </div>
    </div>

    <!-- Depoimentos -->
    <div class="depoimentos">
        <div class="wrapper">
            <h1 class="titulo-secao">
                Depoimentos
            </h1>
            <section>
                <article data-aos="fade-right" data-aos-duration="2000">
                    <img src="assets/img/cliente1.png" alt="">
                    <p class="depoimento-cliente-1">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque
                        quis lacinia mi, et condimentum
                        lacus. Donec elementum velit ipsum, non laoreet mauris ultricies ac.</p>
                </article>
                <article data-aos="fade-left" data-aos-duration="2000">
                    <p class="depoimento-cliente-2">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque
                        quis lacinia mi, et condimentum
                        lacus. Donec elementum velit ipsum, non laoreet mauris ultricies ac.</p>
                    <img src="assets/img/cliente2.png" alt="">
                </article>
                <article data-aos="fade-right" data-aos-duration="2000">
                    <img src="assets/img/cliente3.png" alt="">
                    <p class="depoimento-cliente-3">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque
                        quis lacinia mi, et condimentum
                        lacus. Donec elementum velit ipsum, non laoreet mauris ultricies ac.</p>
                </article>
            </section>
        </div>
    </div>

    <!-- Projetos -->
    <div class="projetos">
        <div class="wrapper">
            <h1 class="titulo-secao" id="titulo-projetos">
                Projetos
            </h1>
            <section>
                <article data-aos="flip-left" class="projeto projeto1"></article>
                <article data-aos="flip-right" class="projeto projeto2"></article>
                <article data-aos="flip-left" class="projeto projeto3"></article>
                <article data-aos="flip-right" class="projeto projeto4"></article>
                <article data-aos="flip-left" class="projeto projeto5"></article>
                <article data-aos="flip-right" class="projeto projeto6"></article>

                <div class="modal-projeto1 modal">
                    <div class="conteudo-modal">
                        <h1>Título</h1>
                        <img class="fechar-modal" src="assets/img/close.png" alt="Fechar">
                        <img src="assets/img/capa-projeto1.png" alt="Projeto 1" class="capa-modal">
                        <p class="descricao-modal">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque quis
                            lacinia mi, et condimentum lacus. Donec elementum velit ipsum, non laoreet mauris ultricies
                            ac.
                        </p>
                        <section>
                            <img src="assets/img/detalhes1-projeto1.png" alt="">
                            <p class="legenda-modal">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque
                                quis lacinia mi, et condimentum lacus. Donec elementum velit ipsum, non laoreet mauris
                                ultricies ac. </p>
                        </section>
                        <section>
                            <img src="assets/img/detalhes2-projeto1.png" alt="">
                            <p class="legenda-modal">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque
                                quis lacinia mi, et condimentum lacus. Donec elementum velit ipsum, non laoreet mauris
                                ultricies ac. </p>
                        </section>
                        <h2 class="fechar-modal-final">Fechar</h2>
                    </div>
                </div>

                <div class="modal-projeto2 modal">
                    <div class="conteudo-modal">
                        <h1>Título2</h1>
                        <img class="fechar-modal" src="assets/img/close.png" alt="Fechar">
                        <img src="assets/img/capa-projeto1.png" alt="Projeto 1" class="capa-modal">
                        <p class="descricao-modal">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque quis
                            lacinia mi, et condimentum lacus. Donec elementum velit ipsum, non laoreet mauris ultricies
                            ac.
                        </p>
                        <section>
                            <img src="assets/img/detalhes1-projeto1.png" alt="">
                            <p class="legenda-modal">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque
                                quis lacinia mi, et condimentum lacus. Donec elementum velit ipsum, non laoreet mauris
                                ultricies ac. </p>
                        </section>
                        <section>
                            <img src="assets/img/detalhes2-projeto1.png" alt="">
                            <p class="legenda-modal">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque
                                quis lacinia mi, et condimentum lacus. Donec elementum velit ipsum, non laoreet mauris
                                ultricies ac. </p>
                        </section>
                        <h2 class="fechar-modal-final">Fechar</h2>
                    </div>
                </div>

                <div class="modal-projeto3 modal">
                    <div class="conteudo-modal">
                        <h1>Título3</h1>
                        <img class="fechar-modal" src="assets/img/close.png" alt="Fechar">
                        <img src="assets/img/capa-projeto1.png" alt="Projeto 1" class="capa-modal">
                        <p class="descricao-modal">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque quis
                            lacinia mi, et condimentum lacus. Donec elementum velit ipsum, non laoreet mauris ultricies
                            ac.
                        </p>
                        <section>
                            <img src="assets/img/detalhes1-projeto1.png" alt="">
                            <p class="legenda-modal">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque
                                quis lacinia mi, et condimentum lacus. Donec elementum velit ipsum, non laoreet mauris
                                ultricies ac. </p>
                        </section>
                        <section>
                            <img src="assets/img/detalhes2-projeto1.png" alt="">
                            <p class="legenda-modal">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque
                                quis lacinia mi, et condimentum lacus. Donec elementum velit ipsum, non laoreet mauris
                                ultricies ac. </p>
                        </section>
                        <h2 class="fechar-modal-final">Fechar</h2>
                    </div>
                </div>

                <div class="modal-projeto4 modal">
                    <div class="conteudo-modal">
                        <h1>Título4</h1>
                        <img class="fechar-modal" src="assets/img/close.png" alt="Fechar">
                        <img src="assets/img/capa-projeto1.png" alt="Projeto 1" class="capa-modal">
                        <p class="descricao-modal">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque quis
                            lacinia mi, et condimentum lacus. Donec elementum velit ipsum, non laoreet mauris ultricies
                            ac.
                        </p>
                        <section>
                            <img src="assets/img/detalhes1-projeto1.png" alt="">
                            <p class="legenda-modal">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque
                                quis lacinia mi, et condimentum lacus. Donec elementum velit ipsum, non laoreet mauris
                                ultricies ac. </p>
                        </section>
                        <section>
                            <img src="assets/img/detalhes2-projeto1.png" alt="">
                            <p class="legenda-modal">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque
                                quis lacinia mi, et condimentum lacus. Donec elementum velit ipsum, non laoreet mauris
                                ultricies ac. </p>
                        </section>
                        <h2 class="fechar-modal-final">Fechar</h2>
                    </div>
                </div>

                <div class="modal-projeto5 modal">
                    <div class="conteudo-modal">
                        <h1>Título5</h1>
                        <img class="fechar-modal" src="assets/img/close.png" alt="Fechar">
                        <img src="assets/img/capa-projeto1.png" alt="Projeto 1" class="capa-modal">
                        <p class="descricao-modal">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque quis
                            lacinia mi, et condimentum lacus. Donec elementum velit ipsum, non laoreet mauris ultricies
                            ac.
                        </p>
                        <section>
                            <img src="assets/img/detalhes1-projeto1.png" alt="">
                            <p class="legenda-modal">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque
                                quis lacinia mi, et condimentum lacus. Donec elementum velit ipsum, non laoreet mauris
                                ultricies ac. </p>
                        </section>
                        <section>
                            <img src="assets/img/detalhes2-projeto1.png" alt="">
                            <p class="legenda-modal">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque
                                quis lacinia mi, et condimentum lacus. Donec elementum velit ipsum, non laoreet mauris
                                ultricies ac. </p>
                        </section>
                        <h2 class="fechar-modal-final">Fechar</h2>
                    </div>
                </div>

                <div class="modal-projeto6 modal">
                    <div class="conteudo-modal">
                        <h1>Título6</h1>
                        <img class="fechar-modal" src="assets/img/close.png" alt="Fechar">
                        <img src="assets/img/capa-projeto1.png" alt="Projeto 1" class="capa-modal">
                        <p class="descricao-modal">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque quis
                            lacinia mi, et condimentum lacus. Donec elementum velit ipsum, non laoreet mauris ultricies
                            ac.
                        </p>
                        <section>
                            <img src="assets/img/detalhes1-projeto1.png" alt="">
                            <p class="legenda-modal">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque
                                quis lacinia mi, et condimentum lacus. Donec elementum velit ipsum, non laoreet mauris
                                ultricies ac. </p>
                        </section>
                        <section>
                            <img src="assets/img/detalhes2-projeto1.png" alt="">
                            <p class="legenda-modal">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque
                                quis lacinia mi, et condimentum lacus. Donec elementum velit ipsum, non laoreet mauris
                                ultricies ac. </p>
                        </section>
                        <h2 class="fechar-modal-final">Fechar</h2>
                    </div>
                </div>

            </section>
        </div>
    </div>

    <!-- Entre em Contato -->
    <div class="contato">
        <div class="wrapper">
            <section class="contato-informacoes">
                <h3>Ricardo Macedo Arquitetura</h3>
                <p>Rua Dr. Tomás Carvalhal, 714 - Conjunto 2 - São Paulo</p>
                <p><a href="mailto:ricmacedo@terra.com.br">ricmacedo@terra.com.br</a></p>
                <p>Tel +55 11 3887 6669</p>
                <p>Cel +55 11 97307 2645</p>
            </section>
            <section class="contato-formulario">
                <form method="POST" action="https://formspree.io/gabrieltomonari@gmail.com">
                    <input type="email" name="email" placeholder="Email">
                    <button type="submit">Enviar</button>
                    <textarea name="message" placeholder="Mensagem"></textarea>
                </form>
            </section>
        </div>
    </div>

    <!-- Scripts -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    <script src="assets\util\slick\slick.min.js"></script>
    <script src="assets\js\jquery.js"></script>
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>

</body>

</html>