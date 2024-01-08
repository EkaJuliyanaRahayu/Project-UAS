# Project-UAS
## Profil
| Variabel | Isi |
| -------- | --- |
|**Nama**| Eka Juliyana Rahayu |
|**NIM** | 312310594 |
|**Kelas** | TI.23.A6 |
|**Mata Kuliah** | Pemrograman |
|**Link Penjelasan** |     https://youtu.be/wSqL-iuBYcU?feature=shared         |

# Project UAS

<P>Buatlah program kasir di sebuah kantin, dengan kondisi berikut:</P>
<P>• List opsi pilihan makanan/minuman dan aksi, bisa menggunakan
format dictionary</P>
<P>• Program harus meminta input pilihan makanan dari pengguna.</P>
<P>• Program harus menghitung total harga makanan yang dipesan.</P>
<P>• Program harus menampilkan struk pembelian.</P>

### 1. `print("==============Warung Amanah============"):` Ini adalah header yang menampilkan nama warung atau kafe.
<p>Ini adalah baris kode yang menampilkan header atau judul program, yang mungkin mencerminkan nama warung atau restoran ("Warung Amanah" dalam hal ini).</p>

<p>Contoh dari tampilan</p>

<img width="312" alt="Screenshot 2024-01-08 142101" src="https://github.com/ekarahayu24/Project-UAS/assets/147680283/fe213118-8c5f-4347-9651-0229767074ac">

## 2. Pembeli = input("Nama Pembeli : "): Menggunakan fungsi `input()` untuk meminta pengguna memasukkan nama pembeli.
<p>contoh dari tampilan</p>

<img width="210" alt="Screenshot 2024-01-08 142740" src="https://github.com/ekarahayu24/Project-UAS/assets/147680283/cbd32acb-9c7c-40cf-9c45-ec3a36469504">

# 3. `totalmakanan = 0` dan `totalminuman = 0:` 
<p>Variabel global yang digunakan untuk menyimpan total biaya makanan dan minuman yang akan dihitung selama proses pemesanan.</p>
<p>Contoh dari tampilan</p>

 <img width="134" alt="Screenshot 2024-01-08 143643" src="https://github.com/ekarahayu24/Project-UAS/assets/147680283/1cab9428-baed-415c-87bb-913cbd17dd37">

# 4.  `def makanan() ` dan  `def minuman(): ` Fungsi-fungsi yang menampilkan menu makanan dan minuman serta mengumpulkan input dari pengguna terkait pilihan dan jumlah porsi/gelas.

``` Python
def makanan():
    global totalmakanan
    global porsi
    global makan
    print("\n==============MENU MAKANAN=====================")
    print("1. Nasi Ayam Mentega - Rp.25000,00")
    print("2. Nasi Goreng Seafood - Rp.30000,00")
    print("3. Mie Goreng Baso - Rp.20000,00")
    nomor = int(input("Masukkan Pilihan 1/2/3 : "))
    porsi = int(input("Berapa Porsi : "))
    
    if nomor == 1:
        totalmakanan = porsi * 25000
        print(porsi,' Nasi Ayam Mentega = Rp.',totalmakanan)
        makan = "Nasi Ayam Mentega"
    elif nomor == 2:
        totalmakanan = porsi * 30000
        print(porsi,'Nasi Goreng Seafood = Rp.',totalmakanan)
        makan = "Nasi Goreng Seafood"
    elif nomor == 3:
        totalmakanan = porsi * 20000
        print(porsi,' Mie Goreng Baso = Rp.',totalmakanan)
        makan = "Mie Goreng Baso"
    else:
        print("Pilihan tidak ada dalam daftar menu\nSilahkan pilih kembali !!!")

def minuman():
    global totalminuman
    global gelas
    global minum
    print("\n==============MENU MINUMAN=====================")
    print("1. Es Teh - Rp.10000,00")
    print("2. Milk Shake Stawberry - Rp.25000,00")
    print("3. Jus Mangga - Rp.20000,00")
    nomor = int(input("Masukkan Pilihan 1/2/3 : "))
    gelas = int(input("Berapa gelas : "))
    
    if nomor == 1:
        totalminuman = gelas * 10000
        print(gelas,' Es Teh = Rp.',totalminuman)
        minum = "Es Teh"
    elif nomor == 2:
        totalminuman = gelas * 25000
        print(gelas,'Milk shake Stawberry = Rp.',totalminuman)
        minum = "Milk Shake Stawberry"
    elif nomor == 3:
        totalminuman = gelas * 20000
        print(gelas,' Jus Mangga = Rp.',totalminuman)
        minum = "Jus Mangga"
    else:
        print("Pilihan tidak ada dalam daftar menu\nSilahkan pilih kembali !!!")

```
# 5. `print("Nama\t\t:", Pembeli):` Menampilkan nama pembeli. `print("Beli\t\t:", porsi, makan, "(Rp.", totalmakanan, ")")` dan `print("\t\t:", gelas, minum, "(Rp.", totalminuman, ")"):` Menampilkan detail pemesanan makanan dan minuman beserta harga totalnya.
<p>contoh dari tampilan</p>

<img width="354" alt="Screenshot 2024-01-08 144459" src="https://github.com/ekarahayu24/Project-UAS/assets/147680283/acf52a5c-5559-4f39-a483-2b1bed684381">

# 6. `print("Tagihan\t\t:Rp.", total_semua):` Menampilkan total tagihan yang harus dibayarkan oleh pembeli. `print("Dibayar\t\t: Rp.", uang):` Menampilkan jumlah uang yang dibayarkan oleh pembeli. `print("Kembalian\t: Rp.", kembalian):` Menampilkan jumlah kembalian yang harus diberikan kepada pembeli.
<p>contoh dari tampilan</p>

<img width="272" alt="Screenshot 2024-01-08 144742" src="https://github.com/ekarahayu24/Project-UAS/assets/147680283/10d0a962-4815-4888-a1ec-6cda8fd300a9">

# HASIL OUTPUT

<img width="629" alt="Screenshot 2024-01-08 121240" src="https://github.com/ekarahayu24/Project-UAS/assets/147680283/b050be35-d636-4bc2-b456-ef720dee0e64">


