# -WSQs06-TC1017
#include <iostream>
using namespace std;
int main()
{
	int numero, contador;
	bool repetidor = true;
	cout << "I chose a number betwen 1 and 100" << endl;
	cout << "Please guess the number" << endl;
	cin >> numero;

	while (repetidor)
 {
		if ( numero == 30)
	{
	    cout << "Nice job! the right number is 30" << endl;
        repetidor = false;
    }
    else if (numero > 30)
    {
    	cout << "Im sorry" << numero << "is too hight, try again:"<< endl;
    	cin >> numero;
    }
    else if (numero < 30)
    {
    	cout << "Im sorry" << numero << "is too low, try again:"<< endl;
    	cin >> numero;
    }
     contador +1;
  }
  cout << " You made " << contador<< "guesses to grt the right number"<< endl;
  return 0;
} 
