#include <iostream>
#include <stdio.h>      /* printf, scanf, puts, NULL */
#include <stdlib.h>     /* srand, rand */
#include <time.h>       /* time */

using namespace std;

int main()
{
    srand (time(NULL));

    int valeur,reponse,reponse2,reponse3,vie;
    string rejouer;
    //creation d'un nombre aleatoire entre 2 et 1
    valeur = rand() % 4+ 1;
    vie = 2;



        if (valeur == 1 || valeur == 3)
        {
            while (reponse != 1 && reponse != 2 && reponse != 3)
            {
                cout<<" Combien de temps a duree la guerre de 100ans ? "<<endl;
                cout<<" [1] 100ans "<<endl;
                cout<<" [2] 98ans "<<endl;
                cout<<" [3] 116ans "<<endl;
                cin>>reponse;
            }





                if (reponse == 1)
                {
                    cout<<" Dommage"<<endl;
                    vie = vie - 1;
                    cout<<"Il te reste "<<vie<<" vie !";
                }
                else if (reponse == 2)
                {
                    cout<<"Dommage "<<endl;
                    vie = vie - 1;
                    cout<<"Il te reste "<<vie<<" vie !";
                }
                else
                {
                    cout<<"Exact ! la guerre de 100ans n'a pas duree 100 ans mais 116ans "<<endl;
                    cout<<"Il te reste "<<vie<<" vie !"<<endl<<endl;
                }

        }




        if (valeur == 2 || valeur == 4)
        {
            while (reponse != 1 && reponse != 2 && reponse != 3)
            {
                cout<<" Quel est la vitesse de la lumiere en km/s ? "<<endl;
                cout<<" [1] 300,000 km/s "<<endl;
                cout<<" [2] 200,000 km/s "<<endl;
                cout<<" [3] 299,800 km/s "<<endl;
                cin>>reponse;
            }




                if (reponse == 1)
                {
                    cout<<"GG ! c'etait bien 300,000 km/s "<<endl;
                    cout<<"Il te reste "<<vie<<" vie !"<<endl<<endl;
                }
                else if (reponse == 2)
                {
                    cout<<"Dommage "<<endl;
                    vie = vie - 1;
                    cout<<"Il te reste "<<vie<<" vie !"<<endl<<endl;
                }
                else
                {
                    cout<<"Dommage "<<endl;
                    vie = vie - 1;
                    cout<<"Il te reste "<<vie<<" vie !"<<endl<<endl;


                }
        }



                //nouvelle valeur random pour des nouvelles questions aleatoire 2
                srand (time(NULL));
                valeur = rand() % 4+ 1;


         if (valeur == 1 || valeur == 3)
        {
            while (reponse2 != 1 && reponse2 != 2 && reponse2 != 3)
            {
                cout<<" QUESTION 2 "<<endl;
                cout<<"A combien de km/h est aller la voiture de serie la plus rapide du monde ? "<<endl;
                cout<<" [1] 421 km/h "<<endl;
                cout<<" [2] 431 km/h "<<endl;
                cout<<" [3] 441 km/h "<<endl;
                cin>>reponse2;
            }





                if (reponse2 == 1)
                {
                    cout<<" Dommage"<<endl;
                    vie = vie - 1;
                    cout<<"Il te reste "<<vie<<" vie";
                    if (vie == 0)
                    {
                        cout<<" Tu a perdu";
                        return 0;
                    }
                }
                else if (reponse2 == 2)
                {
                    cout<<"Bien ouej c'est la bugatti veyron "<<endl;
                    cout<<"Il te reste "<<vie<<" vie"<<endl<<endl;

                }
                else
                {
                    cout<<"Dommage "<<endl;
                    vie = vie - 1;
                    cout<<"Il te reste "<<vie<<" vie";
                    if (vie == 0)
                    {
                        cout<<" Tu a perdu";
                        return 0;
                    }
                }

        }

                if (valeur == 2 || valeur == 4)
        {
            while (reponse2 != 1 && reponse2 != 2 && reponse2 != 3)
            {
                cout<<" QUESTION 2 "<<endl;
                cout<<"En quelle annee est sortie ROBLOX ? "<<endl;
                cout<<" [1] 2006 "<<endl;
                cout<<" [2] 2008 "<<endl;
                cout<<" [3] 2012 "<<endl;
                cin>>reponse2;
            }





                if (reponse2 == 1)
                {
                    cout<<"Roblox est effectivement sortie le 1er septembre 2006"<<endl;
                    cout<<"Il te reste "<<vie<<" vie"<<endl<<endl;
                }
                else if (reponse2 == 2)
                {
                    cout<<"Dommage "<<endl;
                    vie = vie - 1;
                    cout<<"Il te reste "<<vie<<" vie";
                    if (vie == 0)
                    {
                        cout<<" Tu a perdu";
                        return 0;
                    }

                }
                else
                {
                    cout<<"Dommage "<<endl;
                    vie = vie - 1;
                    cout<<"Il te reste "<<vie<<" vie";
                    if (vie == 0)
                    {
                        cout<<" Tu a perdu";
                        return 0;
                    }
                }

        }


             //nouvelle valeur random pour des nouvelles questions aleatoire 3
                srand (time(NULL));
                valeur = rand() % 4+ 1;


         if (valeur == 1 || valeur == 3)
        {
            while (reponse3 != 1 && reponse3 != 2 && reponse3 != 3)
            {
                cout<<" QUESTION 3 "<<endl;
                cout<<"En quelle annee est sortie MINECRAFT ? "<<endl;
                cout<<" [1] 2009 "<<endl;
                cout<<" [2] 2010 "<<endl;
                cout<<" [3] 2011 "<<endl;
                cin>>reponse3;
            }





                if (reponse3 == 1)
                {
                    cout<<" Dommage"<<endl;
                    vie = vie - 1;
                    cout<<"Il te reste "<<vie<<" vie";
                    if (vie == 0)
                    {
                        cout<<" Tu a perdu";
                        return 0;
                    }
                }
                else if (reponse3 == 2)
                {
                    cout<<" Dommage"<<endl;
                    vie = vie - 1;
                    cout<<"Il te reste "<<vie<<" vie";
                    if (vie == 0)
                    {
                        cout<<" Tu a perdu";
                        return 0;
                    }

                }
                else
                {
                   cout<<"Yes ! minecraft est sortie le 18 novembre 2011 "<<endl;
                    cout<<"Il te reste "<<vie<<" vie";
                }

        }

         if (valeur == 2 || valeur == 4)
        {
            while (reponse3 != 1 && reponse3 != 2 && reponse3 != 3)
            {
                cout<<" QUESTION 3 "<<endl;
                cout<<"Combien coute la dualtron mini ? "<<endl;
                cout<<" [1] 999,99€ "<<endl;
                cout<<" [2] 699,99€ "<<endl;
                cout<<" [3] 1099,99€ "<<endl;
                cin>>reponse3;
            }





                if (reponse3 == 1)
                {
                    cout<<"GG a toi la dualtron mini coute bien 999,99€ "<<endl;
                    cout<<"Il te reste "<<vie<<" vie";
                }
                else if (reponse3 == 2)
                {
                    cout<<" Dommage"<<endl;
                    vie = vie - 1;
                    cout<<"Il te reste "<<vie<<" vie";
                    if (vie == 0)
                    {
                        cout<<" Tu a perdu";
                        return 0;
                    }

                }
                else
                {
                   cout<<"Dommage "<<endl;
                   vie = vie - 1;
                   cout<<"Il te reste "<<vie<<" vie";
                    if (vie == 0)
                    {
                        cout<<" Tu a perdu";
                        return 0;
                    }
                }

        }




















    return 0;

}
