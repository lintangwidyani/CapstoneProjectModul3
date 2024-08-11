# CapstoneProjectModul3
Capstone Project Modul 3 - Customer Lifetime Value Perusahaan Asuransi Mobil

**Business Problem Understanding**

**Context**

Sebuah perusahaan asuransi mobil akan mengidentifikasi Customer lifetime value (CLV) atau nilai umur pelanggan, yaitu ukuran seberapa berharga seorang pelanggan bagi perusahaan. Dari nilai ini, perusahaan dapat menentukan berapa banyak keuntungan yang diperoleh dari satu pelanggan dan biaya yang dikeluarkan untuk mendapatkan atau mempertahankan pelanggan baru. 

**Problem Statement**

Menentukan target pemasaran kepada pelanggan yang memiliki value secara efektif dan bagaimana perubahan pelanggan perusahaan di masa depan.

**Analytic Approach**

Melakukan analisis data untuk dapat menemukan pola dari fitur-fitur yang ada, sehingga dapat diketahui CLV dari masing-masing pelanggan.

Selanjutnya, kita akan membangun suatu model regresi yang akan membantu perusahaan untuk dapat menentukan CLV dari seorang pelanggan.

**Metric Evaluation**

Evaluasi metrik yang akan digunakan adalah RMSE, MAE, dan MAPE.

**Conclusion**

- Random forest merupakan best model dengan RMSE 3,891.37, MAE 1,726.48, dan MAPE 14%.
- Menurut Lewis (1982) model dengan MAPE 14% tersebut memiliki performa yang baik dalam memprediksi, dengan kesalahan rata-rata persentase absolut di bawah 20%
- Feature yang paling mempengaruhi CLV adalah Number of Policies

**Recommendation**

- Dapat dilakukan penambahan data dan feature yang dapat mempengaruhi CLV, antara lain durasi atau kontinuitas kepemilikan polis asuransi, frekuensi pembayaran premi secara tepat waktu atau pembayaran tahunan, rating dari pelanggan terkait kualitas layanan, dan sebagainya.

