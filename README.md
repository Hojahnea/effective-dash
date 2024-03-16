# effective-dash
Hello world! Code that I worked on. 
// Square.cpp : This file contains the 'main' function. Program execution begins and ends there.
// A program that asks the user to enter a character and an integer no greater than 16 

#include <iostream>
using namespace std;
int main()
{
    // Declare variables used in the program 
    int number, col, row;
    char holder;

    // Prompt user to enter a number below the maximum integer given
    cout << "Enter a positive integer no greater than 16: " << " " << endl;
    cin >> number;

    //Prompt the user to enter a character
    cout << "Enter a character : " << " " << endl;
    cin >> holder;

    // If the numbers entered by the user are true then display the results 
    if (number < 1)
        number = 1;
    else if (number > 16)
        number = 16;
    for (int row = 0; row < number; row++)
    {
        for ( col = 0; col < number; col++)
        {
            cout << holder;
        }
        cout << endl;
    }
    system("pause");

    // Terminate program
    return 0;
}

