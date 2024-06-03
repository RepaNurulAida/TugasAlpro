# praktikum 1
```
#include <iostream>
#include <string>

class Mahasiswa {
    private:
        int nrp;
};

class Fakultas {
    public:
      int kode;
};

int main() {
   // Mahasiswa mhs;
    Fakultas fkl; 
   // mhs.nrp = 12345;
    fkl.kode=22;

   // std::cout <<"NRP"<< mhs.nrp << 
    std::cout <<"kode:"<< fkl.kode << std::endl;

    return 0;
}

```
# output
![ss1](https://github.com/RepaNurulAida/TugasAlpro/assets/156889243/c6b7ff96-2763-4099-ba15-fbdebc58efa1)

# praktikum 2
```
#include <iostream>
#include <string>

class Mahasiswa {
    private:
        int nrp;

    public:
        // Getter untuk mendapatkan nilai nrp
        int getNrp() {
            return nrp;
        }

        // Setter untuk mengatur nilai nrp
        void setNrp(int a) {
            nrp = a;
        }
};

class Fakultas {
    public:
      int kode;
};

int main() {
    Mahasiswa mhs;
    Fakultas fkl;

   // Mengatur nilai nrp
    mhs.setNrp(12345);
   // Mengatur nilai kode
    fkl.kode=22;

   // Mengakses dan mencetak nilai nrp 
    std::cout <<"NRP:"<<mhs.getNrp()<<std::endl;
    std::cout <<"kode:"<<fkl.kode<<std::endl;

    return 0;
}

```
# output
![ss2](https://github.com/RepaNurulAida/TugasAlpro/assets/156889243/89d40396-7f3d-4660-aae7-42d759907281)

