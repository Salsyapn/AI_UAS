Prediksi Kelulusan Mahasiswa Tepat Waktu Berdasarkan Indeks Prestasi Semester Menggunakan Metode Decision Tree

Deskripsi
Program ini merupakan aplikasi sederhana untuk memprediksi kategori kelulusan mahasiswa berdasarkan nilai Indeks Prestasi Semester (IPS) dari semester 1 hingga semester 8. Model yang digunakan untuk prediksi adalah Decision Tree Classifier.

Fitur
Memuat dataset dari file CSV (df.csv).
Melakukan preprocessing data, termasuk encoding label kelulusan (A, B, C, D).
Membagi data menjadi data latih dan data uji.
Melatih model Decision Tree dengan kriteria entropy dan max_depth tertentu.
Mengevaluasi performa model menggunakan akurasi dan classification report.
Memungkinkan pengguna untuk memasukkan nilai IPS secara manual untuk mendapatkan prediksi kelulusan.

Kategori Kelulusan
Program ini memprediksi 4 kategori kelulusan:
A: Lulus Dengan Sangat Baik
B: Lulus Dengan Baik
C: Lulus Dengan Cukup
D: Tidak Lulus

Instalasi
Pastikan Anda memiliki Python terinstal. Anda juga perlu menginstal library berikut:
pip install pandas scikit-learn
Penggunaan
Pastikan file df.csv berada di direktori yang sama dengan script program.
Jalankan script Python.
Program akan meminta Anda untuk memasukkan nilai IPS untuk setiap semester (1-8).
Setelah semua input diberikan, program akan menampilkan hasil prediksi kategori kelulusan Anda.
Struktur Data (df.csv)

File df.csv diharapkan memiliki kolom-kolom berikut:
ips1, ips2, ..., ips8: Nilai IPS untuk setiap semester yang digunakan sebagai fitur.
label: Kategori kelulusan yang digunakan sebagai target.

Model
Algoritma: Decision Tree Classifier
Kriteria: Entropy
Max Depth: 6

Kontributor
Salsya Purita Niditiani (2330511061)
Syifa Shefiany Taslitsa(2330511062)
Khansa Nisrina(2330511089)
