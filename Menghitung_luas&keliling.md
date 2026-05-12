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
A --> B
B --> C
C --> L
L --> H
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



## Flowchart

```mermaid
flowchart TD
A@{ shape: circle, label: "Start" }
B@{ shape: lean-r, label: "r" }
C@{ shape: diamond, label: "r % 7 == 0" }
E@{ shape: rect, label: "'K = 2 X {phi} X r X r'"}
F@{ shape: rect, label: "'L = {phi} X r X r'"}
H@{ shape: rect, label: "phi = 3,14"}
I@{ shape: lean-r, label: "'{L}'" }
J@{ shape: lean-r, label: "'{K}'" }
K@{ shape: dbl-circ, label: "Stop"}
L@{ shape: lean-r, label: "phi = 22/7" }

A --> B
B --> C
C --true--> L
C --false--> H
H --> E
L --> E
E --> F
F --> J
J --> I
I --> K






```
