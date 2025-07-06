# 📊 Analisis Faktor-Faktor yang Mempengaruhi Survival Time Pasien Penderita Primary Biliary Cirrhosis

## 📌 Latar Belakang

Primary Biliary Cirrhosis (PBC) adalah penyakit hati autoimun kronis yang dapat menyebabkan kerusakan hati progresif dan peningkatan risiko kematian. Memahami faktor-faktor yang memengaruhi kelangsungan hidup pasien sangat penting untuk meningkatkan strategi pengobatan dan pengambilan keputusan klinis. Proyek ini menggunakan teknik **analisis survival** untuk mengkaji pengaruh berbagai variabel klinis dan demografis terhadap waktu bertahan hidup pasien PBC.

## 🛠 Metodologi

Analisis dilakukan melalui beberapa tahapan berikut:

1. **Pra-pemrosesan Data**: Pembersihan dan transformasi dataset PBC dari Mayo Clinic.
2. **Kurva Kaplan-Meier**: Mengestimasi probabilitas bertahan hidup dari waktu ke waktu.
3. **Uji Log-rank**: Membandingkan distribusi survival antar kelompok pasien yang berbeda.
4. **Model Cox Proportional Hazard**: Mengidentifikasi prediktor signifikan terhadap kelangsungan hidup.
5. **Model Cox Ekstensi dengan Kovariat Bergantung Waktu**: Menangani pelanggaran asumsi proporsionalitas untuk meningkatkan akurasi model.

## 📊 Kesimpulan

* **Kurva Kaplan-Meier** menunjukkan bahwa faktor seperti ascites, hepatomegali, dan jenis kelamin secara signifikan memengaruhi peluang bertahan hidup.
* **Uji log-rank** mengonfirmasi adanya perbedaan statistik dalam survival berdasarkan faktor klinis tertentu.
* **Model Cox Proportional Hazard** mengidentifikasi kadar bilirubin, albumin, dan usia sebagai prediktor signifikan terhadap waktu bertahan hidup.
* **Model Cox Ekstensi** mampu menangani kovariat yang berubah seiring waktu, sehingga meningkatkan akurasi prediksi.

Proyek ini memberikan wawasan berharga tentang pola survival pasien PBC dan berpotensi mendukung strategi pengobatan yang lebih personal.
