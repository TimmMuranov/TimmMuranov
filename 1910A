#include <iostream>
#include <string>
using namespace std;

int main()
{
    string input;
    int s = 0;
    cin >> s;
    for (int x = 0; x<s; x++){
        cin >> input;

        while(true){
           int str_s = input.length();
           if(input[str_s-1] == '0'){
            input = input.erase(str_s-1, 1);
           }
           str_s = input.length();
           if(input[str_s-1] != '0'){
            input = input.erase(str_s-1, 1);
            cout << input << endl;
            break;
           }
         }
       }
    return 0;
}