# Study of computer science thorugh c++
# Introduction
I'll use this repository to deeply study c++, starting from the basics of the language up to using it to analyse different areas of computer science. I already have experiences in some programming languages so I will take for granted some basics notions of general programming.

## Hello World!
Yes, pretty boring but let's try to analyze it anyway:
- `#include <iostream>` the include directive is used to include files in the program if the name of the file is surrounded by brackets (<>) the file is probably part of the standard c++ library and the preprocessor will search it in the system directories, if the name is between double quotes ("") then the file is user-defined so the preprocessor will search it in the same directory as the main file.
- `using namespace std;` a namespace is a region of the code where we can create variables, functions, classes, etc..., to acces this elements outside the namespace region it's possible to use the :: operator otherwise the directive "using namespace" will give acces to all the elements declared in the namespace. std is a special namespace that includes a lot of basics c++ identifiers.
- `int main(){}`  pretty straightforward function declaration, each c++ program needs a main function wich will be called on execution. I will analyze functions better further ahead.
- `cout << "Hello World" << endl;` the sentence that prints on console "Hello World", each sentence in c++ must end with ";". Cout and endl are two objects of type "ostream" declared in the iostream header, the first one control the output of the stream buffer the second one add an end of the line character. The << operator is defined in the iostream header, it's called insertion operator and it's a overload of the classic bits shift operator of c++. 
## Types



