# bilgisayar_programlama-2
#include <iostream>
#include <cmath> // pow() ve sqrt() fonksiyonları için

using namespace std;

int main() {
    double x1, y1, x2, y2;
    double fark_x, fark_y, toplam, mesafe;
    cout << "Birinci noktanin x koordinatini girin (x1): ";
    cin >> x1;
    cout << "Birinci noktanin y koordinatini girin (y1): ";
    cin >> y1;
    cout << "Ikinci noktanin x koordinatini girin (x2): ";
    cin >> x2;
    cout << "Ikinci noktanin y koordinatini girin (y2): ";
    cin >> y2;
    fark_x = x2 - x1;
    fark_y = y2 - y1;
    toplam = pow(fark_x, 2) + pow(fark_y, 2);

    mesafe = sqrt(toplam);

    cout << "\nIki nokta arasindaki mesafe (d): " << mesafe << endl;

    return 0;
}
