Modul 6 
praktikum yang berfokus pada pengembangan model untuk mengenali gestur tangan dalam permainan batu, kertas, gunting (Rock-Paper-Scissors atau RPS). Dataset yang digunakan terdiri dari gambar-gambar representatif dari ketiga gestur tersebut, yaitu ROCK, PAPER, dan SCISSORS.

Pada modul ini, model dilatih menggunakan pendekatan Transfer Learning dengan memanfaatkan arsitektur . EffNetmod5 adalah serangkaian arsitektur jaringan saraf yang dikembangkan oleh Google, yang merupakan evolusi dari model sebelumnya, yaitu EfficientNet.

Proses pelatihan model dilakukan dengan 10 epochs, dan penerapan teknik data augmentation juga diterapkan. Data augmentation merupakan teknik yang digunakan untuk menghasilkan variasi dalam dataset pelatihan dengan melakukan transformasi seperti rotasi, pergeseran, dan pembalikan gambar. Hal ini membantu model untuk lebih general dalam mengenali gestur tangan pada berbagai variasi posisi dan sudut.

Plot hasil pelatihan dan validasi model dapat memberikan informasi visual tentang performa model selama proses pelatihan. Grafik accuracy (akurasi) dan loss (kerugian) pada set pelatihan dan validasi dapat membantu untuk memahami sejauh mana model telah belajar dan seberapa baik kinerjanya terhadap dataset yang digunakan.

hasil akurasi yang didapatkan pada dataset ini : 100%
