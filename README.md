# 28Sep2021_Assignment

// Mark my Words
#include <iostream>
using namespace std;
int main()
{
	int grade = 120;
	if ((grade >= 70) && (grade <= 100)) {
		cout << "A" << endl;
	}
	else if ((grade >= 60) && (grade <= 69)) {
		cout << "B" << endl;
	}
	else if ((grade >= 50) && (grade <= 59)) {
		cout << "C" << endl;
	}
	else if ((grade >= 40) && (grade <= 49)) {
		cout << "D" << endl;
	}
	else if (grade < 40) {
		cout << "F" << endl;
	}
	else {
		cout << "Invalid input" << endl;
	}
}
  
  
  
----------------------------------------------------------
  
  // Starting a Band
#include <iostream>
#include <string>
using namespace std;
int main()
{
	bool musicalFriend = true;
	string friendPlays = "guitar";
	string friendPlays2 = "guitar";
	if (friendPlays.compare (friendPlays2) == 0) {
		cout << "He can join the band!";
	}
	else {
		cout << "He cannot join the band." << endl;
	}
	return 0;
}
	
	
	
	
-------------------------------------------------------
// Killing Time
#include <iostream>
using namespace std;
int main()
{
	int time = 15;
	int money = 5;
	cout << "You are waiting for your friend to come meet you at Dubai mall. \n";
	cout << "You receive a message from her a few minutes later. \n";
	if (time >= 15) {
		cout << "It will take her another 15 or more minutes to meet you there. \n";
		cout << "You check your pocket money to see if you have enough to buy a coffee. \n";
		if (money >= 5) {
			cout << "You see that you have enough so you went to buy a cup of coffee." << endl;
		}
		else {
			cout << "You see that you don't have enough so you just went for a walk." << endl;
		}
	}
	else {
		cout << "She tells you that she will be there in less than 15 minutes" << endl;
		cout << "so you sat and waited at the food zone. \n";
	}
	return 0;
}
	
	
	
	
-------------------------------------------------------------------------------------------------------------------------
// Earthquake
#include <iostream>
using namespace std;
int main()
{
	bool earthquake = true;
	double magnitude;
	cout << "What was the magnitude of the earthquake?" << endl;
	cin >> magnitude;
	if (earthquake) {
		if (magnitude < 2.0) {
			cout << "That is a micro earthquake." << endl;
		}
		else if ((magnitude >= 2.0) && (magnitude < 3.0)) {
			cout << "That is a very minor earthquake." << endl;
		}
		else if ((magnitude >= 3.0) && (magnitude < 4.0)) {
			cout << "That is a minor earthquake." << endl;
		}
		else if ((magnitude >= 4.0) && (magnitude < 5.0)) {
			cout << "That is a light earthquake." << endl;
		}
		else if ((magnitude >= 5.0) && (magnitude < 6.0)) {
			cout << "That is a moderate earthquake." << endl;
		}
		else if ((magnitude >= 6.0) && (magnitude < 7.0)) {
			cout << "That is a strong earthquake." << endl;
		}
		else if ((magnitude >= 7.0) && (magnitude < 8.0)) {
			cout << "That is a major earthquake. \n";
		}
		else if ((magnitude >= 8.0) && (magnitude < 10)) {
			cout << "That is a great earthquake. \n";
		}
		else if (magnitude >= 10) {
			cout << "That is a meteoric earthquake. \n";
		}
		return 0;
	}
}
