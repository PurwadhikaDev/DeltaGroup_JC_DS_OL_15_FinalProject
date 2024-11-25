KELOMPOK DELTA

Anggota:

- Muhammad Khoirul Huda - JCDSOL-015-003

- Sekar Endah Sriwedari - JCDSOL-015-009

- Muhammad Amin Rais Nugroho - JCDSOL-015-002


LINK TABLEAU

https://public.tableau.com/app/profile/rais.nugroho/viz/FinalProject_17325454357820/DashboardAutoInsurance

LINK COLAB


# CONTEXT

Dataset AutoInsurance menghimpun informasi terkait dengan pelanggan asuransi otomotif dan digunakan untuk menganalisis faktor-faktor yang mempengaruhi perilaku pelanggan serta kinerja polis asuransi. Data ini mencakup berbagai atribut seperti status pekerjaan, jenis kelamin, pendapatan tahunan, status perkawinan, jumlah premi bulanan, jumlah klaim, dan banyak lagi. Dataset ini sering digunakan untuk memodelkan dan memprediksi perilaku pelanggan, seperti respons terhadap penawaran perpanjangan polis, serta untuk mengevaluasi faktor-faktor yang mempengaruhi keputusan pembelian asuransi.
Dataset ini sering digunakan dalam berbagai studi dan analisis oleh perusahaan asuransi untuk memahami lebih baik tentang dinamika pasar dan preferensi pelanggan, terutama dalam mengidentifikasi segmen pelanggan yang lebih mungkin merespon positif terhadap kampanye pemasaran. Sebagai pemangku kepentingan utama, perusahaan asuransi memanfaatkan wawasan dari data ini untuk merancang produk asuransi yang lebih efektif dan mengembangkan strategi pemasaran yang lebih terarah. Informasi yang terkandung dalam dataset ini berasal dari data pelanggan nyata dan mencakup berbagai fitur terkait dengan profil pelanggan dan detail polis asuransi, menjadikannya sumber yang kaya untuk mengajarkan dasar-dasar analisis data dan machine learning dalam konteks asuransi otomotif.
Melalui analisis ini, perusahaan asuransi dapat mengidentifikasi pola dalam perilaku pelanggan yang dapat membantu dalam pengambilan keputusan strategis dan operasional, serta dalam peningkatan kepuasan dan retensi pelanggan. Khususnya, analisis terfokus pada pelanggan yang merespon 'Yes' memungkinkan perusahaan untuk secara efektif menargetkan dan mengoptimalkan kampanye pemasaran mereka. Dataset ini tidak hanya mengungkapkan pola dalam perilaku pelanggan tetapi juga memberikan perusahaan asuransi kemampuan untuk menyesuaikan tawaran mereka dengan lebih baik, sehingga meningkatkan efektivitas penjualan dan efisiensi operasional. Dengan memahami faktor-faktor yang mendorong pelanggan untuk merespon positif, perusahaan dapat merancang kampanye yang lebih menarik dan relevan yang meningkatkan tingkat partisipasi dan konversi.


# PROBLEM STATEMENT

Dalam industri asuransi kendaraan, memahami perilaku pembelian dan respons pelanggan terhadap penawaran asuransi adalah krusial untuk meningkatkan penjualan dan efisiensi pemasaran. Dengan dataset AutoInsurance yang mengandung informasi sosio-ekonomi pelanggan serta detail tentang polis asuransi kendaraan mereka, terdapat peluang untuk menganalisis dan mengklasifikasikan pelanggan berdasarkan respons mereka terhadap penawaran asuransi sebelumnya. Tujuan utama dari analisis ini adalah untuk mengidentifikasi faktor-faktor yang mempengaruhi keputusan pelanggan dalam merespons penawaran asuransi, khususnya pelanggan yang merespons 'Yes', sehingga memungkinkan perusahaan untuk melakukan pemasaran yang lebih terarah dan efisien.


# SOLUTION APPROACH

1. Data Exploration and Preprocessing:
Melakukan eksplorasi data untuk memahami distribusi variabel, hubungan antar variabel, dan mengidentifikasi adanya missing values atau outliers yang perlu ditangani.
Membersihkan data dengan mengisi missing values, mengatasi outliers, dan melakukan encoding pada variabel kategorikal.

2. Exploratory Data Analysis (EDA):
Menganalisis variabel-variabel yang berpotensi mempengaruhi respons pelanggan ('Response') menggunakan visualisasi data dan statistik deskriptif.
Menentukan korelasi antara 'Response' dan variabel lain untuk memahami faktor-faktor yang berpengaruh signifikan, dengan fokus khusus pada variabel yang mempengaruhi pelanggan untuk merespons 'Yes'.

