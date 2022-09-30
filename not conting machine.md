#include <iostream>
using namespace std;

int main() {
    #include <iostream>
using namespace std;

int main() {
    int a,c,d,e,f;
    
    cout<<"Enter the value of a"<<endl;
    cin >> a;
    
    int num = 1;
    cout<<"Enter the operation you want to perform"<<endl;
    
    
   c = a/100 ;
   d =  a - c*100  ;
   e =  d/20  ;
   f =  d - 20 ;
    switch(num){
        case 1: cout<<"100 rupe note requre : " <<c << endl;
        case 2: cout<<"20 rupe note requre : " <<e <<endl;
        case 3: cout<<"1 rupe note requre : " <<f <<endl;
        
    }

    return 0;
}
