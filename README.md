# berat-badan-ideal
#include <iostream>
using namespace std;

int main(){
	string Nama;
	string Goldarah;;
	float Beratbadan;
	float Tinggibadan;
	
	getline (cin, Nama);
	getline (cin, Goldarah);
	cin>>Beratbadan;
	cin>>Tinggibadan;
	
	cout<<endl;
	cout<<"Nama 			: "<<Nama<<endl;
	cout<< "Gol Darah		: "<<Goldarah<<endl;
	cout<<"Berat Badan 		: "<<Beratbadan<<endl;
	cout<<"Tinggi Badan		: "<<Tinggibadan<<endl;
	cout<< "Berat Badan Ideal	: "<<Tinggibadan-100-((Tinggibadan-100)*0.15)<<endl;
	return 0;
}
