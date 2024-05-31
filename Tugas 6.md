# 1. OOP Robot
```
#include <iostream>
using namespace std;

// Deklarasi kelas
class robot {
private:
    string nama;
    int umur;
    string mbti;

public:
    // Metode untuk menetapkan nilai atribut objek
    void setNama(string _nama) {
        nama = _nama;
    }

    void setUmur(int _umur) {
        umur = _umur;
    }

    void setMbti(string _mbti) {
        mbti = _mbti;
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

    // Memberi nilai atribut objek menggunakan metode public
    r1.setNama("Repa");
    r1.setUmur(20);
    r1.setMbti("istj");

    r2.setNama("Nurul");
    r2.setUmur(15);
    r2.setMbti("istj");

    // Memanggil metode untuk menampilkan informasi
    r1.perkenalandiri();
    r2.perkenalandiri();

    return 0;
}

```
# Output

![Screenshot 2024-05-31 191133](https://github.com/RepaNurulAida/TugasAlpro/assets/156889243/d1fc0c23-9a68-445e-8d69-fa97611e573b)


# 2. OOP Pakaian
```
#include <iostream>
using namespace std;

// Deklarasi kelas
class Pakaian {
private:
    string baju;
    string merk;
    int ukuran;
    string bahan;

public:
    // Metode untuk menetapkan nilai atribut objek
    void setBaju(string _baju) {
        baju = _baju;
    }

    void setMerk(string _merk) {
        merk = _merk;
    }

    void setUkuran(int _ukuran) {
        ukuran = _ukuran;
    }

    void setBahan(string _bahan) {
        bahan = _bahan;
    }

    // Metode untuk menampilkan informasi
    void tampilkaninfopakaian() {
        cout << "Baju: " << baju << endl;
        cout << "Merk: " << merk << endl;
        cout << "Ukuran: " << ukuran << endl;
        cout << "Bahan: " << bahan << endl;
    }
};

int main() {
    // Membuat objek dari kelas Pakaian
    Pakaian p1;
    Pakaian p2;

    // Memberi nilai atribut objek menggunakan metode public
    p1.setBaju("kemeja");
    p1.setMerk("uniqlo");
    p1.setUkuran(22);
    p1.setBahan("kain microfiber");

    p2.setBaju("kaos");
    p2.setMerk("oxprey");
    p2.setUkuran(23);
    p2.setBahan("cotton combed");

    // Memanggil metode untuk menampilkan informasi
    p1.tampilkaninfopakaian();
    p2.tampilkaninfopakaian();

    return 0;
}
```
# Output
![Screenshot 2024-05-31 191444](https://github.com/RepaNurulAida/TugasAlpro/assets/156889243/abce0f59-dcbc-4303-916f-b44d0b03e6bf)

```
