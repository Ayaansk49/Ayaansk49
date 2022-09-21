#include<iostream>
using namespace std;
int main()
  {
     int num,chance,special=12;
     string name;
  
    cout<<"Enter your name:";
    getline(cin,name);
    
  for(int i=0;i<3;i++)
   {
      cout<<"Enter your number:"
      cin>>num;}
  
  if(chance == special)
  {
     cout<<"Congrats you have won the game....";}
  
  else
  {
     cout<<"Sorry you have lost the game ....";
  }
  
  return 0;
  
  }