3. Model Development and Validation:
Mengembangkan model klasifikasi untuk memprediksi peluang respons positif ('Yes') dari pelanggan terhadap penawaran campaign asuransi. Model ini akan memungkinkan perusahaan untuk mengidentifikasi pelanggan yang paling mungkin untuk merespons positif terhadap penawaran campaign asuransi, sehingga memfasilitasi kampanye pemasaran yang lebih efektif.
Dengan pendekatan ini, perusahaan dapat lebih efisien dalam mengalokasikan sumber daya pemasaran mereka, memfokuskan upaya pada pelanggan yang memiliki probabilitas tinggi untuk merespons positif terhadap penawaran asuransi, dan akhirnya meningkatkan konversi penjualan serta kepuasan pelanggan.


# GOALS

Tujuan utama dari analisis ini menggunakan dataset AutoInsurance adalah untuk meningkatkan pemahaman tentang perilaku pelanggan, khususnya mereka yang merespons positif ('Yes') terhadap tawaran asuransi, dan untuk mengoptimalkan strategi pemasaran berdasarkan wawasan berbasis data. Berikut adalah tujuan-tujuan terperinci yang disusun berdasarkan tujuan utama, dengan fokus khusus pada pelanggan yang cenderung merespon positif dan berpartisipasi dalam kampanye:

1. Memahami Perilaku Pelanggan: Mengidentifikasi Faktor yang Mempengaruhi Respons: Melakukan analisis mendalam pada dataset untuk mengidentifikasi variabel-variabel yang signifikan dalam mempengaruhi respons pelanggan terhadap tawaran asuransi, khususnya mereka yang merespons dengan 'Yes'. Ini melibatkan evaluasi statistik deskriptif dan inferensial serta analisis korelasi untuk menentukan fitur-fitur yang paling berpengaruh dalam keputusan pelanggan untuk merespon positif.
2. Analitik Prediktif: Prediksi Respon: Membangun model prediktif untuk memperkirakan kemungkinan pelanggan merespons positif terhadap tawaran asuransi. Model ini akan membantu dalam menargetkan pelanggan secara lebih efektif, khususnya mereka yang memiliki kecenderungan tinggi untuk merespon 'Yes'.
3. Pengaruh Variabel: Menentukan variabel mana yang paling signifikan mempengaruhi keputusan pelanggan untuk menerima tawaran asuransi, dengan fokus pada faktor-faktor yang mendorong respons positif. Ini termasuk menganalisis dampak faktor demografis, detail polis, dan interaksi historis yang mungkin memotivasi pelanggan untuk terlibat dalam kampanye.
4. Optimisasi Upaya Pemasaran:
    - Kampanye Pemasaran yang Ditargetkan: Memanfaatkan wawasan dari segmentasi pelanggan dan model prediktif untuk merancang dan melaksanakan kampanye pemasaran yang ditargetkan yang kemungkinan akan menghasilkan tingkat konversi yang lebih tinggi. Fokus utama adalah pada pelanggan yang diprediksi untuk merespon 'Yes', memastikan bahwa sumber daya pemasaran dialokasikan secara efisien untuk memaksimalkan hasil.
    - Alokasi Sumber Daya: Mengoptimalkan alokasi sumber daya pemasaran dengan memfokuskan upaya pada segmen yang diprediksi memiliki respons tertinggi terhadap jenis tawaran tertentu, khususnya mereka yang cenderung merespon positif. Ini akan memungkinkan perusahaan untuk mengurangi pemborosan dan meningkatkan ROI dari kampanye pemasaran.
Dengan pendekatan ini, perusahaan dapat secara efektif menarik dan mempertahankan pelanggan yang paling mungkin merespon positif, meningkatkan efektivitas kampanye pemasaran dan memperkuat loyalitas pelanggan.


# ANALYTICS APPROACH

