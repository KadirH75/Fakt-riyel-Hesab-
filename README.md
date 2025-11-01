#include <iostream>
using namespace std;
int main()
{
short int i, f=1, n;
 cout << "faktöriyelini istediğiniz sayıyı giriniz :";
   cin >> n;
     for (i = 1; i <= n; i++) {
     f = f * i;
    }
       cout << n << "! = " << f;
return 0;
}
