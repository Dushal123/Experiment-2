🎯 Aim:
To write a C++ program that demonstrates the declaration, initialization, and usage of basic built-in data types such as int, float, double, char, and bool, and to understand how different types of data are handled in C++.

🧠 Theory (Expanded & Detailed):
In C++, data types define the type and size of data a variable can hold. Every variable in a C++ program must be declared with a data type, so the compiler knows:

How much memory to allocate for the variable.

What type of operations can be performed on it.

How the value should be interpreted during program execution.

C++ is a statically typed language, which means the type of every variable must be known at compile time. This allows for type safety and optimized memory usage.

🔹 Categories of Data Types in C++:
C++ supports the following broad categories of data types:

Primitive/Built-in Data Types

Derived Data Types (e.g., arrays, functions, pointers)

User-defined Data Types (e.g., structures, classes, unions)

In this program, we focus on primitive or fundamental data types. These are the building blocks of all data handling in C++.

🔸 Primitive Data Types in Detail:
🔹 1. int (Integer):
Used to store whole numbers (positive or negative).

Commonly used to store values like age, roll number, item count, etc.

Occupies 4 bytes of memory (in most compilers/systems).

Value range: from -2,147,483,648 to 2,147,483,647 (32-bit systems).

Real-world use: Number of products in a store, employee ID, etc.

🔹 2. float (Floating Point):
Stores decimal or fractional numbers with single precision.

Occupies 4 bytes of memory.

Precision up to 6–7 decimal places.

Suitable for applications where approximate values are acceptable.

Real-world use: Measuring height, temperature, ratings, etc.

🔹 3. double (Double Precision Float):
Like float but stores decimal numbers with higher accuracy and range.

Occupies 8 bytes of memory.

Precision up to 15–16 decimal places.

Used where precision is critical, like in scientific calculations or financial applications.

Real-world use: Physics formulas, currency operations, and GPS coordinates.

🔹 4. char (Character):
Stores a single character.

Occupies 1 byte of memory.

Stores letters, digits, or special symbols (enclosed in single quotes like 'A', '9', or '$').

Internally stored using ASCII values (e.g., 'A' = 65).

Real-world use: Grade assignment, gender input ('M'/'F'), menu options.

🔹 5. bool (Boolean):
Stores logical values: either true or false.

Typically occupies 1 byte, but only 1 bit is logically required.

Used in decision-making (conditions, loops, flags).

When printed, true shows as 1, and false as 0.

Real-world use: Is the user logged in? Is the payment complete? etc.

📌 Why Are Data Types Important?
Prevent incorrect data operations (e.g., adding a number to a character).

Optimize memory usage by choosing the right size (e.g., int vs double).

Help the compiler catch errors during compilation.

Improve code readability and maintainability.

Make the program efficient and reliable.

🔬 How This Program Helps You Learn:
This program introduces a practical way to explore:

The declaration and initialization of different data types.

Understanding what kind of data each type stores.

Seeing how values are stored and retrieved.

Recognizing how boolean values are interpreted numerically (true = 1, false = 0).

Realizing the differences in precision between float and double.

It is also a stepping stone toward:

Understanding typecasting and conversions.

Building functions and handling return types.

Working with arrays and structures (which are combinations of data types).

📝 Summary of Data Types:
Data Type	Description	Size (Typical)	Example Value	Use Case Example
int	Whole numbers	4 bytes	20	Age, count
float	Decimal (single precision)	4 bytes	5.9f	Height, rating
double	Decimal (double precision)	8 bytes	65.75	Weight, price, scientific calc
char	Single character	1 byte	'A'	Grade, initial, gender
bool	Logical true/false	1 byte	true	Flags, decisions
