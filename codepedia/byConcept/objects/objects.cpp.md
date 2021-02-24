# Objects in C++

In C++, an object is an instance of a class that encapsulates data and functionality pertaining to that data.


Suppose we have already created a class named _MyClass_, so now we can use this to create objects.

To create an object of MyClass, specify the class name, followed by the object name.

```cpp
City nyc;      // Used the City class to create an object named nyc
City shanghai; // Used the City class to create an object named shanghai
```

To access the class attributes, use the dot syntax (`.`) on the object:

Create an object called "myObj" and access the attributes:

```cpp
class MyClass {       
  public:
    int myNum;
    string myString;
};

int main() {
  // Create an object of MyClass
  MyClass myObj;

  // Access attributes and set values
  myObj.myNum = 15; 
  myObj.myString = "Some text";

  // Print attribute values
  cout << myObj.myNum << "\n";
  cout << myObj.myString;

  return 0;
}
```