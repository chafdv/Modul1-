# <h1 align="center">Laporan Praktikum Modul 1<br> Modul 1 Pengenalan C++ </h1>
<p align="center">Osha Alfida Valyana - 103112430202</p>

Dasar Teori

Bahasa C++ (dibaca *Si plus plus*) adalah bahasa pemrograman yang dikembangkan oleh **Bjarne Stroustrup** pada tahun 1985 sebagai pengembangan dari bahasa C. C++ dikenal dengan fitur **pemrograman berorientasi objek (OOP)** yang membuat program lebih modular, mudah dikelola, dan efisien. Dengan performa tinggi serta kontrol penuh terhadap manajemen memori, C++ banyak digunakan untuk membangun aplikasi kompleks seperti **game, perangkat lunak, dan sistem berkinerja tinggi**. 


GUIDED

SOAL 1

#include <iostream>
#include <string>
using namespace std;

// Definisi struct
struct Mahasiswa {
    string nama;
    string nim;
    float ipk;
};

int main() {

    Mahasiswa mhs1;

    cout << "Masukkan Nama Mahasiswa: ";
    getline(cin, mhs1.nama);
    // cin >> mhs1.nama;
    cout << "Masukkan NIM Mahasiswa : ";
    cin >> mhs1.nim;
    cout << "Masukkan IPK Mahasiswa : ";
    cin >> mhs1.ipk;

    cout << "\n=== Data Mahasiswa ===" << endl;
    cout << "Nama : " << mhs1.nama << endl;
    cout << "NIM  : " << mhs1.nim << endl;
    cout << "IPK  : " << mhs1.ipk << endl;

    return 0;
}
