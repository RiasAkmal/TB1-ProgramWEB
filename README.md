Rias Akmal Sembiring -41523010227

Proyek ini adalah tugas besar 1 berupa aplikasi web sederhana yang dibuat menggunakan framework Laravel. Aplikasi ini mempunyai tujuan
untuk mengelola produk, termasuk menampilkan daftar produk, menambah produk baru, mengedit produk yang sudah ada, dan menghapus produk.

Struktur Kode
Controller ProdukController

Controller ProdukController bertanggung jawab untuk mengelola semua interaksi yang terkait dengan produk. Berikut adalah penjelasan untuk setiap metode:

ViewProduk: Menampilkan semua produk yang ada di database dengan memanggil model Produk dan mengirimkan data ke view produk.

CreateProduk: Memvalidasi dan menyimpan produk baru ke database. Jika validasi berhasil, produk baru ditambahkan, dan pengguna akan diarahkan kembali dengan pesan sukses.

ViewAddproduk: Menampilkan formulir untuk menambah produk baru.

DeleteProduk: Menghapus produk dari database berdasarkan kode_produk yang diberikan. Setelah penghapusan, pengguna diarahkan kembali dengan pesan sukses.

ViewEditProduk: Menampilkan formulir untuk mengedit produk berdasarkan kode_produk. Jika produk tidak ditemukan, pengguna akan mendapatkan pesan error.

UpdateProduk: Memvalidasi dan memperbarui data produk yang ada. Jika produk ditemukan, data produk akan diperbarui, dan pengguna diarahkan kembali dengan pesan sukses.
