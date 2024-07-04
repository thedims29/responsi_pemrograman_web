<template>
  <section class="about" id="about">
    <div class="container">
      <div class="row">
        <div class="col">
          <h2 class="heading">Home</h2>
        </div>
      </div>
      <div class="row">
        <div class="col-4 foto">
          <img src="assets/profil.jpg" class="border" alt="" />
        </div>
        <div class="col-8">
          <p class="paragraf">
            Halo nama saya Dimas. Saya mahasiswa jurusan Informatika dikampus Amikom Yogayakarta. 
            Mau kenalan lebih jauh yuk jelajahi website ini.
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "AboutSection",
};
</script>

<style scoped>
html {
  scroll-behavior: smooth;
}

.about {
  margin: 10px 0 0 100px;
  padding: 50px 0;
  background: #fff;
}

.container {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}

.foto {
  margin-top: 50px;
  padding: 20px;
}

.heading {
  font-weight: bold; /* Atur bold pada judul */
  margin-right: 20px;
  padding-right: 40px;
  margin-bottom: 20px; /* Atur jarak antara judul dan isi */
  padding-bottom: 10px;
  justify-content: center;
  text-align: center;
  font-size: 30px; /* Atur ukuran font */
}

.border {
  width: 250px; /* Atur lebar elemen */
  height: 250px; /* Atur tinggi elemen */
  border: 2px solid #ccc; /* Atur ukuran dan warna border */
  border-radius: 50%; /* Membuat border menjadi bulat */
  margin: 0 auto;
}

.paragraf {
  font-size: 18px;
  text-align: justify;
  padding-top: 100px;
  padding-bottom: 50px;
  padding-left: 20px;
  padding-right: 20px;
}

@media (max-width: 768px) {
  .about {
    margin: 50px 0;
    padding: 50px 20px;
  }
  .heading {
    padding-left: 0;
    font-size: 20px; /* Sesuaikan ukuran font untuk layar kecil */
  }
  .paragraf {
    padding-left: 10px;
    padding-right: 10px;
  }
}
</style>