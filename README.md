include <iostream>
using namespace std;

int main() {
	int Calificaciones [5];
	float Promedio;
	int Nota,Tolate;
	cout<<"Ingrese Las Calificaciones De Los Alumnos: "<<endl;	
	
	for (int i=0;i<=5;i++){
		cout<<"Alumno "<<i+1<<" : "<<endl;
		cin>>Calificaciones[i];	
		if (Calificaciones[i]<0){
			cout<<"No se puede we :v"<<endl;
			i--;
		}else if (Calificaciones[i]>100){
			cout<<"No se puede bro :v"<<endl;
			i--;
		}else{
			Nota=Calificaciones[1];
			Tolate=Tolate+Nota;
		}

	}
	
	
	Promedio= Tolate/5;
	cout<<"La Suma De LAs Notas Es De: "<<endl;
	cout<<Promedio<<endl;
	return 0;
}
