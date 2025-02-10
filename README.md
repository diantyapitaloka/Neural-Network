# Neural-Network

Pada zaman komputasi modern ini, neural network telah menjadi salah satu komponen inti dari kecerdasan buatan. Konsep ini terinspirasi dari jaringan saraf biologis manusia dan dapat mengubah cara komputer belajar dalam berbagai tugas kompleks. 

Dengan kemampuannya untuk memproses informasi melalui jutaan koneksi neuron buatan, neural network mampu mengenali pola dalam data, membuat prediksi, dan bahkan belajar dari pengalaman seperti manusia. Hal ini membuka pintu bagi kemajuan besar dalam bidang pengenalan gambar, pengolahan bahasa alami, robotika, dan banyak lagi.

Melalui penggunaan neural network, kita dapat melihat aplikasi praktisnya dalam kehidupan sehari-hari, mulai dari sistem rekomendasi pada platform streaming hingga kendaraan otonom yang dapat mengenali lingkungan sekitarnya. 

Taksonomi AI
First thing first, sebelum belajar terkait neural network dan deep learning, ada baiknya kita mengetahui posisi dalam kelas ini agar lebih memberikan gambaran yang komprehensif. Urutan itu disebut taksonomi AI, yang menggambarkan evolusi konsep dan teknologi dalam bidang kecerdasan buatan, mulai dari artificial intelligence hingga deep learning (DL).
<img width="457" alt="image" src="https://github.com/user-attachments/assets/f70a1f7f-bb0c-4714-bb93-4c8ca6a3e0f2" />

Berikut adalah urutan taksonomi AI secara lebih rinci.

Artificial Intelligence (AI)
Artificial intelligence adalah konsep yang mendasari seluruh bidang kecerdasan buatan. Pada tingkat paling dasar, AI mencakup penggunaan komputer atau mesin untuk melakukan tugas yang membutuhkan kecerdasan manusia, seperti pengambilan keputusan, pengenalan pola, dan pemecahan masalah.
Machine Learning (ML)
Machine learning adalah cabang dari AI, ketika komputer dapat belajar dari data tanpa perlu diprogram secara eksplisit. Teknik-teknik ML memungkinkan komputer untuk mengenali pola dalam data, membuat prediksi, dan mengambil keputusan berdasarkan informasi yang dipelajari dari pengalaman atau data latihan.
Neural Network (NN)
Neural network adalah model matematis yang terinspirasi dari struktur jaringan saraf manusia. Dalam konteks ML, NN digunakan untuk memproses informasi dan belajar dari data. Model ini terdiri atas neuron-neuron buatan yang saling terhubung dalam lapisan-lapisan dan mampu mempelajari representasi yang semakin abstrak dari data.
Deep Learning (DL)
Deep learning adalah sub-bidang dari ML yang menggunakan NN dengan banyak lapisan atau deep neural network (DNN) untuk memahami representasi data yang abstrak dan kompleks. DL telah menghasilkan kemajuan besar dalam bidang pengenalan gambar, pemrosesan bahasa alami, dan berbagai aplikasi AI lainnya.
Gen AI
Generative AI adalah cabang dari AI yang berfokus pada penciptaan konten baru dan original. Berbeda dengan AI tradisional yang biasanya beroperasi berdasarkan aturan yang telah ditetapkan dan data yang ada, generative AI memiliki kemampuan untuk menghasilkan teks, gambar, musik, video, dan bentuk konten lainnya yang belum pernah ada sebelumnya.
Nah, setelah Anda mempelajari konsep dasar AI dan machine learning dalam kelas Belajar Dasar AI serta Belajar Machine Learning untuk Pemula, kini saatnya untuk melanjutkan pembelajaran kita pada bagian NN dan DL dengan lebih mendalam.

Dengan memahami NN dan DL, Anda akan mendapatkan pemahaman lebih komprehensif tentang teknologi yang mendasari banyak aplikasi canggih dalam kecerdasan buatan. Mari kita jelajahi bersama-sama di kelas ini untuk memperluas pengetahuan dan keterampilan kita dalam menghadapi tantangan baru pada bidang AI! 

Makan seblak jangan lupa pakai kencur, meluncurrr~

Konsep Dasar Neural Network
Neural network (NN) atau jaringan saraf tiruan adalah model matematis yang terinspirasi dari struktur jaringan saraf manusia. NN dirancang untuk meniru cara otak manusia bekerja dengan menggunakan unit-unit pemrosesan sederhana yang disebut neuron. Jaringan saraf tiruan terdiri dari beberapa lapisan neuron yang saling terhubung. Informasi yang dibawa akan mengalir melalui jaringan ini untuk melakukan tugas-tugas tertentu, seperti pengenalan pola, klasifikasi, atau prediksi berdasarkan data yang diberikan.

Saraf Biologis vs Saraf Tiruan
Kata pepatah, “tak kenal maka tak sayang”, jadi mari kenalan dulu, apa sih saraf tiruan ini?

