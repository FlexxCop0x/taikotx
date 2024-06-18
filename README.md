# Taiko Blazer Script

Script ini dirancang untuk melakukan berbagai transaksi pada jaringan Taiko dengan menggunakan beberapa dompet. Script ini mendukung beberapa mode operasi, termasuk berinteraksi dengan bridge, melakukan transaksi acak, deposit native, mengirim pesan, inisialisasi kontrak, dan memproses pesan.

## Persyaratan

Pastikan Anda telah menginstal paket-paket berikut sebelum menjalankan script:

- `web3`
- `eth_account`

Anda dapat menginstal paket-paket ini menggunakan `pip`:

```bash
pip install web3 eth_account
Cara Menggunakan
Jalankan Script

## Jalankan script Python menggunakan perintah berikut:


python run.py
Masukkan Password

Anda akan diminta untuk memasukkan password. Gunakan password Winsnip untuk mengakses script.

## Pilih Mode Operasi

Anda akan disajikan dengan menu pilihan mode operasi. Pilih mode yang diinginkan dengan memasukkan angka yang sesuai:

------------------------------------------------------------
-                 Push Point Taiko Blazer                  -
-               GAS fee CUSTOM - Multi Akun                -
------------------------------------------------------------
-                     Pilih Mode Operasi                   -
-            1. Interact Bridge       2. Random Tx         -
-            3. Deposit Native        4. Send Message      -
-            5. Init                  6. ProcessMessage    -
-            7. Random                                     -
------------------------------------------------------------
## Pilih mode (1 - 7):
Masukkan Jumlah Wallet

Masukkan jumlah wallet yang ingin Anda gunakan:

## Run Berapa Wallet: 
Masukkan Data Wallet

## Masukkan alamat dan private key dari setiap wallet yang akan digunakan:


Wallet 1
Masukkan alamat wallet: 
Masukkan private key: 
Wallet 2
Masukkan alamat wallet: 
Masukkan private key: 
...
Masukkan Jumlah Transaksi per Wallet

Masukkan jumlah transaksi yang ingin dilakukan per wallet:


Masukkan jumlah transaksi per wallet:
Masukkan Rentang Delay

## Masukkan rentang waktu delay antara transaksi (contoh: 20-60 detik):


## Masukkan rentang delay (contoh: 20-60):
Masukkan Nilai Gwei

## Masukkan nilai gwei untuk transaksi (contoh: 0.1):


Masukkan nilai gwei untuk transaksi (contoh: 0.1):
Mode Operasi
Berikut adalah penjelasan setiap mode operasi:

Interact Bridge

Berinteraksi dengan bridge untuk menarik dana dari kontrak.
Random Tx

Melakukan transaksi ETH acak ke alamat yang dihasilkan secara acak.
Deposit Native

Melakukan deposit native ke kontrak.
Send Message

Mengirim pesan ke kontrak.
Init

Melakukan inisialisasi kontrak.
ProcessMessage

Memproses pesan dalam kontrak.
Random

Melakukan tindakan acak dari mode di atas.
Catatan
Pastikan Anda memiliki cukup saldo ETH pada setiap wallet yang digunakan untuk menutupi biaya transaksi (gas fee).
"""
