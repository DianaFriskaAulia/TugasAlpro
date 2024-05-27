# percobaan
```
#include <iostream>
#include <string>

class Mahasiswa {
    // Bagian private hanya dapat diakses oleh member functions dalam kelas ini
private:
    std::string nama;
    int umur;

    // Bagian public dapat diakses dari luar kelas
public:
    // Konstruktor untuk menginisialisasi objek Mahasiswa
    Mahasiswa(std::string n, int u) {
        nama = n;
        umur = u;
    }

    // Setter untuk mengatur nama
    void setNama(std::string n) {
        nama = n;
    }

    // Getter untuk mendapatkan nama
    std::string getNama() {
        return nama;
    }

    // Setter untuk mengatur umur
    void setUmur(int u) {
        umur = u;
    }

    // Getter untuk mendapatkan umur
    int getUmur() {
        return umur;
    }

    // Metode untuk menampilkan informasi Mahasiswa
    void tampilkanInfo() {
        std::cout << "Nama: " << nama << ", Umur: " << umur << std::endl;
    }
};

int main() {
    // Membuat objek Mahasiswa
    Mahasiswa mhs("hoshi", 21);

    // Menggunakan metode public untuk mengakses data private
    std::cout << "Informasi awal Mahasiswa:" << std::endl;
    mhs.tampilkanInfo();

    // Mengubah nama dan umur menggunakan setter
    mhs.setNama("soonyoung");
    mhs.setUmur(22);


    // Menampilkan informasi yang sudah diubah
    std::cout << "Informasi setelah diubah:" << std::endl;
    mhs.tampilkanInfo();

    std::cout << "Nama:" << mhs.getNama() << std::endl;
    std::cout << "Umur:" << mhs.getUmur() << std::endl;

    return 0;
}
```
# running hasil capture

![Screenshot (16)](https://github.com/DianaFriskaAulia/TugasAlpro/assets/156889167/328579ad-c33c-41c6-afb4-b6dda46cd8fb)

# pratikumpii
```
#include <iostream>
#include <string>

class Mahasiswa {
    // Bagian private hanya dapat diakses oleh member functions dalam kelas ini
private:
    std::string nama;
    int umur;
    std::string prodi;
    std::string fakultas;

    // Bagian public dapat diakses dari luar kelas
public:
    // Konstruktor untuk menginisialisasi objek Mahasiswa
    Mahasiswa(std::string n, int u, std::string p, std::string f) {
        nama = n;
        umur = u;
        prodi = p;
        fakultas = f;
    }

    // Setter untuk mengatur nama
    void setNama(std::string n) {
        nama = n;
    }

    // Getter untuk mendapatkan nama
    std::string getNama() {
        return nama;
    }

    // Setter untuk mengatur umur
    void setUmur(int u) {
        umur = u;
    }

    // Getter untuk mendapatkan umur
    int getUmur() {
        return umur;
    }

    // Setter untuk mengatur prodi
    void setProdi(std::string p) {
        prodi = p;
    }

    // Getter untuk mendapatkan prodi
    std::string getProdi() {
        return prodi;
    }

    // Setter untuk mengatur fakultas
    void setFakultas(std::string f) {
        fakultas = f;
    }

    // Getter untuk mendapatkan fakultas
    std::string getFakultas() {
        return fakultas;
    }

    // Metode untuk menampilkan informasi Mahasiswa
    void tampilkanInfo() {
        std::cout << "Nama: " << nama << ", Umur: " << umur
                  << ", Prodi: " << prodi << ", Fakultas: " << fakultas << std::endl;
    }
};

int main() {
    // Membuat objek Mahasiswa
    Mahasiswa mhs("hoshi", 21, "Kedokteran hewan", "Kedokteran");
    
    // Menampilkan nama, umur, prodi, dan fakultas yang didapatkan dengan getter
    std::cout << "Nama: " << mhs.getNama() << std::endl;
    std::cout << "Umur: " << mhs.getUmur() << std::endl;
    std::cout << "Prodi: " << mhs.getProdi() << std::endl;
    std::cout << "Fakultas: " << mhs.getFakultas() << std::endl;

    return 0;
}
```
# capture hasil running
![Screenshot (17)](https://github.com/DianaFriskaAulia/TugasAlpro/assets/156889167/fb24caf2-d278-4893-82c5-40b4c67ec996)


