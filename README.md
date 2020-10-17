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
## Soal 3
### Wireshark filter
```http.request.method == POST```
## Soal 4
### Wireshark filter
```frame contains basic```
## Soal 5 (lom kelar)
### Wireshark filter
```http.host contains "aku.pengen.pw"```
## Soal 6 (lom kelar)
### Wireshark filter
```ftp-data```
## Soal 7
### Wireshark filter
```ftp-data contains Yes.pdf```
Follow -> tcp stream -> raw -> save as -> .pdf
## Soal 8
### Wireshark filter
```ftp.request.command == RETR```
## Soal 9 (lom kelar)
### Wireshark filter
```tcp.dstport == 21```
## Soal 10
### Langkah - Langkah
1. edit -> find packet
2. Hex value = 25 50 44 46
3. follow -> tcp stream -> raw -> save as -> .pdf
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
