#include<iostream>
#include<conio.h>
using namespace std;
void Luaspersegi(){
	int panjang,lebar;
	cout<<"Masukkan Panjang : ";
	cin>>panjang;
	cout<<"Masukkan Lebar : ";
	cin>>lebar;
	cout<<"Luas Persegi "<<panjang*lebar;
}

int main (){
	Luaspersegi();
	getch();
}
