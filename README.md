### Tugas Kelompok: Implementasi Generative Adversarial Network (GAN)_ Kelompok2

## Deskripsi Singkat Tugas
Proyek ini merupakan implementasi Generative Adversarial Network (GAN) menggunakan PyTorch dengan dataset MNIST (gambar angka tulisan tangan 0–9).  
GAN terdiri dari dua komponen utama:
- Generator (G)     → Membuat gambar palsu yang menyerupai dataset asli.
- Discriminator (D) → Membedakan gambar asli dan palsu.

Proses pelatihan dilakukan secara kompetitif:
1. Generator     = Belajar membuat gambar yang realistis untuk menipu Discriminator.
2. Discriminator = Belajar membedakan gambar asli dari dataset dan gambar palsu dari Generator.
3. Pelatihan berlangsung hingga Generator mampu membuat gambar yang sulit dibedakan dari data asli.

## Cara Menjalankan Kode:
1. Clone repository atau simpan file notebook kelompok-2-gan.ipynb.
2. Memastikan Python 3.8+ sudah terpasang.
3. Install library yang dibutuhkan:
      pip install torch torchvision matplotlib
   
4. Membuka notebook menggunakan Jupyter Notebook atau Google Colab.
5. Menjalankan setiap cell secara berurutan:
   - Import library
   - Load dataset MNIST
   - Definisi Generator dan Discriminator
   - Inisialisasi model, loss, dan optimizer
   - Training loop
   - Visualisasi hasil training dan loss
6. Hasil gambar Generator tersimpan di folder generated_images.
7. Model tersimpan di folder models.

Kode ini juga menampilkan beberapa visualisasi, yaitu:
- Perubahan loss Generator dan Discriminator selama training.
- Contoh gambar hasil Generator pada beberapa epoch.

## Anggota Kelompok Beserta User Github-nya:
- Amisha Hersavina Salsabila (amishahersavina22)
- Nasywa Kynda Sanina (nakyn123)
- Aisha Utwa Haura Karimah (haura1704)
- Azmi Nur Al Qodar (maulash-miee & ankirsydii) 
- Nur Aisyah Maharani (Noninuraisyah)

## Link Repositori Github: https://github.com/amishahersavina22/Kelompok2-Gan/commits/main/