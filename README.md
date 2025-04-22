# elearning2

Materi Input Control pada Android Native 

Saya akan memberikan penjelasan tentang Input Control di Android Native dan implementasi untuk Date Time, Alert, Toast, dan Input Phone Number. Mari kita mulai dengan penjelasan dan dilanjutkan dengan kode yang bisa dijalankan di Android Studio. 

Input Control pada Android Native 

Input Control adalah komponen UI yang memungkinkan pengguna memasukkan data atau berinteraksi dengan aplikasi. Android menyediakan berbagai jenis input control, seperti button, text field, checkbox, radio button, toggle button, spinner, dan lainnya. 

Implementasi Input Control yang Diminta 

Berikut adalah implementasi dari empat Input Control yang diminta: 

1.	Date Time: Memungkinkan pengguna memilih tanggal dan Waktu dengan DatePickerDialog dan TimePickerDialog 

2.	Alert: Menampilkan pesan peringatan kepada pengguna dengan AlertDialog 

3.	Toast: Menampilkan pesan singkat yang muncul sebentar lalu hilang 

4.	Input Phone Number: Input khusus untuk nomor telepon dengan EditText dan atribut khusus 

Penjelasan Implementasi 

Implementasi yang saya buat mencakup 4 jenis Input Control yang diminta: 

1. Date Time 

Implementasi Date Time menggunakan komponen bawaan Android: 

•	DatePickerDialog untuk memilih tanggal 

•	TimePickerDialog untuk memilih Waktu 

•	Hasil pilihan ditampilkan di TextView 

2. Alert 

Implementasi Alert menggunakan AlertDialog yang dapat: 

•	Menampilkan pesan dengan judul 

•	Memiliki tombol positif (OK) dan negative (Cancel) 

•	Memberikan feedback berbentuk Toast saat tombol ditekan 3. Toast 

Implementasi Toast Message menampilkan pesan singkat yang muncul dan hilang otomatis dengan: 

•	Toast.makeText() untuk membuat Toast 

•	Toast.LENGTH_LONG untuk durasi yang lebih lama 

4. Input Phone Number 

Implementasi Input Phone Number pada activity terpisah dengan: 

•	EditText dengan inputType="phone" khusus nomor telepon 

•	Validasi nomor telepon saat tombol ditekan 

•	Menampilkan hasil validasi di TextView 

Cara Menjalankan Proyek 

1.	Buat project baru di Android Studio dengan nama "Input Controls" 

2.	Buat package com.example.inputcontrols 

3.	Tambahkan semua file yang telah disediakan sesuai struktur folder 

4.	Build dan jalankan project pada emulator atau device fisik
