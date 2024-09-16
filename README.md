#include <iostream>

int main() {
    int x = 10;
    int y = 3;
    double z = static_cast<double>(x) / y; // Cast x to double to ensure floating-point division
    std::cout << z << std::endl; // Output the result
    return 0;
}

//To ensure the result of the division is a double value in C++, I needed to make sure that at least 
//one of the operands is a double. In this code, both the x and y are a type of integer so performing (x/y) will 
//result in an integer division. To obtain a double result, you need to cast one or both of the integers to double 
//before performing the division.
