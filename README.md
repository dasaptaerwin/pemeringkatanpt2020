# DATA MAKALAH YANG ADA DALAM DAFTAR SCOPUS TAUN 2019

Data yang tersedia berasal dari perguruan tinggi sbb (urut abjad):

- IPB
- ITB
- UGM
- UI
- UNAIR
- TEL-U

Saya mengundang ibu dan bapak untuk mengekstrak data sejenis dari perguruan tinggi masing-masing.

## UNTUK MENJADI PERHATIAN

Data dan visualisasi yang ibu dan bapak lihat di sini bersifat sempit, jadi pasti tidak akan menggambarkan kondisi yang sebenarnya, karena data diambil hanya dari basis data scopus artinya hanya akan menampilkan informasi yang:

- dipublikasi dalam format makalah
- terbit sebagai makalah di jurnal yang ada dalam daftar scopus
- terbit sebagai makalah yang ditulis dalam Bahasa Inggris

## Perangkat keras dan perangkat lunak yang dibutuhkan

Untuk dapat memanfaatkan repositori ini secara optimum, ibu dan bapak memerlukan:

- Komputer atau laptop dengan spesifikasi setera prosesor Intel i3. Spesifikasi yang lebih rendah atau lebih tinggi dapat digunakan tapi akan mempengaruhi waktu proses tentunya.
- Perangkat lunak _open source_ [Vosviewer](vosviewer.com).
- Perangkat lunak pembaca `pptx` dan `xlsx`.


## Penjelasan tentang data

Data ini merupakan jumlah makalah yang ada dalam daftar Scopus tahun 2019, yang umumnya dipakai oleh berbagai sistem pemeringkatan perguruan tinggi di Indonesia.

- Agregator data: [Dasapta Erwin Irawan](https://orcid.org/0000-0002-1526-0863) (Institut Teknologi Bandung, [RINarxiv](rinarxiv.lipi.go.id))
- Tanggal pengunduhan data:	25-26 Agt 2020	
- Metode:	`Search by Affiliation`, pilih document `affiliation only`, `limit to` 2019	
- Layanan akses Scopus dari:	[Institut Teknologi Bandung](itb.ac.id) 
- Keterangan:	Kondisi data sangat bergantung tanggal pengunduhan

## Lisensi

Dokumen data ini saya rilis dengan lisensi [CC-0 (public domain)](https://creativecommons.org/share-your-work/public-domain/cc0/).
Dengan demikian, pengguna dapat langsung menggunakan ulang dokumen ini tanpa perlu izin dari saya. 

## Tujuan

Saya membuat repositori ini adalah untuk:

- mengajak ibu dan bapak sekalian untuk melihat melampaui (_beyond_) metrik yang hanya menunjukkan angka hasil penjumlahan dan pembagian,
- memperlihatkan bahwa data yang diunduh dari pangkalan data (apapun itu) dapat ditelaah untuk mengevaluasi dan menentukan langkah selanjutnya,
- menyemangati ibu dan bapak agar selalu membagikan data/informasi selengkap mungkin dengan dokumentasi selengkap mungkin agar dapat digunakan ulang oleh orang lain.


## Struktur folder dan data

- `Root folder`: berisi `readme.md` dan `license.md`. Saat ini, anda sedang membaca dokumen `readme`. Sempatkan untuk membacanya sampai selesai untuk mendapatkan gambarkan isi repositori data ini.
- `REKAPITULASI`: berisi file `pptx` dan `xls` yang merekapitulasi berbagai data dan visualisasi.
- `DATASETS`: berisi file data dalam format `csv`, hasil pengunduhan metadata dari scopus.
- `NETWORK-MAP-VOSVIEWER`: berisi file pptx dan xls yang merekapitulasi berbagai data dan visualisasi.


## Petunjuk penggunaan data

- Untuk kebutuhan instan, ibu dan bapak langsung menuju folder `REKAPITULASI` dan membuka dokumen `pptx` dan `xls`. Saat melihat angka-angka dalam tabel, harap tidak heran jika melihat perbedaan angka. Scopus memang sering (selalu) mengupdate basis data jurnal yang diindeksnya, sehingga berakibat kepada jumlah makalah yang diindeks, yang pada akhirnya dapat mempengaruhi jumlahnya. Jadi mohon diingat selalu bahwa angka-angka ini saya buat berdasarkan data yang diekstraksi tanggal 25-26 Agt 2020.
- Untuk melihat hasil visualisasi, ibu dan bapak dapat membuka dokumen pptx, namun demikian karena di dalamnya hanyalah hasil tangkapan layar (_screenshot_), maka pasti tidak dapat dipelajari lebih lanjut. Untuk itu, saya menyediakan file hasil visualisasi sebagai `map` dan `network` berformat `txt` untuk setiap visualisasi. 
- Cara untuk mengeksplorasi hasil visualisasi adalah dengan membukanya menggunakan [Vosviewer](vosviewer.com):
		* ada menu `Create a map based on network data`,
		* pilih tab `Vosviewer`
		* kemudian buka folder visualisasi misal `MAP-TEXT`, 
		* kemudian buka:
				- file `net` misal `VOS-NET-ITB-title-abstract.txt` dan 
				- file `map` misal `VOS-MAP-ITB-title-abstract.txt` untuk data ITB. 
				- Untuk data perguruan tinggi lain, anda dapat membuka file sejenis dengan memperhatikan nama perguruan tinggi yang tertera pada nama filenya,
		* setelah visualisasi terbuka, anda dapat melakukan _hover_, _zoom in_, dan _zoom out_
