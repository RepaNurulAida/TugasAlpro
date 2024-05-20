#Robot
'''

#include <iostream>
using namespace std;

// Deklarasi kelas
class robot {
public:
    string nama;
    int umur;
    string mbti;

    // Metode untuk menampilkan informasi
    void perkenalandiri() {
        cout << "Nama: " << nama << endl;
        cout << "Umur: " << umur << endl;
        cout << "MBTI: " << mbti << endl;
    
    }
    
};

int main() {
    // Membuat objek dari kelas Manusia
    robot r1;
    robot r2;

    // Memberi nilai atribut objek
    r1.nama = "Repa";
    r1.umur = 20;
    r1.mbti = "istj";

    r2.nama = "Nurul";
    r2.umur = 15;
    r2.mbti = "istj";

    // Memanggil metode untuk menampilkan informasi
    r1.perkenalandiri();
    r2.perkenalandiri();

    return 0;
}

'''
output
![Screenshot (54)](https://github.com/RepaNurulAida/TugasAlpro/assets/156889243/53b4041b-a200-4a4d-abc5-fde38d8b4f5b)



#Pakaian
'''

#include <iostream>
using namespace std;

// Deklarasi kelas
class Pakaian {
public:
    string baju;
    string merk;
    int ukuran;
    string bahan;

    // Metode untuk menampilkan informasi
    void tampilkaninfopakaian() {
        cout << "Baju: " << baju << endl;
        cout << "Merk: " << merk << endl;
        cout << "Ukuran: " << ukuran << endl;
        cout << "Bahan: " << bahan << endl;
    }

};

int main() {
    // Membuat objek dari kelas Manusia
    Pakaian p1;
    Pakaian p2;

    // Memberi nilai atribut objek
    p1.baju = "kemeja";
    p1.merk = "uniqlo";
    p1.ukuran = 22 ;
    p1.bahan = "kain microfiber";

    p2.baju = "kaos";
    p2.merk = "oxprey";
    p2.ukuran = 23 ;
    p2.bahan = "cotton combed";


    // Memanggil metode untuk menampilkan informasi
    p1.tampilkaninfopakaian();
    p2.tampilkaninfopakaian();

    return 0;
}

'''

output
```
![Screenshot (55)](https://github.com/RepaNurulAida/TugasAlpro/assets/156889243/53871a0d-8f0a-4d1a-aaa1-53bd7077d32b)



