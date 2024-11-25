# KELOMPOK DELTA

Anggota:

- Muhammad Khoirul Huda - JCDSOL-015-003

- Sekar Endah Sriwedari - JCDSOL-015-009

- Muhammad Amin Rais Nugroho - JCDSOL-015-002


# LINK TABLEAU

https://public.tableau.com/app/profile/rais.nugroho/viz/FinalProject_17325454357820/DashboardAutoInsurance

# LINK COLAB

https://colab.research.google.com/drive/1NymVKCnhfQPVJpsJKunie3wUz5EZKcu_?usp=sharing


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

![Evaluation Metrics](https://github.com/PurwadhikaDev/DeltaGroup_JC_DS_OL_15_FinalProject/blob/main/Image.jpeg)

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

# LIMITASI

| Feature | Range |
|---|---|
| Policy | Corporate L1-L3, Personal L1-L3, Special L1-L3|
| Vehicle Class | Two-Door Car, Four-Door Car, SUV, Luxury SUV, Sports Car, Luxury Car |
| Education | Bachelor - Doctor |
| State | Washington, Arizona, Nevada, California, Oregon |
| EmploymentStatus | Employed, Unemployed, Medical Leave, Disabled, Retired |
| Renew Offer Type | Offer1 - Offer4 |
| Sales Channel | Agent, Call Center, Web, Branch |
| Marital Status | Married, Single, Divorced |
| Location Code | Suburban, Rural, Urban |
| Coverage | Basic, Extended, Premium
| Policy Type | Corporate Auto, Personal Auto, Special Auto |
| Vehicle Size | Medsize, Small, Large |
| Gender | F, M |
| Response | No, Yes |
| Number of Open Complaints | 0 - 5 |
| Number of Policies | 1 - 9 |
| Months Since Last Claim | 0 - 35 |
| Months Since Policy Inception | 0 - 99 |
| Monthly Premium Auto | 61 - 298 |
| Total Claim Amount | 0.099 - 2893.23 |
| Income | 0 - 99981 |
| Customer Lifetime Value | 1898 - 83325 |

**Kesimpulan dan Limitasi dari Fitur yang Digunakan dalam Model**

Dalam pengembangan model prediktif untuk industri asuransi kendaraan, kami telah menggunakan 22 fitur yang telah ditentukan dengan rentang spesifik. Berikut adalah kesimpulan dan batasan yang terkait dengan fitur-fitur tersebut:

1. **Rentang Fitur yang Ditentukan**:
   - Model telah dilatih menggunakan data yang berada dalam rentang tertentu untuk setiap fitur, seperti yang dijelaskan dalam tabel. Jika data masukan baru berada di luar rentang ini, model mungkin tidak dapat memberikan prediksi yang akurat. Misalnya, jika 'Monthly Premium Auto' melebihi 298 atau 'Income' di atas 99981, model mungkin tidak memiliki informasi yang cukup untuk menilai kondisi ini dengan benar, yang dapat menyebabkan prediksi yang tidak tepat.

2. **Ketergantungan pada Fitur Tertentu**:
   - Fitur seperti 'Policy', 'Vehicle Class', dan 'State' memiliki kategori yang jelas dan terbatas. Setiap perubahan dalam definisi atau penambahan kategori baru dalam fitur-fitur ini memerlukan pelatihan ulang model untuk memasukkan pemahaman tentang variabel baru tersebut.

3. **Adaptasi dengan Industri Lain**:
   - Model ini secara khusus dilatih dengan data dari industri asuransi kendaraan. Mengaplikasikan model ini pada industri lain, seperti asuransi kesehatan atau properti, tanpa modifikasi yang signifikan mungkin tidak efektif. Hal ini disebabkan oleh perbedaan dalam faktor-faktor yang mempengaruhi keputusan di berbagai industri.

4. **Pembaruan dan Pemeliharaan Model**:
   - Untuk memastikan bahwa model tetap relevan dan akurat, penting untuk melakukan pembaruan dan pelatihan ulang secara berkala. Ini termasuk memperbarui model dengan data terbaru dan menyesuaikan model untuk mengakomodasi perubahan dalam tren pasar atau kebijakan perusahaan.

5. **Penggunaan dalam Kondisi Operasional Nyata**:
   - Saat menerapkan model dalam operasi nyata, penting untuk memonitor performa model secara kontinu dan siap untuk melakukan penyesuaian jika diperlukan. Pengawasan ini membantu mengidentifikasi kapan model mulai kehilangan presisi atau kapan perubahan pasar mempengaruhi asumsi yang digunakan dalam pelatihan model.

Kesimpulannya, sementara model ini menawarkan alat yang berharga untuk prediksi dalam konteks asuransi kendaraan, ada beberapa batasan dan pertimbangan yang harus diperhatikan untuk memaksimalkan efektivitasnya. Memahami dan mengelola batasan ini adalah kunci untuk berhasil menerapkan model prediktif dalam praktik bisnis.

# KESIMPULAN

## **Kesimpulan**

Analisis yang dilakukan menggunakan data asuransi otomatis untuk memprediksi respons nasabah terhadap kampanye telah menunjukkan bahwa model **XGBoost Classifier** memberikan performa yang sangat baik.

**Berikut adalah beberapa poin kunci dari hasil analisis yang lebih mendalam :**

1. **Recall Tinggi (0.9943)**: Model ini berhasil mengidentifikasi 99.43% dari semua kasus positif (respons yes) yang sebenarnya, menunjukkan efektivitas model dalam menangkap respons positif yang krusial dalam konteks kampanye pemasaran. Ini penting karena memastikan bahwa peluang untuk menjangkau pelanggan yang berpotensi merespon positif tidak terlewatkan.

2. **Precision Tinggi (0.9577)**: Tingkat presisi yang tinggi ini menunjukkan bahwa hampir semua prediksi positif yang dibuat oleh model adalah akurat. Ini mengurangi risiko mengganggu pelanggan dengan komunikasi yang tidak relevan, yang dapat berdampak negatif pada reputasi merek dan kepuasan pelanggan.

3. **F1 Score (0.9756)**: Skor F1 yang tinggi menunjukkan keseimbangan yang sangat baik antara recall dan precision. Hal ini menunjukkan bahwa model ini sangat robust dalam mengidentifikasi pelanggan yang benar-benar berpotensi merespon positif, tanpa mengorbankan akurasi atau menghasilkan banyak kesalahan positif.

4. **Accuracy Tinggi (0.9929)**: Akurasi yang sangat tinggi menunjukkan bahwa model berhasil mengklasifikasikan respons secara keseluruhan dengan sangat baik, tanpa ada prediksi yang salah dari seluruh dataset. Ini menunjukkan keandalan model dalam penggunaan praktis untuk kampanye pemasaran.

5. **Insight dari Data**: Analisis lebih lanjut menunjukkan bahwa fitur seperti Policy, Policy Type, dan Vehicle Class memiliki pengaruh besar terhadap prediksi model. Ini mengindikasikan pentingnya faktor-faktor ini dalam memahami perilaku pelanggan dan merancang kampanye yang lebih tepat sasaran.

**Parameter Terbaik Untuk Tuning**

Pada project ini, penggunaan model XGBoost Classifier yang dioptimalkan melalui teknik Grid Search dengan parameter terpilih bootstrap: True, max_depth: None, max_features: auto, min_samples_leaf: 1, min_samples_split: 2, n_estimators: 200, telah terbukti sangat efektif dalam memprediksi respons nasabah terhadap kampanye asuransi kendaraan. Dengan akurasi yang mencapai 0.99, model ini memberikan wawasan yang sangat akurat mengenai pelanggan yang kemungkinan besar akan merespon Yes terhadap tawaran kampanye.

**Penjelasan Estimasi Keuntungan**

Penerapan model ini secara signifikan meningkatkan efisiensi penggunaan sumber daya pemasaran. Dengan fokus hanya pada pelanggan yang diprediksi akan merespon positif, perusahaan berhasil mengurangi biaya kampanye secara drastis dari \$14.616 menjadi hanya \$2.096. Ini menghasilkan peningkatan keuntungan bersih dari \$40.928 menjadi \$53.448, memberikan peningkatan keuntungan sebesar \$12.520.

**Kesimpulan Dari Project**

Implementasi model ini tidak hanya membawa efisiensi biaya yang lebih besar tetapi juga memungkinkan perusahaan untuk lebih personal dalam pendekatannya, meningkatkan kepuasan pelanggan dan kemungkinan retensi pelanggan jangka panjang. Dengan menargetkan pelanggan yang paling mungkin merespon, perusahaan dapat mengalokasikan sumber daya untuk mengembangkan tawaran yang lebih menarik dan komunikasi yang lebih relevan, yang pada akhirnya memperkuat hubungan pelanggan.

Kesimpulan dari project ini menunjukkan pentingnya integrasi teknologi Machine Learning dalam strategi pemasaran modern. Model prediktif seperti XGBoost Classifier membantu perusahaan asuransi kendaraan untuk tidak hanya mengoptimalkan kampanye mereka dari segi biaya tetapi juga dalam membangun hubungan yang lebih kuat dan lebih pribadi dengan pelanggan. Ke depan, perusahaan harus terus menerapkan dan menyempurnakan teknologi ini, serta mengeksplorasi aplikasi serupa dalam operasi lain untuk terus meningkatkan efektivitas dan efisiensi operasional.

Dengan memanfaatkan kekuatan model XGBoost Classifier dan mengintegrasikan hasil analisis ini ke dalam strategi bisnis, perusahaan asuransi dapat meningkatkan efektivitas kampanye mereka, terutama dalam menargetkan pelanggan yang paling mungkin merespon yes. Pendekatan yang berbasis data ini memungkinkan adaptasi yang lebih cepat terhadap perubahan kebutuhan dan perilaku pelanggan, memastikan bahwa strategi yang diimplementasikan selalu relevan dan efektif dalam mencapai pelanggan yang berpotensi merespon positif terhadap tawaran kampanye.


**Strategi Campaign**

Strategi campaign akan difokuskan dan diprioritaskan berdasarkan jumlah respons "Yes" terbanyak dari setiap segmen analisis. Berikut adalah strategi campaign yang direkomendasikan berdasarkan karakteristik dan perilaku pelanggan:

- **Berdasarkan Karakteristik Pelanggan**:
  - **Gender**: Mengimplementasikan pendekatan pemasaran yang lebih emosional dan membangun rasa komunitas untuk mendorong respons positif dari pelanggan wanita.
  - **Status Perkawinan**: Menawarkan paket keluarga dengan manfaat tambahan seperti perlindungan untuk anak atau pasangan bagi pelanggan yang sudah menikah, menekankan keamanan dan perlindungan keluarga.
  - **Lokasi**: Fokus pada kampanye di California dan Oregon, di mana terdapat kecenderungan respons positif yang tinggi, dengan menawarkan produk yang menyesuaikan dengan risiko lokal yang lebih besar.
  - **Status Pekerjaan**: Menargetkan pelanggan yang bekerja (Employed) dengan manfaat yang menonjolkan investasi jangka panjang dan keamanan finansial.
  - **Pendidikan**: Menargetkan pelanggan dengan pendidikan tingkat Bachelor dan lebih tinggi dengan menekankan nilai dan manfaat jangka panjang dari produk asuransi, menggunakan data dan statistik untuk mendukung klaim.

- **Berdasarkan Perilaku Pelanggan**:
  - **Jenis Coverage**: Melakukan upselling pada pelanggan dengan coverage dasar (Basic) dengan menawarkan upgrade ke coverage yang lebih komprehensif, menunjukkan manfaat dan perlindungan tambahan yang mereka dapatkan.
  - **Tipe Polis**: Pelanggan dengan polis tipe "Personal Auto" akan menjadi target utama untuk kampanye, dengan menawarkan manfaat yang lebih spesifik dan disesuaikan dengan kebutuhan individu.
  - **Kelas Kendaraan**: Memberikan promosi tambahan kepada pemilik kendaraan empat pintu, seperti diskon pada pembelian paket tambahan atau layanan purna jual, mengingat kecenderungan mereka untuk merespons positif terhadap penawaran.

**Rekomendasi untuk Strategi Campaign**:
- **Integrasi Data dan Teknologi**: Menggunakan analitik canggih untuk terus memonitor dan mengevaluasi efektivitas kampanye, memungkinkan penyesuaian strategi secara real-time berdasarkan respons pelanggan.
- **Personalisasi Komunikasi**: Mengembangkan pesan yang sangat personalisasi yang resonan dengan segmen target berdasarkan analisis data, meningkatkan relevansi dan resonansi pesan.
- **Kolaborasi Lintas Fungsi**: Bekerja lintas departemen, seperti antara tim pemasaran dan operasional, untuk memastikan bahwa kampanye disampaikan secara efektif dan manfaatnya dirasakan oleh pelanggan.
- **Feedback dan Iterasi**: Membangun mekanisme untuk mengumpulkan umpan balik dari pelanggan dan secara berkala meninjau serta menyesuaikan kampanye berdasarkan umpan balik tersebut untuk meningkatkan kepuasan dan retensi pelanggan.

Dengan menerapkan strategi ini, perusahaan asuransi dapat meningkatkan efektivitas pemasaran, meningkatkan penjualan, dan secara signifikan memperkuat hubungan pelanggan.

# REKOMENDASI
## **Rekomendasi Untuk Model**

- **Integrasi Data yang Lebih Luas**: Volume data yang digunakan dalam analisis ini masih terbatas. Untuk meningkatkan keakuratan model, disarankan untuk mengintegrasikan data dari berbagai sumber tambahan, seperti interaksi layanan pelanggan, aktivitas di media sosial, dan log transaksi yang lebih detail. Pengayaan dataset ini akan membantu dalam memahami perilaku pelanggan secara lebih komprehensif.

- **Pengembangan Fitur Baru**: Untuk mengukur tingkat keterlibatan pelanggan lebih efektif, pengembangan fitur baru seperti click-through rate, durasi sesi, dan frekuensi interaksi dengan berbagai kategori produk sangat disarankan. Fitur-fitur ini akan memberikan wawasan yang lebih dalam mengenai preferensi dan tingkat aktivitas pelanggan.

- **Pemodelan Prediktif untuk Respons Positif**: Berdasarkan analisis yang telah dilakukan, ada potensi untuk mengembangkan model prediktif yang menargetkan pelanggan yang berpotensi merespons positif terhadap kampanye. Model ini dapat membantu dalam menyusun strategi pemasaran yang lebih terfokus dan efektif.

- **Optimasi Hyperparameter**: Meskipun model yang dikembangkan telah menunjukkan recall yang baik, masih ada ruang untuk peningkatan. Disarankan untuk melakukan tuning hyperparameter secara lebih ekstensif dengan menggunakan teknik seperti optimasi Bayesian atau pencarian grid dengan validasi silang. Ini akan membantu dalam menemukan kombinasi parameter yang optimal untuk meningkatkan kinerja model.

- **Penerapan Deep Learning untuk Analisis Sentimen**
Dalam konteks media sosial dan interaksi layanan pelanggan, model berbasis **deep learning** seperti CNN atau LSTM untuk analisis sentimen bisa sangat berharga. Model ini dapat membantu mengidentifikasi sentimen pelanggan dari data teks, yang bisa menjadi indikator kuat dalam prediksi perilaku pelanggan.

- **Identifikasi dan Penghapusan Outlier** : Identifikasi dan penghapusan outlier yang berfungsi sebagai noise juga sangat penting, analisis lebih lanjut terhadap outlier dapat memberikan wawasan mengenai pengaruhnya terhadap model.

- **Eksplorasi teknik lanjutan** : Seperti neural networks atau deep learning, juga bisa menjadi langkah strategis untuk menangkap pola kompleks dalam data yang mungkin tidak teridentifikasi oleh model tradisional.

- **Evaluasi A/B Testing** : Pelaksanaan A/B testing dengan berbagai versi model sangat dianjurkan untuk mengevaluasi efektivitas dan akurasi model dalam konteks operasional nyata.


## **Rekomendasi Untuk Bisnis**

Berdasarkan hasil analisis yang mengesankan dari model XGBoost Classifier dalam memprediksi respons nasabah terhadap kampanye asuransi otomatis, berikut adalah beberapa rekomendasi bisnis yang dapat diimplementasikan untuk meningkatkan efektivitas dan efisiensi strategi pemasaran serta operasional, khususnya dalam meningkatkan respons 'yes' pada kampanye:

1. **Penargetan Kampanye yang Lebih Akurat**: Dengan memanfaatkan kemampuan model untuk memprediksi dengan akurasi tinggi pelanggan yang paling mungkin merespon positif, perusahaan asuransi dapat lebih fokus menargetkan upaya pemasaran mereka pada segmen ini. Hal ini tidak hanya meningkatkan konversi tetapi juga mengoptimalkan penggunaan sumber daya pemasaran, memastikan bahwa kampanye mencapai pelanggan yang paling berpotensi untuk mengatakan 'yes'.

2. **Personalisasi Tawaran**: Menggunakan insight dari variabel penting seperti 'Policy', 'Policy Type', dan 'Vehicle Class', perusahaan dapat menyesuaikan penawaran mereka untuk meningkatkan daya tarik dan relevansi bagi pelanggan individu yang diprediksi akan merespon 'yes'. Penyesuaian ini dapat mencakup premi yang lebih kompetitif, manfaat tambahan yang disesuaikan, atau kondisi polis yang lebih fleksibel, sehingga meningkatkan probabilitas respons positif.

3. **Peningkatan Retensi Pelanggan**: Dengan memanfaatkan model untuk mengidentifikasi pelanggan yang berpotensi merespon 'yes' atau yang mungkin churn, perusahaan dapat proaktif dalam menerapkan strategi retensi yang ditargetkan. Ini bisa berupa komunikasi yang lebih intensif, penawaran khusus, atau program loyalitas yang ditujukan khusus untuk mempertahankan pelanggan berharga ini.

4. **Optimasi Alokasi Anggaran**: Memahami segmen pelanggan yang lebih responsif terhadap kampanye memungkinkan perusahaan untuk mengalokasikan anggaran secara lebih efisien, mengarahkan dana ke inisiatif yang paling mungkin menghasilkan respons 'yes' dan ROI tinggi.

5. **Evaluasi dan Adaptasi Berkelanjutan**: Penting untuk terus mengevaluasi dan menyesuaikan model berdasarkan data terbaru dan umpan balik pelanggan. Pengujian A/B dan analisis respons kampanye harus dilakukan secara berkala untuk memastikan bahwa model tetap relevan dan efektif dalam memprediksi pelanggan yang akan merespon 'yes'.

6. **Penggunaan Data Secara Etis**: Memastikan bahwa semua data yang digunakan untuk melatih model diperoleh dan digunakan dengan cara yang etis dan sesuai dengan regulasi privasi. Menjaga transparansi dengan pelanggan tentang penggunaan data mereka memperkuat kepercayaan dan memastikan kepatuhan terhadap norma-norma etika.

7. **Segmentasi Pasar yang Ditingkatkan**: Model membantu mengidentifikasi nuansa karakteristik pelanggan yang mungkin tidak segera jelas, memungkinkan segmentasi pasar yang lebih mendalam. Strategi pemasaran yang lebih terpersonalisasi dapat dikembangkan untuk menargetkan pelanggan yang lebih mungkin untuk merespon 'yes', meningkatkan efektivitas keseluruhan kampanye.

Dengan mengimplementasikan rekomendasi ini, perusahaan asuransi tidak hanya dapat meningkatkan jumlah respons 'yes' dalam kampanye mereka, tetapi juga meningkatkan kepuasan pelanggan, memperkuat loyalitas, dan secara keseluruhan meningkatkan kinerja bisnis.
