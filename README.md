<<<<<<< HEAD
#include<iostream>
using namespace std;

int fibo(int n)
{
    if(n == 0 || n == 1)
       return n;
    else
       return fibo(n - 2) + fibo(n - 1);
}

int main()
{
    cout<<"\n         FIBONACCI \n\n";
    
    int i, num ;
    
    do
    {
        cout<<"Ingrese un numero entero y positivo: ";
        cin>>num;
        
    } while(num < 0);
    
    cout<<"\nLa serie es: \n\n\t";
    
    for(i=0; i<num; i++)
    {
       if(fibo(i) != 0)
          cout<< ", "; 
        
        cout<< fibo(i);       
    }
    
    system("pause");
    
    return 0;
}
=======
# Posix
Que onda que pez

Hoy vamos a jugar?
>>>>>>> 70f7b912b27fc3e0d09a7db1e8e567261fa93839
