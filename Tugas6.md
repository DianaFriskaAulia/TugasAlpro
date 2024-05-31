# 1. OOP ROBOT
```
#include <iostream>
using namespace std;

// Deklarasi kelas
class robot {
private:
    string nama, mbti;
    int umur;

public:
    // Metode untuk menetapkan nilai atribut
    void setNama(string n) {
        nama = n;
    }

    void setMbti(string m) {
        mbti = m;
    }

    void setUmur(int u) {
        umur = u;
    }

    // Metode untuk menampilkan informasi
    void perkenalandiri() {
        cout << "Nama: " << nama << endl;
        cout << "Umur: " << umur << endl;
        cout << "MBTI: " << mbti << endl;
    }
};

int main() {
    // Membuat objek dari kelas robot
    robot r1;
    robot r2;

    // Memberi nilai atribut objek menggunakan metode setter
    r1.setNama("John");
    r1.setUmur(30);
    r1.setMbti("ISTJ");
    r1.perkenalandiri();

    // Memberi nilai atribut objek menggunakan metode setter
    r2.setNama("Mingyu");
    r2.setUmur(30);
    r2.setMbti("ISTJ");
    r2.perkenalandiri();

    return 0;
}
```
# OUTPUT
![Screenshot (9)](https://github.com/DianaFriskaAulia/TugasAlpro/assets/156889167/e3fd2520-f525-4f9a-a00d-a38e452c90df)

# 2. 00P PARFUM
```
#include <iostream>
using namespace std;

// Deklarasi kelas
class parfum {
private:
    string nama;
    string merk;
    string aroma;
    float harga;

public:
    // Metode untuk menetapkan nilai atribut
    void setNama(string n) {
        nama = n;
    }

    void setMerk(string m) {
        merk = m;
    }

    void setAroma(string a) {
        aroma = a;
    }

    void setHarga(float h) {
        harga = h;
    }

    // Metode untuk mendapatkan nilai atribut
    string getNama() {
        return nama;
    }

    string getMerk() {
        return merk;
    }

    string getAroma() {
        return aroma;
    }

    float getHarga() {
        return harga;
    }

    // Metode untuk menampilkan informasi
    void tampilkan_infoparfum() {
        cout << "Nama: " << getNama() << endl;
        cout << "Merk: " << getMerk() << endl;
        cout << "Aroma: " << getAroma() << endl;
        cout << "Harga: " << getHarga() << endl;
    }
};

int main() {
    // Membuat objek dari kelas parfum
    parfum p1;
    parfum p2;

    // Memberi nilai atribut objek menggunakan metode setter
    p1.setNama("Parfum");
    p1.setMerk("Diptyque Orpheon");
    p1.setAroma("Do Son");
    p1.setHarga(700.000);

    p2.setNama("Parfum");
    p2.setMerk("YSL");
    p2.setAroma("Libre");
    p2.setHarga(900.000);

    // Memanggil metode untuk menampilkan informasi
    p1.tampilkan_infoparfum();
    p2.tampilkan_infoparfum();

    return 0;
}
```
# OUTPUT
![Screenshot (10)](https://github.com/DianaFriskaAulia/TugasAlpro/assets/156889167/b904d0f2-fa19-47c6-b735-500befd5172b)

