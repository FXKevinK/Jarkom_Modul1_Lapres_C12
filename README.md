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
Pada display filter masukan sintaks `ftp-data` diikuti dengan pencarian (Find tekan tombol `Ctrl + F`) `Answer.zip` berupa string.
![6 0](https://user-images.githubusercontent.com/58078219/96087248-c334fd80-0eed-11eb-8ff1-7af32a0badf8.jpg)

Setelah memilih paket, klik kanan -> Follow -> TCP Stream.
![6 1](https://user-images.githubusercontent.com/58078219/96087251-c5975780-0eed-11eb-93e9-f983e34d923d.jpg)

Ubah Show and save data as menjadi `RAW`, lalu save as dengan nama `Answer.zip`.
![6 2](https://user-images.githubusercontent.com/58078219/96087261-c92ade80-0eed-11eb-8350-c95cd1a63117.jpg)

File `Answer.zip` sudah di-save.
![6 3](https://user-images.githubusercontent.com/58078219/96087267-cb8d3880-0eed-11eb-99c5-8ebf01b4fbae.jpg)

Jika membuka file `.zip` tersebut, file `Open This.pdf` memerlukan password.
![6 4](https://user-images.githubusercontent.com/58078219/96087270-cc25cf00-0eed-11eb-800c-a9f8647fdc0d.jpg)

Kembali ke Wireshark, masukan sintaks yang sama `ftp-data` dan lakukan pencarian (Find tekan tombol `Ctrl + F`) `zipkey` berupa string. Lalu pilih pake yang ditemukan -> Kilk kanan -> Follow -> TCP Stream.
![6 5](https://user-images.githubusercontent.com/58078219/96087273-ccbe6580-0eed-11eb-941b-7ed451cd506c.jpg)

Ditemukan password yang diperlukan untuk membuka file pdf yang ditemukan sebelumnya.
![6 6](https://user-images.githubusercontent.com/58078219/96087278-cdef9280-0eed-11eb-84b3-004f1daba5ca.jpg)

Masukan password `hey997400323051`
![6 7](https://user-images.githubusercontent.com/58078219/96087281-cf20bf80-0eed-11eb-8e9a-1e5a371e4813.jpg)

Hasil berupa file `.pdf` akan terbuka.
![6 8](https://user-images.githubusercontent.com/58078219/96087283-cfb95600-0eed-11eb-9727-b461dceda865.jpg)

## Soal 7

Pada display filter masukan sintaks `frame contains "Yes.pdf"`diikuti dengan pencarian (Find tekan tombol `Ctrl + F`) `zipkey` berupa string. Lalu memilih paket yang dicari dan klik kanan pada paket tersebut -> Follow -> TCP Stream.
![7 0](https://user-images.githubusercontent.com/58078219/96088521-bfa27600-0eef-11eb-88c0-ee412ce6e200.jpg)

Ubah Show and save data as menjadi `RAW`, lalu save as dengan nama `no7.zip`. Namun penamaan file tidak memeiliki ketentuan sehingga penamaan file `no7.zip` dapat diganti.
![7 1](https://user-images.githubusercontent.com/58078219/96088527-c16c3980-0eef-11eb-9980-96929d67284f.jpg)

File `no7.zip` sudah di-save
![7 2](https://user-images.githubusercontent.com/58078219/96088533-c4672a00-0eef-11eb-8630-e5785bdf0a2a.jpg)

Buka file tersebut, maka di dalamnya terdapay file `Yes.pdf`, dan buka file `Yes.pdf`.
![7 3](https://user-images.githubusercontent.com/58078219/96088537-c4ffc080-0eef-11eb-8668-682b64845e86.jpg)

Hasil berupa file `.pdf` akan terbuka.
![7 4](https://user-images.githubusercontent.com/58078219/96088541-c630ed80-0eef-11eb-97c5-f1cbf74a4e3a.jpg)

## Soal 8

## Soal 9

## Soal 10

Pada display filter masukan sintaks masukan sintaks `tcp containss "pdf"` diikuti dengan pencarian (Find tekan tombol `Ctrl + F`) `25 50 44 46` berupa Hexadecimal. Lalu memilih paket yang dicari dan klik kanan pada paket tersebut -> Follow -> TCP Stream.
![10 0](https://user-images.githubusercontent.com/58078219/96089765-80752480-0ef1-11eb-92f0-95687badde1b.jpg)

Ubah Show and save data as menjadi `RAW`, lalu save as dengan nama `nomor 10.pdf`. Namun penamaan file tidak memeiliki ketentuan sehingga penamaan file `nomor 10.pdf` dapat diganti.
![10 1](https://user-images.githubusercontent.com/58078219/96089773-823ee800-0ef1-11eb-9b18-0587a120896a.jpg)

File `nomor 10.pdf` sudah di-save
![10 2](https://user-images.githubusercontent.com/58078219/96089779-84a14200-0ef1-11eb-8bc1-6dad6de882db.jpg)

Hasil berupa file `.pdf` akan terbuka.
![10 3](https://user-images.githubusercontent.com/58078219/96089785-8539d880-0ef1-11eb-8506-cac1a24a4693.jpg)

Kembali ke [Daftar isi](#daftar-isi)

## Capture Filter (Soal 11 - 15)
Menggunakan capture filter dan Wireshark masing-masing.

## Soal 11

Pada Capture Filter masukan sintaks `port 21`. Pilih Wi-Fi (Disesuaikan dengan jaringan yang digunakan saat meng-capture).
![11 0](https://user-images.githubusercontent.com/58078219/96091605-04c8a700-0ef4-11eb-9d39-48a307c554ca.jpg)

Hasil Capture Filter hanya mengambil paket yang mengandung `port 21`, namun tidak terdapat paket karena tidak adanya `port 21`.
![11 1](https://user-images.githubusercontent.com/58078219/96091613-05f9d400-0ef4-11eb-932d-ad4dfa996b3d.jpg)

## Soal 12

Pada Capture Filter masukan sintaks `src port 80`. Pilih Wi-Fi (Disesuaikan dengan jaringan yang digunakan saat meng-capture).
![12 0](https://user-images.githubusercontent.com/58078219/96091616-072b0100-0ef4-11eb-84d0-d0205bb2ebf9.jpg)

Hasil Capture Filter hanya mengambil paket yang berasal dari `port 80`.
![12 1](https://user-images.githubusercontent.com/58078219/96091623-085c2e00-0ef4-11eb-80e3-fc042617af62.jpg)

## Soal 13

Pada Capture Filter masukan sintaks `dst port 443`. Pilih Wi-Fi (Disesuaikan dengan jaringan yang digunakan saat meng-capture).
![13 0](https://user-images.githubusercontent.com/58078219/96091627-098d5b00-0ef4-11eb-9d3e-8b7feb9f3eea.jpg)

Hasil Capture Filter hanya menampilkan paket yang menuju port 443, `dst port 443`.
![13 1](https://user-images.githubusercontent.com/58078219/96091632-0abe8800-0ef4-11eb-813f-bf7a13b29c21.jpg)

## Soal 14

Pada Capture Filter masukan sintaks `src host 192.168.1.2`. IP Address yang digunakan juga disesuaikan dengan perangkat pengguna. Pilih Wi-Fi (Disesuaikan dengan jaringan yang digunakan saat meng-capture).
![14 0](https://user-images.githubusercontent.com/58078219/96091634-0befb500-0ef4-11eb-8817-4875b0f9c211.jpg)

Hasil Capture Filter hanya mengambil paket yang berasal dari ip pengguna.
![14 1](https://user-images.githubusercontent.com/58078219/96091638-0c884b80-0ef4-11eb-8b7c-6bb1cd341c8e.jpg)

## Soal 15

Pada Capture Filter masukan sintaks `dst host monta.if.its.ac.id`. PIlih Wi-Fi (Disesuaikan dengan jaringan yang digunakan saat meng-capture)
![15 0](https://user-images.githubusercontent.com/58078219/96091643-0db97880-0ef4-11eb-9dd4-8e26c2e08e15.jpg)

Hasil Capture Filter hanya mengambil paket yang tujuannya ke monta.if.its.ac.id, paket terdetksi dan dapat di-capture dikarenakan pengguna juga sedang membuka situs monta.if.its.ac.id. Apabila sedang tidak membuka situs tersebt, maka tidak ada paket yang ter-capture.
![15 1](https://user-images.githubusercontent.com/58078219/96091648-0eeaa580-0ef4-11eb-960c-29c6d7fbbdf9.jpg)

Kembali ke [Daftar isi](#daftar-isi)

## Kendala yang  dihadapi saat pengerjaan
Kurangnya ketelitian di bagian Capture Filter, dan sempat ada terjadinya pencarian filter yang dilakukan secara manual oleh karena terkendala pada comparison operator.

Kembali ke [Daftar isi](#daftar-isi)
