# Regresi Apartment Data

# Latar Belakang
Pemilik apartemen di perkotaan sering kesulitan menetapkan harga yang tepat karena keterbatasan informasi. Harga yang tidak akurat dapat menyebabkan penjualan lambat atau kerugian finansial. Model prediksi harga yang mempertimbangkan faktor internal dan eksternal, seperti ukuran dan akses transportasi, penting untuk memaksimalkan penjualan.

Permasalahan Bisnis:
Pemilik apartemen kesulitan menentukan harga sesuai pasar, sering kali berdasarkan informasi terbatas. Harga yang terlalu tinggi memperlambat penjualan, sementara harga yang terlalu rendah menyebabkan kerugian.

Tujuan:
Mengembangkan model regresi yang dapat memprediksi harga apartemen berdasarkan faktor seperti ukuran, tahun dibangun, fasilitas, dan jarak ke transportasi umum, sehingga pemilik dapat menetapkan harga yang sesuai dengan kondisi pasar.

Pendekatan Analitik:
Model regresi akan dikembangkan untuk memprediksi harga jual berdasarkan fitur-fitur yang tersedia. Analisis fitur akan dilakukan untuk mengetahui faktor-faktor yang paling berpengaruh terhadap harga.

Metrik Evaluasi:
RMSE dan MAPE digunakan untuk mengukur akurasi model, di mana nilai yang lebih kecil menunjukkan prediksi yang lebih baik.

# Kesimpulan dan Rekomendasi
Kesimpulan:
Fitur utama yang mempengaruhi harga apartemen adalah Size(sqf), N_FacilitiesInApt, N_Parkinglot(Basement), YearBuilt, dan HallwayType. Ukuran (Size) apartemen adalah faktor paling berpengaruh. Model mencapai MAPE sebesar 18%, menunjukkan akurasi yang cukup baik, meskipun masih bisa ditingkatkan.

Rekomendasi:
Pemilik apartemen sebaiknya mempertimbangkan ukuran, tipe apartemen, fasilitas dalam apartemen, dan tahun dibangunnya apartemen saat menetapkan harga jual. Sedangkan untuk meningkatkan model dapat dilakukan:
- Gunakan teknik lain untuk menangani outlier selain penghapusan, seperti robust.
- Mencoba model lebih kompleks seperti Gradient Boosting dan XGBoost.
- Tambahkan fitur seperti jumlah kamar atau ruangan dan jarak ke pusat kota untuk prediksi yang lebih baik.

# Dataset
Sumber: Dataset Apartment Data
