# Supermarket-Products-Analysis

## About Dataset
Dataset ini merupakan dataset customer personality yang dimiliki oleh supermarket dari tahun 2012 - 2014. Dataset ini dibagi menjadi 4 kategori, yaitu data customer, product yang dibeli, promosi yang di ambil, dan platform yang digunakan.

Berdasarkan hasil riset yang telah dilakukan, ditemukan bahwa dataset ini diupload oleh Akash Patel (seorang pengajar di Texas) di Kaggle[[1]](https://time.com/6179344/akash-patel-innovative-teachers-2022/). Oleh karena itu, selanjutnya akan diasumsikan bahwa dataset  ini adalah dataset salah satu supermarket yang ada di Texas. Adapun hal-hal yang akan dapat mendukung asumsi ini akan di jelaskan di bagian analisa.

Dataset dan data dictionary dapat diakses [di sini](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis).

## Background
Sebuah supermarket di Texas menjual beberapa jenis product yakni wine, meat, fish, fruit, sweet dan gold product. Supermarket ini telah melakukan pendataan terhadap customernya sejak tahun 2012 hingga 2014 dan ingin mengevaluasi tingkat penjualan produk 3 tahun belakangan ini.

## Problem Statement
Purchasing Manager/Procurement Manager supermarket ingin mengetahui produk apa saja yang penjualannya efektif agar supermarket dapat lebih memaksimalkan profitnya.

## Conclusion
Berikut adalah rangkuman setiap kesimpulan dari hasil analisa sebelumnya.

1. Berdasarkan Data Total Penjualan Masing-Masing Produk, kita dapat melihat bahwa penjualan produk **Fish** lebih rendah dibandingkan dengan penjualan produk **Meat**. Hal ini karena texas secara geografi luas perairannya hanya sekitar 2.7% jika dibandingkan dengan luas daratannya (97.3)[[2]](https://www.infoplease.com/us/states/land-and-water-area-of-states). Karena kondisi ini, penduduk di texas yang memiliki minat tinggi terhadap produk fish hanya mereka yang ada di pesisir kota texas seperti [Galveston](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.southernliving.com%2Ftravel%2Ftexas%2Fwhats-new-in-galveston&psig=AOvVaw2r-2J7pErJiwsU0ZMHK5SN&ust=1684091720391000&source=images&cd=vfe&ved=0CBEQjRxqFwoTCJjK_taA8_4CFQAAAAAdAAAAABAE), [Corpus Christi](https://www.google.com/url?sa=i&url=https%3A%2F%2Ftotallytexastravel.com%2Fthings-to-do-in-corpus-christi%2F&psig=AOvVaw3g0HCJIYmFUkKUfDNtB0P4&ust=1684091775945000&source=images&cd=vfe&ved=0CBEQjRxqFwoTCOCZ3_GA8_4CFQAAAAAdAAAAABAR), dan [Port Aransas](https://www.google.com/search?q=Port+Aransas&source=lmns&bih=706&biw=1536&rlz=1C1GCEA_enID973ID973&hl=id&sa=X&ved=2ahUKEwjnh-Ky__L-AhV_AbcAHfnuBDsQ_AUoAHoECAEQAA). Adapun penduduk yang jauh dari area pantai atau pesisir, minat terhadap produk fish tidak sebesar mereka yang tinggal di dekat pantai karena kurangnya aksesibilitas untuk bisa mendapatkan produk fish yang segar. Oleh karena itu, mereka memilih produk lain seperti meat.
1. Minat orang texas terhadap produk **wine** terbilang tinggi. Hal ini karena texas memiliki iklim yang beragam dan kondisi tanah yang baik sehingga memiliki potensi tumbuhnya anggur yang berkualitas[[3]](https://www.reddyvineyards.com/blog/wine-and-grape-growers-in-west-texas-high-plains-ava/). Selain itu, di texas ada beberapa daerah wine terkenal seperti [Hill Country](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.decanter.com%2Fwine-travel%2Ftexas-hill-country-for-winelovers-the-places-to-know-472115%2F&psig=AOvVaw0ebWgWbsXkYy81VxitFRlC&ust=1684092518950000&source=images&cd=vfe&ved=2ahUKEwiXjZTUg_P-AhWlXmwGHdTkAKQQjRx6BAgAEAw), [Fredericksburg](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.viator.com%2Ftours%2FFredericksburg%2FFredericksburg-Hill-Country-Wine-Tour%2Fd50796-34335P1&psig=AOvVaw0UCWgrgUCbOmF6dI-tsLFN&ust=1684092514199000&source=images&cd=vfe&ved=2ahUKEwjjiPLRg_P-AhXeXmwGHd1MC5gQjRx6BAgAEAw) dan [Texas Plains](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.decanter.com%2Fpremium%2Ftexas-high-plains-ava-profile-plus-10-exciting-wines-to-try-490864%2F&psig=AOvVaw0acImiPtu57QtbrMW1rAX5&ust=1684092662236000&source=images&cd=vfe&ved=0CBEQjRxqFwoTCMiunpiE8_4CFQAAAAAdAAAAABAE) yang menarik banyak wisatawan tiap tahun. Berbagai festival dan event bertema wine di area tersebut hampir diadakan sepanjang tahun sehingga semakin meningkatkan minat penduduk di texas terhadap wine. 
1. **Gold** bukanlah produk yang dibutuhkan untuk dikonsumsi setiap hari sebagaimana meat, fish dan lainnya. Customer hanya membeli gold di waktu atau keadaan tertentu seperti ketika mereka memiliki kelebihan dana dan ingin menginvestasikannya dengan membeli gold. Sehingga untuk angka penjualan dari gold terbilang hal yang wajar dan sulit jika ingin ditingkatkan.
1. Berdasarkan data, dapat dilihat jika customer supermarket paling banyak adalah mereka yang telah married. Kemudian diurutan kedua terbanyak adalah customer yang masih single. Dengan mengetahui banyaknya customer dari segi marital status, kita dapat menyusun strategi terkait product apa yang paling diminati oleh kedua kategori marital status tersebut sehingga dapat lebih meningkatkan penjualan produk dari supermarket itu sendiri.
1. Meskipun Gen X generasi terbanyak pertama dan baby boomer adalah generasi terbanyak kedua, bukan berarti kita harus memfokuskan product yang paling diminati oleh Gen X dan baby boomer. Kita tetap harus mempertimbangkan bagaimana caranya supermarket ini bisa tetap survive ke depannya. Oleh karena itu, sebaiknya supermarket memfokuskan product yang paling diminati oleh generasi millenial agar total customer millenial supermarket bisa meningkat. Bahkan jika perlu, supermarket juga sudah bisa merancang dan mempersiapkan product untuk generasi Gen Z berikutnya.

## Recommendation
### Strategi untuk meningkatkan penjualan produk yang telah ada.
**Fish**

* Jika ingin meningkatkan penjualan produk fish, supermarket dapat menargetkan event-event tertentu yang ada di texas. Ada beberapa event atau festival yang mengadopsi tema laut seperti [Texas Seafood Festival](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.texasrealfood.com%2Fevents%2Fthe-port-isabel-shrimp-cook-off-seafood-festival-2022%2F&psig=AOvVaw0duo3g2UxqwJjQZF_0rLM2&ust=1684093159160000&source=images&cd=vfe&ved=0CBEQjRxqFwoTCKikvoWG8_4CFQAAAAAdAAAAABAE) dan beberapa festival lainnya.

**Sweet**
* Adapun untuk produk sweet, ini dapat dilakukan bundling dengan produk wine yang merupakan produk yang paling diminati. Hal ini karena produk wine dan makanan manis adalah salah satu menu yang sering disajikan saat acara-acara formal seperti pernikahan, acara bisnis, dan acara-acara formal lainnya. Dengan begitu, penjualan sweet juga bisa lebih meningkat.

**Fruit**
* Sementara untuk produk fruit, kita bisa bundling dengan produk meat. Hal ini karena kedua produk tersebut memiliki kesinambungan dalam hal gizi. Daging dapat memberikan protein yang dibutuhkan tubuh sementara buah dapat memenuhi asupan vitamin dan mineral dalam tubuh.

### Strategi pengadaan produk untuk menarik lebih banyak customer.

* Karena mayoritas customer supermarket adalah mereka yang telah menikah, maka ada beberapa saran produk yang berpeluang untuk bisa menarik customer sekaligus meningkatkan profit. Produk tersebut adalah produk peralatan rumah tangga dan kesehatan. Hal ini karena orang yang telah menikah akan cenderung membutuhkan peralatan rumah tangga. Selain itu, baik bagi mereka yang masih single maupun bagi mereka yang telah merried dan memiliki anak atau bahkan secara umum akan selalu membutuhkan produk kesehatan.
*  Beberapa produk yang umumnya diminati oleh generasi millenial adalah produk teknologi seperti smartphone, laptop, maupun aksesorisnya serta beberapa product teknologi lainnya. Hal ini karena generasi millenial adalah generasi yang tidak dapat lepas dari yang namanya teknologi. Tanpa menggunakan teknologi, generasi ini akan terhambat dalam menjalankan aktivitasnya dan akan sulit untuk berkembang. Sehingga jenis produk teknologi adalah pilihan yang tepat jika ingin menarik customer millenial.
---
Untuk overview melalui tableau bisa dilihat di [sini](https://public.tableau.com/app/profile/harry.maulana/viz/Capstone2Supermarketproductanalysis/SupermarketProductAnalysis).