Dalam upaya untuk meningkatkan efektivitas pemasaran dan respons pelanggan terhadap tawaran asuransi, kami akan mengadopsi pendekatan analitik yang melibatkan pengembangan dan validasi model klasifikasi machine learning. Model ini akan digunakan untuk memprediksi variabel dependen 'Response', yang menandakan apakah pelanggan merespons positif terhadap tawaran asuransi. Berikut adalah langkah-langkah yang akan kami ambil dalam membangun model klasifikasi :
1. Pemilihan Model : Dalam proses pemilihan model, kami akan mengevaluasi berbagai algoritma klasifikasi untuk menentukan model yang paling efektif berdasarkan dataset kami. Pendekatan ini didasarkan pada kemampuan model dalam menangani data kategorikal dan numerik serta fleksibilitasnya dalam menyesuaikan kompleksitas model dengan data. Berikut adalah delapan model yang akan kami latih dan evaluasi : Logistic Regression (lr), Decision Tree Classifier (dt), K-Nearest Neighbors (knn), Support Vector Classifier (svc), Voting Classifier (vc_hard, vc_soft), Stacking Classifier (stacking), Random Forest Classifier (rf), Gradient Boosting (gb, xgb). Setiap model memiliki keunggulan dan kelemahannya sendiri dalam konteks data dan masalah yang diberikan. Pengujian dan evaluasi lebih lanjut dari setiap model dalam pipeline akan membantu menentukan pendekatan terbaik untuk memaksimalkan akurasi prediksi dalam dataset asuransi kendaraan ini.
2. Feature Engineering :
Kami akan melaksanakan langkah-langkah feature engineering untuk meningkatkan prediktivitas model. Ini termasuk :
Konversi Label Respons : Mengubah label respons dari 'Yes' dan 'No' menjadi nilai numerik, memfasilitasi pemrosesan oleh model.
Penghapusan Variabel Tidak Relevan : Variabel seperti 'Customer' dan 'Effective To Date' akan dihapus karena tidak memberikan nilai prediktif.
Binning pada Variabel Pendapatan (Income) : Melakukan binning pada variabel 'Income' untuk mengkategorikan pendapatan pelanggan menjadi tiga kelompok : 'Low', 'Medium', dan 'High'.
3. Preprocessing Data :
Langkah-langkah preprocessing akan dilakukan untuk mempersiapkan dataset sebelum pemodelan, termasuk :
Penentuan Variabel X dan Y : Menetapkan variabel X yang mencakup semua fitur kecuali kolom respons dan variabel Y yang berisi kolom respons yang telah dikonversi.
Pemisahan Data Pelatihan dan Pengujian : Memisahkan dataset menjadi set pelatihan (80%) dan pengujian (20%) untuk validasi yang objektif.
Pembuatan dan Penerapan Transformers : Mengembangkan transformer untuk normalisasi dan pengkodean data, memastikan bahwa data diproses dengan konsisten dan sesuai untuk pemodelan.
4. Pelatihan Model :
Model akan dilatih menggunakan set data latih yang telah dipreproses, dengan penerapan validasi silang untuk mengevaluasi kinerja model secara objektif dan memastikan keandalannya.



# EVALUATION METRICS

- Type 1 error : False Positive
Konsekuensi: sia-sianya biaya kampanye, waktu dan sumber daya
- Type 2 error : False Negative
Konsekuensi: kehilangan pelanggan dengan respon Yes yang berpotensi menambah keuntungan

- Metrik Evaluasi Model
Kinerja model prediktif akan dievaluasi menggunakan metrik evaluasi klasifikasi yang komprehensif, termasuk Accuracy Score, Precision, Recall, F1 Score, dan AUC Score. Fokus utama akan diberikan pada metrik Recall, Precision, dan F1 Score, yang sangat relevan dalam konteks pemasaran asuransi kendaraan, terutama dalam memprediksi respons "Yes" dari pelanggan terhadap penawaran asuransi.
  1. Recall (Sensitivitas): Score: 0.9943, Recall mengukur kemampuan model untuk mengidentifikasi semua respons "Yes" yang relevan dari pelanggan. Skor Recall yang tinggi (0.9943) menunjukkan bahwa model efektif dalam menangkap hampir semua pelanggan yang berpotensi merespon positif terhadap penawaran, memaksimalkan peluang untuk sukses dalam kampanye pemasaran.
  2. Precision: Score: 0.9577, Precision mengukur keakuratan model dalam memprediksi respons "Yes" yang benar. Skor Precision yang tinggi (0.9577) menunjukkan bahwa ketika model memprediksi pelanggan akan merespon 'Yes', ada kepastian tinggi bahwa prediksi tersebut akurat. Hal ini mengurangi risiko sumber daya yang dihabiskan untuk pelanggan yang tidak mungkin merespon, sehingga meningkatkan efisiensi kampanye.
  3. F1 Score: Score: 0.9756, F1 Score adalah harmonik mean dari Precision dan Recall. Skor F1 yang tinggi (0.9756) menunjukkan bahwa model berhasil mencapai keseimbangan yang sangat baik antara menangkap peluang (Recall tinggi) dan efisiensi alokasi sumber daya (Precision tinggi). Ini sangat relevan dalam konteks pemasaran asuransi, di mana penting untuk menangkap sebanyak mungkin peluang tanpa menghabiskan sumber daya pada prospek yang tidak tepat.
  4. Accuracy Score: Score: 0.9929, Accuracy Score mengukur keseluruhan keakuratan model dalam mengklasifikasikan respons secara benar. Skor Accuracy yang sangat tinggi (0.9929) menunjukkan bahwa model ini sangat efektif dalam membuat prediksi yang tepat untuk kedua kelas respons, baik 'Yes' maupun 'No'.
  5. AUC Score: Score: 1.0, AUC Score (Area Under the Curve) mengukur kemampuan model untuk membedakan antara kelas-kelas dengan benar. Skor AUC yang sempurna (1.0) menunjukkan bahwa model memiliki performa yang luar biasa dalam membedakan antara respons positif dan negatif. Ini vital dalam konteks pemasaran untuk memastikan bahwa upaya pemasaran sangat akurat dan minim kesalahan dalam penargetan pelanggan.

