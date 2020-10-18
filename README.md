# Lapres Jarkom Modul 1

##soal
![](.//img/soal.png)

## Soal 1 
### Wireshark filter
```http.host contains "testing.mekanis.me"```

### Jawaban
Server : nginx/1.14.0 (Ubuntu)
![](.//media/1.png)
## Soal 2
### Langkah - Langkah
1. File -> Export object -> Http
2. Text Filter "Tim_Kunjungan_Kerja_BAKN_DPR_RI_ke_Sukabumi141436.jpe"
3. save
### Jawaban
foto kunjungan
![](.//media/2.png)
## Soal 3
### Wireshark filter
```http.request.method == POST```
### Jawaban
username = 10pemuda
password = guncang dunia
![](.//media/3.png)
## Soal 4
### Wireshark filter
```frame contains basic```
### Jawaban
HTTP -> WWW-Autheticate: Basic realm="ini namanya basic authentication"
![](.//media/4.png)
## Soal 5 
### Wireshark filter
```http.host contains "aku.pengen.pw"```
### Langkah - langkah
Length = 574 -> HTTP autorization -> user = kakakgamtenk;pass = hartatahtabermuda
![](.//media/5.png)
### Jawaban
Putih Orange, Orange, Putih Hijau, Biru, Putih biru, Hijau, Putih coklat, Coklat
![](.//media/5_1.png)
## Soal 6
### Wireshark filter
```ftp-data```
### Langkah - langkah
1. edit -> find packet -> String "Abswer.zip" -> find -> Follow -> TCP Stream -> Raw -> save as -> .zip
![](.//media/6.png)
2. edit -> find packet -> String "Zipkey.txt" -> find -> Follow -> TCP Stream -> Raw -> save as -> .txt
![](.//media/6_1.png)
> Pass = hey997400323051
![](.//media/6_2.png)
3. insert pass to open zip
### Jawaban
foto kucing
![](.//media/6_3.png)
## Soal 7
### Wireshark filter
```ftp-data contains Yes.pdf```
Follow -> tcp stream -> raw -> save as -> .pdf
### Jawaban
Puisi Can You Find It?
![](.//media/7.png)
## Soal 8
### Wireshark filter
```ftp.request.command == RETR```
![](.//media/8_0.png)
### Jawaban
pilih yang length 67 untuk microsoft ( Readme)
![](.//media/8.png)
## Soal 9
### Wireshark filter
```tcp.dstport == 21```
### Langkah - langkah
1. navbar menu -> Analyze -> Follow -> TCP Stream
### Jawaban
User = dhana; Pass dhana123
![](.//media/9.png)
## Soal 10
### Langkah - Langkah
1. edit -> find packet
2. Hex value = 25 50 44 46
3. follow -> tcp stream -> raw -> save as -> .pdf
### Jawaban
Salinan Pengesahan UU
![](.//media/10.png)
## Soal 11
### Wireshark capture filter
```port 21```
![](.//media/11.png)
## Soal 12
### Wireshark capture filter
```src port 80```
![](.//media/12.png)
## Soal 13
### Wireshark capture filter
```dst port 443```
![](.//media/13.png)
## Soal 14
### Langkah - Langkah
1. open cmd
2. IPconfig
3. find IPv4 Address
### Wireshark capture filter
```src host 192.168.100.5```
![](.//media/14.png)
## Soal 15
### Wireshark capture filter
```dst host monta.if.ac.id```
![](.//media/15.png)