Sebelum kita belajar mengenai saraf tiruan, kita akan mengenal lebih dahulu saraf biologis (neuron). National Institute of Neurological Disorders and Stroke dalam tulisannya yang berjudul “Brain Basics: The Life and Death of a Neuron” menyatakan bahwa neuron atau saraf adalah pembawa pesan atau informasi. Mereka menggunakan impuls listrik dan sinyal kimiawi untuk mengirimkan informasi di antara area otak yang berbeda, serta antara otak dan seluruh sistem saraf.

Sebuah saraf terdiri dari tiga bagian utama, yaitu akson, dendrit, dan badan sel yang di dalamnya terdapat nukleus. Nukleus berisi materi genetik dan bertugas mengontrol seluruh aktivitas sel. Akson adalah cabang yang terlihat seperti ekor panjang dan bertugas mengirimkan pesan dari sel. Panjang akson berkisar antara beberapa kali lebih panjang dari badan sel, sampai 10 ribu kali. Berikutnya, dendrit adalah cabang-cabang pendek yang terlihat seperti cabang pohon dan bertugas menerima pesan untuk sel. 

Setiap ujung akson dari sebuah neuron terhubung dengan dendrit dari neuron lainnya. Neuron berkomunikasi satu sama lain dengan mengirimkan senyawa kimia yang disebut neurotransmitter, melintasi ruang kecil (synapse) antara akson dan dendrit neuron yang berdekatan. 

Ketika sebuah neuron mendapatkan rangsangan, ia akan mengirim sinyal ke neuron lainnya. Contohnya, ketika tidak sengaja menyentuh panci yang panas, saraf di tangan kita mengirim sinyal ke saraf lain sampai ke otak, lalu merespons dengan cepat. Pengiriman sinyal antar neuron terjadi sangat cepat, yaitu hanya dalam beberapa milidetik.

dos-a1d0444556fd76dda8f91477fb14991c20240620155214.png

Tahukah Anda? Konsep kerja dan struktur NN ternyata terinspirasi dari saraf biologis kita, lo!  Pada NN, ada unit-unit pemrosesan disebut neuron buatan dan saling terhubung dalam struktur yang mirip dengan jaringan saraf biologis. Setiap neuron buatan menerima sejumlah input, menghitung hasil berdasarkan bobot yang ditetapkan, dan mengirimkan output ke neuron-neuron lainnya.  

Pengaturan bobot ini adalah kunci dalam NN. Selama proses pelatihan, NN belajar untuk mengubah bobot-bobot ini berdasarkan data latihan yang diberikan. Jadi, NN mampu mengenali pola-pola kompleks dan membuat prediksi atau keputusan berdasarkan informasi yang diterima. 

Meskipun tidak sekompleks saraf biologis manusia, konsep NN memberikan dasar kuat untuk pengembangan kecerdasan buatan dan aplikasi-aplikasi yang inovatif dalam berbagai bidang. Artificial neural network (ANN) merupakan implementasi konkret dari konsep NN dalam konteks kecerdasan buatan. Bagaimana cara kerja ANN ini? Kita akan bahas pada bagian selanjutnya!

Struktur Artificial Neural Network
Neural network yang paling sederhana atau minimal terdiri dari satu unit perceptron tunggal, juga dikenal sebagai single perceptron. Perceptron ini memproses input dengan mengalikan nilai input (x) dengan bobot (w), kemudian menjumlahkannya dengan bias (b). Hasil dari operasi ini disebut net input (z) dan kemudian akan diproses melalui fungsi aktivasi (f) untuk menghasilkan output (y) dari perceptron tersebut. 

dos-4d3be3bf3c7715479db3c29dcecfbd6d20240620155232.png

Secara matematis, single perceptron dapat ditulis sebagai berikut.

dos-4b6c07dbec4230312b2beba99d8abcbb20240628162604.jpeg

 Keterangan:

x  : x1, x2, …, xn; xi adalah nilai input ke-i.
w : w1, w2, …, wn; wi adalah bobot terkait dengan input xi.
b : nilai bias (konstanta tambahan) yang dimiliki oleh perceptron.
z : fungsi linear.
f : fungsi aktivasi untuk menghasilkan output y.
y : output.
Jadi, secara matematis, single perceptron dapat dijelaskan sebagai sebuah fungsi matematis yang mengambil input, mengalikannya dengan bobot, menambahkan bias, dan kemudian menerapkan fungsi aktivasi pada hasilnya untuk menghasilkan output. Prosedur ini adalah dasar dari komputasi dalam NN yang lebih kompleks.

Cara Kerja Artificial Neural Network
Cara kerja artificial neural network (ANN) mengambil inspirasi dari struktur jaringan saraf manusia. Pada sebuah ANN, ada jutaan atau bahkan miliaran "neuron" buatan yang terorganisir dalam lapisan-lapisan. Setiap neuron menerima input dari neuron-neuron dalam lapisan sebelumnya, melakukan operasi matematika pada input ini, dan menghasilkan output yang akan diteruskan ke neuron-neuron dalam lapisan berikutnya.

