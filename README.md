#include <iostream>
using namespace std;
int main ()
{
     int paket, jumlah ;
     cout << " *************************"<<endl;
     cout << "| LAUNDRY WANGI SEMRIWING |" <<endl;
     cout << " *************************"<<endl;
     cout << " "<<endl;
     cout << " 1. setrika             ( Biaya Rp 2.500,00/kg)" <<endl;
     cout << " 2. cuci basah          ( Biaya Rp 2.000,00/kg)" <<endl;
     cout << " 3. cuci kering         ( Biaya Rp 2.500,00/kg)" <<endl;
     cout << " 4. cuci kering setrika ( Biaya Rp 4.000,00/kg)" <<endl;
     cout << " "<<endl;
     cout << " =================================================="<<endl;
     cout<<" "<<endl;

     cout << " Masukkan pilihan paket : ";
     cin>> paket ;
     if (paket==1)
     {
         cout << " 1. setrika             ( Biaya Rp 2.500,00/kg)"<<endl;
         cout << " Masukkan jumlah (kg): ";
         cin>>jumlah;
         cout<<" ___________________________________________________"<<endl;
         cout<<" "<<endl;
         cout << " Biaya yang harus dibayar : "<<jumlah*2500;
     }
     else if (paket==2)
     {
         cout << " 2. cuci basah          ( Biaya Rp 2.000,00/kg)"<<endl;
         cout << " Masukkan jumlah (kg) : ";
         cin>>jumlah;
         cout<<" ___________________________________________________"<<endl;
         cout<<" "<<endl;
         cout << " Biaya yang harus dibayar : "<<jumlah*2000;
     }
     else if (paket==3)
     {
         cout << " 3. cuci kering         ( Biaya Rp 2.500,00/kg)"<<endl;
         cout << " Masukkan jumlah (kg) : ";
         cin>>jumlah;
         cout<<" __________________________________________________"<<endl;
         cout<<" "<<endl;
         cout << " Biaya yang harus dibayar : "<<jumlah*2500;
     }
     else if (paket==4)
     {
         cout << " 4. cuci kering setrika ( Biaya Rp 4.000,00/kg)"<<endl;
         cout << " Masukkan jumlah (kg) : ";
         cin>>jumlah;
         cout<<" __________________________________________________"<<endl;
         cout<<" "<<endl;
         cout << " Biaya yang harus dibayar : "<<jumlah*4000;
     }
     else {
         cout << " Pilihan yang anda inginkan tidak ada ";

     }
     cout<<" "<<endl;
     cout<<" "<<endl;
     cout<<" ===================================================="<<endl;
     cout<<" "<<endl;
     cout << " TERIMAKASIH KAMI TUNGGU KEDATANGAN ANDA SELANJUTNYA ";
     
}
