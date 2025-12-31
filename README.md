# pretest-data-analyst

## DATA ANALYST – KNOWLEDGE BASE & USE CASE
### A. KNOWLEDGE BASE
1. SQL Aggregation Understanding
Sebuah tabel transaksi memiliki struktur sebagai berikut:

transaction_id | user_id | amount | transaction_date

Pertanyaan:
Jelaskan perbedaan hasil antara:

SUM(amount)

SUM(DISTINCT amount)

2. Data Architecture Understanding
Pertanyaan:
- Apa perbedaan antara data source dan data warehouse?
- Mengapa dashboard atau laporan sebaiknya tidak langsung membaca data dari data source?

3. Error Analysis & Debugging
Pertanyaan:
- Apa perbedaan antara error yang disebabkan oleh perubahan schema dan error karena query yang salah?
- Bagaimana cara membedakan kedua jenis error tersebut dalam praktik sehari-hari?

4. ETL Concept
Pertanyaan:
- Jelaskan definisi dari ETL (Extract, Transform, Load) process.
- Sebutkan secara singkat fungsi dari masing-masing tahap ETL.

5. BI Tool & Performance Awareness
Kondisi:
Sebuah dashboard Business Intelligence (BI) menjadi sangat lambat ketika dibuka oleh user.
Pertanyaan:
- Sebutkan minimal tiga penyebab utama dashboard menjadi lambat.

### B. USE CASE (STUDI KASUS)
Use Case 1: Data Belum Tersedia

Kondisi:
Anda diminta membuat visualisasi dashboard, namun data yang dibutuhkan belum tersedia atau belum dimigrasikan ke data warehouse.

Pertanyaan:
- Apa langkah pertama yang harus dilakukan?

Use Case 2: Perbedaan Nilai Database dan Dashboard

Kondisi:
Terdapat data transaksi di database dan di dashboard, namun nilai yang ditampilkan di dashboard berbeda dengan nilai di database.

Pertanyaan:
- Apa kemungkinan penyebab terjadinya perbedaan tersebut?
- Langkah apa yang harus dilakukan untuk memverifikasi dan menyelesaikan masalah ini?

Use Case 3: Filter Tidak Sesuai Ekspektasi User

Kondisi:
User ingin memfilter data berdasarkan kondisi tertentu, namun hasil yang ditampilkan tidak sesuai atau data tidak muncul seperti yang diharapkan.

Pertanyaan:
- Apa langkah-langkah yang perlu dilakukan untuk menganalisis masalah ini?
- Bagaimana cara memastikan filter bekerja sesuai dengan logika data?

Use Case 4: Tipe Data Tidak Mendukung Aggregasi

Kondisi:
Tipe data pada database tidak sesuai untuk dilakukan agregasi di BI tools (misalnya data numerik tersimpan sebagai string).

Pertanyaan:
- Apa yang harus dilakukan untuk mengatasi masalah ini?
- Apa nama proses yang dilakukan untuk memperbaiki kondisi tersebut?

Use Case 5: Nilai Terlalu Besar atau Terlalu Kecil

Kondisi:
Query tidak menghasilkan error, namun hasil perhitungan menunjukkan angka yang terlalu besar atau terlalu kecil.

Pertanyaan:
- Apa langkah-langkah validasi yang perlu dilakukan?
- Bagaimana cara memastikan bahwa hasil perhitungan sudah benar?
