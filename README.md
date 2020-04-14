#include <iostream>
using namespace std;
int main ()
{
     int paket, jumlah ;
     cout << " ***********************/n";
     cout << "| Program Kasir Barokah |" <<endl;
     cout << " ***********************/n";
     cout << " \n";
     cout << " 1. setrika             ( Biaya Rp 2.500,00/kg)" <<endl;
     cout << " 2. cuci basah          ( Biaya Rp 2.000,00/kg)" <<endl;
     cout << " 3. cuci kering         ( Biaya Rp 2.500,00/kg)" <<endl;
     cout << " 4. cuci kering setrika ( Biaya Rp 4.000,00/kg)" <<endl;
     cout << " \n";
     cout << " _____________________________________________________\n";
     cout<<" \n";

     cout << " Masukkan pilihan paket : ";
     cin>> paket ;
     if (paket==1)
     {
         cout << " 1. setrika             ( Biaya Rp 2.500,00/kg)"<<endl;
         cout << " Masukkan jumlah (kg): ";
         cin>>jumlah;
         cout<<" ___________________________________________________\n";
         cout<<" \n";
         cout << " Biaya yang harus dibayar : "<<jumlah*2500;
     }
     else if (paket==2)
     {
         cout << " 2. cuci basah          ( Biaya Rp 2.000,00/kg)"<<endl;
         cout << " Masukkan jumlah (kg) : ";
         cin>>jumlah;
         cout<<" ___________________________________________________\n";
         cout<<" \n";
         cout << " Biaya yang harus dibayar : "<<jumlah*2000;
     }
     else if (paket==3)
     {
         cout << " 3. cuci kering         ( Biaya Rp 2.500,00/kg)"<<endl;
         cout << " Masukkan jumlah (kg) : ";
         cin>>jumlah;
         cout<<" ___________________________________________________\n";
         cout<<" \n";
         cout << " Biaya yang harus dibayar : "<<jumlah*2500;
     }
     else if (paket==4)
     {
         cout << " 4. cuci kering setrika ( Biaya Rp 4.000,00/kg)"<<endl;
         cout << " Masukkan jumlah (kg) : ";
         cin>>jumlah;
         cout<<" ___________________________________________________\n";
         cout<<" \n";
         cout << " Biaya yang harus dibayar : "<<jumlah*4000;
     }
     else {
         cout << " Pilihan yang anda inginkan tidak ada ";

     }
     cout<<" \n";
     cout<<" \n";
     cout<<" ______________________________________________________\n";
     cout<<" \n";
     cout << " TERIMAKASIH KAMI TUNGGU KEDATANGANNYA ANDA BERIKUTNYA ";
     
}
