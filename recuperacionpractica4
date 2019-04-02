//* Practica de recuperación */
//* Esta practica es válida como recuperación de la práctica 4 del semestre 2018_2 */
//* Si usted decide realizar esta práctica entoces su nota final en la práctica 4 */
//* será la que obtenga en esta misma práctica de recuperación */

//1. Diseñe e implemente una clase abstracta llamada Animal, dicha clase debe implementar
//por lo menos 3 metodos relacionados con las funciones o caracteristicas de los animales.
//(Repirar, desplazarse, almentarse, etc...).

// Luego implemente 4 clases: Mamifero, Ave, Anfibio y Reptil. Estas clases deben heredar de
//la clase Animal y deben de reimplementar (redefinir) cada una a su manera los metodos heredados
//de la clase Animal y deben agregar metodos adicionales de acuerdo a la naturaleza en particular,
//por ejemplo las aves deberian tener un método volar.

//Finalmente implemente una clase Ornitorrinco que debe heredar de las clases Ave, Anfibio y Mamifero.
//Implementar una clase "Animal_X" que hereda de las clases Ave y Réptil.

//Diseñe una aplicación que permita implementar objetos de las clases Ornitorrinco y "Animal_X"
//¡En caso de que haya problemas a la hora de implementar dichos objetos entonces consulte como
//solucionar el problema "Diamante" de la herencia.

#include <iostream>
using namespace std;

class Animal
{
public:
  string nombre;

  void getNombre(){
      cout<<nombre<<endl;

  }

  virtual void comer ()=0;

  };

  void desplazamiento (){
      cout<<"Me estoy moviendo"<<endl;
  }

  void volver_al_nido (){
      cout<<"Volviendo al nido"<<endl;

};

class Mamifero:virtual public Animal
 {
    public:
  void comer ()
  {
    cout << "yo me alimento en la selva" << endl;
  }
  void desplazamiento ()
  {
    cout << "camino en la selva " << endl;
  }
  void volver_al_nido ()
  {
    cout << "llega en la noche" << endl;
  }
};

class Ave:virtual public Animal
 {
    public:
  void comer ()
  {
    cout << "yo me alimento en la cima de los arboles" << endl;
  }
  void desplazamiento ()
  {
    cout << "Yo vuelo por los aires" << endl;
  }
  void volver_al_nido ()
  {
    cout << "vuela pa llegar al arbol a las 6" << endl;
  }
};

class Anfibio:virtual public Animal
 {
    public:
  void comer ()
  {
    cout << "yo como en diversos lugares y situaciones" << endl;
  }
  void desplazamiento ()
  {
    cout << "yo nado, brinco, corro, camino hago muchas cosas " << endl;
  }
  void volver_al_nido ()
  {
    cout << "me dirijo a mi aposento al anochecer y a veces al amanecer" << endl;
  }
};

class Reptil:virtual public Animal
 {
    public:
  void comer ()
  {
    cout << "yo me alimento en el borde del rio" << endl;
  }
  void desplazamiento ()
  {
    cout << "yo corro demasiado" << endl;
  }
  void volver_al_nido ()
  {
    cout << "apenas consigo mi alimento regreso a mi calido bosque " << endl;
  }
};



class Ornitorrinco:public Ave, public Anfibio,public Mamifero
{
public:
  void comer (){
      cout<<"Estoy comiendo"<<endl;
  }

  void desplazamiento (){
      cout<<"Me estoy moviendo"<<endl;
  }

  void volver_al_nido (){
      cout<<"Volviendo al nido"<<endl;
  }
};


class Animal_X:public Reptil, public Ave
{
public:
  void comer (){
      cout<<"Estoy comiendo"<<endl;
  }

  void desplazamiento (){
      cout<<"Me estoy moviendo"<<endl;
  }

  void volver_al_nido (){
      cout<<"Volviendo al nido"<<endl;
  }
};

int main()

