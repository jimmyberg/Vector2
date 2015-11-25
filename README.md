# 3d Vector c++ libary
Made by Jimmy van den Berg in The Netherlands
18 August 2015

c++ library for 3 dimensional vector calculations

## Example

**main.cpp**
```c++
#include <iostream>
#include "Vector2.hpp"
using namespace std;

int main(void){
    Vector2<double> testVector1(1, 2);
    Vector2<double> testVector2(3, 2);
    cout << "testVector1 = " << testVector1 << endl
    << "testVector2 = " << testVector2 << endl
    << "testVector1 + testVector2 = " << testVector1 + testVector2 << endl
    << "testVector1 - testVector2 = " << testVector1 - testVector2 << endl
    << "testVector1 * testVector2 = " << testVector1 * testVector2 << endl
    << "Vector2<double>::dotProduct(testVector1, testVector2) = " << Vector2<double>::dotProduct(testVector1, testVector2) << endl;

    cout << "Press enter to exit." << endl;
    cin.get();
    return 1;
}
```
**output**
```
testVector1 = {1,2}
testVector2 = {3,2}
testVector2 + testVector2 = {4,4}
testVector2 - testVector2 = {-2,0}
testVector2 * testVector2 = {3,4}
Vector2<double>::dotProduct(testVector1, testVector2) = 7
Press enter to exit.
```