Mirip dengan kerja jaringan saraf manusia, setiap koneksi antar neuron dalam ANN memiliki bobot atau nilai yang memengaruhi pentingnya informasi dari neuron sebelumnya. Selama proses pembelajaran, bobot-bobot ini diatur ulang agar ANN dapat belajar memahami pola-pola yang ada dalam data.

dos-3f62a1109580b20a85ce8afd06e5033820240620155249.png

Saat ANN diberikan masukan (misalnya gambar, teks, atau data numerik), sinyal-sinyal ini bergerak melalui jaringan neuron, diolah, dan menghasilkan keluaran. Proses ini memungkinkan ANN untuk mengenali pola-pola kompleks pada data, seperti pengenalan wajah dalam gambar, klasifikasi teks, atau prediksi harga saham berdasarkan data historis.

Secara konseptual, ANN dapat diibaratkan sebagai "sarang semut" yang sangat besar dan kompleks, tempat setiap "semut" (neuron) bekerja sama untuk menyelesaikan tugas yang rumit. Dengan kekuatan komputasi luar biasa, ANN mampu memecahkan masalah sulit dan melakukan tugas-tugas cerdas yang mendukung berbagai aplikasi teknologi modern.

Perceptron
Perceptron adalah komponen dasar pembangun jaringan saraf tiruan. Frank Rosenblatt dari Cornell Aeronautical Library adalah ilmuwan yang pertama kali menemukan perceptron pada tahun 1957. Perceptron terinspirasi dari neuron pada jaringan saraf dalam otak manusia. Dalam jaringan saraf tiruan, perceptron dan neuron merujuk pada hal yang sama. 

Lantas, bagaimana perceptron bekerja pada jaringan saraf tiruan? 

Sebuah perceptron menerima masukan berupa bilangan numerik. Perceptron kemudian memproses masukan tersebut untuk menghasilkan sebuah keluaran. Agar lebih memahami cara kerja perceptron, kita akan menggunakan diagram di bawah.

dos-30f2e1458ba12e969d7cc0b86b85ec1620240620155313.png

 Sebuah perceptron terdiri dari 5 komponen, yaitu

input (xi),
bobot atau weights (wi) dan bias (w0),
penjumlahan atau sum (∑),
fungsi aktivasi atau non linearity function (⎰), dan
output (y).
Sebuah perceptron tunggal saat berdiri sendiri mungkin tidak memberikan hasil yang signifikan dalam konteks pemrosesan data kompleks. Namun, ketika perceptron ini dihubungkan dengan ratusan atau ribuan perceptron lain dalam sebuah jaringan yang lebih besar, kemampuannya untuk memproses informasi dan memberikan hasil akan jauh lebih kuat. 

Banyak perceptron yang saling terhubung dalam neural network. Setiap perceptron melakukan komputasi terhadap inputnya sendiri dengan bobot dan bias yang spesifik. Kemudian, informasi hasil komputasi dari satu perceptron akan mengalir ke perceptron-perceptron lainnya melalui koneksi yang terbentuk di antara mereka. Proses ini memungkinkan jaringan untuk mempelajari pola kompleks dalam data dan membuat prediksi atau keputusan yang akurat.

Dengan koneksi yang kuat antar-perceptron serta kemampuan untuk menyesuaikan bobot dan bias selama proses pelatihan, neural network dapat mengungguli banyak metode machine learning lainnya dalam hal keakuratan, begitu pun kemampuan adaptasi terhadap masalah yang rumit. 

Seiring dengan meningkatnya ukuran dan kompleksitas jaringan, performa neural network dapat semakin ditingkatkan. Ini menjadikannya alat yang sangat efektif dalam berbagai aplikasi, termasuk pengenalan pola, klasifikasi, prediksi, dan banyak lagi.

Berikut adalah proses yang menjelaskan bagaimana perceptron bekerja.




Pertama, input menerima masukan berupa angka-angka. Setiap input memiliki bobot masing-masing. Bobot adalah parameter yang akan dipelajari oleh sebuah perceptron dan menunjukkan kekuatan node tertentu. 

Selanjutnya adalah tahap penjumlahan input. Pada tahap ini, setiap input akan dikalikan dengan bobotnya masing-masing, lalu hasilnya ditambahkan dengan bias yang berupa sebuah konstanta atau angka. Nilai bias memungkinkan Anda untuk mengubah kurva fungsi aktivasi ke atas atau bawah sehingga bisa lebih fleksibel dalam meminimalkan error. Hasil penjumlahan pada tahap ini biasanya disebut weighted sum.

Langkah berikutnya, aplikasikan weighted sum pada fungsi aktivasi atau disebut juga non-linearity function. Fungsi aktivasi digunakan untuk memetakan nilai hasil menjadi nilai yang diperlukan, misalnya antara (0, 1) atau (-1, 1). Fungsi ini memungkinkan perceptron dapat menyesuaikan pola untuk data yang non-linier. Penjelasan lebih lanjut tentang fungsi aktivasi akan diulas pada paragraf di bawah.

