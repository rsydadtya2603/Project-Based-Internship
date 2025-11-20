# Project-Based-Internship
Project Based Internship Home Credit Indonesia X Rakamin Academy dengan judul prediksi resiko gagal bayar pada nasabah di home credit indonesia

🏦 Prediksi Risiko Gagal Bayar Nasabah – Home Credit Indonesia

Dalam industri pembiayaan, setiap keputusan pemberian kredit adalah pertaruhan. Tidak semua peminjam mampu membayar cicilan tepat waktu, dan bagi perusahaan seperti Home Credit Indonesia, kemampuan menilai risiko sejak awal adalah kunci untuk menjaga stabilitas bisnis. Dari sinilah proyek ini berawal.

Saya membangun sebuah model prediksi risiko gagal bayar dengan memanfaatkan data historis nasabah. Dataset berukuran besar—lebih dari 300 ribu entri dengan 122 fitur—memberikan tantangan sekaligus peluang untuk menggali pola perilaku finansial calon peminjam.

Proyek ini dimulai dengan memahami struktur data, membersihkan ratusan ribu baris dari noise seperti missing value dan duplikasi, serta mengubah fitur-fitur kompleks (misalnya DAYS_BIRTH) menjadi informasi yang lebih bermakna seperti usia. Variabel kategorikal diolah dengan label encoding, sedangkan fitur numerik dinormalisasi agar model dapat belajar dengan lebih baik.

Salah satu tantangan terbesar adalah ketidakseimbangan data: hanya sebagian kecil nasabah yang benar-benar gagal bayar. Untuk itu, saya menggunakan teknik SMOTE dan undersampling agar model tidak hanya “pintar menebak mayoritas”, tetapi mampu memahami pola risiko yang lebih halus.

Setelah data siap, berbagai algoritma diuji—mulai dari Logistic Regression hingga Random Forest dan Gradient Boosting. Setiap model dibandingkan menggunakan metrik seperti Accuracy, ROC-AUC, dan Confusion Matrix.
Hasilnya menarik:

Random Forest dan Gradient Boosting tampil paling stabil dan akurat secara keseluruhan

Logistic Regression unggul sedikit pada AUC, namun kurang kuat dalam prediksi kelas risiko sebenarnya

Temuan ini bukan hanya soal angka, tetapi memberikan insight nyata: dengan model yang tepat, perusahaan dapat membedakan nasabah berisiko tinggi dan rendah jauh sebelum keputusan kredit dibuat.

Proyek ini menggambarkan bagaimana data, jika diolah dengan benar, dapat menjadi alat strategis untuk mengurangi kerugian, meningkatkan kualitas portofolio kredit, dan membuat proses penilaian risiko menjadi lebih cerdas dan terukur.
