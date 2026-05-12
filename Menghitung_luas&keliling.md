# Algoritma
## Menghitung Luas dan Keliling Lingkaran

Algoritma yang ditulis untuk menyelesaikan masalah menghitung luas lingkaran dan keliling lingkaran

## Deskriptif

1. Mulai
2. Masukan panjang jari-jari (r)
3. kalikan r pangkat 2 dengan pi yang bernilai 3,14 atau 22/7  
4. Munculkan hasilnya sebagai luas
5. lanjut
6. kalikan r dengan pi yang bernilai 3,14 atau 22/7 lalu dikalikan kembali dengan 2
7. munculkan hasilnya sebagai keliling
8. selesai


## Flowchart

```mermaid
flowchart TD
A@{ shape: circle, label: "Start" }
B@{ shape: lean-r, label: "r" }
C@{ shape: rect, label: "phi = {r}%7" }
D@{ shape: rect, label: "22/7 X {r} X {r}"}
E@{ shape: rect, label: "2 X 3,14 X {r} X {r}"}
F@{ shape: rect, label: "3,14 X {r} X {r}"}
G@{ shape: rect, label: "2 X 22/7 X {r}"}
H@{ shape: diamond, label: "phi == 0"}
I@{ shape: lean-r, label: "'Hasil Luas'" }
J@{ shape: lean-r, label: "'Hasil Keliling'" }
K@{ shape: dbl-circ, label: "Stop"}



A --> B
B --> C
C --> H
H --true--> D
H --false--> E
H --true--> G
H --false--> F
G --> J
F --> J
D --> I
E --> I
J --> K
I --> K

```