Setelah semua langkah di atas, akhirnya kita memperoleh output, yaitu hasil perhitungan sebuah perceptron yang berupa bilangan numerik.

dos-ff3fc91f889bdd30ca1f53a8aeb1ea3020240620155429.png

Fungsi matematis dari perceptron dapat kita lihat di atas. Rumus tersebut adalah notasi matematis yang menjelaskan proses sebelumnya. Keluaran (ŷ) dari perceptron adalah bias (w0) ditambah dengan jumlah setiap input (xi) yang dikali dengan bobot masing-masing (wi) sehingga menghasilkan weighted sum, kemudian dimasukkan dalam fungsi aktivasi (g). 

Multilayer Perceptron (MLP)
dos-c7062e7bdd637d3a31c9b419171cc17820240620155452.png

Multilayer perceptron (MLP) atau feedforward neural network adalah jenis neural network yang terdiri dari banyak perceptron (neuron) yang saling terhubung dalam beberapa lapisan. MLP memiliki struktur yang terdiri dari tiga jenis layer utama.

Input Layer
Layer pertama dari MLP adalah input layer. Ini berfungsi untuk menerima data atau input dari luar. Setiap neuron dalam input layer mewakili satu fitur atau variabel dari data yang masuk ke jaringan. Misalnya, dalam aplikasi pengenalan gambar, setiap neuron dapat mewakili nilai intensitas piksel dari gambar.
Hidden Layer
Setelah menerima input, data akan diteruskan ke hidden layer (lapisan tersembunyi) dalam MLP. Hidden layer terdiri dari satu atau lebih lapisan antara input layer dan output layer. Neuron-neuron dalam hidden layer memproses input yang diterima dari layer sebelumnya dengan melakukan operasi matematika menggunakan bobot (weights) dan fungsi aktivasi tertentu. Hidden layer berfungsi sebagai penyaring atau extractor fitur yang membantu jaringan dalam mempelajari pola-pola kompleks pada data.
Output Layer
Output layer adalah layer terakhir dalam MLP yang menghasilkan output berdasarkan hasil pemrosesan oleh hidden layer. Jumlah neuron dalam output layer bergantung pada tipe tugas yang ingin diselesaikan oleh jaringan. Misalnya, untuk tugas klasifikasi biner, output layer dapat memiliki satu neuron yang menghasilkan nilai antara 0 dan 1 (mengindikasikan probabilitas kelas), sedangkan untuk klasifikasi multiclass, setiap neuron mungkin mewakili probabilitas dalam kelas tertentu.
Terms pada Neural Network
Selanjutnya, mari kita mulai dengan membahas beberapa istilah umum yang penting dalam pengembangan kecerdasan buatan menggunakan neural network. Istilah-istilah ini adalah activation function, loss function, dan optimizer.

Activation Function (Fungsi Aktivasi)
Fungsi aktivasi adalah sebuah fungsi matematika yang menentukan bahwa neuron dalam jaringan saraf tiruan akan menghasilkan output atau tidak berdasarkan inputnya. Analoginya, fungsi ini meniru cara neuron biologis "aktif" atau "tidak aktif" berdasarkan sinyal masukan yang diterima.

Fungsi aktivasi pada perceptron bertugas untuk membuat jaringan saraf mampu menyesuaikan pola dengan data non linier. Sebagaimana yang sudah pernah dibahas sebelumnya, mayoritas data di dunia nyata adalah data non linier seperti di bawah.
dos-019a5f58112c4fab7f50bcdccd74ef9220240620155508.pngFungsi aktivasilah yang memungkinkan jaringan saraf dapat mengenali pola non-linier seperti di bawah. Tanpa fungsi aktivasi, jaringan saraf hanya bisa mengenali pola linier layaknya garis pada regresi linier.
dos-8a00f5df55ed02844c365762101dd2a420240620155528.pngSecara umum, ada dua jenis activation function, linear, dan non-linear activation function. Ada beberapa jenis fungsi aktivasi yang umum digunakan dalam jaringan saraf sebagai berikut.
Linear
dos-ea8d5e7e924c7fb9df21eb18a9cd04fb20240620155543.pngLinear activation function (fungsi aktivasi linear) dalam konteks jaringan saraf tiruan adalah sebuah fungsi dengan keluaran yang proporsional secara linear terhadap input. Dengan kata lain, fungsi ini hanya melakukan transformasi linear sederhana dari input ke output tanpa memperkenalkan non-linearitas.

Pada rumus linear, x adalah input ke neuron atau lapisan jaringan. Dalam hal ini, keluaran dari neuron atau lapisan tersebut sama dengan inputnya sendiri. Oleh karena itu, tidak ada transformasi non-linear yang terjadi.

Sebagai tambahan informasi, fungsi aktivasi linear jarang digunakan dalam lapisan tersembunyi (hidden layers) karena tidak mampu memodelkan hubungan yang kompleks antara variabel input dan output. Namun, fungsi ini dapat digunakan pada lapisan output untuk masalah regresi.

