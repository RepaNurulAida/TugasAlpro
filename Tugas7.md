## coding 
```c++
#include <iostream>
using namespace std;

// Class Kalkulator untuk melakukan operasi matematika sederhana
class Kalkulator {
public:
    // Metode untuk melakukan penjumlahan
    int tambah(int a, int b) {
        return a + b;
    }

    // Metode untuk melakukan pengurangan
    int kurang(int a, int b) {
        return a - b;
    }

    // Metode untuk melakukan perkalian
    int kali(int a, int b) {
        return a * b;
    }

    // Metode untuk melakukan pembagian
    double bagi(int a, int b) {
        return (double) a / b;
    }
};

// Class Penghitung untuk menghitung luas dan keliling persegi
class Penghitung {
public:
    // Metode untuk menghitung luas persegi
    int luasPersegi(int panjang, int lebar) {
        return panjang * lebar;
    }

    // Metode untuk menghitung keliling persegi
    int kelilingPersegi(int panjang, int lebar) {
        return 2 * (panjang + lebar);
    }
};

int main() {
    // Membuat objek dari kelas Kalkulator dan Penghitung
    Kalkulator kalkulator;
    Penghitung penghitung;

    // Melakukan perhitungan menggunakan kalkulator
    int hasilTambah = kalkulator.tambah(5, 3);
    int hasilKurang = kalkulator.kurang(5, 3);
    int hasilKali = kalkulator.kali(5, 3);
    double hasilBagi = kalkulator.bagi(5, 3);

    // Melakukan perhitungan menggunakan penghitung
    int luasPersegi = penghitung.luasPersegi(5, 3);
    int kelilingPersegi = penghitung.kelilingPersegi(5, 3);

    // Menampilkan hasil perhitungan
    cout << "Hasil perhitungan dengan Kalkulator:" << endl;
    cout << "5 + 3 = " << hasilTambah << endl;
    cout << "5 - 3 = " << hasilKurang << endl;
    cout << "5 * 3 = " << hasilKali << endl;
    cout << "5 / 3 = " << hasilBagi << endl;

    cout << "\nHasil perhitungan dengan Penghitung:" << endl;
    cout << "Luas persegi dengan panjang = 5 dan lebar = 3 adalah " << luasPersegi << endl;
    cout << "Keliling persegi dengan panjang = 5 dan lebar = 3 adalah " << kelilingPersegi << endl;

    return 0;
}

```
# output
![output kalkulator](https://github.com/RepaNurulAida/TugasAlpro/assets/156889243/ff2fd8ed-17e7-4679-b0ba-ad02a3138cec)


