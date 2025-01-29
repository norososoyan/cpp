#include <iostream>

int main() {
    double a, b;
    char c;
    std::cin >> a >> c >> b;

    switch (c) {
        case '+':
            std::cout << a + b << std::endl;
            break;
        case '-':
            std::cout << a - b << std::endl;
            break;
        case '*':
            std::cout << a * b << std::endl;
            break;
        case '/':
            if (b != 0)
                std::cout << a / b << std::endl;
            else
                std::cout << "Error: Division by zero" << std::endl;
            break;
        default:
            std::cout << "Error: Invalid operator" << std::endl;
    }

    return 0;
}
