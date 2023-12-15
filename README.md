Dataset: RPS

ROCK
PAPER
SCISSORS
Model di train menggunakan Transfer Learning EfficientNetV2B0 dilakukan dengan 10 epochs serta penerapan data augmentation.

EfficientNetV2B0: EfficientNetV2 adalah serangkaian arsitektur jaringan saraf yang dikembangkan oleh Google yang diperkenalkan sebagai evolusi dari EfficientNet. Versi EfficientNetV2B0 adalah model yang lebih kecil dari serangkaian tersebut. Model ini menggunakan teknik optimasi yang inovatif untuk mencapai tingkat kinerja yang baik dengan jumlah parameter yang lebih sedikit dibandingkan dengan arsitektur lainnya.

Pada modul ini, model dilatih menggunakan pendekatan Transfer Learning dengan memanfaatkan arsitektur . EffNetmod5 adalah serangkaian arsitektur jaringan saraf yang dikembangkan oleh Google, yang merupakan evolusi dari model sebelumnya, yaitu EfficientNet.

Proses pelatihan model dilakukan dengan 10 epochs, dan penerapan teknik data augmentation juga diterapkan. Data augmentation merupakan teknik yang digunakan untuk menghasilkan variasi dalam dataset pelatihan dengan melakukan transformasi seperti rotasi, pergeseran, dan pembalikan gambar. Hal ini membantu model untuk lebih general dalam mengenali gestur tangan pada berbagai variasi posisi dan sudut.

Plot hasil pelatihan dan validasi model dapat memberikan informasi visual tentang performa model selama proses pelatihan. Grafik accuracy (akurasi) dan loss (kerugian) pada set pelatihan dan validasi dapat membantu untuk memahami sejauh mana model telah belajar dan seberapa baik kinerjanya terhadap dataset yang digunakan.

hasil akurasi yang didapatkan pada dataset ini : 100%
