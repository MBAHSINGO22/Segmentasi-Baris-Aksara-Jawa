<h1 align="center">Segmentasi Baris Tulisan Aksara Jawa</h1>

<hr>

<h2>📌 Deskripsi</h2>

<p>
Project ini dibuat untuk melakukan segmentasi baris pada tulisan aksara Jawa menggunakan teknik pengolahan citra digital dengan Python dan OpenCV.
Program akan mendeteksi setiap baris tulisan dari gambar aksara Jawa menggunakan metode horizontal projection, kemudian memisahkan setiap baris menjadi potongan gambar tersendiri.
</p>

<p>
Project ini cocok digunakan untuk:
</p>

<ul>
  <li>Preprocessing OCR aksara Jawa</li>
  <li>Pengolahan citra digital</li>
  <li>Segmentasi tulisan tangan</li>
  <li>Pembelajaran computer vision</li>
  <li>Penelitian aksara Jawa</li>
</ul>

<hr>

<h2>🛠 Teknologi yang Digunakan</h2>

<ul>
  <li>Python</li>
  <li>OpenCV</li>
  <li>NumPy</li>
  <li>Matplotlib</li>
  <li>Google Colab</li>
</ul>

<hr>

<h2>✨ Fitur</h2>

<ul>
  <li>Upload gambar langsung melalui Google Colab</li>
  <li>Konversi gambar ke grayscale</li>
  <li>Pengurangan noise menggunakan Gaussian Blur</li>
  <li>Thresholding biner menggunakan metode Otsu</li>
  <li>Operasi morfologi untuk memperjelas tulisan</li>
  <li>Perhitungan horizontal projection</li>
  <li>Deteksi puncak untuk menentukan baris tulisan</li>
  <li>Segmentasi otomatis setiap baris aksara Jawa</li>
  <li>Menyimpan hasil segmentasi menjadi gambar terpisah</li>
  <li>Visualisasi hasil segmentasi</li>
</ul>

<hr>

<h2>⚙️ Alur Program</h2>

<ol>
  <li>Mengimpor library yang dibutuhkan</li>
  <li>Mengupload gambar aksara Jawa</li>
  <li>Melakukan preprocessing gambar</li>
  <li>Mengubah gambar menjadi biner</li>
  <li>Menghitung horizontal projection</li>
  <li>Mendeteksi posisi baris tulisan</li>
  <li>Menentukan batas segmentasi</li>
  <li>Memotong setiap baris tulisan</li>
  <li>Menyimpan hasil segmentasi</li>
</ol>

<hr>

<h2>📂 Struktur Folder</h2>

<pre>
project-folder/
│
├── VIKASABARU_235314099.ipynb
├── hasil_baris/
│   ├── line_1.png
└── README.md
</pre>

<hr>

<h2>🚀 Instalasi</h2>

<p>Clone repository:</p>

<pre>
git clone https://github.com/username/nama-repository.git
</pre>

<p>Install dependency:</p>

<pre>
pip install opencv-python numpy matplotlib
</pre>

<hr>

<h2>▶️ Cara Menjalankan</h2>

<ol>
  <li>Buka notebook di Google Colab atau Jupyter Notebook</li>
  <li>Upload gambar tulisan aksara Jawa</li>
  <li>Jalankan seluruh cell program</li>
  <li>Lihat hasil segmentasi baris</li>
</ol>

<hr>

<h2>💻 Contoh Kode</h2>

<pre>
projection = np.sum(clean == 255, axis=1)

kernel_avg = np.ones(k) / k
smooth = np.convolve(projection, kernel_avg, mode='same')
</pre>

<hr>

<h2>📈 Pengembangan Selanjutnya</h2>

<ul>
  <li>Segmentasi karakter aksara Jawa</li>
  <li>Integrasi OCR aksara Jawa</li>
  <li>Pengenalan karakter menggunakan Deep Learning</li>
  <li>Peningkatan akurasi segmentasi</li>
  <li>Dukungan untuk berbagai jenis tulisan tangan</li>
</ul>

<hr>

<h2>👨‍💻 Author</h2>

<p>
Eugenius Kriswinar Adi Cahya
</p>

<hr>

<h2>📄 License</h2>

<p>
Project ini dibuat untuk kebutuhan pembelajaran dan penelitian.
</p>
