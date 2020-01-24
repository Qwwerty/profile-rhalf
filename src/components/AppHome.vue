<template>
  <div>
    <div class="site-wrap">
      <div class="site-mobile-menu site-navbar-target">
        <div class="site-mobile-menu-header">
          <div class="site-mobile-menu-close mt-3">
            <span class="icon-close2 js-menu-toggle"></span>
          </div>
        </div>
        <div class="site-mobile-menu-body"></div>
      </div>

      <header
        class="site-navbar py-4 js-sticky-header site-navbar-target"
        role="banner"
      >
        <div class="container-fluid">
          <div class="row align-items-center justify-content-center">
            <div class="">
              <nav
                class="site-navigation position-relative text-right"
                role="navigation"
              >
                <ul
                  class="site-menu main-menu js-clone-nav mr-auto d-none d-lg-block"
                >
                  <li><a href="#home-section" class="nav-link">Início</a></li>
                  <li>
                    <a href="#services-section" class="nav-link">Serviços</a>
                  </li>
                  <li><a href="#about-section" class="nav-link">Sobre</a></li>
                </ul>
              </nav>
            </div>

            <div class=" text-center mx-5">
              <h1 class="m-0 site-logo"><a href="index.html">Eu.</a></h1>
            </div>

            <div class="text-left">
              <nav class="site-navigation position-relative" role="navigation">
                <ul
                  class="site-menu main-menu js-clone-nav mr-auto d-none d-lg-block"
                >
                  <li>
                    <a href="#portfolio-section" class="nav-link">Portfólio</a>
                  </li>
                  <li>
                    <a href="#clients-section" class="nav-link">Cliente</a>
                  </li>
                  <li>
                    <a href="#contact-section" class="nav-link">Contato</a>
                  </li>
                </ul>
              </nav>

              <div
                class="d-inline-block d-lg-none"
                style="position: relative; top: 3px;"
              >
                <a href="#" class="site-menu-toggle js-menu-toggle float-right"
                  ><span class="icon-menu h3"></span
                ></a>
              </div>
            </div>
          </div>
        </div>
      </header>

      <div class="site-blocks-cover overlay bg-light" id="home-section">
        <div class="container">
          <div class="row justify-content-center">
            <div
              class="col-md-12 mt-lg-5 text-left align-self-center text-intro"
            >
              <div class="row">
                <div class="col-lg-6">
                  <h1 class="text-black">Eu sou o Rhalf</h1>
                  <p class="lead">Eu sou Desenvolvedor Web</p>
                  <p>
                    <a
                      href="#portfolio-section"
                      class="btn smoothscroll btn-primary"
                      >Portfólio</a
                    >
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>

        <img
          src="images/face.png"
          alt="Image"
          class="img-face"
          data-aos="fade"
        />
      </div>

      <div class="site-section" id="services-section">
        <div class="container">
          <div class="row ">
            <div class="col-12 mb-5 position-relative">
              <h2 class="section-title text-center mb-5">Meus Serviços</h2>
            </div>

            <div class="col-md-6 mb-4">
              <div class="service d-flex h-100">
                <div class="service-number mr-4">
                  <span class="icon-style"></span>
                </div>
                <div class="service-about">
                  <h3>UI/UX Designer</h3>
                  <p>
                    Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                    Perferendis ipsum error eligendi molestiae eaque quas,
                    ducimus sequi excepturi?
                  </p>
                </div>
              </div>
            </div>

            <div class="col-md-6 mb-4">
              <div class="service d-flex h-100">
                <div class="service-number mr-4">
                  <span class="icon-business_center"></span>
                </div>
                <div class="service-about">
                  <h3>Web Development</h3>
                  <p>
                    Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                    Perferendis ipsum error eligendi molestiae eaque quas,
                    ducimus sequi excepturi?
                  </p>
                </div>
              </div>
            </div>

            <div class="col-md-6 mb-4">
              <div class="service d-flex h-100">
                <div class="service-number mr-4">
                  <span class="icon-desktop_windows"></span>
                </div>
                <div class="service-about">
                  <h3>Brand &amp; Logo Design</h3>
                  <p>
                    Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                    Perferendis ipsum error eligendi molestiae eaque quas,
                    ducimus sequi excepturi?
                  </p>
                </div>
              </div>
            </div>

            <div class="col-md-6 mb-4">
              <div class="service d-flex h-100">
                <div class="service-number mr-4">
                  <span class="icon-layers"></span>
                </div>
                <div class="service-about">
                  <h3>Web Design</h3>
                  <p>
                    Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                    Perferendis ipsum error eligendi molestiae eaque quas,
                    ducimus sequi excepturi?
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="site-section" id="about-section">
        <div class="container">
          <div class="row ">
            <div class="col-12 mb-4 position-relative">
              <h2 class="section-title">Sobre mim</h2>
            </div>
            <div class="col-lg-4 order-1 order-lg-2 mb-4 mb-lg-0">
              <div class="bg-light pt-5">
                <img src="images/face.png" alt="Image" class="img-fluid" />
              </div>
            </div>
            <div class="col-lg-4 order-2 order-lg-1">
              <p>
               Sou um jovem de 21 anos que busca um futuro promissor na área da computação, apaixonado por
               programação desde criança
              </p>
              <p>
                No momento ainda estou cursando faculdade de ciência da computação
              </p>
            </div>
            <div class="col-lg-4 order-3 order-lg-3">
              <p>
                Um fato sobre mim, não sou pessoa de desistir à primeira tentativa, pois acredito que as maiores bênçãos estão guardadas para quem se esforça em lutar.
              </p>
              <p>
                Meu gosto musical é eletrônica
              </p>
              <p>
                <a href="#contact-section" class="btn smoothscroll btn-primary"
                  >Contate me</a
                >
              </p>
            </div>
          </div>
        </div>
      </div>

      <section class="site-section block__62272" id="portfolio-section">
        <div class="container">
          <div class="row mb-5">
            <div class="col-12 position-relative">
              <h2 class="section-title text-center mb-5">Meu Portfólio</h2>
            </div>
          </div>

          <div id="posts" class="row no-gutter">
            <div
              class="item web col-6 col-sm-6 col-md-6 col-lg-4 col-xl-4 mb-4"
            >
              <a href="images/post_2.jpg" class="item-wrap fancybox">
                <span class="icon-search2"></span>
                <img class="img-fluid" src="images/post_2.jpg" />
              </a>
            </div>
            <div
              class="item web col-6 col-sm-6 col-md-6 col-lg-4 col-xl-4 mb-4"
            >
              <a href="images/post_3.jpg" class="item-wrap fancybox">
                <span class="icon-search2"></span>
                <img class="img-fluid" src="images/post_3.jpg" />
              </a>
            </div>

            <div
              class="item brand col-6 col-sm-6 col-md-6 col-lg-4 col-xl-4 mb-4"
            >
              <a href="images/post_4.jpg" class="item-wrap fancybox">
                <span class="icon-search2"></span>
                <img class="img-fluid" src="images/post_4.jpg" />
              </a>
            </div>

            <div
              class="item design col-6 col-sm-6 col-md-6 col-lg-4 col-xl-4 mb-4"
            >
              <a href="images/post_5.jpg" class="item-wrap fancybox">
                <span class="icon-search2"></span>
                <img class="img-fluid" src="images/post_5.jpg" />
              </a>
            </div>

            <div
              class="item web col-6 col-sm-6 col-md-6 col-lg-4 col-xl-4 mb-4"
            >
              <a href="images/post_6.jpg" class="item-wrap fancybox">
                <span class="icon-search2"></span>
                <img class="img-fluid" src="images/post_6.jpg" />
              </a>
            </div>

            <div
              class="item brand col-6 col-sm-6 col-md-6 col-lg-4 col-xl-4 mb-4"
            >
              <a href="images/post_2.jpg" class="item-wrap fancybox">
                <span class="icon-search2"></span>
                <img class="img-fluid" src="images/post_2.jpg" />
              </a>
            </div>

            <div
              class="item web col-6 col-sm-6 col-md-6 col-lg-4 col-xl-4 mb-4"
            >
              <a href="images/post_3.jpg" class="item-wrap fancybox">
                <span class="icon-search2"></span>
                <img class="img-fluid" src="images/post_3.jpg" />
              </a>
            </div>

            <div
              class="item design col-6 col-sm-6 col-md-6 col-lg-4 col-xl-4 mb-4"
            >
              <a href="images/post_4.jpg" class="item-wrap fancybox">
                <span class="icon-search2"></span>
                <img class="img-fluid" src="images/post_4.jpg" />
              </a>
            </div>

            <div
              class="item web col-6 col-sm-6 col-md-6 col-lg-4 col-xl-4 mb-4"
            >
              <a href="images/post_6.jpg" class="item-wrap fancybox">
                <span class="icon-search2"></span>
                <img class="img-fluid" src="images/post_6.jpg" />
              </a>
            </div>
          </div>
        </div>
      </section>

      <section class="site-section bg-dark">
        <div class="container">
          <div class="row">
            <div class="col-12 mb-5 position-relative">
              <h2 class="section-title text-center mb-5 text-white">
                Depoimentos
              </h2>
            </div>
          </div>
          <div class="owl-carousel slide-one-item">
            <div class="slide">
              <blockquote>
                <p>
                  O importante não é vencer todos os dias, mas lutar sempre.
                </p>
                <p><cite>&mdash; Waldemar Valle Martins</cite></p>
              </blockquote>
            </div>
            <div class="slide">
              <blockquote>
                <p>
                  Nossos fracassos, às vezes, são mais frutíferos do que os êxitos.
                </p>
                <p><cite>&mdash; Henry Ford</cite></p>
              </blockquote>
            </div>
            <div class="slide">
              <blockquote>
                <p>
                  Viver é enfrentar um problema atrás do outro. O modo como você o encara é que faz a diferença.
                </p>
                <p><cite>&mdash; Benjamin Franklin</cite></p>
              </blockquote>
            </div>
          </div>
        </div>
      </section>

      <section class="site-section" id="clients-section">
        <div class="container">
          <div class="row">
            <div class="col-12 mb-5 position-relative">
              <h2 class="section-title text-center">Clientes</h2>
            </div>
            <div class="col-6 col-sm-6 col-md-4 col-lg-4 text-center">
              <img src="images/logo_1.jpg" alt="Image" class="img-fluid" />
            </div>
            <div class="col-6 col-sm-6 col-md-4 col-lg-4 text-center">
              <img src="images/logo_2.jpg" alt="Image" class="img-fluid" />
            </div>
            <div class="col-6 col-sm-6 col-md-4 col-lg-4 text-center">
              <img src="images/logo_3.jpg" alt="Image" class="img-fluid" />
            </div>
            <div class="col-6 col-sm-6 col-md-4 col-lg-4 text-center">
              <img src="images/logo_4.jpg" alt="Image" class="img-fluid" />
            </div>

            <div class="col-6 col-sm-6 col-md-4 col-lg-4 text-center">
              <img src="images/logo_5.jpg" alt="Image" class="img-fluid" />
            </div>
            <div class="col-6 col-sm-6 col-md-4 col-lg-4 text-center">
              <img src="images/logo_6.jpg" alt="Image" class="img-fluid" />
            </div>
          </div>
        </div>
      </section>

      <section class="site-section" id="contact-section">
        <div class="container">
          <div class="row">
            <div class="col-12 mb-5 position-relative">
              <h2 class="section-title text-center mb-5">Formulário de Contato</h2>
            </div>
          </div>
          <form action="#" class="form">
            <div class="row mb-4">
              <div class="form-group col-6">
                <input
                  type="text"
                  class="form-control"
                  placeholder="Primeiro nome"
                />
              </div>
              <div class="form-group col-6">
                <input
                  type="text"
                  class="form-control"
                  placeholder="Último nome"
                />
              </div>
            </div>

            <div class="row mb-4">
              <div class="form-group col-12">
                <input
                  type="email"
                  class="form-control"
                  placeholder="Endereço de E-mail"
                />
              </div>
            </div>

            <div class="row mb-4">
              <div class="form-group col-12">
                <input
                  type="text"
                  class="form-control"
                  placeholder="Assunto da mensagem"
                />
              </div>
            </div>

            <div class="row mb-4">
              <div class="form-group col-12">
                <textarea
                  name=""
                  id=""
                  cols="30"
                  rows="10"
                  class="form-control"
                  placeholder="Digite sua mensagem aqui .."
                ></textarea>
              </div>
            </div>

            <div class="row">
              <div class="col-md-6">
                <input
                  type="submit"
                  class="btn btn-primary"
                  value="Send Message"
                />
              </div>
            </div>
          </form>
        </div>
      </section>

      <footer class="site-section bg-light footer">
        <div class="container">
          <div class="row mb-5">
            <div class="col-md-3">
              <h3 class="footer-title">Me Address</h3>
              <p>
                Ubá, Minas Gerais, Brasil
              </p>
            </div>
            <div class="col-md-5 mx-auto">
              <div class="row">
                <div class="col-lg-4">
                  <h3 class="footer-title">Serviços</h3>
                  <ul class="list-unstyled">
                    <li><a href="#">Web</a></li>
                    <li><a href="#">Graphic</a></li>
                    <li><a href="#">Branding</a></li>
                  </ul>
                </div>
                <div class="col-lg-4">
                  <h3 class="footer-title">Resources</h3>
                  <ul class="list-unstyled">
                    <li><a href="#">Web App</a></li>
                    <li><a href="#">Graphic</a></li>
                    <li><a href="#">Branding</a></li>
                  </ul>
                </div>
                <div class="col-lg-4">
                  <h3 class="footer-title">Links</h3>
                  <ul class="list-unstyled">
                    <li><a href="#">Web App</a></li>
                    <li><a href="#">Graphic</a></li>
                    <li><a href="#">Branding</a></li>
                  </ul>
                </div>
              </div>
            </div>
            <div class="col-md-3">
              <h3 class="footer-title">Follow Me</h3>
              <a href="#" class="social-circle"
                ><span class="icon-twitter"></span
              ></a>
              <a href="#" class="social-circle"
                ><span class="icon-facebook"></span
              ></a>
              <a href="#" class="social-circle"
                ><span class="icon-instagram"></span
              ></a>
              <a href="#" class="social-circle"
                ><span class="icon-dribbble"></span
              ></a>
              <a href="#" class="social-circle"
                ><span class="icon-linkedin"></span
              ></a>
            </div>
          </div>

          <div class="row">
            <div class="col-12 text-center">
              <p>
                <!-- Link back to Colorlib can't be removed. Template is licensed under CC BY 3.0. -->
                Copyright &copy;
                All rights reserved | This template is made with
                <i class="icon-heart text-danger" aria-hidden="true"></i> by
                <a href="https://colorlib.com" target="_blank">Colorlib</a>
                <!-- Link back to Colorlib can't be removed. Template is licensed under CC BY 3.0. -->
              </p>
            </div>
          </div>
        </div>
      </footer>
    </div>
    <!-- .site-wrap -->
  </div>
</template>

<script>
export default {
  name: "AppHome",
  components: {}
};
</script>

<style></style>