ReLU (Rectified Linear Activation)
dos-b49875730ccd46d04fd8d25d80da6a7620240620155605.pngReLU (rectified linear activation) adalah jenis fungsi aktivasi yang umum digunakan dalam jaringan saraf tiruan. Fungsi ReLU didefinisikan sebagai f(x) = max(0, x). Ini berarti output dari ReLU adalah nilai inputnya jika nilai input tersebut lebih besar dari atau sama dengan nol, dan output-nya adalah nol jika nilai inputnya kurang dari nol.

Keuntungan utama dari ReLU adalah sederhana pada komputasi dan memperkenalkan non-linearitas ke dalam jaringan. ReLU umumnya digunakan sebagai fungsi aktivasi pada lapisan tersembunyi karena kemampuannya untuk mempercepat konvergensi pembelajaran dan mengurangi risiko overfitting.

ReLU adalah pilihan populer dan efektif untuk fungsi aktivasi dalam jaringan saraf modern karena sederhana, efisien, serta mampu membantu jaringan mempelajari representasi yang kompleks dari data dengan baik.

Leaky ReLU
Kekurangan pada ReLU adalah beberapa gradien dapat menjadi sangat rapuh selama proses pelatihan, yang dapat menyebabkan fenomena "neuron mati". Ini berarti bahwa selama pelatihan, beberapa neuron dapat terkunci dalam keadaan mereka tidak akan pernah diaktifkan lagi pada sebagian besar atau semua data yang diberikan. Hal itu terjadi karena gradien (turunan) dari fungsi ReLU menjadi nol pada bagian negatifnya.
dos-c0fac8dab286681b64dc0e61d2b655be20240620155628.pngUntuk mengatasi masalah ini, modifikasi lain dari fungsi ReLU diperkenalkan, dikenal sebagai leaky ReLU. Ia memperkenalkan kemiringan kecil (biasanya nilai tetap yang sangat kecil, seperti 0.01) pada bagian negatif dari fungsi ReLU.

Hal ini membantu menjaga agar neuron tetap aktif selama pelatihan, bahkan jika gradien pada bagian negatifnya mendekati nol. Dengan demikian, leaky ReLU dapat mencegah "kematian" neuron dan membantu meningkatkan stabilitas serta kecepatan konvergensi dalam pelatihan jaringan saraf.

Sigmoid
Sigmoid akan menerima angka tunggal dan mengubah x menjadi sebuah nilai yang memiliki rentang mulai dari 0 sampai 1. Fungsi ini biasanya dapat diinterpretasikan sebagai probabilitas dalam konteks klasifikasi biner.

Keuntungan utama dari sigmoid adalah kemampuannya dalam menghasilkan keluaran dengan batas antara 0 dan 1, yang berguna untuk tugas klasifikasi ketika kita ingin memprediksi probabilitas keanggotaan pada kelas tertentu.
dos-b5c63e85ef6660072a92a490557abf1220240620155646.pngNamun, ada beberapa perhatian terkait penggunaan sigmoid.
Gradien yang Menghilang
Ketika nilai input sangat besar (positif atau negatif), gradien sigmoid cenderung mendekati nol, yang dapat menyebabkan masalah lambatnya konvergensi selama pelatihan jaringan.
Output yang Tidak Seimbang
Sigmoid memiliki kecenderungan untuk menghasilkan output yang condong ke nilai 0 atau 1 dengan cepat; ini dapat menghambat pembelajaran dalam beberapa kasus.

Tanh
dos-7066ed2190eb13018032fc00b847055e20240620155706.pngTanh (hyperbolic tangent) adalah jenis fungsi aktivasi lain yang umum digunakan dalam jaringan saraf tiruan. Tanh akan mengubah nilai input x-nya menjadi sebuah nilai yang memiliki rentang mulai dari -1 hingga 1.

Namun, serupa halnya dengan sigmoid, tanh juga memiliki beberapa masalah, seperti rentang output yang terbatas (-1 sampai 1). Ini juga bisa menyebabkan gradien menghilang pada jaringan. Meskipun demikian, tanh masih menjadi pilihan populer untuk fungsi aktivasi dalam beberapa kasus, terutama ketika rentang output yang simetris di sekitar nol diinginkan atau saat sigmoid tidak memberikan hasil yang memuaskan.

Beberapa karakteristik dari fungsi tanh adalah berikut.
Rentang Output
Fungsi tanh menghasilkan output antara -1 dan 1. Ini membuatnya lebih simetris di sekitar titik nol dibandingkan sigmoid yang memiliki rentang antara 0 dan 1.
Non-linearitas
Layaknya sigmoid, tanh juga memperkenalkan non-linearitas ke jaringan. Ini memungkinkan jaringan untuk mempelajari hubungan yang lebih kompleks antara input dan output.
Penggunaan di Lapisan Tersembunyi
Tanh sering digunakan sebagai alternatif sigmoid pada lapisan tersembunyi karena rentangnya simetris dan kemampuannya untuk menangani gradien yang menghilang lebih baik daripada sigmoid.

