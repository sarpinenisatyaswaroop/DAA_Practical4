#include <iostream>
using namespace std;

long long factorialIterative(int n)
{
    long long fact = 1;

    for (int i = 1; i <= n; i++)
    {
        fact = fact * i;
    }

    return fact;
}

long long factorialRecursive(int n)
{
    if (n == 0 || n == 1)
        return 1;

    return n * factorialRecursive(n - 1);
}

int main()
{
    int n;

    cout << "Enter a number: ";
    cin >> n;

    if (n < 0)
    {
        cout << "Factorial is not defined for negative numbers.";
    }
    else
    {
        cout << "Factorial using Iterative Method: "
             << factorialIterative(n) << endl;

        cout << "Factorial using Recursive Method: "
             << factorialRecursive(n) << endl;
    }

    return 0;
}
