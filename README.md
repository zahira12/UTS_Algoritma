# UTS_Algoritma

# Latihan1 # Membuat nilai dengan perulangan.

	Alur Algoritmanya.
	-Mendeklarasikan int x,y,a,b,progres.
	-Program mulai berjalan dengan membaca nilai inputan a dan b
	-nilai a=x dan b=y
	-Mendeklarasikan nilai (x!=y) jika bernilai benar maka akan dibandingkand (x<y)
		jika x<y maka nilai x+a
		jika y<x maka nilai y+b
	-sampai nilai x==y
	-jika nilai x!=y bernilai salah maka program akan mencetak nilai x dan programpun berhenti.

~ Berikut kode lengkapnya

	int main()
	{
		int x,y,a,b,progres;
		cout<< " Masukan Nilai A :";
		cin>> a;
		cout<< " Masukan Nilai B :";
		cin>> b;
		progres= true;
		x=a;
		y=b;
	    
		while (progres)
	{
		if (x!=y)
	{
		if (x<y)
	{
		x=x+a;
	}
	else
	{
		y=y+b;
	}
	}
	else
	{
		progres=false;
	}
	}
		cout<< x;
	}

~ Berikut Hasilnya

![img](https://github.com/zahira12/UTS_Algoritma/blob/master/latihan1/hasil1screenshot.png)
![img](https://github.com/zahira12/UTS_Algoritma/blob/master/latihan1/hasil2screenshot.png)

# Latihan2 # Menentukan nilai dengan perulangan dan menginputkan NIM.

	Alur algoritmanya
	-mendeklrasikan int T,X,N,Batas
	-mendeklrasikan variabel T,X sebagai penyimpan nilai
	-mendelrasikan variabel N sebagai inputan
	-mendeklrsikan variabel Batas sebagai perulangan.
	-Membuat perbandingan untuk perulangan 
		while ( T<= Batas)
		T=N+X
		X=X+10

~ Berikut kode lengkapnya.

	int main()
	{
		int N,X,T,Batas;
		cout<< " Masukan Nilai N :" ;
		cin>> N;
		cout<< endl;

		Batas = N + 100;
		X=20;
		T=N;

		while ( T <= Batas)
	{
		T=T+X;
		X=X+10;
	}
		cout << "Hasilnya Adalah :" << T;
	return 0;
	}

~ Berikut hasilnya

![img](https://github.com/zahira12/UTS_Algoritma/blob/master/latihan2/hasil3screenshot.png)
