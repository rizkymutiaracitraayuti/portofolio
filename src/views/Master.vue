<template>
  <div id="home">
    <nav class="navbar navbar-expand-lg navbar-dark shadow-sm fixed-top" style="background-color: rgb(255, 137, 166)">
      <div class="container">
        <a class="navbar-brand" href="#home">Rizky Mutiara Citra Ayuti</a>
        <img src="/frontend/img/logo.png" alt="logo" width="30" height="30" class="d-inline-block align-text-top" />
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav ms-auto">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#home">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#about">Tentang</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#penghargaan">Penghargaan</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#projects">Projects</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#contact">Kontak </a>
            </li>
          </ul>
        </div>
      </div>
    </nav>

    <section class="jumbotron text-center">
      <img src="/frontend/img/profile.jpeg" alt="profile" width="100" class="rounded-circle img-thumbnail" />
      <h1 class="display-4">Rizky Mutiara Citra Ayuti</h1>
      <p class="lead"></p>
      <a class="btn btn-outline-danger" href="#about" role="button">More About Citra</a>
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
        <path
          fill="#ffffff"
          fill-opacity="1"
          d="M0,224L21.8,224C43.6,224,87,224,131,218.7C174.5,213,218,203,262,181.3C305.5,160,349,128,393,144C436.4,160,480,224,524,256C567.3,288,611,288,655,256C698.2,224,742,160,785,154.7C829.1,149,873,203,916,229.3C960,256,1004,256,1047,229.3C1090.9,203,1135,149,1178,149.3C1221.8,149,1265,203,1309,213.3C1352.7,224,1396,192,1418,176L1440,160L1440,320L1418.2,320C1396.4,320,1353,320,1309,320C1265.5,320,1222,320,1178,320C1134.5,320,1091,320,1047,320C1003.6,320,960,320,916,320C872.7,320,829,320,785,320C741.8,320,698,320,655,320C610.9,320,567,320,524,320C480,320,436,320,393,320C349.1,320,305,320,262,320C218.2,320,175,320,131,320C87.3,320,44,320,22,320L0,320Z"
        ></path>
      </svg>
    </section>

    <section id="about">
      <div class="container">
        <div class="row text-center mb-3">
          <div class="col">
            <h1>About CITRA</h1>
          </div>
        </div>
        <div class="row fs-5">
          <div class="col-md-3 mb-5" data-aos="fade-right" data-aos-duration="1000">
            <div class="card text-center">
              <img src="/frontend/img/foto.JPG" class="card-img-top" alt="about" />
              <div class="card-body">
                <p class="justify">Rizky Mutiara Citra Ayuti, Dipanggil Citra tempat tinggal di Gresik. Menempuh pendidikan S1 Pendidikan Teknologi Informasi di Universitas Negeri Surabaya</p>
              </div>
            </div>
          </div>
          <div class="col text-center" data-aos="flip-up" data-aos-delay="200">
            <p>
              Mahasiswa dari kampus Universitas Negeri Surabaya, jurusan Teknik Informatika. Merupakan pribadi yang kreatif, memiliki jiwa kepimimpinan yang tinggi, dapat bekerja dalam tim, dan mudah beradaptasi dengan hal baru. Selama
              kuliah memiliki pengalaman dalam dalam mengerjakan project untuk membuat aplikasi android menggunakan Android Studio, membuat website dengan HTML,CSS,PHP membuat game dekstop menggunakan Unity 2D, dan membuat desain UI/UX
              untuk aplikasi mobile dan aplikasi website.
            </p>
          </div>

          <div class="col-md-3" data-aos="fade-left" data-aos-duration="1000">
            <div class="card" style="width: 18rem">
              <div class="card-body text-center">
                <h3 class="card-title text-center">Sosial Media</h3>
                <p class="justify">Untuk kenal lebih dekat dengan citra bisa kunjungi sosial media berikut ini</p>
                <a href="https://www.instagram.com/rizkymutiaracitraayuti/" class="card-link"><i class="bi bi-instagram"></i></a>
                <a href="https://www.youtube.com/channel/UCNHaJTzv4RpTWBv1qi6HkJg/" class="card-link"><i class="bi bi-youtube"></i></a>
                <a href="https://github.com/rizkymutiaracitraayuti" class="card-link"><i class="bi bi-github"></i></a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section id="penghargaan">
      <div class="container">
        <div class="row text-center mb-3">
          <div class="col">
            <h2>PENGHARGAAN</h2>
          </div>
        </div>
        <div id="carouselExampleCaptions" class="carousel slide col-lg-8 offset-lg-2">
          <div class="carousel-indicators">
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="3" aria-label="Slide 4"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="4" aria-label="Slide 5"></button>
          </div>
          <div class="carousel-inner">
            <div class="carousel-item active mb-5">
              <img src="/frontend/img/sertif1.jpeg" class="d-block w-100" alt="project 1" />
            </div>
            <div class="carousel-item mb-5">
              <img src="/frontend/img/sertif2.jpg" class="d-block w-100" alt="project 2" />
            </div>
            <div class="carousel-item mb-5">
              <img src="/frontend/img/sertif3.jpg" class="d-block w-100" alt="project 3" />
            </div>
            <div class="carousel-item mb-5">
              <img src="/frontend/img/sertif4.jpg" class="d-block w-100" alt="project 4" />
            </div>
            <div class="carousel-item mb-5">
              <img src="/frontend/img/sertif5.png" class="d-block w-100" alt="project 5" />
            </div>
          </div>
          <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
          </button>
          <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
          </button>
        </div>
      </div>
    </section>

    <section id="projects">
      <div class="container mb-5">
        <div class="row text-center mb-5">
          <div class="col">
            <h2>MY PROJECTS</h2>
          </div>
        </div>
        <div class="row justify-content-center">
          <div class="col-md-4 mb-3">
            <div class="card" data-aos="zoom-in-up" data-aos-duration="500">
              <img src="/frontend/img/p1.jpg" class="card-img-top" alt="project 1" />
              <div class="card-body">
                <p class="card-text text-center">Design UI/UX website Doman sebuah website donasi mendapat juara harapan 1</p>
              </div>
            </div>
          </div>
          <div class="col-md-4 mb-3">
            <div class="card" data-aos="zoom-in-up" data-aos-duration="500" data-aos-delay="100">
              <img src="/frontend/img/p2.png" class="card-img-top" alt="project 2" />
              <div class="card-body">
                <p class="card-text text-center">Aplikasi game dekstop untuk pembelajaran yang dibuat menggunakan unity 2D</p>
              </div>
            </div>
          </div>
          <div class="col-md-4 mb-3">
            <div class="card" data-aos="zoom-in-up" data-aos-duration="500" data-aos-delay="150">
              <img src="/frontend/img/p3.png" class="card-img-top" alt="project 3" />
              <div class="card-body">
                <p class="card-text text-center">Design UI/UX mobile GIMIK yang mengusut UMKM berhasil Mendapat Juara 3</p>
              </div>
            </div>
          </div>
          <div class="col-md-4 mb-3">
            <div class="card" data-aos="zoom-in-up" data-aos-duration="500" data-aos-delay="200">
              <img src="/frontend/img/p4.jpeg" class="card-img-top" alt="project 4" />
              <div class="card-body">
                <p class="card-text text-center">Aplikasi mobile android doa sehari hari</p>
              </div>
            </div>
          </div>
          <div class="col-md-4 mb-3">
            <div class="card" data-aos="zoom-in-up" data-aos-duration="500" data-aos-delay="250">
              <img src="/frontend/img/p5.png" class="card-img-top" alt="project 5" />
              <div class="card-body">
                <p class="card-text text-center">Aplikasi website e-learning yang dibangun menggunakan wordpress</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section id="contact">
      <div class="container">
        <div class="row text-center">
          <div class="col">
            <h2>Contact Me</h2>
          </div>
        </div>
        <div class="row justify-content-center">
          <div class="col-md-6 mb-5">
            <form>
              <div class="mb-3">
                <label for="name" class="form-label">Nama Lengkap</label>
                <input type="text" class="form-control" id="name" aria-describedby="name" />
              </div>
              <div class="mb-3">
                <label for="exampleFormControlInput1" class="form-label">Email</label>
                <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="name@example.com" />
              </div>
              <div class="mb-3">
                <label for="pesan" class="form-label">Pesan</label>
                <textarea class="form-control" id="pesan" rows="3"></textarea>
              </div>

              <button type="submit" class="btn btn-primary">Kirim</button>
            </form>
          </div>
        </div>
      </div>
    </section>

    <footer class="footer text-white text-center p-3 mt-5" style="background-color: rgb(255, 137, 166)">
      <p>Created with <i class="bi bi-suit-heart-fill text-danger"></i> by Citra 2023</p>
    </footer>
  </div>
</template>

<script>
export default {
  name: "Master",
};
</script>

<style></style>
