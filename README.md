```cpp
#include <iostream>

using namespace std;
 int main()

{

           int valeur;
           string reponse;


           cout<<"Bienvenue dans se QCM ton but va etre de repondre par 1 / 2 / 3 ou 4 , bonne chance !"<<endl;
           cout<<"1er question : depuis quel version les pommes on t-elles apparru sur Minecraft ?"<<endl;
           cout<<"1 : 1.4"<<endl;
           cout<<"2 : 2.1"<<endl;
           cout<<"3 : 1.1"<<endl;
           cout<<"4 : 1.6.6"<<endl;
           cout<<"================================================="<<endl;
           cin>>valeur;



           while (valeur != 1 && valeur != 2 && valeur != 3 && valeur != 4)
           {

           cout<<"Bienvenue dans se QCM ton but va etre de repondre par 1 / 2 / 3 ou 4 , bonne chance !"<<endl;
           cout<<"1er question : depuis quel version les pommes on t-elles apparru sur Minecraft ?"<<endl;
           cout<<"1 : 1.4"<<endl;
           cout<<"2 : 2.1"<<endl;
           cout<<"3 : 1.1"<<endl;
           cout<<"4 : 1.6.6"<<endl;
           cout<<"================================================="<<endl;
           cin>>valeur;
           }



           if (valeur == 1)
           {

              cout<<"Dommage voulez vous rejouez ? oui ou non "<<endl;
               cin>>reponse;

               if (reponse == "oui" || reponse == "OUI")
               {
                   return main();
               }
               else
               {
                   return 0;
               }
           }
           else if (valeur == 2)
           {

               cout<<"Dommage voulez vous rejouez ? oui ou non "<<endl;
               cin>>reponse;

               if (reponse == "oui" || reponse == "OUI")
               {
                   return main();
               }
               else
               {
                   return 0;
               }
           }

           else if (valeur == 3)
           {
               cout<<"Bien jouer ! Maintenent prochaine question"<<endl;
           }

           else
           {
               cout<<"Dommage voulez vous rejouez ? oui ou non "<<endl;
               cin>>reponse;

               if (reponse == "oui" || reponse == "OUI")
               {
                   return main();
               }
               else
               {
                   return 0;
               }
           }
}
```