Softmax
Softmax adalah jenis fungsi aktivasi yang umum digunakan pada lapisan output dari jaringan saraf, terutama untuk tugas klasifikasi multiclass. Fungsi softmax mengubah nilai input menjadi distribusi probabilitas yang memetakan output pada rentang (0, 1) sehingga total probabilitas output menjadi 1.
dos-49443f80a2c9daff6c1e1037c3e47f3720240620155730.pngBerikut adalah beberapa karakteristik dari fungsi softmax.
Interpretasi Probabilitas
Output dari softmax dapat diinterpretasikan sebagai probabilitas bahwa input termasuk dalam setiap kelas yang mungkin karena nilai-nilainya berada pada rentang (0, 1) dan total probabilitasnya adalah 1.
Penanganan Masalah Multikelas
Softmax sangat berguna dalam tugas klasifikasi, yakni ketika ada lebih dari dua kelas yang mungkin. Ini memungkinkan model dalam menghasilkan prediksi probabilitas untuk setiap kelas.
Loss Function
Softmax sering digunakan bersama dengan cross-entropy loss function sebagai fungsi kerugian (loss function) dalam jaringan saraf untuk tugas klasifikasi multiclass. Ini karena softmax menghasilkan distribusi probabilitas dan cross-entropy dapat digunakan untuk mengukur kesalahan antara distribusi prediksi dan distribusi target.

Penggunaan softmax biasa ditemukan dalam lapisan output jaringan saraf, sedangkan pada lapisan tersembunyi, fungsi aktivasi lainnya, seperti ReLU atau tanh, lebih umum digunakan. Kombinasi softmax dengan fungsi aktivasi yang sesuai pada lapisan tersembunyi membentuk arsitektur jaringan saraf yang efektif untuk tugas klasifikasi multi kelas.

Berikut adalah beberapa fungsi aktivasi yang lainnya.
dos-04121f54319dadafd19e20a5cb1508d220240620155748.png
Loss Function
Loss function (fungsi kerugian) dalam konteks jaringan saraf adalah algoritma matematis yang digunakan untuk mengukur seberapa baik atau buruk kinerja model neural network pada data pelatihan. Fungsi kerugian memberikan representasi numerik tentang seberapa besar kesalahan atau perbedaan antara prediksi model dan nilai yang sebenarnya dalam data pelatihan.
Tujuan utama dari loss function untuk membimbing proses pelatihan jaringan saraf agar dapat meminimalkan kesalahan prediksi. Saat model melakukan prediksi pada data pelatihan, loss function menghitung seberapa jauh hasil prediksi dari nilai yang sebenarnya. Semakin kecil nilai loss function, semakin baik kinerja model.
dos-41adbb96fe8102df900b1d694430bdaa20240620155804.pngContoh loss function yang umum digunakan adalah mean square error (MSE). MSE menghitung rata-rata dari kuadrat selisih antara prediksi model dan nilai yang sebenarnya pada setiap titik data. Nilai MSE yang lebih kecil menunjukkan bahwa model memiliki kesalahan prediksi lebih rendah.

Selain MSE, ada juga berbagai jenis loss function lainnya, seperti cross entropy loss yang umum digunakan untuk masalah klasifikasi. Setiap jenis loss function memiliki karakteristik dan aplikasi berbeda tergantung pada tipe masalah yang dihadapi dalam pembelajaran mesin.
dos-52a5d09d26ec39041b713e87826f317220240620155831.pngPada dasarnya, loss function berperan penting dalam membantu model jaringan saraf untuk belajar dari data pelatihan. Dengan mengukur kesalahan prediksi secara objektif, loss function memungkinkan kita untuk menyesuaikan parameter model. Jadi, model dapat menghasilkan prediksi lebih akurat dan sesuai dengan data yang diberikan.
Optimizer
Optimizer (pengoptimal) adalah komponen kunci dalam pelatihan jaringan saraf tiruan yang bertanggung jawab untuk mengoptimalkan atau menyesuaikan bobot dan bias pada jaringan agar dapat mengurangi kesalahan prediksi. Tujuan utama dari pengoptimal adalah untuk menemukan nilai bobot dan bias dengan hasil prediksi paling akurat dan generalisasi yang baik terhadap data baru.
dos-33cac5a4f9c7b8a94f4d03db3ddf863a20240620155844.pngBeberapa fungsi utama dari optimizer dalam konteks jaringan saraf adalah berikut.
Menghitung Gradien
Optimizer menghitung gradien dari loss function terhadap parameter (weights dan biases) dalam jaringan. Gradien ini memberikan informasi tentang arah dan seberapa besar perubahan yang harus dilakukan pada parameter untuk mengurangi nilai fungsi kerugian.
Memperbarui Parameter
Berdasarkan gradien yang dihitung, optimizer akan memperbarui nilai parameter (weights dan biases) jaringan. Update ini dilakukan dengan cara menggerakkan nilai parameter ke arah yang mengurangi nilai fungsi kerugian. Cara update ini biasanya menggunakan metode gradient descent atau varian-varian lainnya, yakni momentum, RMSprop, Adam, dan lainnya.
Menangani Masalah Optimalisasi
Optimizer berusaha menangani masalah, seperti lambatnya konvergensi, kemungkinan terjebak dalam optimum lokal, ataupun masalah gradien yang meledak atau menghilang. Beberapa optimizer menggunakan berbagai teknik, seperti momentum, learning rate scheduling, atau adaptive learning rate untuk mengatasi masalah-masalah ini.
Beberapa contoh optimizer yang umum digunakan dalam pelatihan jaringan saraf seperti berikut.