- Implementasi Metrik pada Model XGBoost Classifier: Berdasarkan hasil pengujian model XGBoost Classifier, kinerja yang sangat baik dari model ini dengan skor metrik yang tinggi menunjukkan bahwa model sangat efektif dalam mengidentifikasi pelanggan yang akan merespon positif terhadap penawaran asuransi kendaraan. Tingkat keakuratan dan efisiensi yang tinggi ini memungkinkan perusahaan asuransi untuk mengoptimalkan strategi pemasaran mereka berdasarkan wawasan berbasis data, memastikan bahwa kampanye pemasaran lebih terarah dan efisien, serta memaksimalkan peluang untuk merespon "Yes".


# DATA DICTIONARY

| No | Nama Kolom                  | Data Type | Penjelasan                                                                                      |
|----|-----------------------------|-----------|-------------------------------------------------------------------------------------------------|
| 1  | Customer                    | object    | Kode unik yang mengidentifikasi setiap pelanggan.                                               |
| 2  | State                       | object    | Negara bagian tempat pelanggan berada.                                                          |
| 3  | Customer Lifetime Value     | float64   | Estimasi pendapatan yang diharapkan dari hubungan dengan pelanggan.                             |
| 4  | Response                    | object    | Apakah pelanggan merespon tawaran terakhir yang diberikan kepadanya (Ya/Tidak).                 |
| 5  | Coverage                    | object    | Jenis cakupan asuransi yang dipilih oleh pelanggan (misalnya, Basic, Extended, Premium).        |
| 6  | Education                   | object    | Tingkat pendidikan terakhir yang dicapai oleh pelanggan.                                        |
| 7  | Effective To Date           | object    | Tanggal ketika polis asuransi mulai berlaku.                                                    |
| 8  | EmploymentStatus            | object    | Status pekerjaan pelanggan saat ini (misalnya, Employed, Unemployed, Medical Leave).            |
| 9  | Gender                      | object    | Jenis kelamin pelanggan (F untuk perempuan, M untuk laki-laki).                                 |
| 10 | Income                      | float64   | Pendapatan tahunan pelanggan.                                                                   |
| 11 | Location Code               | object    | Kategori lokasi tempat tinggal pelanggan (misalnya, Urban, Suburban, Rural).                    |
| 12 | Marital Status              | object    | Status perkawinan pelanggan (misalnya, Single, Married, Divorced).                              |
| 13 | Monthly Premium Auto        | float64   | Jumlah premi bulanan yang dibayar pelanggan untuk asuransi kendaraan.                           |
| 14 | Months Since Last Claim     | int64     | Jumlah bulan sejak pelanggan terakhir kali mengajukan klaim.                                    |
| 15 | Months Since Policy Inception| int64    | Jumlah bulan sejak polis asuransi dimulai.                                                      |
| 16 | Number of Open Complaints   | int64     | Jumlah keluhan yang masih terbuka dari pelanggan.                                               |
| 17 | Number of Policies          | int64     | Jumlah polis asuransi yang dimiliki pelanggan.                                                  |
| 18 | Policy Type                 | object    | Tipe polis asuransi (misalnya, Personal Auto, Corporate Auto).                                  |
| 19 | Policy                      | object    | Polis spesifik yang dimiliki pelanggan (misalnya, Corporate L3, Personal L1).                   |
| 20 | Renew Offer Type            | object    | Tipe penawaran perpanjangan yang diberikan kepada pelanggan (misalnya, Offer1, Offer2).         |
| 21 | Sales Channel               | object    | Saluran melalui mana polis dibeli (misalnya, Agent, Call Center, Web).                          |
| 22 | Total Claim Amount          | float64   | Jumlah total klaim yang diajukan oleh pelanggan.                                                |
| 23 | Vehicle Class               | object    | Kelas kendaraan yang diasuransikan (misalnya, Two-Door Car, Four-Door Car, SUV).                |
| 24 | Vehicle Size                | object    | Ukuran kendaraan yang diasuransikan (misalnya, Small, Medsize, Large).                          |

LIMITASI

KESIMPULAN

REKOMENDASI
