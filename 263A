#include <iostream>
using namespace std;
int main()
{
    bool matrix[5][5]={
    {0,0,0,0,0},
    {0,0,0,0,0},
    {0,0,0,0,0},
    {0,0,0,0,0},
    {0,0,0,0,0}};
    
 int result = 0;
    
    for (int x=0; x<5; x++){
        for (int y=0; y<5; y++){
            cin >> matrix[x][y];
        }
    }
    
int m_x = 0; int m_y = 0;
for (int x = 0; x<5; x++){
    for (int y = 0; y<5; y++){
        if(matrix [x][y] != 0){
            m_x = x; m_y = y;
        }
    }
}

for (int x=0; x<2; x++){
    if(m_x < 2){
        m_x++; result++;
    }
    if(m_x > 2){
        m_x--; result++;
    }
    if(m_y < 2){
        m_y++; result++;
    }
    if(m_y > 2){
        m_y--; result++;
    }
}
   
cout << result;

return 0;
}