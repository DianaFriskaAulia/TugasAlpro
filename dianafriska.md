# pratikum 1
```
#include <iostream>
#include <string>
using namespace std;

class mahasiswa {
    private:
      int nrp;
};

 
class fakultas {
    public:
      int kode;
};

int main() {
    // mahasiswa mhs
    fakultas fkl;
    // mhs.nrp = 12345
    fkl.kode = 22;
    // std::cout <<"NRP"<<mhs.nrp<<
    cout <<"kode : "<<fkl.kode<<endl;

    return 0;
}
```
# output
![Screenshot (19)](https://github.com/DianaFriskaAulia/TugasAlpro/assets/156889167/bdbe4dad-691d-44f6-b142-3934bdbdbc55)

# pratikum 2
```
#include <iostream>
#include <string>
using namespace std;

class mahasiswa {
    private:
      int nrp;

    public:
      // Getter untuk mendapatkan nilai nrp
      int getNrp() {
          return nrp;
      }

      // Setter untuk mengatur nilai nrp (jika diperlukan)
      void setNrp(int a) {
          nrp = a;
      }
};
 
class fakultas {
    public:
      int kode;
};

int main() {
    mahasiswa mhs;
    fakultas fkl;

    // Mengatur nilai nrp
    mhs.setNrp(12345);
    // Mengatur nilai kode
    fkl.kode = 22;

    // Mengakses dan mencetak nilai nrp
    cout <<"NRP : "<<mhs.getNrp()<<endl;
    cout <<"Kode : "<<fkl.kode<<endl;

    return 0;
}
```
# pratikum 2
```
#include <iostream>
#include <string>
using namespace std;

class mahasiswa {
    private:
      int nrp;

    public:
      // Getter untuk mendapatkan nilai nrp
      int getNrp() {
          return nrp;
      }

      // Setter untuk mengatur nilai nrp (jika diperlukan)
      void setNrp(int a) {
          nrp = a;
      }
};
 
class fakultas {
    public:
      int kode;
};

int main() {
    mahasiswa mhs;
    fakultas fkl;

    // Mengatur nilai nrp
    mhs.setNrp(12345);
    // Mengatur nilai kode
    fkl.kode = 22;

    // Mengakses dan mencetak nilai nrp
    cout <<"NRP : "<<mhs.getNrp()<<endl;
    cout <<"Kode : "<<fkl.kode<<endl;

    return 0;
}
```
# output
![Screenshot (20)](https://github.com/DianaFriskaAulia/TugasAlpro/assets/156889167/94e2cf1c-8b0a-486d-803c-65da90b1f034)
