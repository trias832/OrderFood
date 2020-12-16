# OrderFood
Aplikasi ini berfungsi untuk memilih menu makanan dan minuman serta menampilkan harga beli beserta ongkir dan potongannya dan alamat pemesan

# Fitur
- User dapat Menginput menu yang dipilih
- User dapat Menghapus menu yang telah dipilih

# CODE
 Pada folder MODEL terdapat 3 class yaitu 
``Item.cs`` ``KeranjangBelanja.cs``
dan `` Payment.cs``

- pada ``Item.cs``digunakan untuk mendapatkan nilai dan mengambil nilai  nama dan garga dari item
- Pada ``KeranjangBelanja.cs``  digunakan  untuk menampung koleksi item yang akan dibeli serta melakukan kalkulasi subtotal
- Pada ``Payment.cs`` digunakan untuk perhitungan Ono

Pada folder Controller terdiri atas ``PenawaranController.cs`` dan ``MainWindoController.cs``
- ``PenawaranController.cs`` berisi logika dari menu-menu yang ada
- ``MainWindoController.cs`` berisi logika dari menambah dan menghapus item

Pada ``MainWindow.xaml.cs`` berisi code untuk mengatur tampilan item yang dipilih,sedangkan ``Penawaran.xaml.cs`` berisi code untuk mengatur tampilan menu pop upnya



