# Proyek Akhir: Solving Human Resources 

## Business Understanding
Jaya Jaya Maju adalah perusahaan multinasional yang didirikan sejak tahun 2000, dengan lebih dari 1000 karyawan yang tersebar di berbagai wilayah di seluruh negeri

### Business Problems
Meskipun Jaya Jaya Maju merupakan perusahaan yang cukup besar, perusahaan ini menghadapi tantangan dalam mengelola karyawannya secara efektif. Hal ini menyebabkan tingkat turnover yang tinggi lebih dari 10% yang mencerminkan proporsi karyawan yang keluar dibandingkan dengan total jumlah karyawan. Tingkat turnover yang tinggi ini dapat menimbulkan berbagai masalah bagi perusahaan, seperti penurunan produktivitas, meningkatnya biaya rekrutmen dan pelatihan, serta hilangnya pengetahuan berharga dari karyawan yang berpengalaman. Untuk mengatasi masalah ini, data scientist perlu mengidentifikasi faktor-faktor yang memengaruhi tingginya tingkat turnover tersebut.

### Cakupan Proyek
Proyek ini bertujuan untuk menekan tingkat turnover karyawan (attrition rate) di Jaya Jaya Maju dengan menganalisis dan memvisualisasikan faktor-faktor yang memengaruhi karyawan untuk meninggalkan perusahaan. Selain itu, proyek ini juga akan mengembangkan sistem klasterisasi untuk mengidentifikasi karyawan dengan risiko tinggi mengalami turnover. Hasil proyek ini akan berupa dashboard visualisasi dan program prediksi yang dapat menentukan apakah seorang karyawan berpotensi mengalami turnover."

### Preparation

Sumber data: https://github.com/dicodingacademy/dicoding_dataset/tree/main/employee

Dasboard Link: https://lookerstudio.google.com/reporting/48ab36bf-3e42-41a8-8219-9455404efa52

Link Google Colab : https://colab.research.google.com/drive/1YYb_NMvmOJ8xtKn7AwDlV2gYZmLrb8vU?usp=sharing

Setup environment:

1. Install pipenv
```
pip install pipenv
```

2. Create an environment 
```
pipenv install
```

3. Install dependencies
```
pipenv install -r requirements.txt
```

## Business Dashboard
Dashboard analisis karyawan menunjukkan tren penting dari 1.058 karyawan, dengan tingkat turnover 16,9% dimana 179 karyawan keluar terutama dari departemen R&D (107) dan Penjualan (64), khususnya mempengaruhi Teknisi Laboratorium (49) dan Eksekutif Penjualan (39); analisis menunjukkan karyawan yang keluar memiliki kompensasi lebih rendah (rata-rata pendapatan bulanan ~4.500 vs ~7.000 untuk karyawan yang bertahan) meski memiliki tarif bulanan lebih tinggi, dengan 45,3% bekerja lembur, mengindikasikan tantangan retensi terkait struktur kompensasi, manajemen beban kerja, dan peluang pengembangan karir di bidang teknis dan penjualan.

## Conclusion
Berdasarkan analisis yang diberikan, tingkat turnover karyawan menjadi salah satu isu penting bagi perusahaan, dengan tingkat attrition sebesar 16,9% yang menunjukkan bahwa 179 karyawan telah keluar dari total 1.058 karyawan. Meskipun tidak terlalu tinggi, angka ini mengungkapkan beberapa area yang perlu diperhatikan, terutama di departemen seperti Research & Development (R&D) dan Sales. Posisi seperti Laboratory Technician, Sales Executive, dan Research Scientist mencatat tingkat turnover tertinggi, menunjukkan tantangan dalam mempertahankan talenta di peran teknis dan eksekutif.

Data juga menunjukkan beberapa faktor penyebab, seperti kerja lembur dan pola kompensasi. Karyawan yang bertahan di perusahaan umumnya menerima rata-rata pendapatan harian dan bulanan yang lebih tinggi, mengindikasikan bahwa gaji dan tambahan kompensasi sangat memengaruhi tingkat retensi. Hubungan antara pendapatan dan turnover ini menekankan pentingnya kompensasi yang adil, kepuasan kerja, dan peluang pengembangan karier. Mengatasi faktor-faktor ini melalui strategi retensi yang terarah dan didukung oleh wawasan data akan menjadi kunci untuk meningkatkan kepuasan karyawan dan menekan tingkat turnover.

### Rekomendasi Action Items
1.Evaluasi struktur kompensasi di departemen R&D dan Penjualan - penyesuaian gaji dan tunjangan untuk menyeimbangkan kesenjangan pendapatan bulanan, terutama untuk posisi Teknisi Lab dan Eksekutif Penjualan.
2.Tingkatkan kebijakan lembur dan beban kerja - implementasi sistem rotasi kerja dan pengaturan jadwal yang lebih efektif, mengingat 45,3% karyawan yang keluar bekerja sering mengalami lembur.
3.Kembangkan jalur karir yang jelas - fokus pada departemen R&D dan Penjualan dengan program pengembangan karir terstruktur, pelatihan khusus, dan mentoring untuk posisi teknis dan penjualan yang memiliki turnover tinggi.
