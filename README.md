# day_1-C-
A collection of basic C++ programs demonstrating fundamental concepts such as variables, data types, escape sequences, comments, and simple problem-solving.  This repository is part of my journey to mastering programming and building strong foundations in C++.
// 1. Print Basic Info
// Write a C++ program to print:
// Name: YourName
// Age: YourAge 

#include<iostream>

using namespace std;

int main () {
	cout <<"Name = Dhanush"<<endl;
	cout<<"Age = 21" <<endl;

	return 0;
}
2. Using Variables
Create variables for:
name (string)
age (int)
Print them using cout.

#include<iostream>
using namespace std;
int main(){
	string name="Dhanush";
	int Age=21;
	cout<<"name = "<<name<<endl;
	cout<<"Age = "<<Age<<endl;
	return 0;
}

3. Escape Sequence Practice
Print the following exactly using escape sequences:
Hello
    World
    
#include<iostream>
using namespace std;
int main (){
	cout<<"Hello\n\tWorld";
	return 0;
}

4. Quotes Printing
Print this sentence:
He said, "C++ is powerful!"

#include<iostream>
using namespace std;
int main (){
	cout<<"he said,\"C++ is powerfull!";
	return 0;
}

5. Multiple Lines Output
Print:
Welcome to C++
This is your first program 

#include <iostream>
using namespace std;
int main(){
	cout<<"welcome to c++\n this is your program";
	return 0;
}

6. Add Two Numbers
Take two integer variables and print their sum.
Example:
a = 5, b = 3 ? Output: 8

#include<iostream>
using namespace std;
int main (){
	int A=5;
	int B=3;
	cout<< "output = "<<A+B;
	return 0;
}

7. Swap Two Variables
Swap two numbers using a third variable.

#include<iostream>
using namespace std;
int main (){
	int A=10,B=20,C;
	C=A;
	A=B;
	B=C;
	cout<<"A = "<<A<< "B = "<<B;
	return 0;
}

8. Comments Practice
Write a program with:
single-line comment
multi-line comment
Explain what the program does 

#include <iostream>
using namespeace std;
int main (){
	// Single-line Comment
	/* Multi-line Comment 
	Explain what the pragram does 
	*/
	return 0;
}

9. Combine Everything ??
Write a program that:
Uses variables
Uses escape sequences
Uses comments
Output example:
Name: Dhanush
Favorite Language: C++


#include <iostream>
using namespace std;

int main() {
    string name = "Dhanush";
    string language = "C++";
    cout << "Name: " << name << "\n";
    cout << "Favorite Language: " << language;
    return 0;
}

10. ASCII Value
Store a character in a variable and print its ASCII value.
Example:
char ch = 'A';
Output: 65

#include <iostream>
using namespace std;

int main() {
    char ch = 'A';
    cout << "ASCII value: " << int(ch);
    return 0;
}














