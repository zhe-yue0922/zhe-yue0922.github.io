title: "Temperature Converter" excerpt: "A simple temperature converter written in C++." collection: portfolio date: 2023-10-27 header: teaser: https://www.google.com/search?q=https://placehold.co/400x200/4CAF50/ffffff%3Ftext%3DSTEM%2BProject
Project Description

This project is a basic command-line tool that converts Celsius to Fahrenheit and vice versa. It was a great way for me to practice fundamental C++ syntax and learn about core concepts like variables, conditional statements, and user input/output.

Technologies and Concepts

Programming Language: C++

Development Environment: Visual Studio Code

Core Concepts:

Variables and data types

Conditional statements (if-else)

User input (cin) and output (cout)

Project Code

Here is a simple C++ code snippet that shows the core logic of the temperature converter.

#include <iostream>

int main() {
    char choice;
    double temp;

    std::cout << "Please select conversion type:" << std::endl;
    std::cout << "1. Celsius to Fahrenheit (C to F)" << std::endl;
    std::cout << "2. Fahrenheit to Celsius (F to C)" << std::endl;
    std::cout << "Enter 1 or 2: ";
    std::cin >> choice;

    std::cout << "Please enter the temperature value: ";
    std::cin >> temp;

    if (choice == '1') {
        double fahrenheit = (temp * 9.0 / 5.0) + 32.0;
        std::cout << "The temperature in Fahrenheit is: " << fahrenheit << " F" << std::endl;
    } else if (choice == '2') {
        double celsius = (temp - 32.0) * 5.0 / 9.0;
        std::cout << "The temperature in Celsius is: " << celsius << " C" << std::endl;
    } else {
        std::cout << "Invalid choice!" << std::endl;
    }

    return 0;
}

My Learning Reflection

Through this project, I was able to strengthen my basic C++ skills and learn how to break down a real-world problem (temperature conversion) into simple programming steps. It has given me confidence for my future programming studies.

