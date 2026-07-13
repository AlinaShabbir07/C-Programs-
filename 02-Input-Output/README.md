# 02- Input Output in C++

Is folder mein C++ ke Basic Input aur Output ke programs hain.

**Topics Covered:**
- `cout` - Output print karna
- `cin` - Input lena 
- `endl` - New line
- Basic programs like Hello World, Name input, Sum

**Program**
- #include <iostream>
using namespace std;

int main()
{
    string name;
    int age;

    cout << "Enter your name: ";
    cin >> name;

    cout << "Enter your age: ";
    cin >> age;

    cout << "\n----- Output -----" << endl;
    cout << "Name: " << name << endl;
    cout << "Age: " << age << endl;

    return 0;
}

**Output**
Enter your name: Alina
Enter your age: 19

----- Output -----
Name: Alina
Age: 19

**Language:** C++
