# Proyek Pertama: Menyelesaikan Permasalahan Human Resources

## Business Understanding

Jaya Jaya Maju merupakan perusahaan multinasional yang telah berdiri sejak tahun 2000 dan memiliki lebih dari 1000 karyawan yang tersebar di seluruh Indonesia. Meskipun telah tumbuh menjadi perusahaan besar, Jaya Jaya Maju menghadapi tantangan dalam mengelola karyawannya, yang berdampak pada tingginya attrition rate atau rasio karyawan keluar terhadap total karyawan. Tingkat attrition yang tinggi ini dapat menimbulkan biaya tambahan untuk perekrutan ulang, pelatihan, serta berpotensi mengganggu produktivitas dan moral tim. Oleh karena itu, perusahaan ingin memahami faktor-faktor yang memengaruhi attrition dan memitigasi risikonya.


### Permasalahan Bisnis

- Tingginya attrition rate (lebih dari 10%) di perusahaan.
- Tidak adanya alat bantu visual (dashboard) untuk memantau faktor-faktor yang memengaruhi keputusan karyawan untuk keluar.
- Belum ada model prediktif yang dapat membantu mengidentifikasi karyawan yang berisiko tinggi keluar.

### Cakupan Proyek

- Melakukan eksplorasi dan pemahaman data karyawan untuk mengetahui karakteristik yang berhubungan dengan attrition.
- Membangun model prediksi untuk memprediksi kemungkinan karyawan akan keluar.
- Menggunakan berbagai algoritma machine learning (Logistic Regression, Random Forest, dan XGBoost) untuk melakukan prediksi.
- Membuat dashboard visualisasi untuk memantau metrik yang berkaitan dengan attrition.

### Persiapan

Sumber data: [employee_data.csv](https://github.com/dicodingacademy/dicoding_dataset/blob/main/employee/employee_data.csv)

Setup environment - Google Colaboratory:
- Buka Google Colab: https://colab.research.google.com/
- Upload file notebook: [Proyek_Pertama_Nabila_Salsabila.ipynb](https://colab.research.google.com/drive/1re1ts79ReW9FSZCo7yQYTaXXguz-E6xV?usp=sharing)
- Install library tambahan jika diperlukan:
- Upload Dataset
-- Klik ikon folder di sisi kiri Google Colaboratory
-- Klik "Upload files"
-- Upload file dataset: [employee_data.csv](https://github.com/dicodingacademy/dicoding_dataset/blob/main/employee/employee_data.csv)
- Run Notebook
-- Klik menu "Runtime" > "Run all" untuk menjalankan seluruh analisis
- Dashboard - Looker Studio
-- Link dashboard: [HR Attrition Dashboard - Jaya Jaya Maju](https://lookerstudio.google.com/reporting/83989796-bf09-452e-a932-8c6cb955053f)

## Business Dashboard

Untuk membantu manajer departemen HR dalam memantau faktor-faktor yang mempengaruhi tingkat attrition (keluarnya karyawan), HR Attrition Dashboard ini menampilkan berbagai visualisasi dan metrik terkait kondisi karyawan di perusahaan Jaya Jaya Maju, antara lain:

- **Total Employee:** 1.081.185 karyawan  
- **Total Attrition:** 1.058 karyawan  
- **Attrition Rate:** 16,92%  
- **Average Monthly Income:** Rp6.502,93  

Dashboard ini juga menyajikan visualisasi attrition berdasarkan berbagai dimensi seperti:

- **Job Role**: Menunjukkan peran pekerjaan dengan tingkat attrition tertinggi.
- **Department**: Memperlihatkan departemen dengan angka attrition tertinggi (misalnya Research & Development).
- **Overtime**: Menampilkan bahwa mayoritas karyawan yang mengalami attrition bekerja lembur.
- **Gender**: Membandingkan attrition antara karyawan laki-laki dan perempuan.

Visualisasi ini memungkinkan pihak HR untuk lebih cepat mengidentifikasi pola dan potensi akar permasalahan yang menyebabkan karyawan keluar.

Dashboard dapat diakses melalui link berikut:
[HR Attrition Dashboard - Jaya Jaya Maju](https://lookerstudio.google.com/reporting/83989796-bf09-452e-a932-8c6cb955053f)

## Conclusion

Berdasarkan analisis yang telah dilakukan, ditemukan beberapa karakteristik umum dari karyawan yang cenderung mengalami attrition, yaitu:

- Karyawan yang sering bekerja lembur (OverTime) memiliki kemungkinan attrition lebih tinggi.
- Attrition lebih banyak terjadi pada karyawan yang bekerja di departemen Research & Development dan Sales.
- Dari sisi jabatan, Sales Executive dan Research Scientist menjadi posisi dengan tingkat attrition tertinggi.
- Attrition lebih banyak terjadi pada karyawan laki-laki (60,3%) dibanding perempuan (39,7%).
- Sebagian besar karyawan yang mengalami attrition tidak melakukan lembur (Overtime), namun karyawan yang lembur tetap menunjukkan proporsi signifikan (29%).

Dengan mengetahui faktor-faktor ini, departemen HR dapat merancang strategi retensi, seperti program pengembangan karier serta pemberian penghargaan dan insentif berdasarkan kinerja.

### Rekomendasi Action Items (Optional)

- Meningkatkan strategi retensi di departemen dengan tingkat attrition tinggi, seperti program pengembangan karier dan mentoring di departemen Research & Development dan Sales.
- Memberikan perhatian khusus pada kelompok jabatan dengan tingkat risiko tinggi seperti Sales Executive.
- Meningkatkan employee engagement melalui pelatihan, jenjang karier, atau fleksibilitas kerja.
- Mengintegrasikan model ini ke sistem HR untuk monitoring berkala.
