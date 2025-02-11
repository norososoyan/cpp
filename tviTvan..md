#include <iostream>

int main() {
    int num, sum = 0;
    std::cout << "Մուտքագրեք թիվը: ";
    std::cin >> num;
    
    while (num > 0) {
        sum += num % 10;
        num /= 10;
    }
    
    std::cout << "Թվանշանների գումարը: " << sum << std::endl;
    return 0;
}
