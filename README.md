# Basic String Input Program

A simple C++ program demonstrating basic string input and output operations using `cin`.

## Description

This program shows how to read strings from the user using `cin` and display them back to the console. It demonstrates basic string handling in C++ with a focus on `cin` usage for input.

### Key Features
- String input using `cin`
- Basic console I/O
- Simple user interaction

## Code Structure

```cpp
#include <iostream>
using namespace std;

int main()
{
    char str[100];
    cout << "Enter a String: ";
    cin >> str;
    cout << "You Entered: " << str << endl;
    
    cout << "\nEnter another String: ";
    cin >> str;
    cout << "You Entered: " << str << endl;
    
    return 0;
}
