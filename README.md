# TextGame

Battle turn base combat





#pragma 

#include <iostream>

using namespace std;

class Battle
{

};

int main()
{
int PlayerHealth = 20;
int EnemieHealth = 20;
string choice;


    while (PlayerHealth > 0 && EnemieHealth > 0) // While The player and the enemies health has not reach 0 this will continue being called
    {
    cout << "Player has: " << PlayerHealth << " HP" << endl;
    cout << "Enemie has: " << EnemieHealth << " HP" << endl;
    
    cin >> choice;

    if (choice == "attack")
    {
        cout << "You dealt 2 damage!";

        EnemieHealth -= 2;
    
    }
    }
    return 0;
}

