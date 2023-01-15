Variables:
    Declare with a data type (e.g. int, double, char) followed by the variable name (e.g. int x; double y; char c;)
    Assign values using the assignment operator (=) (e.g. x = 5; y = 3.14; c = 'a';)

    // Example
    int x = 5;
    double y = 3.14;
    char c = 'a';



Input/Output:
    Use cin to read input and cout to write output (e.g. cin >> x; cout << "x = " << x << endl;)

    // Example
    #include <iostream>
    using namespace std;
    int main() {
        int x;
        cin >> x;
        cout << "x = " << x << endl;
        return 0;
    }



Conditional statements:
    if-else statements: (e.g. if (x > 0) cout << "x is positive"; else cout << "x is non-positive";)
    switch statement: (e.g. switch (c) { case 'a': cout << "c is a"; break; case 'b': cout << "c is b"; break; default: cout << "c is neither a nor b"; } )

    // Example
    if (x > 0) 
        cout << "x is positive"; 
    else 
        cout << "x is non-positive";

    switch (c) {
        case 'a': 
            cout << "c is a"; 
            break;
        case 'b': 
            cout << "c is b"; 
            break;
        default: 
            cout << "c is neither a nor b";
    }



Loops:
    for loops: (e.g. for (int i = 0; i < 10; i++) cout << i << " ";)
    while loops: (e.g. while (x > 0) { x--; cout << x << " "; } )
    do-while loops: (e.g. do { x++; cout << x << " "; } while (x < 10); )

    // Example
    for (int i = 0; i < 10; i++) 
        cout << i << " ";

    while (x > 0) { 
        x--; 
        cout << x << " "; 
    }

    do { 
        x++; 
        cout << x << " "; 
    } while (x < 10);



Functions:
    Define with a return type, name, and parameters (if any) (e.g. int add(int x, int y) { return x + y; })
    Call with the function name and arguments (e.g. int sum = add(3, 4);)

    // Example
    int add(int x, int y) {
    return x + y;
    }

    int main() {
        int sum = add(3, 4);
        cout << "sum = " << sum << endl;
        return 0;
    }



Arrays:
    Declare with a data type, name, and size (e.g. int a[10];)
    Access elements using the array name and an index in square brackets (e.g. a[0] = 5; cout << a[1];)

    // Example
    int a[10];
    a[0] = 5;
    cout << a[1];



Classes and Objects:
    Define a class with data members (variables) and member functions (methods)
    Create an object of a class using the class name and the keyword "new"
    Access class members using the dot operator (.) or the arrow operator (->)

    // Example
    class MyClass {
        public:
            int x;
            void setX(int x) { this->x = x; }
            int getX() { return x; }
    };

    int main() {
        MyClass obj;
        obj.setX(5);
        cout << obj.getX() << endl;
        return 0;
    }



Pointers:
    Declare a pointer variable using the asterisk (*) operator
    Assign the address of a variable to a pointer using the ampersand (&) operator
    Access the value at a pointer address using the dereference operator (*)

    // Example
    int x = 5;
    int* p = &x;
    cout << *p << endl;



Templates:
    Define a template class or function with the keyword "template"
    Use the template with different data types by specifying the type in angle brackets (<>)

    // Example
    template <typename T>
    T add(T x, T y) {
        return x + y;
    }

    int main() {
        int x = 5, y = 3;
        double a = 3.14, b = 2.71;
        cout << add(x, y) << endl;
        cout << add(a, b) << endl;
        return 0;
    } 



Operator Overloading:
    Overload operators for custom classes by defining member functions with the keyword "operator"

    // Example
    class MyComplex {
        public:
            double re, im;
            MyComplex operator + (MyComplex b) {
                MyComplex res;
                res.re = re + b.re;
                res.im = im + b.im;
                return res;
            }
    };

    int main() {
        MyComplex c1, c2, c3;
        c1.re = 1; c1.im = 2;
        c2.re = 3; c2.im = 4;
        c3 = c1 + c2;
        cout << c3.re << " + " << c3.im << "i" << endl;
        return 0;
    }



Inheritance:
    Define a class that inherits from another class using the colon (:) operator and the keyword "public" or "private"

    // Example
    class Shape {
        public:
            double area() { return 0; }
    };

    class Circle : public Shape {
        public:
            double radius;
            double area() { return 3.14 * radius * radius; }
    };

    int main() {
        Circle c;
        c.radius = 5;
        cout << "Area of circle: " << c.area() << endl;
        return 0;
    }



Exception Handling:
    Use try-catch blocks to handle exceptions thrown by a function or method
    Throw exceptions using the keyword "throw"

    // Example
    int divide(int x, int y) {
        if (y == 0) 
            throw "Division by zero";
        return x / y;
    }

    int main() {
        try {
            int x = 5, y = 0;
            cout << divide(x, y) << endl;
        } catch (const char* msg) {
            cerr << msg << endl;
        }
        return 0;
    }



Namespaces:
    Use namespaces to organize code and prevent naming conflicts

    // Example
    namespace MyNamespace {
        int x = 5;
    }

    int main() {
        cout << MyNamespace::x << endl;
        return 0;
    }



Standard Template Library (STL):
    Use STL containers such as vector, list, and map to store data
    Use STL algorithms such as sort, find, and for_each to manipulate data

    // Example
    #include <vector>
    #include <algorithm>
    using namespace std;

    int main() {
        vector<int> v = {3, 1, 4, 1, 5, 9};
        sort(v.begin(), v.end());
        for (int x : v)
            cout << x << " ";
        cout << endl;
        return 0;
    }