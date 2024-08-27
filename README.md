# Mendeteksi Tingkat Kepercayaan Bunga-Iris Ungu menggunakan YOLOv5
Metode yang digunakan dalam mendeteksi bunga iris ungu :
![image](https://github.com/user-attachments/assets/5152613c-5788-44d3-89de-723744e9ab12)

1. Pengumpulan data dilakukan dengan tujuan memperoleh dataset sebanyak 150 gambar/citra dengan menggunakan bahasa pemrograman _Python_
2. Processing data melibatkan tahapan _labelling_ dataset dengan tujuan menandai objek yang diteliti dengan dikelompokan berdasarkan jenisnya.
3. Merancang Yolo
Peracancangan dibuat dengan mengkloning _repository _YOLOv5 dan mendapatkan klasifikasi sebanyak 8 kelas
![image](https://github.com/user-attachments/assets/cf141b35-a84d-4604-a235-f6c0cb6da14a)
4. Percobaan
Percobaan dilakukan dengan memasukkan data setelah dilakukan klasifikasi dan mengujinya dengan penerapan algoritma YOLOv5 pada _google colab_

# Hasil Pembahasan
Dari hasil yang dilakukan terdapat pembagian gambar/citra
![image](https://github.com/user-attachments/assets/0d4b1eac-fe65-4ff6-a89d-c12377c84ae2)
Dengan menggunakan _img_ 416, _batch_ 8 dan _epochs_ 80. memperoleh grafik model _training_ dan validasi
![image](https://github.com/user-attachments/assets/d3c782e5-3e5f-434e-a88f-a1188e00cd11)
Serta terdapat output berupa kurva _precision-recall_ dengan kurva tertinggi paling tinggi yaitu bunga iri ungu, dapat dikatakan kinerja model berjalan dengan baik pada saat mengenali objek yang diuji_
![image](https://github.com/user-attachments/assets/d326de3d-fa8a-4f67-8c80-939d80689256)
