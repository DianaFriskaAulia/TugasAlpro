# robot
'''
#include <iostream>
using namespace std;

// Deklarasi kelas
class robot {
public:
    string nama, mbti;
    int umur;

    // Metode untuk menampilkan informasi
    void perkenalandiri() {
        cout << "Nama: " << nama << endl;
        cout << "Umur: " << umur << endl;
        cout << "mbti: " << mbti << endl;
    }
};

int main() {
    // Membuat objek dari kelas robot
    robot r1;
    robot r2;

    // Memberi nilai atribut objek
    r1.nama = "John";
    r1.umur = 30;
    r1.mbti = "istj";
    r1.perkenalandiri();

    // Memberi nilai atribut objek
    r2.nama = "mingyu";
    r2.umur = 30;
    r2.mbti = "istj";
    r2.perkenalandiri();

    return 0;
}

'''

# oopparfum
'''
#include <iostream>
using namespace std;

// Deklarasi kelas
class parfum {
public:
    string nama;
    string merk;
    string aroma;
    float harga;

    // Metode untuk menampilkan informasi
    void tampilkan_infoparfum() {
        cout << "nama: " << nama << endl;
        cout << "merk: " << merk << endl;
        cout << "aroma; " << aroma << endl;
        cout << "harga; " << harga << endl;
    }
};

int main() {
    // Membuat objek dari kelas parfum
    parfum p1;
    parfum p2;

    // Memberi nilai atribut objek
    p1.nama = "parfum";
    p1.merk = "diptyqueorpheon";
    p1.aroma = "do son";
    p1.harga = 700.000;

    p2.nama = "parfum";
    p2.merk = "ysl";
    p2.aroma = "libre";
    p2.harga = 900.000;



    // Memanggil metode untuk menampilkan informasi
    p1.tampilkan_infoparfum();
    p2.tampilkan_infoparfum();

    return 0;
}
'''
#capture hasil running
![image](https://github.com/DianaFriskaAulia/TugasAlpro/assets/156889167/a4bc449f-d1d9-4a80-9706-c0d438de4cf3)
