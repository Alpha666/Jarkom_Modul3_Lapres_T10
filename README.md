# Lapres Jaringan Komputer T10

## Christian Andrew T 05311840000017
## Rafi Aldi    05311840000018

# Penjelasan

Pada soal shift kali ini kita diminta membuat topologi sesuai yang diminta dimana ada 3 server, 4 client dan 1 router.
Hal pertama yang kita harus lakukan adalah kita mengganti file ```topologi.sh``` yang kita punya.

![topologi](/image/topo.png)

## Soal 1
Pada soal 1 kita hanya diminta untuk membuat topologi yang sama dengan yang diminta dimana sudah kita lakukan pada step sebelumnya.

## Soal 2 
Pada soal 2 ini kita diminta untuk melakukan setting dimana TUBAN akan ditunjuk sebagai DHCP server sementara SURABAYA menjadi DHCP Relay.
<!-- insert gambar surabaya + tuban -->

## Soal 3 
Pada soal 3 kita diminta untuk melakukan setting terhadap client agar tidak menggunakan IP statis, sehingga kita harus menggunakan DHCP. Selain itu, kita juga perlu memberikan ip range kepada client 1 dan juga 2

<!-- insert gambar dhcp, range 1-->

## Soal 4
Pada soal nomer 4 kita diminta untuk memberikan range ip pada clinet 3 dan 4 yang ada pada subnet 3.

<!-- insert gambar range ip 2 -->

## Soal 5
Pada soal nomer 5 ini kita diminta agar client mendapatkan DNS dari MALANG dan juga dari `202.46.129.2`

<!-- insert gambar client dns -->

## Soal 6
Kita juga perlu untuk mengatur waktu peminjaman IP dimana pada subnet 1 diberikan 5 menit dan pada subnet 2 diberikan 10 menit.

<!-- insert gambar range 1 + 2 -->

## Soal 7
Kita perlu membuat passwd dari squid agar ketika kita mengakses nya maka user perlu memasukkan username dan password.

## Soal 8
Kita perlu memberikan acl agar aturan untuk mengakses nya bisa berjalan dengan baik.

<!-- insert gambar acl rule -->

## Soal 9
Kita perlu memberikan acl agar aturan untuk mengakses nya bisa berjalan dengan baik.
<!-- insert gambar acl rule -->

## Soal 10
Kita perlu melakukan setting pada konfigurasi squid agar ketika mengakses google maka akan di redirect ke website `monta.if.its.ac.id`

## Soal 11
Kita hanya perlu mengunduh file yang diberikan dan kita bisa langsung mereplace halaman denied default dari squid yang terletak di `/usr/share/squid/errors/English`.

## Soal 12
Kita perlu melakukan konfigurasi DNS pada MALANG agar bisa menjalankan melalui domain `janganlupa-ta.t10.pw`.

<!-- insert gambar domain nomer 12 -->