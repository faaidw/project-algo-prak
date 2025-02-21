#include <iostream>
#include <string>

using namespace std;
struct daftar menu
{
varchar makanan;//  dibuat array
varchar minuman;// dibuat array
};

struct harga_menu {
    int makanan1;
    int minuman2;
}

// Fungsi untuk login
int main() {
    string username, password;
    string validUsername = "faaid";  // Ganti dengan nama panggilan
    string validPassword = "123230204";  // Ganti dengan NIM

    // Tampilan login
    cout << "=====================================" << endl;
    cout << "|          Kasir Warmindo           |" << endl;
    cout << "=====================================" << endl;
    cout << "Username : ";
    cin >> username;
    cout << "Password : ";
    cin >> password;

    // Validasi login
    if (username == validUsername && password == validPassword) {
        cout << "Login berhasil!" << endl;
    } else {
        cout << "Login gagal! Username atau password salah." << endl;
    }

    return 0;
}
