# menghitung-dan-cetak-jumlah-uang
Test technical dumbways
#include<conio.h>
#include<iostream>
using namespace std;

main()
{
	cout<<"        ================================="<<endl;
	cout<<"         Wahyu Noer Rahmat               "<<endl;
	cout<<"        ================================="<<endl;
	
	 int bunga, jumlahuang, total;
	 cout<<"Masukan Uang yang akan ditabung : ";cin>>jumlahuang;
	 cout<<"________________________________________________________________________"<<endl;
	 int i=1;
	 while(i<=12)
	 
	 {
	 	cout<<"Tabungan bulan ke : "<<i;
	 	bunga=jumlahuang*2.5;
	 	cout<<"    Bunga : "<<bunga;
	 	jumlahuang=jumlahuang+bunga;
	 	i++;
	 	cout<<"    Saldo : "<<jumlahuang<<endl;
	 }
	 cout<<"________________________________________________________________________"<<endl;
	 total=jumlahuang;
	 cout<<"                    Jumlah Tabungan Anda pada bulan 12 : "<<total;
	 cout<<"\n";
	 getch() ;
}
