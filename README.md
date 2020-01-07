# StringInterpolation
how to make string interpolation
void main (){


// String Interpolation

  String name = "Abdo";
  String message ="my name is “ + name";
//in dart you can use “my name is  $name”; instead
  String message1 = "my name is $name";
  String message2 = "my name is ${name}";


  print(message);

  print (message1);

  print (message2);
/* all of them will have the same output in console but the most common used one of them is the one with curly brackets */

  print ("the number of characters in  String abdo is ${name.length}");
//console output will be (the number of characters in string abdo is 4)
// we can also use String interpolation like this
  int a = 10;
  int b = 20;

  print ("the sum of a and b is ${a+b}");
// console output will be (the sum of a and b is 30)

  print ("the area of rectangle with length of $a and breadth $b is ${a * b}");
//console output will be ( the are of rectangle with length of 10 and breadth 20 is 200 )

}
