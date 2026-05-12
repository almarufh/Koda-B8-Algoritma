# Algoritma
## Menghitung Luas dan Keliling Lingkaran

Algoritma yang ditulis untuk menyelesaikan masalah menghitung luas lingkaran dan keliling lingkaran

## Deskriptif

1. Mulai
2. Masukan panjang jari-jari (r)
3. Phi bernilai 3,14 atau 22/7
3. kalikan r kuadrat dengan phi   
4. Outputkan sebagai Luas
5. lanjut
6. kalikan r dengan Phi kali 2
7. Outputkan sebagai Keliling
8. selesai


## Flowchart

```mermaid
flowchart TD
A@{ shape: circle, label: "Start" }
B@{ shape: lean-r, label: "r" }
C@{ shape: diamond, label: "r % 7 == 0" }
E@{ shape: rect, label: "Keliling = 2 X Phi X r X r"}
F@{ shape: rect, label: "Luas = Phi X r X r"}
H@{ shape: rect, label: "Phi = 3,14"}
I@{ shape: lean-r, label: "'{Luas}'" }
J@{ shape: lean-r, label: "'{Keliling}'" }
K@{ shape: dbl-circ, label: "Stop"}
L@{ shape: lean-r, label: "Phi = 22/7" }

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