Stochastic Gradient Descent (SGD): Optimizer klasik yang menggunakan gradien dari subset data (batch) untuk memperbarui parameter.
RMSprop: Optimizer yang menyesuaikan learning rate untuk setiap parameter berdasarkan perbedaan antara gradien saat ini dan sejarah gradien.
Adam: Optimizer adaptif yang menggabungkan konsep dari momentum dan RMSprop untuk mengatur learning rate secara adaptif berdasarkan estimasi momen gradien.
Pemilihan optimizer sangat penting dalam pelatihan jaringan saraf karena dapat memengaruhi kecepatan konvergensi, kualitas model yang dihasilkan, dan kemampuan jaringan untuk menghindari masalah-masalah optimisasi. Berbagai faktor, seperti jenis tugas, ukuran dataset, dan arsitektur jaringan, dapat memengaruhi pemilihan optimizer yang paling sesuai untuk suatu proyek.

Konsep Metode Forward Propagation dan Backpropagation
Forward propagation dan backpropagation adalah dua proses kunci dalam pelatihan neural network untuk menghasilkan prediksi yang akurat dan mengoptimalkan parameter (bobot) jaringan. Mari kita bahas keduanya secara lebih rinci.

dos-2d4f85074346e86325afc4458a77dd4620240620155859.png

Forward Propagation
Forward propagation adalah langkah pertama dalam proses penggunaan neural network untuk membuat prediksi berdasarkan masukan data. Mari simak penjelasan dengan cara yang lebih sederhana.
dos-5a2abdaad4a7e66c61fa3edf7385241420240620155913.png
Input Data
Langkah pertama dalam penggunaan neural network adalah memberikan data sebagai input pada jaringan. Data ini bisa berupa berbagai jenis informasi, seperti gambar (dalam bentuk piksel), teks (dalam bentuk token atau urutan kata), atau nilai numerik (seperti atribut atau fitur yang menggambarkan suatu objek atau fenomena).

Misalnya, jika kita ingin menggunakan neural network untuk klasifikasi gambar, data input dapat berupa gambar-gambar digital yang direpresentasikan dalam bentuk matriks piksel. Setiap piksel memiliki nilai intensitas yang mewakili warna pada posisi tertentu dalam gambar. Gambar-gambar ini kemudian dijadikan input pada neural network untuk memungkinkan model mempelajari pola dan fitur yang terkandung dalam gambar.

Contoh lainnya, jika kita ingin melakukan analisis sentimen terhadap teks, data input bisa berupa urutan kata atau kalimat. Setiap kata dalam teks direpresentasikan dengan token atau angka yang menunjukkan kata tersebut. Data tersebut kemudian diproses dan dimasukkan ke neural network untuk memprediksi sentimen atau makna dari teks tersebut.

Selain itu, data numerik, seperti atribut dari suatu objek, juga dapat digunakan sebagai input. Misalnya, jika kita ingin memprediksi harga rumah berdasarkan fitur-fitur, seperti luas tanah, jumlah kamar, lokasi, dan sebagainya, atribut-atribut ini dapat dimasukkan sebagai input pada neural network.

Dengan pemberian data sebagai input, neural network dapat memproses informasi ini melalui serangkaian langkah komputasi yang kompleks. Itu bertujuan untuk mempelajari pola, menerapkan transformasi, dan menghasilkan output yang berguna atau prediksi sesuai dengan keinginan berdasarkan tugas atau tujuan.

Neuron dan Bobot
Setelah data dimasukkan dalam neural network, data tersebut melewati serangkaian neuron pada berbagai lapisan jaringan tersebut. Setiap neuron dalam jaringan menerima input data dari neuron-neuron pada lapisan sebelumnya atau data asli, seperti gambar atau teks.

Setiap neuron memiliki parameter "bobot" (weights) yang digunakan untuk mengalikan input tersebut. Bobot ini mewakili kekuatan atau pentingnya setiap input terhadap aktivasi neuron. Misalnya, jika kita memiliki neuron pada lapisan pertama yang menerima gambar sebagai input, setiap piksel dalam gambar akan dikalikan dengan bobot yang sesuai. Bobot ini adalah angka-angka yang dipelajari oleh model selama proses pelatihan untuk mengoptimalkan kinerja jaringan.

Selain bobot, setiap neuron juga memiliki bias sebagai nilai tambahan yang ditambahkan ke hasil perkalian input dengan bobot. Bias membantu neuron untuk belajar membedakan pola yang kompleks dalam data. Misalnya, jika semua input bernilai nol, bias dapat memungkinkan neuron untuk tetap aktif dan belajar dari situasi-situasi yang tidak biasa.

