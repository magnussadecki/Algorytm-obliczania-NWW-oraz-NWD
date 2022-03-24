# Algorytm-obliczania-NWW-oraz-NWD
#include <iostream>

int main()
{

    int a, b;
    std::cout << "Podaj liczbe a: ";
    std::cin >> a;
    std::cout << "Podaj liczbe b: ";
    std::cin >> b;
    //zapamietaj
    int azap = a, bzap = b;
    while (a != b)
    {
        if (b > a)
            b -= a;
        else
            a -= b;
    }
    std::cout << "NDW = " << a << std::endl;
    std::cout << "NWW = " << (azap * bzap) / a;

    return 0;
}
  
