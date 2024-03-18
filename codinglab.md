# menghitung luas dan keliling persegi panjang

```c++
#include <iostream>

int main() {
    float luas,keliling,panjang,lebar;

    std::cout << "Menghitung Luas dan Keliling Persegi Panjang" << std::endl;
    
    std::cout << "Masukan Panjang: ";
    std::cin >> panjang;
    std::cout << "Masukan Lebar: ";
    std::cin >> lebar;
    luas=panjang*lebar;
    keliling=2*(panjang+lebar);

    std::cout<<"Luas Persegi Panjang: "<<luas<< std::endl;
    std::cout<<"Keliling Persegi Panjang: "<<keliling<< std::endl;

    return 0;

}
```
# capture hasil running
![Screenshot (3)](https://github.com/DianaFriskaAulia/TugasAlpro/assets/156889167/6323203a-8349-4ebb-9e7b-1fb3743404a8)
