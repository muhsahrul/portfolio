<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no" />
    <link rel="icon" type="image/x-icon" href="assets/MS.png" />
    <script src="https://use.fontawesome.com/releases/v5.15.3/js/all.js" crossorigin="anonymous"></script>
    <!-- Google fonts-->
    <link href="https://fonts.googleapis.com/css?family=Source+Sans+Pro:300,400,700,300italic,400italic,700italic" rel="stylesheet" type="text/css" />
    <link href="https://fonts.googleapis.com/css?family=Merriweather+Sans:400,700" rel="stylesheet" />
    <link href="https://fonts.googleapis.com/css?family=Merriweather:400,300,300italic,400italic,700,700italic" rel="stylesheet" type="text/css" />

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous" />
    <link href="css/styles.css" rel="stylesheet" />
    <title>Hello, world!</title>
  </head>
  <body id="page-top">
    <nav class="navbar navbar-expand-lg navbar-light fixed-top py-3" id="mainNav">
      <div class="container">
        <a class="navbar-brand" href="#page-top">Portfolio</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarResponsive">
          <ul class="navbar-nav ms-auto my-2 my-lg-0">
            <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
            <li class="nav-item"><a class="nav-link" href="#portfolio">Portfolio</a></li>
            <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
          </ul>
        </div>
      </div>
    </nav>
    <!-- Masthead-->
    <header class="masthead d-flex align-items-center">
      <div class="container px-4 px-lg-5 text-center">
        <h1 class="mb-1 fw-bold text-white">Muhammad Sahrul</h1>
        <h3 class="mb-5 fw-normal text-white">Back End Developer</h3>
        <a class="btn btn-outline-light btn-xl" target="_blank" href="https://drive.google.com/u/0/uc?id=1Rp2mf1ZQToXX_9W9G7ZbQ3NfjPu7_fGL&export=download">Download CV</a>
      </div>
    </header>
    <!-- About Me-->
    <section class="page-section" id="about">
      <div class="container px-4 px-lg-5">
        <h2 class="text-center mt-0">About Me</h2>
        <hr class="divider" />
        <div class="row gx-4 gx-lg-5">
          <div class="col-lg-4 col-md-6 text-center">
            <div class="img-about">
              <img class="mx-auto my-auto rounded-circle border-0" src="assets/me.jpeg" alt="..." />
              <!-- <h4>Muhammad Sahrul</h4> -->
              <!-- <p class="text-muted">Back End Developer</p> -->
            </div>
          </div>
          <div class="col-lg-7 col-md-6">
            <p class="text-muted mb-3">
              Saya seorang lulusan S1 Sistem Informasi Universitas Merdeka Malang, mempunyai kemampuan dalam pemrograman web PHP, mahir menggunakan framework Codeigniter dan database MySQL/MariaDB. Saya sudah membuat beberapa proyek web
              sederhana untuk orang-orang yang membutuhkan layanan saya. Orang yang disiplin, dapat beradaptasi dengan orang lain, dan senang belajar hal-hal baru.
              <!-- I am an information system graduate. Have skills in PHP web programming. I'm also proficient in using the Codeigniter framework and MySQL/MariaDB database. I've made a few simple web projects for people who need my services. A
              disciplined person, have a good sense of teamwork, and eager to learn new things. -->
            </p>
            <h3 class="h4 mb-2">Skills</h3>
            <span class="btn btn-default text-white" style="background-color: #ed6727">HTML</span>
            <span class="btn btn-default text-white" style="background-color: #2bacdf">CSS</span>
            <span class="btn btn-default text-white" style="background-color: #fad838">Javascript</span>
            <span class="btn btn-default text-white" style="background-color: #8a92bf">PHP</span>
            <div class="mt-2">
              <a class="btn btn-default text-white" style="background-color: #464646">Wordpress</a>
              <a class="btn btn-default text-white" style="background-color: #ee4323">Codeigniter</a>
              <a class="btn btn-default text-white" style="background-color: #00618a">MySQL/MariaDB</a>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!--Portfolio-->
    <section class="page-section bg-gray" id="portfolio">
      <div class="container px-4 px-lg-5">
        <h2 class="text-center mt-0">Portfolio</h2>
        <hr class="divider" />
        <div class="row">
          <div class="col-lg-4 col-sm-6 mb-4 mt-2">
            <!-- Portfolio item 1-->
            <div class="portfolio-item">
              <a class="portfolio-link" data-bs-toggle="modal" href="#portfolioModal1">
                <!-- <div class="portfolio-hover">
                  <div class="portfolio-hover-content"><i class="fas fa-plus fa-3x"></i></div>
                </div> -->
                <img class="img-fluid" style="min-height: 100%; height: 170px; object-fit: cover" src="assets/portfolio/koperasi.PNG" alt="..." />
              </a>
              <div class="portfolio-caption">
                <div class="portfolio-caption-heading fw-normal fs-5">Aplikasi Koperasi Simpan Pinjam</div>
                <!-- <div class="portfolio-caption-subheading text-muted">Illustration</div> -->
              </div>
            </div>
          </div>
          <div class="col-lg-4 col-sm-6 mb-4 mt-2">
            <!-- Portfolio item 1-->
            <div class="portfolio-item">
              <a class="portfolio-link" data-bs-toggle="modal" href="#portfolioModal2">
                <!-- <div class="portfolio-hover">
                  <div class="portfolio-hover-content"><i class="fas fa-plus fa-3x"></i></div>
                </div> -->
                <img class="img-fluid" style="min-height: 100%; height: 170px; object-fit: cover" src="assets/portfolio/cokelat.PNG" alt="..." />
              </a>
              <div class="portfolio-caption">
                <div class="portfolio-caption-heading fw-normal fs-5">Web Profile dan Penjualan UMKM</div>
                <!-- <div class="portfolio-caption-subheading text-muted">Illustration</div> -->
              </div>
            </div>
          </div>
          <div class="col-lg-4 col-sm-6 mb-4 mt-2">
            <!-- Portfolio item 1-->
            <div class="portfolio-item">
              <a class="portfolio-link" data-bs-toggle="modal" href="#portfolioModal3">
                <!-- <div class="portfolio-hover">
                  <div class="portfolio-hover-content"><i class="fas fa-plus fa-3x"></i></div>
                </div> -->
                <img class="img-fluid" style="min-height: 100%; height: 170px; object-fit: cover" src="assets/portfolio/kontak2.PNG" alt="..." />
              </a>
              <div class="portfolio-caption">
                <div class="portfolio-caption-heading fw-normal fs-5">Web Kontak dan Cari Kata Baku</div>
                <!-- <div class="portfolio-caption-subheading text-muted">Illustration</div> -->
              </div>
            </div>
          </div>
          <div class="col-lg-4 col-sm-6 mb-4 mt-2">
            <!-- Portfolio item 1-->
            <div class="portfolio-item">
              <a class="portfolio-link" data-bs-toggle="modal" href="#portfolioModal4">
                <!-- <div class="portfolio-hover">
                  <div class="portfolio-hover-content"><i class="fas fa-plus fa-3x"></i></div>
                </div> -->
                <img class="img-fluid" style="min-height: 100%; height: 170px; object-fit: cover" src="assets/portfolio/chat.PNG" alt="..." />
              </a>
              <div class="portfolio-caption">
                <div class="portfolio-caption-heading fw-normal fs-5">Chatbot FAQ Helpdesk</div>
                <!-- <div class="portfolio-caption-subheading text-muted">Illustration</div> -->
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="page-section" id="contact">
      <div class="container px-4 px-lg-5 text-center align-items-center">
        <h2 class="text-center mt-0">Contact</h2>
        <hr class="divider" />
        <div class="row">
          <ul class="list-inline mb-5">
            <li class="list-inline-item">
              <a class="social-link rounded-circle text-white" target="_blank" href="https://api.whatsapp.com/send?phone=6285336167970"><i class="fab fa-whatsapp"></i></a>
            </li>
            <li class="list-inline-item">
              <a class="social-link rounded-circle text-white" target="_blank" href="https://mail.google.com/mail/u/0/?fs=1&to=msahrul1608@gmail.com&su=Your+Subject+Here&body=Write+Your+Message...&tf=cm"><i class="far fa-envelope"></i></a>
            </li>
            <li class="list-inline-item">
              <a class="social-link rounded-circle text-white" target="_blank" href="https://www.instagram.com/md.sahrul/"><i class="fab fa-instagram"></i></a>
            </li>
            <li class="list-inline-item">
              <a class="social-link rounded-circle text-white" target="_blank" href="https://www.linkedin.com/in/muh-sahrul16/"><i class="fab fa-linkedin-in"></i></a>
            </li>
          </ul>
        </div>
      </div>
    </section>
    <!-- Footer-->
    <footer class="bg-linear py-4">
      <div class="container px-4 px-lg-5"><div class="small text-center text-white">Copyright &copy; 2021 - Muhammad Sahrul.</div></div>
    </footer>

    <!-- Portfolio item 1 modal popup-->
    <div class="portfolio-modal modal fade" id="portfolioModal1" tabindex="-1" role="dialog" aria-hidden="true">
      <div class="modal-dialog">
        <div class="modal-content">
          <div class="close-modal" data-bs-dismiss="modal"><img src="assets/close-icon.svg" alt="Close modal" /></div>
          <div class="container">
            <div class="row justify-content-center">
              <div class="col-lg-12">
                <div class="modal-body">
                  <!-- Project details-->
                  <h4 class="text-uppercase mb-4">Web Koperasi Simpan Pinjam Perhutani Malang</h4>
                  <div id="carousel1" class="carousel slide" data-bs-ride="carousel">
                    <div class="carousel-inner">
                      <div class="carousel-item active">
                        <img src="assets/portfolio/koperasi.PNG" class="d-block w-100" alt="..." />
                      </div>
                      <div class="carousel-item">
                        <img src="assets/portfolio/koperasi4.PNG" class="d-block w-100" alt="..." />
                      </div>
                      <div class="carousel-item">
                        <img src="assets/portfolio/koperasi2.PNG" class="d-block w-100" alt="..." />
                      </div>
                      <div class="carousel-item">
                        <img src="assets/portfolio/koperasi5.PNG" class="d-block w-100" alt="..." />
                      </div>
                      <div class="carousel-item">
                        <img src="assets/portfolio/koperasi3.PNG" class="d-block w-100" alt="..." />
                      </div>
                    </div>
                    <button class="carousel-control-prev" type="button" data-bs-target="#carousel1" data-bs-slide="prev">
                      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                      <span class="visually-hidden">Previous</span>
                    </button>
                    <button class="carousel-control-next" type="button" data-bs-target="#carousel1" data-bs-slide="next">
                      <span class="carousel-control-next-icon" aria-hidden="true"></span>
                      <span class="visually-hidden">Next</span>
                    </button>
                  </div>
                  <p class="text-start m-1">
                    Aplikasi koperasi simpan pinjam ini dibagun menggunakan bahasa pemrograman PHP dan framework Codeignier 3. Berguna untuk memudahkan admin dalam melakukan pencatatan transaksi ke nasabah seperti fitur mengelola simpanan,
                    pinjaman, pengajuan pinjaman dan investasi tabungan. fitur-fitur dari aplikasi ini antara lain :
                  </p>
                  <ul class="text-start">
                    <li>Multi user</li>
                    <li>pembagian SHU</li>
                    <li>Pembukuan usaha tahunan</li>
                    <li>perhitungan denda</li>
                    <li>cetak laporan berbentuk PDF</li>
                  </ul>
                  <button class="btn btn-danger btn-xl text-uppercase" data-bs-dismiss="modal" type="button">
                    <i class="fas fa-times me-1"></i>
                    Close
                  </button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Portfolio item 2 modal popup-->
    <div class="portfolio-modal modal fade" id="portfolioModal2" tabindex="-1" role="dialog" aria-hidden="true">
      <div class="modal-dialog">
        <div class="modal-content">
          <div class="close-modal" data-bs-dismiss="modal"><img src="assets/close-icon.svg" alt="Close modal" /></div>
          <div class="container">
            <div class="row justify-content-center">
              <div class="col-lg-12">
                <div class="modal-body">
                  <!-- Project details-->
                  <h4 class="text-uppercase mb-4">Web Profile dan Penjualan UMKM</h4>
                  <div id="carousel2" class="carousel slide" data-bs-ride="carousel">
                    <div class="carousel-inner">
                      <div class="carousel-item active">
                        <img src="assets/portfolio/cokelat.PNG" class="d-block w-100" alt="..." />
                      </div>
                      <div class="carousel-item">
                        <img src="assets/portfolio/cokelat1.PNG" class="d-block w-100" alt="..." />
                      </div>
                      <div class="carousel-item">
                        <img src="assets/portfolio/cokelat2.PNG" class="d-block w-100" alt="..." />
                      </div>
                      <div class="carousel-item">
                        <img src="assets/portfolio/cokelat3.PNG" class="d-block w-100" alt="..." />
                      </div>
                      <div class="carousel-item">
                        <img src="assets/portfolio/cokelat_admin.PNG" class="d-block w-100" alt="..." />
                      </div>
                      <div class="carousel-item">
                        <img src="assets/portfolio/cokelat4.PNG" class="d-block w-100" alt="..." />
                      </div>
                    </div>
                    <button class="carousel-control-prev" type="button" data-bs-target="#carousel2" data-bs-slide="prev">
                      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                      <span class="visually-hidden">Previous</span>
                    </button>
                    <button class="carousel-control-next" type="button" data-bs-target="#carousel2" data-bs-slide="next">
                      <span class="carousel-control-next-icon" aria-hidden="true"></span>
                      <span class="visually-hidden">Next</span>
                    </button>
                  </div>
                  <p class="text-start m-1">
                    Web profile dan penjualan UMKM ini dibagun menggunakan bahasa pemrograman PHP dan framework Codeignier 4. Berguna untuk memudahkan para pemilik usaha UMKM untuk mempromosikan usahanya dan mengatur produk-produk yang akan
                    dijual. fitur-fitur dari aplikasi ini antara lain :
                  </p>
                  <ul class="text-start">
                    <li>Multi user</li>
                    <li>Keranjang belanja</li>
                    <li>pengelolaan produk</li>
                    <li>pengelolaan pesanan</li>
                  </ul>
                  <button class="btn btn-danger btn-xl text-uppercase" data-bs-dismiss="modal" type="button">
                    <i class="fas fa-times me-1"></i>
                    Close
                  </button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Portfolio item 3 modal popup-->
    <div class="portfolio-modal modal fade" id="portfolioModal3" tabindex="-1" role="dialog" aria-hidden="true">
      <div class="modal-dialog">
        <div class="modal-content">
          <div class="close-modal" data-bs-dismiss="modal"><img src="assets/close-icon.svg" alt="Close modal" /></div>
          <div class="container">
            <div class="row justify-content-center">
              <div class="col-lg-12">
                <div class="modal-body">
                  <!-- Project details-->
                  <h4 class="text-uppercase mb-4">Web Kontak dan Cari Kata Baku</h4>
                  <div id="carousel3" class="carousel slide" data-bs-ride="carousel">
                    <div class="carousel-inner">
                      <div class="carousel-item active">
                        <img src="assets/portfolio/kontak2.PNG" class="d-block w-100" alt="..." />
                      </div>
                      <div class="carousel-item">
                        <img src="assets/portfolio/kontak1.PNG" class="d-block w-100" alt="..." />
                      </div>
                      <div class="carousel-item">
                        <img src="assets/portfolio/kontak3.PNG" class="d-block w-100" alt="..." />
                      </div>
                      <div class="carousel-item">
                        <img src="assets/portfolio/kontak4.PNG" class="d-block w-100" alt="..." />
                      </div>
                    </div>
                    <button class="carousel-control-prev" type="button" data-bs-target="#carousel3" data-bs-slide="prev">
                      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                      <span class="visually-hidden">Previous</span>
                    </button>
                    <button class="carousel-control-next" type="button" data-bs-target="#carousel3" data-bs-slide="next">
                      <span class="carousel-control-next-icon" aria-hidden="true"></span>
                      <span class="visually-hidden">Next</span>
                    </button>
                  </div>
                  <p class="text-start m-1">
                    Web kontak dan cari kata baku ini dibagun menggunakan bahasa pemrograman PHP dan framework Codeignier 4. Berguna untuk memudahkan para siswa yang kesulitan mencari kontak dari siswa lain, agar siswa dapat berbahasa yang
                    baik sesuai kata baku disediakan menu pencarian kata baku yang terhubung dengan Kateglo menggunakan API. fitur-fitur dari aplikasi ini antara lain :
                  </p>
                  <ul class="text-start">
                    <li>Multi user</li>
                    <li>pengelolaan kontak siswa</li>
                    <li>API untuk pecarian kata baku</li>
                  </ul>
                  <button class="btn btn-danger btn-xl text-uppercase" data-bs-dismiss="modal" type="button">
                    <i class="fas fa-times me-1"></i>
                    Close
                  </button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Portfolio item 4 modal popup-->
    <div class="portfolio-modal modal fade" id="portfolioModal4" tabindex="-1" role="dialog" aria-hidden="true">
      <div class="modal-dialog">
        <div class="modal-content">
          <div class="close-modal" data-bs-dismiss="modal"><img src="assets/close-icon.svg" alt="Close modal" /></div>
          <div class="container">
            <div class="row justify-content-center">
              <div class="col-lg-12">
                <div class="modal-body">
                  <!-- Project details-->
                  <h4 class="text-uppercase mb-4">Web Kontak dan Cari Kata Baku</h4>
                  <div id="carousel4" class="carousel slide" data-bs-ride="carousel">
                    <div class="carousel-inner">
                      <div class="carousel-item active">
                        <img src="assets/portfolio/chat.PNG" class="d-block w-100" alt="..." />
                      </div>
                      <div class="carousel-item">
                        <img src="assets/portfolio/chat1.PNG" class="d-block w-100" alt="..." />
                      </div>
                      <div class="carousel-item">
                        <img src="assets/portfolio/chat2.PNG" class="d-block w-100" alt="..." />
                      </div>
                      <div class="carousel-item">
                        <img src="assets/portfolio/chat3.PNG" class="d-block w-100" alt="..." />
                      </div>
                      <div class="carousel-item">
                        <img src="assets/portfolio/chat4.PNG" class="d-block w-100" alt="..." />
                      </div>
                    </div>
                    <button class="carousel-control-prev" type="button" data-bs-target="#carousel4" data-bs-slide="prev">
                      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                      <span class="visually-hidden">Previous</span>
                    </button>
                    <button class="carousel-control-next" type="button" data-bs-target="#carousel4" data-bs-slide="next">
                      <span class="carousel-control-next-icon" aria-hidden="true"></span>
                      <span class="visually-hidden">Next</span>
                    </button>
                  </div>
                  <p class="text-start m-1">
                    Chatbot FAQ Helpdesk ini dibagun menggunakan bahasa pemrograman PHP Native. Berguna untuk membantu menjawab pertanyaan karyawan Kimia Farma yang mengalami kendala pada perangkatnya. jika pertanyaan ada yang tidak ada
                    dalam database FAQ Kiia Farma maka sistem akan mengarahkan user untuk membuat tiket pengaduan. fitur-fitur dari aplikasi ini antara lain :
                  </p>
                  <ul class="text-start">
                    <li>Pengelolaan pertanyaan dan jawaban</li>
                    <li>Grafik pertanyaan yang banyak ditanyakan</li>
                    <li>Pengelolaan pertanyaan yang belum ada jawaban</li>
                  </ul>
                  <button class="btn btn-danger btn-xl text-uppercase" data-bs-dismiss="modal" type="button">
                    <i class="fas fa-times me-1"></i>
                    Close
                  </button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.min.js" integrity="sha384-QJHtvGhmr9XOIpI6YVutG+2QOK9T+ZnN4kzFN1RtK3zEFEIsxhlmWl5/YESvpZ13" crossorigin="anonymous"></script>
    <script src="js/scripts.js"></script>
  </body>
</html>
