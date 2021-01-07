#include <iostream>
int main() {
    double weight;
    int num;

    std::cout << "Enter your weight on Planet Earth: ";
    std::cin >> weight;
    std::cout << "\n";
    std::cout << "1. Mercury   2. Venus   3. Mars   4. Jupiter  5. Saturn   6. Uranus   7. Neptune\n\n";
    std::cout << "Enter a number to choose a planet: ";
    std::cin >> num;
    std::cout <<"\n\n";
    std::cout << "#   Planet        Relative Gravity\n";
    switch (num) {
    case 1:
        std::cout << "1   Mercury       0.38\n";
        break;

    case 2:
        std::cout << "2   Venus         0.91\n";
        break;

    case 3:
        std::cout << "3   Mars          0.38\n";
        break;

    case 4:
        std::cout << "4   Jupiter       2.34\n";
        break;

    case 5:
        std::cout << "5   Saturn        1.06\n";
        break;

    case 6:
        std::cout << "6   Uranus        0.92\n";
        break;

    case 7:
        std::cout << "7   Neptune       1.19\n";
        break;

    default:
        std::cout << "Invalid\n";
        std::cout << "Choose a number between 1 and 7 next time buddy!\n";
        break;
    }

    return 0;
}
