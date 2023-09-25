#include <iostream>
#include <ctime>
#include <cstdlib>


int main()
{
	int gnum; // the number p1 & p2 will guess!


	system("Color 3E");

	srand(time(NULL));

	int p1amount;
	int p2amount;
	int p1guess;
	int p2guess;


	std::cout << "Hello, Player1 & Player2" << '\n';
	std::cout << "Player1 please enter the amount of money you want to bet from $1-1000" << '\n';
	std::cin >> p1amount;
	std::cout << "Player2 please enter the amount of money you want to bet from $1-1000" << '\n';
	std::cin >> p2amount;
	int result = p1amount + p2amount;
	std::cout << "The total amount being bet is " << result << " the game shall continue." << '\n';
	gnum = rand() % 10 + 1;

	do
	{
		std::cout << "Player1, please guess!\n";
		std::cin >> p1guess;
		if (p1guess == gnum)
		{
			std::cout << "You win! the money is all yours!\n";
			break;
		}
		else if (p1guess != gnum)
		{
			std::cout << "Incorrect gangy!\n";
		};




		std::cout << "Player2, please guess!\n";
		std::cin >> p2guess;
		if (p2guess == gnum)
		{
			std::cout << "You win! the money is all yours!\n";
			break;
		}
		else if (p2guess != gnum)
		{
			std::cout << "Incorrect gangy!\n";
		};
		

	} while (p1guess != gnum|| p2guess != gnum);


}
