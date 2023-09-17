# Thalassemia Prediction

## Deskripsi Proyek

Proyek ini bertujuan untuk memprediksi apakah pasien menderita thalassemia berdasarkan fitur-fitur tertentu. Thalassemia adalah gangguan darah yang dapat memengaruhi produksi hemoglobin. Dengan menggunakan machine learning, proyek ini dapat membantu dalam mendeteksi thalassemia secara lebih cepat dan akurat.

## Kebutuhan

Sebelum memulai proyek ini, pastikan Anda telah memenuhi beberapa persyaratan berikut:

-   **Python**: Versi yang direkomendasikan adalah 3.7 atau lebih tinggi.
-   **Jupyter Notebook**: Opsional, tetapi berguna untuk menjalankan dan menguji kode.
-   **Library**: Instal library yang diperlukan dengan menjalankan `pip install -r requirements.txt`.

## Tahap Persiapan Data

-   Data awal kami berupa file CSV yang berisi informasi medis dan hasil tes thalassemia.
-   Data diacak dan disimpan dalam file CSV baru untuk memastikan keberagaman data.

## Tahap Praproses Data

-   Mengatasi nilai-nilai yang hilang (missing values).
-   Mengkodekan kolom kategorikal seperti jenis kelamin dan hasil tes thalassemia.
-   Normalisasi data agar model dapat bekerja dengan baik.

## Pembangunan Model

-   Menggunakan algoritma Support Vector Machine (SVM) untuk membangun model klasifikasi.
-   Model dapat mengklasifikasikan data menjadi "Thalassemia Positive" atau "Thalassemia Negative".

## Pengujian Model

-   Model diuji menggunakan data uji yang telah dipisahkan sebelumnya.
-   Hasil pengujian ditampilkan dalam bentuk matriks kebingungan (confusion matrix) untuk mengukur performa model.

## Penyetelan Hiperparameter

-   Penyetelan hiperparameter dilakukan dengan menggunakan GridSearchCV.
-   Membantu menemukan parameter terbaik untuk model SVM.

## Author

-   Nama: M.Fathir Arya Nafis
-   [Email](fathirarya2002@gmail.com)
-   [GitHub](https://github.com/fathirarya)

## Kontribusi

Kami menghargai kontribusi dari semua orang. Jika Anda ingin berkontribusi pada proyek ini, silakan buat _pull request_.

## Tautan Berguna

-   [Dokumentasi scikit-learn](https://scikit-learn.org/stable/documentation.html)
-   [Tutorial SVM](https://www.analyticsvidhya.com/blog/2017/09/understaing-support-vector-machine-example-code/)
