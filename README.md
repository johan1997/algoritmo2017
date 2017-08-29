# algoritmo2017
#include "stdafx.h"
#include <iostream>
#include "conio.h"
#include <string>

using namespace std;


void main()
{int longitud,y;
 string palabra,palabra2,p;
 cout<<"ingrese la palabra"<<endl;
 cin>>palabra;
 longitud=palabra.length();
 cout<<"la longitud de la palabra es:"<<longitud<<endl;
 y=palabra.length();
 y=y-1;
 for(int i=0; 1<(longitud/2);i++)
 {
    if (palabra[i]!=palabra[y]);
	y--;

  cout<<"la palabra "<<palabra<<" no es un palindromo"<<endl;
 }
  cout<<"la palabra "<<palabra<<" es un palindromo";
 getch();
}
