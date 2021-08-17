## Data Types in Dart
1. Numbers (Integers and Double)
  Integer is represented with Int Keyword. Example: 1, 2, 3, 5 , etc. 
  Double is represented with double keyword. Examples: 1.2, 3.55, etc
  
  Declaring the Integer Data Type in Dart:
  Int age = 5; 
  Int size = 4;
  
  Declaring the Double Data Type in Dart:
  double size = 5.8; 
  double Averageage= 4.9;
  
## Declaring Variables in Dart
Variables is declared in Dart using the var keyword. 
Example: var percentage = 50.5; 
         var age = 10;
         var name = Favour;

2. Strings
    Strings are declared in Dart with the String Keyword. 
    Example: 
    string name = Favour; 
    
3. Boolean
    Boolean is also a Data type in Dart. Boolean is declared using the bool keyword. 
    Booleans have only two values which are True and False
    Example: 
    bool isLogin = true; 
    
4. Lists
   A list is an ordered group of objects. We have two types of lists in Dart Programming Language: 
   Fixed Length List: A fixed list does not grow or shrink during runtime. That is you can't add or remove from the initial declared list size
   Declaring a Fixed Length List in Dart:
  var fixedLengthList = List<int>.filled(4, 0);
  fixedLengthList [0] = 3;
  fixedLengthList [1] = 3;
  fixedLengthList [2] = 3;
  fixedLengthList [3] = 3;
  
  //This is a fixed list with only 4 contents, starting from 0. Adding another list item to this list will throw an exception error. 
  The current size of the above list is 5, which was what we declared. Adding or removing to the list size will throw an Exception error
  
   Growable List: A growale list can grow or shrink during runtime. That is you can add or remove from the initial declared list size
   
   Declaring a Growable List in Dart: 
   var subject = [1,2,3,4]; //List containing specified values
   var subject = new List(); // List of size zero
   subject.add(15);
   subject.add(20);

   PS: The list index starts from 0. 
5. Maps - The map object is a simple key or value type. It can have any Data type. It's a dynmaic collection. That is it can grow and shrink at runtime. A Map can be declared in two ways: 
- Using Map Literals
- Using a Map Constructor

Declaring a map using map literals: 
var user_details = {'Username':'Dgreat', 'Password':'pass1234'};

To add values to the map literals at runtime: 
    user_details['age'] = '16';
    
Declaing a map using a map constuctor: 
To do this we have two steps:

1. Declare the map
2. Initialize the map

var subject = new Map {};
    subject['Maths'] = '45'; 
    subject['Chemistry'] = '25'; 
Note: A map value can be an object including NON. 
6. Runes
7. Symbols
