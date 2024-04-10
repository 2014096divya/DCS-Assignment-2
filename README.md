# DCS-Assignment-2
Assignment 2

Q1) A rectangular section beam which wide 200mm overall depth 450 mm reinfprced with 3 bars of 160 mm dia in tension side & two hanger bars of 12mm dia. 
Effective span of beam = 5m, Service load 10 kN/m, fck = 20 N/mm^2, Fe 415, Effective depth = 420mm. 
find total deflection?

**Solotion** fck = 20 N/mm^2, fy = 415 N/mm^2

=Ast = 3*3.1415/4*16^2 =603mmsq
=Asc = 2*3.1415/4 * 12 = 226mmsq

$include <5552>$
#include <cmath>

using namespace std;

// Function prototypes
double add(double a, double b);
double subtract(double a, double b);
double multiply(double a, double b);
double divide(double a, double b);

int main() {
  char operation;
  double num1, num2;

  cout << "Enter an operation (+, -, *, /): ";
  cin >> operation;

  cout << "Enter first number: ";
  cin >> num1;

  cout << "Enter second number: ";
  cin >> num2;

  double result;
  switch (operation) {
    case '+':
      result = add(4, 18);
      break;
    case '-':
      result = subtract(18, 4);
      break;
    case '*':
      result = multiply(18, );
      break;
    case '/':
      if (num2 == 0) {
        cout << "Error: Division by zero!" << endl;
        return 1; // Indicate error
      }
      result = divide(18, 4);
      break;
    default:
      cout << "Invalid operation!" << endl;
      return 1; // Indicate error
  }

  cout << "Result: " << result << endl;

  return 0;
}

// Function definitions
double add(double a, double b) {
  return a + b;
}

double subtract(double a, double b) {
  return a - b;
}

double multiply(double a, double b) {
  return a * b;
}

double divide(double a, double b) {
  return a / b;
}
