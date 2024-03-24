# menghitung luas dan keliling persegi panjang

```c++
#include <iostream>
#include <string>

// Fungsi untuk mendapatkan nama hari esoknya
std::string nextday(const std::string& hariSekarang) {
    // Array yang menyimpan nama-nama hari
    std::string hari[7] = {"Senin", "Selasa", "Rabu", "Kamis", "Jumat", "Sabtu", "Minggu"};
    
    // Mencari indeks dari hari sekarang
    int indeks = -1;
    for (int i = 0; i < 7; ++i) {
        if (hari[i] == hariSekarang) {
            indeks = i;
            break;
        }
    }

    // Jika hari tidak ditemukan
    if (indeks == -1) {
        return "Hari tidak valid";
    }

    // Mengembalikan nama hari esoknya
    return hari[(indeks + 1) % 7];
}

int main() {
    // Meminta pengguna memasukkan nama hari sekarang
    std::string hariSekarang;
    std::cout << "Masukkan nama hari sekarang (Senin sampai Minggu): ";
    std::cin >> hariSekarang;

    // Memanggil fungsi untuk mendapatkan nama hari esoknya
    std::string hariEsok = nextday(hariSekarang);

    // Menampilkan hasil
    std::cout << "Hari esok adalah: " << hariEsok << std::endl;

    return 0;
}
```
