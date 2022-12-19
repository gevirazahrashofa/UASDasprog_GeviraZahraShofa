# UASDasprog_GeviraZahraShofa

<br> Mata Kuliah : Dasar Pemrograman
<br> Nama : Gevira Zahra Shofa
<br> NIM : 1227050050
<br> Jurusan : [Teknik Informatika](http://if.uinsgd.ac.id/) [UIN Sunan Gunung Djati Bandung] (https://uinsgd.ac.id/


# Deskripsi umum

Matriks merupakan kumpulan-kumpulan bilangan yang disusun secara baris (vertikal) dan kolom (horizontal) bisa disebut juga array dua dimensi (multi-dimensional). perkalian matriks memiliki syarat yaitu jumlah kolom matriks pertama sama dengan jumlah baris matriks kedua. Kelebihan program ini adalah jumlah baris dan kolom bisa diinput, jadi bersifat fleksibel, tidak terpaku hanya di bilangan tertentu.


# Source code   
        PROGRAM PERTAMA
        
        #include <iostream>
        using namespace std;

        int main (){

          cout << "......................................"<<endl;
          cout << "Mata Kuliah		: Dasar Pemrograman"<<endl;
          cout << "Nama			: Gevira Zahra Shofa"<<endl;
          cout << "NIM			: 1227050050"<<endl;
          cout << "Jurusan			: Teknik Informatika"<<endl;
          cout << "......................................"<<endl;

          int A [20][20];
          int b, k, i, j;
          cout << "Masukkan jumlah baris : ";
          cin >> b;
          cout << "Masukkan jumlah kolom : ";
          cin >> k;

          for (i=0;i<=b-1;i++) {
            for(j=0;j<=k-1;j++) {
              cout << "Masukkan nilai (" << i << "." << j << ") : ";
              cin >> A [i][j];
            }
          }
          cout << "Nilai yang diinputkan : \n";
          for(int i = 0; i < b; i++){
            for(int j = 0; j < k; j++){
              cout<<A[i][j]<<"\t";
            }
            cout<<endl;
          }

              }
              
        PROGRAM KEDUA
        
        #include <iostream>
        #include <iomanip>
        using namespace std;
        int main(){
	
	cout << "......................................"<<endl;
	cout << "Mata Kuliah		: Dasar Pemrograman"<<endl;
	cout << "Nama			: Gevira Zahra Shofa"<<endl;
	cout << "NIM			: 1227050050"<<endl;
	cout << "Jurusan		: Teknik Informatika"<<endl;
	cout << "......................................"<<endl;
    int arr[100][100], jumlahBaris, jumlahKolom, i, j, baris, kolom;

    int A [20][20];
	int b, k, i, j;
	cout << "Masukkan jumlah baris : ";
	cin >> b;
	cout << "Masukkan jumlah kolom : ";
	cin >> k;
	
	for (i=0;i<=b-1;i++) {
		for(j=0;j<=k-1;j++) {
			cout << "Masukkan nilai (" << i << "." << j << ") : ";
			cin >> A [i][j];
		}
	}
	cout << "Nilai yang diinputkan : \n";
	for(int i = 0; i < b; i++){
		for(int j = 0; j < k; j++){
			cout<<A[i][j]<<"\t";
		}
		cout<<endl;
	}

    cout << "\nAngka yang habis di bagi 3, 5, 7 adalah : " << endl;

    for(i = 0; i < jumlahBaris ; i++){
    for(j = 0; j < jumlahKolom; j++){
        if(arr[i][j] % 3 == 0 || arr[i][j] % 5 == 0 || arr[i][j] % 7 == 0){
        cout << setw(3) << arr[i][j] << " ";
        }
    }
    cout << endl;
    }

    
    cout << endl;
    return 0;
}
      
  # Output
  
  ......................................
Mata Kuliah             : Dasar Pemrograman
Nama                    : Gevira Zahra Shofa
NIM                     : 1227050050
Jurusan                 : Teknik Informatika
......................................
Masukkan jumlah baris : 2
Masukkan jumlah kolom : 3
Masukkan nilai (0.0) : 4
Masukkan nilai (0.1) : 3
Masukkan nilai (0.2) : 5
Masukkan nilai (1.0) : 6
Masukkan nilai (1.1) : 7
Masukkan nilai (1.2) : 2
Nilai yang diinputkan :
4       3       5
6       7       2

--------------------------------
Process exited after 7.599 seconds with return value 0

......................................
Mata Kuliah             : Dasar Pemrograman
Nama                    : Gevira Zahra Shofa
NIM                     : 1227050050
Jurusan                 : Teknik Informatika
......................................
Input jumlah baris: 3
Input jumlah kolom: 4

Baris 1, kolom 1 = 2
Baris 1, kolom 2 = 3
Baris 1, kolom 3 = 4
Baris 1, kolom 4 = 5

Baris 2, kolom 1 = 6
Baris 2, kolom 2 = 7
Baris 2, kolom 3 = 4
Baris 2, kolom 4 = 5

Baris 3, kolom 1 = 6
Baris 3, kolom 2 = 6
Baris 3, kolom 3 = 3
Baris 3, kolom 4 = 2

Hasil matriks:
  2   3   4   5
  6   7   4   5
  6   6   3   2

Hasil yang habis di bagi 3, 5, 7 adalah :
  3   5
  6   7   5
  6   6   3


--------------------------------
Process exited after 18.08 seconds with return value 0
Press any key to continue . . .


