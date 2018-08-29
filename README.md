# Codigo_clase
DE las clases
#include <iostream>


using namespace std;

int main()
{   int a1,b1,c1,a2,b2,c2,t1,t2,t3;
    cout<<"Ingrese valores del primer ángulo:"<<endl<<"G1: ";
    cin>>a1;
    cout<<"M1: ";
    cin>>b1;
    cout<<"S1: ";
    cin>>c1;
    cout<<"Ingrese valores del segundo ángulo:"<<endl<<"G2: ";
    cin>>a2;
    cout<<"M2: ";
    cin>>b2;
    cout<<"S2: ";
    cin>>c2;
    c1=3600*a1+60*b1+c1;
    c2=3600*a2+60*b2+c2;
    t3=c1+c2;
    t1=t3/3600;
    t3=t3%3600;
    t2=t3/60;
    t3=t3%60;
    cout<<"EL ángulo resultante es: \nG1: "<<t1<<endl<<"M1: "<<t2<<endl<<"S1: "<<t3;
    cin>>c1;

    return 0;
}