Proses perkalian input dengan bobot dan penambahan bias pada setiap neuron menghasilkan nilai yang diteruskan ke fungsi aktivasi. Fungsi aktivasi bertujuan untuk memutuskan bahwa neuron tersebut harus "aktif" atau "tidak aktif" berdasarkan hasil perhitungan tersebut. Fungsi aktivasi yang umum digunakan adalah ReLU untuk lapisan tersembunyi dan softmax dalam lapisan output pada masalah klasifikasi.

Selanjutnya, hasil aktivasi dari setiap neuron akan menjadi input bagi neuron-neuron pada lapisan berikutnya dalam jaringan. Proses ini berulang terus menerus melalui seluruh jaringan dan setiap lapisan akan menghasilkan representasi yang semakin abstrak dari data asli. Hasil akhir dari neural network adalah prediksi atau output berdasarkan input data yang dipelajari oleh model selama proses pelatihan.

Perhitungan di Neuron
Pada sebuah neural network, setiap neuron memiliki peran penting dalam menghitung output berdasarkan input yang diterimanya. Proses perhitungan dalam neuron dimulai dengan menerima input, yang bisa berasal dari neuron-neuron pada lapisan sebelumnya atau data asli, seperti gambar, teks, atau nilai numerik. Tiap input ini kemudian dikalikan dengan bobot yang telah dipelajari oleh jaringan selama proses pelatihan. Bobot ini menentukan seberapa penting setiap input terhadap aktivasi neuron.

Selain itu, neuron memiliki bias yang ditambahkan ke hasil perkalian input dan bobot sebelum memasuki fungsi aktivasi. Bias ini membantu neuron mempelajari pola-pola yang kompleks dalam data. Setelah itu, hasil perkalian input dan bobot dengan bias dimasukkan ke fungsi aktivasi. Fungsi aktivasi, seperti ReLU atau sigmoid, bertujuan untuk menentukan output neuron berdasarkan ambang batas tertentu.

Output ini kemudian menjadi input bagi neuron-neuron pada lapisan berikutnya dalam jaringan. Proses ini terjadi secara berulang melalui seluruh jaringan, yakni setiap neuron belajar mengoptimalkan bobot dan biasnya untuk menghasilkan representasi yang semakin abstrak dari data.

Hasil akhir dari neural network adalah prediksi atau output sesuai dengan keinginan, yang digunakan untuk menyelesaikan tugas spesifik, seperti klasifikasi, regresi, atau pengenalan pola.
Backpropagation
Backpropagation adalah langkah kedua dalam proses penggunaan neural network untuk menghitung nilai error dari output hasil prediksi. Mari kita bahas secara lebih sederhana.
dos-f294c96dde3167734e1d0fbc6dd7063120240620155930.png
Perhitungan Error
Setelah mendapatkan output dari neural network, kita bandingkan output tersebut dengan nilai target yang sebenarnya (ground truth) dari data latih. Perhitungan error dilakukan dengan menggunakan loss function, seperti mean squared error (MSE) atau cross-entropy loss. Tujuan kita adalah untuk mengukur seberapa jauh prediksi neural network dari target sebenarnya.

Backward Pass
Setelah menghitung error, langkah berikutnya adalah melakukan backward pass. Ide dasar dari backpropagation adalah menghitung seberapa besar setiap bobot harus diubah agar mengurangi kesalahan total neural network.

Pertama, kita hitung gradien (turunan) dari loss function terhadap setiap bobot dalam neural network menggunakan aturan rantai (chain rule) dari kalkulus. Tujuannya untuk memberi tahu kita seberapa besar setiap bobot berkontribusi terhadap kesalahan total.

Gradien ini kemudian digunakan untuk mengubah setiap bobot dalam arah yang mengurangi kesalahan. Dalam hal ini, kita menggunakan algoritma optimasi, seperti gradient descent, ketika bobot diperbarui dengan menggerakkannya melawan arah gradien dengan suatu laju pembelajaran (learning rate).

Perubahan Bobot
Bobot-bobot dalam neural network diperbarui menggunakan hasil gradien yang telah dihitung sebelumnya. Proses ini bertujuan untuk menggerakkan bobot ke arah yang mengurangi nilai fungsi kerugian sehingga prediksi neural network menjadi lebih akurat.

Iterasi
Langkah-langkah forward propagation, perhitungan error, backward propagation, dan optimisasi bobot diulang untuk setiap batch data latihan (mini-batch) hingga bobot-bobot dalam neural network konvergen bernilai optimal. Proses ini dapat melibatkan banyak iterasi (epochs) tergantung pada kompleksitas model dan jumlah data latihan.
Dengan menggunakan backpropagation, neural network bisa belajar dari data latihan dan secara iteratif memperbaiki bobot-bobotnya agar dapat membuat prediksi yang semakin akurat. Backpropagation merupakan salah satu teknik kunci dalam pelatihan neural network dan dasar dari banyak model deep learning yang efektif.
