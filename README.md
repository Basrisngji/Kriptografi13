# Kriptografi13
## Profil
| #               | Biodata           |
| --------------- | ----------------- |
| **Nama**        | Basri Sangaji     |
| **NIM**         | 312110152         |
| **Kelas**       | TI.21.A.1         |
| **Mata Kuliah** | Kriptografi       |

### Penjelasan
1. Baris 1-2   : Mencetak nama dan NIM.
2. Baris 4-6   : Mendefinisikan dua fungsi,**hex_to_bin** dan **bin_to_hex**, untuk mengonversi antara representasi heksadesimal dan biner.
3. Baris 8-28  : Mendefinisikan fungsi **encrypt_ecb** untuk melakukan enkripsi ECB. Prosesnya melibatkan beberapa langkah:<br>
   * Step 4  : Memisahkan plaintext ke dalam blok-blok 4 bit.<br>
   * Step 5-6: Melakukan XOR dan pergeseran pada setiap blok.<br>
   * Step 7  : Mengonversi hasil XOR ke dalam representasi heksadesimal.
4. Baris 31-32 : Meminta input dari pengguna untuk plaintext dan kunci.
5. Baris 35    : Memanggil fungsi **encrypt_ecb** dengan plaintext dan kunci yang diinputkan.
6. Baris 38    : Mencetak hasil enkripsi ECB.

Jadi, keseluruhan kode ini bertujuan untuk mengenkripsi plaintext menggunakan metode ECB dengan operasi XOR dan pergeseran pada blok-blok 4-bit.

### Output
![Gambar 1](https://github.com/Basrisngji/Kriptografi13/blob/main/output.png)

### Terimakasih
