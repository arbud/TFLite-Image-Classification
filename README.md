# TFLite-Image-Classification
Proyek Membuat Model Klasifikasi Gambar Dengan Menggunakan Python Libraries dan Menconvert Model Kedalam Bentk TFLite, Proyek berikut dibuat berdasarkan tugas course "Belajar Pengembangan Machine Learning" sebagai syarat kelulusan course dan untuk memperoleh sertifikasi kompetensi Machine Learning.

Pertama-tama dalam proyek ini saya menggunakan dataset yang diperoleh dari Kaggle yaitu dataset Bottle Synthetic Images yang diperoleh dari User Kaggle Bernama Marionette.

Dataset dari link kaggle tersebut akan dicopy API nya untuk diambil datanya berikut  API dari Bottles Synthetic Images : (kaggle datasets download -d vencerlanz09/bottle-synthetic-images-dataset).

Tujuan dari proyek ini adalah dapat membangun model Machine Learning Untuk Klasifikasi Gambar Botol. Total data berjumlah 25.000 Gambar dan terbagi menjadi 5 folder dengan masing masing folder berjumlah 500 gambar dengan kategori folder yaitu : "Plastic Bottles, Soda Bottles, Water Bottles, Wine Bottles, dan Beer Bottles ".

Dalam pembangunan model menggunakan Conv2D Maxpooling Layer dan menggunakan model sequential, dataset dibagi menjadi 80% merupakan data train dan 20% merupakan data validation, akurasi yang diperoleh sebesar 94%. Kemudian pada tahap akhir melakukan konversi model menjadi TFLite yang dapat di embed di Android dan iOS.
