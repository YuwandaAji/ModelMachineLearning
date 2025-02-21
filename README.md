# Submission Model Clustering dan Model Klasifikasi
Proyek ini merupakan proyek submission dicoding. Proyek ini dibuat menggunakan dataset "Car Sales.xlsx - car_data.csv", berikut link untuk dataset tersebut: https://www.kaggle.com/datasets/missionjee/car-sales-report

**Tentang Proyek**

Proyek ini memiliki dua tahap, yang pertama adalah membangun model clustering yang bertujuan memberikan label pada dataset. Pada tahap ini algoritma yang digunakan adalah algoritma Kmeans. Selanjutnya, tahap kedua adalah membangun model klasifikasi. Pada tahap ini algoritma yang digunkan adalah algoritma K-Nearest Neighbors dan algoritma Random Forest

**Hasil Model Clustering**

Nilai silhouette score: 0.6298427102836633

Tulis hasil interpretasinya di sini.
1. Cluster 1:
* Rata-Rata Annual Income: 50588.93
* Rata-Rata Harga Mobil: 27949.44
* Merek Mobil Paling Banyak Diminati: Chevrolet
* Model Mobil Paling Banyak Diminati: Passat
* Body Style yang Banyak Diminati: SUV

Analisis: Cluster ini terdiri dari pelanggan yang memiliki pendapatan tahunan rendah dengan mobil yang dibeli dengan harga yang rendah juga. Selain itu, dalam cluster ini pelanggan sangat meminati mobil yang bermerek Chevrolet dan juga sangat meminati mobil dengan body style SUV. Namun, di sisi lain pelanggan juga sangat meminati mobil dengan model Passat yang merupakan medel keluaran merek Volkswagen dengan body style hatchback, yang artinya selain didominasi oleh pelanggan yang meminati merek Chevrolet cluster ini juga didominasi oleh pelanggaan yang meminati merek Volkswagen dan juga selain didominasi oleh pelanggan yang meminati body style SUV cluster ini juga didominasi oleh pelanggaan yang meminati body style hatchback. Berdasarkan hal-hal tersebut, dapat disimpulkan bahwa kemungkinan besar cluster ini terdiri dari pelanggan yang mengedepankan fungsionalitas, harga murah, serta memiliki kekayaan rendah dan juga pelanggan yang mengedepankan desain eksterior, harga murah, serta memiliki kekayaan yang juga rendah.

2. Cluster 2:
* Rata-Rata Annual Income: 1469182.95
* Rata-Rata Harga Mobil: 28013.14
* Merek Mobil Paling Banyak Diminati: Chevrolet
* Model Mobil Paling Banyak Diminati: Diamante
* Body Style yang Banyak Diminati: Hatchback

Analisis: Cluster ini menunjukkan pelanggan dengan pendapatan tinggi dengan mobil yang dibeli dengan harga sedang. Selain itu, dalam cluster ini telah ditunjukkan bahwa pelanggan sangat meminati mobil yang bermerek Chevrolet dan juga sangat meminati mobil dengan body style Hatchback. Namun, di sisi lain pelanggan juga sangat meminati mobil dengan model Diamante yang merupakan medel keluaran merek Mitsubishi dengan body style hatchback, yang artinya selain didominasi oleh pelanggan yang meminati merek Chevrolet cluster ini juga didominasi oleh pelanggaan yang meminati merek Mitsubishi. Berdasarkan hal-hal tersebut, dapat disimpulkan bahwa kemungkinan besar cluster ini terdiri dari pelanggan yang mengedepankan desain eksterior (seperti anak muda atau mereka yang berjiwa muda), harga sedang saja, serta memiliki kekayaan yang tinggi.

3. Cluster 3:
* Rata-Rata Annual Income: 2914406.90
* Rata-Rata Harga Mobil: 28996.50
* Merek Mobil Paling Banyak Diminati: Dodge
* Model Mobil Paling Banyak Diminati: Passat
* Body Style yang Banyak Diminati: SUV

