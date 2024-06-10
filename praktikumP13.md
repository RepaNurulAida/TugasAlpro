# coding pertama
```c++
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
# Hasil Output
![Screenshot 2024-06-10 080625](https://github.com/RepaNurulAida/TugasAlpro/assets/156889243/28f24fe6-a0f5-4e21-b7ac-9406dd9f4eda)


# coding kedua
```c++
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
        void Predator(){
        cout<<"Hewan ini adalah Harimau"<<endl;}
};
class Singa:public Hewan {
    public:
        void Predator(){
        cout<<"Hewan ini adalah singa"<<endl;}
};
class Macan:public Hewan {
    public:
        void Predator(){
        cout<<"Hewan ini adalah macan"<<endl;}
};
int main () {
    Harimau harimau;
    harimau.Predator();
   // harimau.predator();
    harimau.taring();
    harimau.cakar();
cout << endl;

    Singa singa;
    singa.Predator();
   // singa.predator();
    singa.taring();
    singa.cakar();

cout << endl;

    Macan macan;
    macan.Predator();
  //  macan.predator();
    macan.taring();
    macan.cakar();

    return 0;
}
```
# hasil output
![Screenshot 2024-06-10 081935](https://github.com/RepaNurulAida/TugasAlpro/assets/156889243/9ba95961-7c66-4645-8ce6-6e7c0ccde767)

# Kesimpulan
Perbedaannya terletak pada fungsi predator() yang dipanggil. 
Pada koding pertama, dipanggil fungsi predator() dari kelas dasar, sehingga outputnya sama untuk semua hewan.
Sementara pada koding kedua, dipanggil fungsi Predator() yang merupakan di ubahdari fungsi predator() pada kelas turunan, sehingga outputnya spesifik untuk setiap hewan.
