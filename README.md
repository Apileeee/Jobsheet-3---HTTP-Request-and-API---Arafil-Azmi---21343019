# Jobsheet 3 HTTP Request and API

## HTTP Request

HTTP Request adalah cara untuk mengirim permintaan dari klien ke server web untuk mengakses halaman web atau sumber daya lainnya. Proses kerja HTTP Request melibatkan inisiasi permintaan, pembentukan request, pengiriman request, pengolahan server, pengiriman respons, dan tindak lanjut klien.

Metode umum HTTP Request meliputi GET, POST, PUT, DELETE, dan lainnya.

## API (Application Programming Interface)

API, atau Application Programming Interface, adalah aturan dan protokol yang memungkinkan perangkat lunak atau aplikasi berkomunikasi satu sama lain. API menyediakan tingkat abstraksi, endpoint, format data, autentikasi, otorisasi, dan dokumentasi. Permintaan-respon adalah model umum yang digunakan oleh API.

Dokumentasi API memberikan informasi lengkap tentang penggunaan API, termasuk parameter, endpoint, dan format data.

# Aplikasi Cuaca

Aplikasi ini memanfaatkan API Weatherstack dan Mapbox untuk memberikan informasi cuaca terkini dan lokasi berdasarkan koordinat geografis. Proyek ini merupakan bagian dari Jobsheet 3 Pemrograman Berbasis Jaringan Menggunakan Node.js.

## Persyaratan

Sebelum memulai, pastikan Anda memiliki:

- Akun di [Weatherstack](https://weatherstack.com/) untuk mendapatkan API key.
- Akun di [Mapbox](https://www.mapbox.com/) untuk mendapatkan token API.

## Penggunaan

## Mengakses Weatherstack API

1. **Buat akun di [weatherstack.com](https://weatherstack.com/) dan peroleh API key.**
2. Gunakan API key untuk mengakses API Weatherstack dan dapatkan informasi cuaca melalui berbagai endpoint.
3. Perhatikan format data JSON yang diterima dari API Weatherstack.

## Membuat Program untuk Mengakses Weatherstack API

1. Buat folder dan file baru dalam Visual Studio Code.
2. Install npm dan modul postman-request.
3. Gunakan kode JavaScript untuk mengakses API Weatherstack, menganalisis data JSON, dan menampilkan informasi cuaca.

## Mengakses Mapbox API

1. **Buat akun di [mapbox.com](https://www.mapbox.com/) dan peroleh token API.**
2. Gunakan token API untuk mengakses Mapbox API dan lakukan forward geocoding.
3. Perhatikan struktur data JSON dari Mapbox API dan gunakan hasilnya dalam program.

## Integrasi Data

Gabungkan hasil dari Weatherstack API dan Mapbox API dalam program untuk menampilkan informasi cuaca dan lokasi.
