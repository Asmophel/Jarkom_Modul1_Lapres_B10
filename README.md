# Lapres Jarkom Modul 1
## Soal 1 
### Wireshark filter
```http.host contains "testing.mekanis.me"```
### Jawaban
Server : nginx/1.14.0 (Ubuntu)
## Soal 2
### Langkah - Langkah
1. File -> Export object -> Http
2. Text Filter "Tim_Kunjungan_Kerja_BAKN_DPR_RI_ke_Sukabumi141436.jpe"
3. save
### Jawaban
foto kunjungan
## Soal 3
### Wireshark filter
```http.request.method == POST```
### Jawaban
username = 10pemuda
password = guncang dunia
## Soal 4
### Wireshark filter
```frame contains basic```
### Jawaban
HTTP -> WWW-Autheticate: Basic realm="ini namanya basic authentication"
## Soal 5 
### Wireshark filter
```http.host contains "aku.pengen.pw"```
### Langkah - langkah
Length = 574 -> HTTP autorization -> user = kakakgamtenk;pass = hartatahtabermuda
### Jawaban
Putih Orange, Orange, Putih Hijau, Biru, Putih biru, Hijau, Putih coklat, Coklat
## Soal 6
### Wireshark filter
```ftp-data```
### Langkah - langkah
1. edit -> find packet -> String "Abswer.zip" -> find -> Follow -> TCP Stream -> Raw -> save as -> .zip
2. edit -> find packet -> String "Zipkey.txt" -> find -> Follow -> TCP Stream -> Raw -> save as -> .txt
> Pass = hey997400323051
3. insert pass to open zip
### Jawaban
foto kucing
## Soal 7
### Wireshark filter
```ftp-data contains Yes.pdf```
Follow -> tcp stream -> raw -> save as -> .pdf
### Jawaban
Puisi Can You Find It?
## Soal 8
### Wireshark filter
```ftp.request.command == RETR```
### Jawaban
pilih yang length 67 untuk microsoft ( Readme)
## Soal 9
### Wireshark filter
```tcp.dstport == 21```
### Langkah - langkah
1. navbar menu -> Analyze -> Follow -> TCP Stream
### Jawaban
User = dhana; Pass dhana123
## Soal 10
### Langkah - Langkah
1. edit -> find packet
2. Hex value = 25 50 44 46
3. follow -> tcp stream -> raw -> save as -> .pdf
### Jawaban
Salinan Pengesahan UU
## Soal 11
### Wireshark capture filter
```port 21```
## Soal 12
### Wireshark capture filter
```src port 80```
## Soal 13
### Wireshark capture filter
```dst port 443```
## Soal 14
### Langkah - Langkah
1. open cmd
2. IPconfig
3. find IPv4 Address
### Wireshark capture filter
```src host 192.168.100.5```
## Soal 15
### Wireshark capture filter
```dst host monta.if.ac.id```
