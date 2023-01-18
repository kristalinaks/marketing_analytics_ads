# Business Analytics: Marketing Analytics

## 1. Intro, Background, Rumusan Masalah, dan Tujuan
Sebuah perusahaan Shopping Mall menjalankan beberapa macam iklan pada Juli-November 2021. Perusahaan ingin menghemat budget marketing tanpa menurunkan performa iklan, sehingga perusahaan harus lebih bijak lagi dalam memasang iklan. \
Perusahaan ingin mengetahui apakah campaign yang dilakukan selama ini menguntungkan dan jenis iklan mana yang memiliki kinerja terbaik.

Tujuan/pertanyaan yang perlu dijawab:
- Apakah campaign secara keseluruhan menguntungkan?
- Di bulan apakah perusahaan mendapatkan profit?
- Dua iklan mana yang menyumbang profit terbanyak pada bulan tersebut?
- Bagaimana kinerja iklan tersebut dalam aspek Brand Awareness?
- Bagaimana kinerja iklan tersebut dalam aspek Trends Generated?
Dengan menjawab pertanyaan-pertanyaan tersebut, perusahaan bisa menggunakan budget marketingnya dengan lebih efektif.

## 2. Dataset dan Tools
Dataset yang digunakan diambil dari kaggle.com dengan judul Shopping Mall Paid Search Campaign Dataset yang terdiri dari 190 baris. Dataset ini berisi iklan dalam mesin pencari yang bertujuan untuk membawa pengunjung ke website berdasarkan keyword yang dicari pengguna. Periode campaign adalah Juli — November 2021.\
Link: https://www.kaggle.com/datasets/marceaxl82/shopping-mall-paid-search-campaign-dataset

## 3. Data Preparation
Dilakukan pengecekan missing value dan duplicated, ekstraksi data dari kolom Ad Group, dan penghitungan Cost per Mille (CPM) dengan bantuan Jupyter Notebook.

## 4. Visualisasi
Berikut adalah dashboard marketing analytics yang dibuat.\
https://public.tableau.com/views/advert_16734525326890/Dashboard1?:language=en-GB&publish=yes&:display_count=n&:origin=viz_share_link

Pengguna dashboard bisa melihat kinerja iklan secara keseluruhan melalui metrics yang ditampilkan di bagian atas dashboard. Trend per bulannya juga dapat dilihat pada line chart. Selain itu, pengguna bisa melihat lebih rinci kinerja masing-masing ad group baik dari brand awareness, traffics generated, maupun sales generated. Pengguna juga bisa melakukan filter data berdasarkan bulan dan tipe device.

## 5. Insight dan Kesimpulan
Secara keseluruhan, campaign iklan yang dijalankan perusahaan belum menguntungkan dan selalu rugi di setiap bulan kecuali di bulan Oktober. Pada bulan Oktober tersebut, dua tipe iklan yang memiliki kinerja terbaik dalam aspek brand awareness, traffics generated, dan sales generated adalah iklan tipe Coupon dan Discount.

Oleh karena itu, dengan analisis yang telah dilakukan saat ini, dapat disimpulkan bahwa perusahaan bisa mempertimbangkan untuk lebih memfokuskan iklan pada kedua tipe iklan tersebut untuk menjawab kebutuhan Manager Marketing dalam menghemat budget marketing tanpa menurunkan performa iklan.

Tentunya analisis lanjutan yang lebih dalam bisa dilakukan terlebih dahulu, terutama untuk analisis di bulan-bulan yang mengalami kerugian.
