#clude <iostream> #include <ctime>

using namespace std;

int main()
{
	int d1;

	int d2;

	srand(time(NULL));
	d1 = rand() % 3 + 1;

	d2 = rand() % 3 + 1;

	cout << "dice roll 1: " << d1 << endl;
	cout << "dice roll 2: " << d2 << endl;
	if (d1&& d2 == 1)

	{
		cout << "you win";
	}

	else

	{
		cout << " you lose";
	}
	return 0;
}
