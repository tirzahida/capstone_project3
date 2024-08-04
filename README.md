## Capstone Project 
Project ini dilakukan untuk menganalisis data serta membangun machine learning yang sesuai dengan data dan kebutuhan bisnis. 
## Bussiness problem understanding
Daegu merupakan salah satu kota terbesar di Korea Selatan. Banyaknya populasi di Daegu membuat penduduk membutuhkan tempat tinggal contohnya apartemen. 
Permintaan terhadap apartemen di lokasi strategis dengan fasilitas lengkap terus meningkat, terutama di sekitar pusat bisnis dan kawasan industri.
Banyaknya apertemen yang ada di Daegu membuat tingginya persaingan antar penyewa atau pemilik apartemen. 
Maka dari itu pemilik apartemen harus memahami faktor apa saja yang mempengaruhi harga penyewaan agar mendapatkan profit maksimal serta mengetahui harga pasaran dengan fasilitas yang dimiliki.
Pemilik apartemen perlu memiliki model bisnis untuk memprediksi harga jual apartemen di Daegu.
Model bisnis yang efektif dapat meningkatkan keuntungan dan menyesuaikan harga jual sesuai dengan permintaan pasar.
Berdasarkan permasalahan tersebut pemilik apartemen dapat menentukan harga jual yang optimal, sehingga dapat memaksimalkan profit bagi pemilik apartemen.
## Metrics evaluation
Evaluation metrics yang akan digunakan adalah R-Squared, MAE, MSE, dan RMSE.
Semakin kecil nilai MAE, MSE, dan RMSE maka model semakin akurat dalam memprediksi harga sewa sesuai dengan limitasi fitur yang digunakan. 
## Model
pada analisis ini kita menggunakan model linear regression dan decision tree. 
Lalu, kita melakukan hyperparameter tuning dengan menggunakan model Polynomial features dan Random forest
## Kesimpulan
Model yang menghasilkan r-squared terbesar dan nilai MAE, MSE, dan RMSE terkecil adalah model random forest yang menggunakan hyperparameter tuning.
Kolom fitur yang paling berpengaruh adalah kolom Size(sqf), HallwayType dengan tipe terraced, dan YearBuilt.
Error terkecil didapatkan 15% kesalahan prediksi. Artinya jika kita menggunakan model ini untuk memperkirakan harga unit apartemen di Daegu, 
maka perkiraan harganya rata-rata akan meleset kurang lebih sebesar 15% dari harga seharusnya, yang berarti masih ada ruang untuk perbaikan lebih lanjut. 
