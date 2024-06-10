# inheritance 1
```
#include <iostream>
#include <string>
using namespace std;

class Hewan{
    public:
        void predator(){
        cout<<"Ini adalah hewan predator"<<endl;}
        void taring(){
        cout<<"Hewan ini memiliki taring"<<endl;}
        void cakar(){
        cout<<"Hewan ini memiliki cakar"<<endl;}
};
class Harimau:public Hewan {
    public:
        void Harimauinfo(){
        cout<<"Hewan ini adalah Harimau"<<endl;}
};
class Singa:public Hewan {
    public:
        void Singainfo(){
        cout<<"Hewan ini adalah singa"<<endl;}
};
class Macan:public Hewan {
    public:
        void Macaninfo(){
        cout<<"Hewan ini adalah macan"<<endl;}
};
int main () {
    Harimau harimau;
    harimau.Harimauinfo();
    harimau.predator();
    harimau.taring();
    harimau.cakar();
cout << endl;

    Singa singa;
    singa.Singainfo();
    singa.predator();
    singa.taring();
    singa.cakar();

cout << endl;

    Macan macan;
    macan.Macaninfo();
    macan.predator();
    macan.taring();
    macan.cakar();

    return 0;
}
```
# output
![Screenshot (24)](https://github.com/DianaFriskaAulia/TugasAlpro/assets/156889167/9f9e1ab5-8a12-423a-88aa-b1caabef9852)

# inheritance 2
```
#include <iostream>
#include <string>
using namespace std;

class Hewan{
    public:
        void predator(){
        cout<<"Ini adalah hewan predator"<<endl;}
        void taring(){
        cout<<"Hewan ini memiliki taring"<<endl;}
        void cakar(){
        cout<<"Hewan ini memiliki cakar"<<endl;}
};
class Harimau:public Hewan {
    public:
        void predator(){
        cout<<"Hewan ini adalah Harimau"<<endl;}
};
class Singa:public Hewan {
    public:
        void predator(){
        cout<<"Hewan ini adalah singa"<<endl;}
};
class Macan:public Hewan {
    public:
        void predator(){
        cout<<"Hewan ini adalah macan"<<endl;}
};
int main () {
    Harimau harimau;
    harimau.predator();
    //harimau.predator();
    harimau.taring();
    harimau.cakar();
cout << endl;

    Singa singa;
    singa.predator();
    //singa.predator();
    singa.taring();
    singa.cakar();

cout << endl;

    Macan macan;
    macan.predator();
    //macan.predator();
    macan.taring();
    macan.cakar();

    return 0;
}
```
# ouput
![Screenshot (25)](https://github.com/DianaFriskaAulia/TugasAlpro/assets/156889167/6855e124-517b-42a4-9689-1fb7a0a85a4a)

# Kesimpulan

Perbedaan output antara dua koding terletak pada bagaimana fungsi predator() dipanggil dari kelas-kelas turunan. 
Pada koding pertama, dipanggil fungsi predator() dari kelas dasar Hewan, menghasilkan output umum "Ini adalah hewan predator" untuk setiap objek.
Sedangkan pada koding kedua, dipanggil fungsi Predator() yang di-override oleh kelas-kelas turunan, menghasilkan output spesifik untuk masing-masing hewan.