Analisis: Cluster ini mencangkup pelanggan dengan pendapatan sangat tinggi dengan mobil yang dibeli dengan harga yang sangat tinggi juga. Selain itu, cluster ini juga mencangkup pelanggan yang sangat meminati mobil yang bermerek Dodge dan juga sangat meminati mobil dengan body style SUV. Namun, di sisi lain pelanggan juga sangat meminati mobil dengan model Passat yang merupakan medel keluaran merek Volkswagen dengan body style hatchback, yang artinya selain didominasi oleh pelanggan yang meminati merek Dodge cluster ini juga didominasi oleh pelanggaan yang meminati merek Volkswagen dan juga selain didominasi oleh pelanggan yang meminati body style SUV cluster ini juga didominasi oleh pelanggaan yang meminati body style hatchback. Berdasarkan hal-hal tersebut, dapat disimpulkan bahwa kemungkinan besar cluster ini terdiri dari pelanggan premium yang mengedepankan fungsionalitas, harga tinggi tidak masalah, serta memiliki kekayaan yang sangat tinggi dan juga pelanggan yang mengedepankan desain eksterior, harga tinggi tidak masalah, serta memiliki kekayaan yang juga sangat tinggi.

4. Cluster 4:
* Rata-Rata Annual Income: 724149.28
* Rata-Rata Harga Mobil: 28116.38
* Merek Mobil Paling Banyak Diminati: Chevrolet
* Model Mobil Paling Banyak Diminati: Prizm
* Body Style yang Banyak Diminati: SUV

Analisis: Cluster ini memperlihatkan pelanggan dengan pendapatan tahunan sedang dengan mobil yang dibeli dengan harga yang tinggi. Selain itu, cluster ini juga memperlihatkan bahwa pelanggan sangat meminati mobil yang bermerek Chevrolet dan juga sangat meminati mobil dengan body style SUV. Di sisi lain, pelanggan juga sangat meminati mobil dengan model Prizm yang juga merupakan model keluaran merek Chevrolet dengan body style Hardtop, yang artinya selain didominasi oleh pelanggan yang meminati body style SUV cluster ini juga didominasi oleh pelanggaan yang meminati body style hardtop. Berdasarkan hal-hal tersebut, dapat disimpulkan bahwa kemungkinan besar cluster ini terdiri dari pelanggan yang mengedepankan fungsionalitas, harga tinggi tidak masalah, serta memiliki kekayaan sedang dan juga pelanggan yang mengedepankan desain klasik atau mobil mewah, harga tinggi tidak masalah, serta memiliki kekayaan yang juga sedang.

**Hasil Model Klasifikasi**

Hasil Evaluasi K-Nearest Neighbors (KNN):
Training Set:
* Accuracy: 0.999582
* Precision: 0.999582
* Recall: 0.999582
* F1-Score: 0.999582
* Training MSE: 0.0024053545283413513

Testing Set:
* Accuracy: 0.999791
* Precision: 0.999791
* Recall: 0.999791
* F1-Score: 0.999791
* Confusion Matrix: terdapat satu kesalahan prediksi
* Testing MSE: 0.001672940192388122

Hasil Evaluasi Random Forest (RF):
Training Set:
* Accuracy: 1.000000
* Precision: 1.000000
* Recall: 1.000000
* F1-Score: 1.000000
* Training MSE: 0.0

Testing Set:
* Accuracy: 0.999582
* Precision: 0.999582
* Recall: 0.999582
* F1-Score: 0.999582
* Confusion Matrix: terdapat dua kesalahan prediksi
* Testing MSE: 0.001672940192388122

Berdasarkan hasil evaluasi tersebut, model yang dihasilkan oleh algoritma K-Nearest Neighbors dan algoritma Random Forest tidak mengalami overfitting maupun underfitting. Hal tersebut dibuktikan dengan nilai training MSE dan Testing MSE masing-masing model yang tidak memiliki selisih yang banyak. Selain itu, kedua model tersebut juga memiliki nilai Accuracy, Precision, Recall, dan F1-Score yang sangat memuaskan. Jika dibandingkan, K-Nearest Neighbors unggul dengan selisih yang sangat kecil dibanding Random Forest. Namun, jika melihat hasil dari confusion matrix K-Nearest Neighbors hanya memiliki satu kesalahan prediksi dan Random Forest memiliki dua kesalahan prediksi. Hal itu hanyalah nilai selisih yang kecil tapi dengan begitu membuat lebih jelas bahwa Model yang paling optimal adalah model K-Nearest Neighbors.

