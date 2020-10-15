# Jarkom_Modul1_Lapres_C12
## Kelompok C12
* 05111840000146 - I Kadek Ricky Suirta
* 05111840000162 - Fransiskus Xaverius Kevin Koesnadi

## Daftar Isi
* [Soal Display Filter](#display-filter-soal-1---10)
* [Soal 1](#soal-1)
* [Soal 2](#soal-2)
* [Soal 3](#soal-3)
* [Soal 4](#soal-4)
* [Soal 5](#soal-5)
* [Soal 6](#soal-6)
* [Soal 7](#soal-7)
* [Soal 8](#soal-8)
* [Soal 9](#soal-9)
* [Soal 10](#soal-10)
* [Soal Capture Filter](#capture-filter-soal-11---15)
* [Soal 11](#soal-11)
* [Soal 12](#soal-12)
* [Soal 13](#soal-13)
* [Soal 14](#soal-14)
* [Soal 15](#soal-15)

## Display Filter (Soal 1 - 10)
Soal 1-5 dan 10 memiliki Wireshark Capture File yang sama. Soal 6, 7, 9 memiliki Wireshark Capture File yang sama. Soal 8 memiliki Wireshark Capture File tersendiri.

## Soal 1
Pada display filter, masukan `sintaks http.host == "testing.mekanis.me"`
![1 0](https://user-images.githubusercontent.com/58078219/96079835-f5d7f980-0edf-11eb-9a4d-b41fe04bf592.jpg)

Klik kanan pada salah satu paket, pilih Follow -> TCP Stream, maka akan didapatkan server nginx
![1 1](https://user-images.githubusercontent.com/58078219/96079942-2e77d300-0ee0-11eb-9510-700acad6f50a.jpg)

## Soal 2
Pada display filter masukan sintaks `http contains Tim_Kunjungan_Kerja_BAKN_DPR_RI_ke_Sukabumi141436.jpg`
![2 0](https://user-images.githubusercontent.com/58078219/96080336-0a68c180-0ee1-11eb-897d-75651814a976.jpg)

Setelah memiliki packet, pilih pada menu bar File -> Export Objects -> HTTP
![2 3](https://user-images.githubusercontent.com/58078219/96080530-73e8d000-0ee1-11eb-83cf-bab609957367.jpg)

Cari Tim_Kunjungan_Kerja_BAKN_DPR_RI_ke_Sukabumi141436. jpg
![2 1](https://user-images.githubusercontent.com/58078219/96080343-0c328500-0ee1-11eb-9664-cc9bc1cefeea.jpg)

Save file pada suatu folder, maka akan diperoleh gambar yang dimaksud
![Tim_Kunjungan_Kerja_BAKN_DPR_RI_ke_Sukabumi141436](https://user-images.githubusercontent.com/58078219/96080355-10f73900-0ee1-11eb-8e8b-f58140a75f6d.jpg)

## Soal 3

## Soal 4
Pada display filter masukan sintaks `http contains basic`, sehingga akan diperoleh web-web yang menggunakan basic authentication
![4 0](https://user-images.githubusercontent.com/58078219/96081150-e5754e00-0ee2-11eb-97dc-c2f63c58521a.jpg)

## Soal 5
Pada display filter masukan sintaks `http.host contains "aku.pengen.pw"`, Setelahnya maka paket networking_meme.png dan dilihat pada Hypertext Transfer Protocol di bagian Wireshark Payload, maka akan ditemukan username: `kakakgamtenk` dan password: `hartatahtabermuda` (Username dan password ini akan dibutuhkan dalam membuka aku.pengen.pw).
![5 0](https://user-images.githubusercontent.com/58078219/96082102-d2fc1400-0ee4-11eb-9f33-e1008a8bc270.jpg)

Buka web browser lalu buka aku.pengen.pw pada searchbar, dan diberikan dialogue box untuk memasukan username dan password.
![5 1](https://user-images.githubusercontent.com/58078219/96082118-d7283180-0ee4-11eb-8d9c-7df644fafeec.jpg)

Masukkan username dan password yang sudah ditemukan sebelumnya.
![5 2](https://user-images.githubusercontent.com/58078219/96082121-d8595e80-0ee4-11eb-8209-de67f12f59a8.jpg)

Hasil diperoleh dengan disertai input urutan konfigurasi kabel T568B. Urutan konfigurasi kabel tersebut:
```
Urutan konfigurasi pengkabelan T568B:
Urutan ke-1: Putih Orange RD+ (data terima+)
Urutan ke-2: Orange RD- (data terima-)
Urutan ke-3: Putih Hijau TD+ (data kirim +)
Urutan ke-4: Biru NC (tidak dipakai)
Urutan ke-5: Putih Biru NC (tidak dipakai)
Urutan ke-6: Hijau TD- (data kirim -)
Urutan ke-7: Putih Coklat NC (tidak dipakai)
Urutan ke-8: Coklat NC (tidak dipakai)
```
![5 3](https://user-images.githubusercontent.com/58078219/96082124-d8f1f500-0ee4-11eb-8264-2c8c71ada034.jpg)

## Soal 6

## Soal 7

## Soal 8

## Soal 9

## Soal 10

Kembali ke [Daftar isi](#daftar-isi)

## Capture Filter (Soal 11 - 15)
Menggunakan capture filter dan Wireshark masing-masing.

## Soal 11

## Soal 12

## Soal 13

## Soal 14

## Soal 15


## Kendala yang  dihadapi saat pengerjaan
1. Tidak ada
2. Tidak ada
3. Tidak ada
