# Algoritma

## Menentukan bilangan ganjil 

## Deskriptif

Algoritma yang ditulis untuk menentukan suatu bilangan merupakan ganjil atau genap

1. Mulai
2. Input Angka
3. Bagi Angka dengan 2
4. Jika Hasilnya sama dengan 0 outputkan GENAP
5. Jika hasilnya tidak sama dengan 0 outpukan GANJIL
6. selesai


## Flowchart

```mermaid
flowchart TD

A@{ shape: circle, label: "Start" }
B@{ shape: lean-r, label: "Angka" }
C@{ shape: diamond, label: "Angka % 2 == 0" }
F@{ shape: lean-r, label: '"GANJIL"' }
G@{ shape: lean-r, label: '"GENAP"' }
H@{ shape: dbl-circ, label: "Stop" }

A --> B
B --> C
C --> G
C --> F
G --> H
F --> H

```

## Pseudo_code

```pseudo
DECLARE Angka: INTEGER
DECLARE Bulat: INTEGER
CONSTANT Modulus: 2

INPUT Angka

Bulat <- Angka % Modulus

IF Bulat == 0 THAN
    OUTPUT "BULAT"
ELSE
    OUTPUT "GANJIL"
ENDIF

```