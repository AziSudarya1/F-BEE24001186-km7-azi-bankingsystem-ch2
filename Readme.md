# Banking System

This project demonstrates a simple banking system using JavaScript classes and custom error handling.

## Features
- **Deposit**: tambah dan ke dalam saldo.
- **Withdraw**: Penarikan dana dengan penanganan kesalahan karena saldo tidak cukup.
- **Custom Error**: `InsufficientFundsError` akan berjalan ketika mencoba menarik lebih dari saldo yang tersedia.

### penjelasan flowchart

- Mulai: Proses dimulai.
- Membuat Instance BankAccount: Membuat objek dari kelas BankAccount.
- Deposit 50000: Memanggil metode deposit untuk menambah saldo.
- Tampilkan "Telah melakukan deposit sebanyak: Rp. 50000": Mengonfirmasi bahwa deposit berhasil.
- Withdraw 10000: Memanggil metode withdraw untuk mengurangi saldo.
- Periksa saldo >= amount?: Memeriksa apakah saldo cukup untuk penarikan.
- Jika tidak: Tampilkan pesan kesalahan.
- Jika ya: Lanjutkan dengan pengurangan saldo.
- Tampilkan "Telah melakukan penarikan sebanyak: Rp. 10000": Mengonfirmasi bahwa penarikan berhasil.
- Tampilkan "Saldo setelah penarikan Rp. {saldo}": Menampilkan saldo akhir setelah penarikan.
- End: Proses selesai.

#### How to run
1. Clone the Repository

- First, clone this repository to your local machine:

git clone https://github.com/yourusername/banking-system.git

2. Navigate to the Project Directory

- Change to the project directory:

cd banking-system


3. To run the bank_system.js file and test the banking system:

node bank_system.js