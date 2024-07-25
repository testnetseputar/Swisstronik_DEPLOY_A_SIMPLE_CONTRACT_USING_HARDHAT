# Swisstronik Tesnet Task 1

## REMINDER !

Sebelumnya Saya Ingatkan Untuk Menggunakan New Wallet, Terserah Masing - Masing, ini Hanya Saran.
Tutorial Yang Saya Berikan Adalah Kumpulan Dari Berbagai Sumber Yang Sudah Saya Rangkum Agar Lebih Mudah Di Pahami Bagi Mereka Yang Mau Mengerjakan ( DYOR )

link Untuk Misinya Disini: [Click!](https://www.swisstronik.com/testnet2/dashboard)


### 1. Salin Alamat Link Dibawah ini Ke Gitpod, ( Link Copas Diawali Https, git clone nya Dihapus) 

```bash
git clone https://github.com/seputartestnet/Swisstronik1
```

```
cd hardhat-deploy-contract
```

### 2. Buat File .env Lalu Copy Paste Tesk Dibawah ini Beserta Masukkan Private Key EVM ( Bisa Gunakan New Wallet Atau Wallet Testnet ) Tergantung Masing - Masing. 

Buat .env file Di Bagian Atas

```bash
PRIVATE_KEY="your private key"
```


### 3. Compile Kontrak Pintar

```bash
npm run compile
```

### 4. Deploy Kontrak Pintar

```bash
npm run deploy
```

### 5. Get Message

```bash
npm run get-message
```

### 8. Get Message

```bash
npm run set-message
```

### 5. Penyelesaian Akhir

- Buka Menu deployed-adddress.ts Di Situ Ada Kontrak Pintar Yang Sudah Dibuat
- Lalu Salin Dan Copy Paste Di Misi Yang Ada Pada Halaman Swisstronik Testnet
- Ingat Pastikan Di isi Dengan Benar.

- ### TERIMAKASIH DAN SEMOGA BERMANFAAT
