//This program randomly generates you a cool name to use on the internet.
//Have fun.

#include <string>
#include <iostream>
#include <stdlib.h>
using namespace std;

int main() {
  // Create variable for user's name
  string userName;
  string newFirstName;
  string newLastName;
  // Creates two arrays with first and last names.
  string firstName[] = { "Zero", "Black", "Acid", "Dark", "Perfect"};
  string lastName[] = {"Cool", "Hacker", "Burn", "Cracker"};
  
  cout << "Please input your name.\n"; //Prompts user for their name.
  cin >> userName;
  cout << "Your name is " << userName << ".\n";

  //Initialize random seed
  srand (time(NULL));
  //Create 2 random numbers for the users name
  int randNum1 = rand() % 5;
  cout << randNum1 << " ";
  int randNum2 = rand() % 4;
  cout << randNum2;
  
  // Now to create the user's cyberpunk name.
  newFirstName = firstName[randNum1];
  newLastName = lastName[randNum2];
  
  cout << "From now on you will be known as " << newFirstName << " " << newLastName << ".\n"; //prints the users new name.
}