{
    int opcion;
    int opcion2;
    do{
    cout<<"bienvenido al recreador de metodos y animales "<<endl;
    cout<<"que clase de aniaml  desea recrear?"<<endl;
    cout<<"1. Mamifero"<<endl;
    cout<<"2. Ave"<<endl;
    cout<<"3. Anfibio"<<endl;
    cout<<"4. Reptil"<<endl;
    cout<<"5. Ornitorrinco"<<endl;
    cout<<"6. Animal_X"<<endl;
    cout<<"7. salir"<<endl;

    cin>>opcion;
    Mamifero mam;
    Ave ave;
    Anfibio anf;
    Reptil rep;
    Ornitorrinco orni;
    Animal_X anx;
    if(opcion>=1 && opcion<=7){
        switch (opcion) {
            case 1:

                cout<<endl<<"Mamifero"<<endl;
                cout<<"Escriba el nombre del animal: "<<endl;
                cin>>mam.nombre;
                cout<<"Elija la opcion"<<endl;
                cout<<"1. Desplazamiento"<<endl;
                cout<<"2. Retorno al nido"<<endl;
                cin>>opcion2;
                switch(opcion2){

                    case 1:
                        mam.comer();
                        printf("\ndesplazamiento \n");
                        mam.getNombre();
                        break;

                    case 2:
                        mam.desplazamiento();
                        printf("\ndesplazamiento \n");
                        mam.getNombre();
                        break;
                    case 3:
                        mam.volver_al_nido();
                        printf("\nvolver_al_nido \n");
                        mam.getNombre();
                        break;


                    }


            break;
            case 2:

                printf("\nAve \n");
                cout<<"Escriba el nombre del animal: "<<endl;
                cin>>ave.nombre;
                cout<<"Elija la opcion"<<endl;
                cout<<"1. Comer"<<endl;
                cout<<"2. Desplazamiento"<<endl;
                cout<<"3. Retorno al nido"<<endl;
                cin>>opcion2;
                switch(opcion2){

                    case 1:
                        ave.comer();
                        printf("\ndesplazamiento \n");
                        ave.getNombre();
                        break;

                    case 2:
                        ave.desplazamiento();
                        printf("\ndesplazamiento \n");
                        ave.getNombre();
                        break;
                    case 3:
                        ave.volver_al_nido();
                        printf("\nvolver_al_nido \n");
                        ave.getNombre();
                        break;


                    }

            break;
            case 3:

                printf("\nAnfibio \n");
                cout<<"Escriba el nombre del animal: "<<endl;
                cin>>anf.nombre;
                cout<<"Elija la opcion"<<endl;
                cout<<"1. Comer"<<endl;
                cout<<"2. Desplazamiento"<<endl;
                cout<<"3. Retorno al nido"<<endl;
                cin>>opcion2;
                switch(opcion2){


                    case 1:
                        anf.comer();
                        printf("\ncomer \n");
                        anf.getNombre();
                        break;
                    case 2:
                        anf.desplazamiento();
                        printf("\ndesplazamiento \n");
                        anf.getNombre();
                        break;
                    case 3:
                        anf.volver_al_nido();
                        printf("\nvolver_al_nido \n");
                        anf.getNombre();
                        break;


                    }


            break;
            case 4:

                printf("\nReptil \n");
                cout<<"Escriba el nombre del animal: "<<endl;
                cin>>rep.nombre;
                cout<<"Elija la opcion"<<endl;
                cout<<"1. Comer"<<endl;
                cout<<"2. Desplazamiento"<<endl;
                cout<<"3. Retorno al nido"<<endl;
                cin>>opcion2;
                switch(opcion2){


                    case 1:
                        rep.comer();
                        printf("\ncomer \n");
                        rep.getNombre();
                        break;
                    case 2:
                        rep.desplazamiento();
                        printf("\ndesplazamiento \n");
                        rep.getNombre();
                        break;
                    case 3:
                        rep.volver_al_nido();
                        printf("\nvolver_al_nido \n");
                        rep.getNombre();
                        break;


                    }
            break;
            case 5:

                printf("\nOrnitorrinco \n");
                cout<<"Escriba el nombre del animal: "<<endl;
                cin>>orni.nombre;
                cout<<"Elija la opcion"<<endl;
                cout<<"1. Comer"<<endl;
                cout<<"2. Desplazamiento"<<endl;
                cout<<"3. Retorno al nido"<<endl;
                cin>>opcion2;
                switch(opcion2){


                   case 1:
                        orni.comer();
                        printf("\ncomer \n");
                        orni.getNombre();
                        break;
                    case 2:
                        orni.desplazamiento();
                        printf("\ndesplazamiento \n");
                        orni.getNombre();
                        break;
                    case 3:
                        orni.volver_al_nido();
                        printf("\nvolver_al_nido \n");
                        orni.getNombre();
                        break;


                    }


            break;
            case 6:

                printf("\nAnimal_X \n");
                cout<<"Escriba el nombre del animal: "<<endl;
                cin>>anx.nombre;
                cout<<"Elija la opcion"<<endl;
                cout<<"1. Comer"<<endl;
                cout<<"2. Desplazamiento"<<endl;
                cout<<"3. Retorno al nido"<<endl;
                cin>>opcion2;
                switch(opcion2){



                    case 1:
                        anx.comer();
                        printf("\ndesplazamiento \n");
                        anx.getNombre();
                        break;
                    case 2:
                        anx.desplazamiento();
                        printf("\ndesplazamiento \n");
                        anx.getNombre();
                        break;
                    case 3:
                        anx.volver_al_nido();
                        printf("\nvolver_al_nido \n");
                        anx.getNombre();
                        break;


                    }


            break;



        }

    }else{
        cout<<"clase no recreable o no creada o no disponible"<<endl;
    }

    }while(opcion!=7);


    return 0;
}
