coding

```c++
#include <iostream>
using namespace std;

int main() { 
    int matriks_a[2][2] = {{1, 2}, {3, 4}}; 
    int matriks_b[2][2] = {{5, 6}, {7, 8}}; 

    // Menampilkan matriks A
    cout << "Matriks A = " << endl;
    for (int i = 0; i < 2; ++i) {
        for (int j = 0; j < 2; ++j) {
            cout << matriks_a[i][j] << " ";
        }
        cout << endl;
    }
    cout << endl;

    // Menampilkan matriks B
    cout << "Matriks B = " << endl;
    for (int i = 0; i < 2; ++i) {
        for (int j = 0; j < 2; ++j) {
            cout << matriks_b[i][j] << " ";
        }
        cout << endl;
    }
    cout << endl;

    // Menampilkan hasil penjumlahan matriks A dan B
    cout << "Hasil penjumlahan matriks A dan B adalah = " << endl;
    for (int i = 0; i < 2; ++i) {
        for (int j = 0; j < 2; ++j) {
            cout << matriks_a[i][j] + matriks_b[i][j] << " ";
        }
        cout << endl;
    }

    return 0;   
}
```
# capture hasil running
![Screenshot (4)](https://github.com/DianaFriskaAulia/TugasAlpro/assets/156889167/26b95b96-1c62-4d3d-99aa-c4614c484a3f)
