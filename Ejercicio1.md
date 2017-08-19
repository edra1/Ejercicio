#include <iostream>
using namespace std;
int main()
{
    float sueldo;
        cout<<"Ingresa tu sueldo actual ";
        cin>>sueldo;

            if(sueldo>=0 && sueldo <=1000)
                sueldo=sueldo+ (sueldo*18 /100);
            else if (sueldo >=1001 && sueldo<=1100)
                sueldo=sueldo+ (sueldo*15/100);
            else if (sueldo>=1101 && sueldo<=1200)
                sueldo=sueldo+ (sueldo*12/100);
            else if (sueldo>=1201 && sueldo<=1300)
                sueldo=sueldo+ (sueldo*10/100);
            else if (sueldo>=1301)
                sueldo=sueldo+ (sueldo*8/100);
    cout<<"\nTu nuevo sueldo es : "<<sueldo;
        return 0;
}
