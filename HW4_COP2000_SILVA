#include <iostream>
#include <string>
#include <iomanip>
using namespace std;

double raceAverage(double, double, double);
void getRaceTime(string &, double &);
void findWinner(string, string, string, double, double, double);

int main()
{
	string Validate_first_name, racer_name_1, racer_name_2, racer_name_3;
	double Validate_race_time, racer_time_1, racer_time_2, racer_time_3;
	return 0;
}

double raceAverage(double racer_time_1, double racer_time_2, double racer_time_3)
{
    racer_time_1;
    racer_time_2;
    racer_time_3;
    float raceAverage;
    raceAverage = (racer_time_1+racer_time_2+racer_time_3)/3;
    cout<<"Overall Race time Average:   "<<raceAverage;
}

void getRaceTimes(string &Validate_first_name, double &Validate_race_time)
{
	cout << "Please enter the racer's first name > ";
	cin >> Validate_first_name;
	cout << "Please enter the racer's time >";
	cin >> Validate_race_time;

	while (Validate_race_time <= 0)
		cout << "Invalid. Please try again.";
	cin >> Validate_race_time;
}

void findwinner(string racer_name_1, string racer_name_2, string racer_name_3, double racer_time_1, double racer_time_2, double racer_time_3)
{
		if (racer_time_1 > racer_time_2 && racer_time_1 > racer_time_3)
		cout << "Congratulations " << racer_name_1 << "!!! You are the winner!!\n";
	    cout << "***** Your winning time is: " << racer_time_1 << " *****";

	
	    else if (racer_time_2 > racer_time_1 && racer_time_2 > racer_time_3)
	{
		cout << "Congratulations " << racer_name_2 << "!!! You are the winner!!\n";
		cout << "***** Your winning time is: " << racer_time_2 << " *****";
	}

	    else if (racer_time_3 > racer_time_1 && racer_time_3 > racer_time_2)
	{
		cout << "Congratulations " << racer_name_3 << "!!! You are the winner!!\n";
		cout << "***** Your winning time is: " << racer_time_3 << " *****";
	}

		else if (racer_time_1 > racer_time_3 && racer_time_1 == racer_time_2)
	{
		cout << "We have a TIE, " << racer_name_1 << "and" << racer_name_2 << "!!\n"
		cout << "***** Your winning time is: " << racer_time_1 << " *****";
	}

	    else if (racer_time_1 > racer_time_2 && racer_time_1 == racer_time_3)
	{
		cout << "We have a TIE, " << racer_name_1 << "and" << racer_name_3 << "!!\n"
		cout << "***** Your winning time is: " << racer_time_1 << " *****";
	}

	    else if (racer_time_2 > racer_name_1 && racer_time_2 == racer_time_3)
	{
		cout << "We have a TIE, " << racer_name_2 << "and" << racer_name_3 << "!!\n"
		cout << "***** Your winning time is: " << racer_time_1 << " *****";
	}

	    else if (racer_time_1 == racer_time_2 && racer_time_2 == racer_time_3)
	{    
		cout << "We have a 3 TIE!! No winner for this race..."
	}


