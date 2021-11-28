#include <iostream>
#include <array>
#include <random>
#include <exception>
using namespace std;
int main()
{
    srand(12);
    array <int,1000> randomArry;
    for(int i=0; i <1000; i++)
    {
        randomArry[i]= rand()%50;
        cout<<randomArry[i]<< " ,";
    }
}
