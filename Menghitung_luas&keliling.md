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
C@{ shape: diamond, label: "r % 7" }
D@{ shape: rect, label: "'phi X r X r'"}
E@{ shape: rect, label: "'2 X phi X r X r'"}
F@{ shape: rect, label: "'phi X r X r'"}
G@{ shape: rect, label: "'2 X phi X r'"}
H@{ shape: diamond, label: "phi = 3,14"}
I@{ shape: lean-r, label: "'Hasil Luas'" }
J@{ shape: lean-r, label: "'Hasil Keliling'" }
K@{ shape: dbl-circ, label: "Stop"}
L@{ shape: diamond, label: "phi = 22/7" }

A --> B
B --> C
C --true--> L
C --false--> H
L --> D
L --> G
H --> F
H --> E
F --> I
D --> I
G --> J
E --> J
J --> K
I --> K



```
