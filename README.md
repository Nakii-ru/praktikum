# Praktikum - Tipe Data, Variable, dan Operator

Nama  : RIDHO FHADLY HAMZAH

NIM   : 32410486

KELAS : TI.24.A5

Mata Kuliah : Bahasa Pemrograman

## Mencari Bilangan Terbesar dari Beberapa Bilangan yang Diinput
Program ini dibuat untuk menentukan bilangan Terbesar dari serangkaian Nilai bilangan yang diinput tanpa henti hingga user memasukkan nilai "0".
Program ini menggunakan loop `while` dan kondisi `if` untuk memperbarui nilai terbesar yang diinputkan.

## Flowchart Program
![foto](https://github.com/Nakii-ru/foto/blob/main/Screenshot%202024-10-20%20153530.png?raw=true)

## Kode Program
```python
# Inisialisasi MAX dengan negatif tak hingga
MAX = float('-inf')
while True:

        # Input Nilai Oleh Pengguna
        N = int(input("Masukkan Nilai N: "))

        # Jika Nilai 0 diinputkan maka loop akan berakhir
        if N == 0:
            break

        # Cek apakah bilangan yang diinputkan lebih besar dari MAX 
        if N > MAX:

        # Update MAX bila N Lebih besar dari MAX
        MAX = N

# OUTPUT Nilai N terbesar
print(f"Bilangan Terbesar yang dimasukan adalah: {MAX}")

```
## Penjelasan Kode Program
```python
MAX = float('-inf')
```
Program dimulai dengan menginisialisasi variabel `MAX` dengan nilai minus tak hingga menggunakan `float('-inf')`, ini bertujuan agar bilangan yg akan diinputkan akan lebih besar dari nilai awal dan akan menggantikan nilai max.
```python
while true:
```
Baris `while true` akan terus berjalan hingga suatu kondisi didalam loop menyebabkan `break`, dalam kode ini kondisi yang dimaksud ialah ketika pengguna menginputkan nilai `0`
```python
N = int(input("Masukkan Nilai N: ))
```
Baris ini akan meminta input dari pengguna berupa bilangan bulat menggunakan `int`(integer), nilai input tersebut kemudian akan disimpan sebagai nilai variabel `N`
```python
if N == 0
```
Baris ini akan memeriksa apakah nilai yg diinputkan oleh pengguna adalah `0`. Jika ya, maka program akan mengakhiri loop dengan perintah `break`.
```python
if N > MAX
```
Ini adalah kondisi yg memeriksa apakah nilai N yg diinputkan oleh pengguna lebih besar dari nilai MAX saat ini. Jika iya, berarti ada bilangan yg lebih besar dari MAX saat ini, dan oleh karena itu nilai MAX perlu diperbarui.
```python
MAX = N
```
Jika kondisi di atas (N > MAX) terpenuhi, maka nilai MAX diperbarui dengan nilai N. Ini bertujuan untuk menyimpan bilangan terbesar yg diinputkan sejauh ini.
```python
print("Bilangan Terbesar yang dimasukkan adalah: ", MAX)
```
Setelah loop selesai, program akan menampilkan bilangan yg terbesar selama proses berlangsung.

## Contoh Hasil Eksekusi Program
![foto](https://github.com/Nakii-ru/foto/blob/main/Screenshot%202024-10-21%20132539.png?raw=true)
