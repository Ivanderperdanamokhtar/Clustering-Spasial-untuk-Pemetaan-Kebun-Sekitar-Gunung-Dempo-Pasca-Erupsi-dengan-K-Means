# Clustering-Spasial-untuk-Pemetaan-Kebun-Sekitar-Gunung-Dempo-Pasca-Erupsi-dengan-K-Means
 Proyek ini memetakan dampak erupsi Gunung Dempo 2023 di Pagar Alam menggunakan K-Means Clustering. Data citra satelit diolah dengan Normalized Burn Ratio (NBR) untuk mengidentifikasi area terdampak dan tidak terdampak. Pengolahan menggunakan QGIS dan Python, dengan evaluasi Davies-Bouldin Score.

# Analisis Clustering Spasial untuk Pemetaan Wilayah Kebun di Sekitar Gunung Dempo Setelah Erupsi dengan Pendekatan K-Means


Erupsi Gunung Dempo pada tahun 2023 menyebabkan kerusakan signifikan pada wilayah perkebunan di sekitarnya. Penelitian ini memanfaatkan analisis clustering spasial menggunakan metode **K-Means** untuk memetakan dampak pasca-erupsi. Data citra satelit dari United States Geological Survey (USGS) diolah dengan metode **Normalized Burn Ratio (NBR)** untuk mengidentifikasi area terdampak. Hasil menunjukkan bahwa wilayah terdampak mencakup 524,95 km², sedangkan wilayah yang tidak terdampak mencakup 59,29 km². 

## Tujuan
1. Menganalisis distribusi vegetasi sebelum dan sesudah erupsi menggunakan **NBR**.
2. Mengidentifikasi area terdampak dan tidak terdampak menggunakan clustering **K-Means**.
3. Mengevaluasi kondisi agrikebun pasca-erupsi.

## Data dan Metode
- **Data:** 
  - Citra satelit sebelum erupsi (07 Agustus 2022).
  - Citra satelit setelah erupsi (27 September 2023).
- **Alat:** 
  - **Quantum GIS (QGIS)**: Pengolahan data geospasial.
  - **Python**: Pengolahan data clustering dan visualisasi.
- **Metode:** 
  - **Normalized Burn Ratio (NBR)**: Analisis kebakaran lahan.
  - **K-Means Clustering**: Pembagian area terdampak dan tidak terdampak (K=2).
  - **Davies-Bouldin Score**: Evaluasi akurasi clustering.

## Hasil
1. **Distribusi Vegetasi:**
   - Sebelum erupsi: Vegetasi lebat terlihat dominan.
   - Setelah erupsi: Area terdampak lebih luas, terutama di wilayah Pagar Alam.
2. **Clustering:**
   - Area terdampak: 524,95 km².
   - Area tidak terdampak: 59,29 km².
3. **Akurasi Clustering:**
   - Davies-Bouldin Score: 0.10575317166343755 (kualitas clustering sangat baik).

## Kesimpulan
- Wilayah kebun di Pagar Alam mengalami kerusakan signifikan akibat erupsi Gunung Dempo.
- **K-Means Clustering** terbukti efektif untuk mengidentifikasi area terdampak.
- Informasi ini dapat digunakan sebagai dasar untuk upaya pemulihan dan mitigasi pasca-bencana.

## Referensi
1. Rahayu, et al. (2014). Dampak erupsi Gunung Merapi terhadap lahan dan upaya-upaya pemulihannya. Caraka Tani.
2. Phillips, J., et al. (2019). Dynamic and extensive risk arising from volcanic ash impacts on agriculture. GAR 2019.
3. Fiantis, D., et al. (2019). Volcanic Ash, Insecurity for the People but Securing Fertile Soil for the Future. Sustainability.
4. Ginting, J. A., & Jadera, A. M. (2018). Analisa Indeks Vegetasi Menggunakan Metode K-Means. IJMC.

## Kontributor
- Ivander Perdana Mokhtar
- Arsyiah Azahra
- Aulia Wardani 
- Lion Abdi Marga
- Kharisma Gumilang
- Sella Dianka Fitri
