#include <iostream>
#include <string>
using namespace std;

int main()
{
string in;
cin >> in;
int s = in.length();

int a = 0;
int b = 0;
int c = 0;

for (int x = 0; x < s; x ++){
   if (in[x]== '1'){
    a++;
   }
   if (in[x]== '2'){
    b++;
   }
   if (in[x]== '3'){
    c++;
   }
}

while (a > 0){
    cout << '1';
    a--;
    if(a+b+c > 0){
        cout << '+';
    }
}
while (b > 0){
    cout << '2';
    b--;
    if(a+b+c > 0){
        cout << '+';
    }
}
while (c > 0){
    cout << '3';
    c--;
    if(a+b+c > 0){
        cout << '+';
    }
}