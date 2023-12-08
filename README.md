# Analyst-Sentiment-Lazada
Lazada Group adalah platform e-Commerce terkemuka di Asia Tenggara. Didirikan pada tahun 2012, Lazada hadir di enam negara, yaitu Indonesia, Malaysia, Filipina, Singapura, 
Thailand, dan Vietnam. Platform ini memiliki jumlah pengunjung hampir 28,58 juta per bulan.

## Latar Belakang
Untuk membantu penjual di aplikasi Lazada mengetahui apakah review dari pembeli terhadap produk mereka adalah positif, negatif, atau netral, mereka dapat menggunakan 
sebuah program analisis sentimen. Program ini akan menganalisis teks review dari pembeli dan memberikan penilaian mengenai sentimen yang terkandung dalam teks tersebut.

Program analisis sentimen dapat menggunakan berbagai metode seperti analisis teks, pemrosesan bahasa alami, atau pendekatan berbasis mesin pembelajaran. 
Dengan menggunakan program ini, penjual dapat dengan cepat mengevaluasi umpan balik pembeli dan mengambil tindakan yang sesuai.

Program ini akan memindai teks review dari pembeli dan mengidentifikasi kata-kata atau frasa yang menunjukkan sentimen positif, negatif, atau netral. 
Misalnya, kata-kata seperti "bagus", "puas", atau "sangat baik" dapat menunjukkan sentimen positif, sedangkan kata-kata seperti "buruk", "tidak memuaskan", atau "kecewa" 
dapat menunjukkan sentimen negatif. Selain itu, program ini juga dapat mengidentifikasi kalimat atau konteks yang menunjukkan sentimen tertentu.

Dengan menggunakan program analisis sentimen ini, penjual di Lazada dapat dengan mudah memantau dan mengevaluasi umpan balik pembeli mereka. Hal ini dapat membantu mereka 
dalam mengambil tindakan yang diperlukan untuk meningkatkan kualitas produk, layanan, atau pengalaman pelanggan secara keseluruhan.

## Tujuan Bisnis
1. Mengetahui produk mana yang mempunyai rating paling tinggi
2. Menampilkan kata-kata yang paling sering digunakan dalam review setiap produk
3. Mendapatkan model machine learning untuk memprediksi sentiment review dari customer

## Hasil


Dari diagram tersebut, terlihat bahwa harddisk eksternal memiliki rating tertinggi dibandingkan dengan produk lainnya. Ini menunjukkan bahwa pelanggan yang membeli 
harddisk eksternal merasa puas dengan pelayanan yang diberikan oleh penjual.



Tanggapan dari customer mengenai produk juga sudah baik, ini terlihat dari kata kata yang sering dijumpai didalam ulasan. Semakin besar kata kata yang divisualisasikan, 
maka kata kata tersebut semakin sering muncul pada di review customer



Dalam kasus ini, kita dapat melihat bahwa model memiliki nilai akurasi rata-rata sebesar 0.8976, presisi rata-rata sebesar 0.8825, recall rata-rata sebesar 0.7264, 
dan F1-score rata-rata sebesar 0.7264. Jika kita hanya melihat angka-angka ini secara terisolasi, kita mungkin cenderung mengatakan bahwa model tersebut sudah baik.



Namun, persebaran label data tidak seimbang. Jumlah sampel untuk kelas 2 (15888) jauh lebih tinggi daripada jumlah sampel untuk kelas 0 (3570) dan kelas 1 (1620). 
Hal ini dapat menyebabkan model cenderung lebih baik dalam memprediksi kelas mayoritas (kelas 2) daripada kelas minoritas (kelas 0 dan 1).

Dalam kasus ketidakseimbangan kelas seperti ini, mengandalkan akurasi saja mungkin tidak memberikan gambaran yang akurat tentang kinerja model. Lebih penting untuk 
memperhatikan metrik evaluasi seperti presisi, recall, dan F1-score untuk setiap kelas secara terpisah.

Dalam kasus ini, presisi rata-rata dan recall rata-rata untuk kelas minoritas (kelas 0 dan 1) adalah 0.8825 dan 0.7264. Hal ini menunjukkan bahwa model memiliki 
kemampuan yang baik untuk mengidentifikasi dan memprediksi dengan benar sampel dari kelas minoritas. Namun, jika penekanan khusus diberikan pada kelas minoritas, 
mungkin perlu dilakukan penyesuaian lebih lanjut untuk meningkatkan performa pada kelas tersebut.

Oleh karena itu, meskipun model ini memiliki kinerja yang baik secara umum, dalam konteks ketidakseimbangan kelas, masih ada ruang untuk meningkatkan kinerja model, 
terutama dalam hal recall dan F1-score untuk kelas minoritas.
