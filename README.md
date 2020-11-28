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

![relay](/image/surabaya_relay.png)
![relay2](/image/dhcp_server_tuban.png)
<!-- insert gambar surabaya + tuban -->

## Soal 3 
Pada soal 3 kita diminta untuk melakukan setting terhadap client agar tidak menggunakan IP statis, sehingga kita harus menggunakan DHCP. Selain itu, kita juga perlu memberikan ip range kepada client 1 dan juga 2

![dhcp](/image/gambar_dhcp.png)
![range1](/image/range_ip_1.png)

<!-- insert gambar dhcp, range 1-->

## Soal 4
Pada soal nomer 4 kita diminta untuk memberikan range ip pada clinet 3 dan 4 yang ada pada subnet 3.

![range2](/image/range_ip_2.png)
<!-- insert gambar range ip 2 -->

## Soal 5
Pada soal nomer 5 ini kita diminta agar client mendapatkan DNS dari MALANG dan juga dari `202.46.129.2`. 

![dns](/image/client_dns.png)

<!-- insert gambar client dns -->

## Soal 6
Kita juga perlu untuk mengatur waktu peminjaman IP dimana pada subnet 1 diberikan 5 menit dan pada subnet 2 diberikan 10 menit.

![range1](/image/range_ip_1.png)
![range2](/image/range_ip_2.png)
<!-- insert gambar range 1 + 2 -->

## Soal 7
Kita perlu membuat passwd dari squid agar ketika kita mengakses nya maka user perlu memasukkan username dan password.

![passwd](/image/signin.png)

## Soal 8
Kita perlu memberikan acl agar aturan untuk mengakses nya bisa berjalan dengan baik. Dimana kita perlu untuk melakukan set waktu yang biasa digunakan oleh Megu.

![acl](/image/acl_rule.png)

<!-- insert gambar acl rule -->

## Soal 9
Kita perlu memberikan acl agar aturan untuk mengakses nya bisa berjalan dengan baik. Selain itu, kita juga melakukan setting agar situs hanya bisa di akses pada jam jam tertentu.

![acl2](/image/acl_rule.png)
<!-- insert gambar acl rule -->

## Soal 10
Kita perlu melakukan setting pada konfigurasi squid agar ketika mengakses google maka akan di redirect ke website `monta.if.its.ac.id`

![monta](/image/redirect.png)
<!-- insert gambar monta -->

## Soal 11
Kita hanya perlu mengunduh file yang diberikan dan kita bisa langsung mereplace halaman denied default dari squid yang terletak di `/usr/share/squid/errors/English`.

![forbid](/image/forbid.png)
<!-- insert gambar forbidden -->

## Soal 12
Kita perlu melakukan konfigurasi DNS pada MALANG agar bisa menjalankan melalui domain `janganlupa-ta.t10.pw`.

![dns1](/image/dns1.png)
![dns2](/image/dns2.png)

<!-- insert gambar domain nomer 12 -->