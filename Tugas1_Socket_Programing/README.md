# Pemahaman Dasar Socket
### Socket adalah antarmuka yang digunakan untuk komunikasi antara dua sistem. Sebuah socket berfungsi seperti pintu yang membuka koneksi untuk saling bertukar data.

- Server Socket: Menunggu dan menerima koneksi dari client.
- Client Socket: Menghubungi server dan mengirimkan data.

## Langkah-langkah Socket Programming
### 1. Menjalankan Server
Server dibuat untuk mendengarkan koneksi dari client, kemudian menerima dan merespons data yang dikirimkan client. 

![Gambar](./image/Screenshot%20from%202024-12-02%2014-10-42.png)

### 2. Menjalankan Client
Client menghubungkan ke server menggunakan alamat IP dan port yang ditentukan, mengirim data, dan menerima respons dari server.

![Gambar](./image/Screenshot%20from%202024-12-02%2014-11-14.png)

### 3. Hasil tampilan Wireshark
Wireshark menampilkan paket-paket data seperti TCP handshake, HTTP request/response, dan komunikasi lainnya antara client dan server.

![Gambar](./image/Screenshot%20from%202024-12-02%2014-10-09.png)

### 4. Hasil Flow Graph
Flow Graph di Wireshark menunjukkan aliran komunikasi antar perangkat secara visual, mencakup pengiriman dan penerimaan paket data secara berurutan.

![Gambar](./image/Screenshot%20from%202024-12-02%2014-13-43.png)

Langkah - langkah diatas menunjukkan interaksi antara server dan client melalui socket programming, di mana server menerima koneksi dari client dan saling bertukar data. Selain itu, Wireshark digunakan untuk menganalisis aliran data dan kinerja komunikasi jaringan, yang memungkinkan untuk memantau proses pengiriman paket antara kedua perangkat.