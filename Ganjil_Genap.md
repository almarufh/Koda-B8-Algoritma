# Algoritma

## Menentukan bilangan ganjil 

## Deskriptif

Algoritma yang ditulis untuk menentukan suatu bilangan merupakan ganjil atau genap

1. Mulai
2. Ambil nilai bilangan
3. bagi nilai bilangan tersebut dengan 2
4. jika hasilnya angka bulat maka difinisikan bilangan tersebut adalah genap
5. jika hasilnya merupakan angka desimal maka tentukan bilangan tersebut adalah ganjil
6. selesai


## Flowchart

```mermaid
flowchart TD

A@{ shape: circle, label: "Start" }
B@{ shape: lean-r, label: "Angka" }
C@{ shape: rect, label: "Angka % 2" }
D@{ shape: diamond, label: "0 = true" }
E@{ shape: diamond, label: "0 = false" }
F@{ shape: lean-r, label: "GANJIL" }
G@{ shape: lean-r, label: "GENAP" }
H@{ shape: dbl-circ, label: "Stop" }

A --IN--> B
B --> C
C --> D
C --> E
D --OUT--> G
E --OUT--> F
G --> H
F --> H



```