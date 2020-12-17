#include <iostream>
#include <windows.h>

#include <cstdlib>
#include <ctime>
using namespace std;



class Islander {

public:

	string name;
	string maybeSexyPJs;
	string yes = yes;
	string no = no;
	int sexy;
	
	


	/*Islander names: Alex, Adrian, Taylor, Morgan, Jamie, Blake */

	void intro() {
		cout << " " << endl;
		cout << "Well you're proper fit luv I'll tell ya that." << endl;
		cout << " " << endl;
		cout << "What's ya name darling." << endl;
		cin >> name;
		cout << "Gorgeous name "<< name<<". I bet ya make ya mum proud with it" << endl;
	}

	void firstCoupling() {



	}

	void bitaBanter() {

	}

	void muggedOff() {

	}

	void Chat() {
		cout << "Alex: It's such a nice night out, I wonder what connections everyone is making." << endl;
		cout << "So babes, is there anyone that your feeling a connection with?" << endl;
		cout << "We have Alex, Adrian, Taylor, Morgan, Jamie, and Blake in the game." << endl;
		cin >> connection >> endl;
		
		if (connection == Alex || Adrian || Taylor || Morgan || Jamie || Blake) {
			cout << "Ooooh " << connection << " is a great choice babes. They've got some good banter haven't they? Why don't you pull them for a chat?" << endl;
			cout << "Enter yes if you want to pull " << connection << " for a chat and no if you want to think about it more" << endl;
			cin >> answer >> endl;
			
			if (answer == yes) {
				cout << "Sparks are absolutely flyin!" << endl;
			else if (answer == no) {
				cout << "No harm in that!" endl;
		
		else {
			cout << "Babes, who is that? Are you still crushing on someone from home?" endl;
	}

	void sexyPJS() {
		cout << "*Adrian walks into the changing room*" << endl;
		cout << "Adrian wants to know whether or not to put on some sexy PJs for alex tonight" << endl;
		cout << "Taylor says there's never a time not to wear some sexy PJs" << endl;
		cout << "Do you think Adrian should wear some sexy PJs ?" << endl;
		cout << "Please enter yes or no" << endl;
		cin >> maybeSexyPJs;

		if (maybeSexyPJs == yes) {
			cout << "Adrian: OOH HOO babes I knew you liked to have some fun. Imma go all out for alex" << endl;
			int sexy = 1;
		}
		else if(maybeSexyPJs == no){
			cout << "Adrian: hmm maybe you're right. I'll keep it a surprise for later." << endl; 
			int sexy = 2;
		}
		else {
			cout << "Well babes you're just no help huh?" << endl;
			int sexy = 3;
		}
		

	}

	void dumbMoment() {
		cout << "Godd morning islander! Why don't you go chat with the other islanders around the pool?" << endl;
		cout << "*You walk up to the other islanders deep into a very intriguin conversation." << endl;
	}

	void recoupling() {

	}


};



int main() {


	/*
	bool played = PlaySound(TEXT("practice noise.m4a"), NULL, SND_SYNC);

	return 0;  

	*/

	
	Islander player;
	string gender;
	int flirt;
	string names[6] = { "Alex"," Adrian", "Taylor", "Morgan", "Jamie", "Blake" };

	

	cout << "Finding Love can be tough, life is nothing but work, eat, sleep, repeat." << endl;
	cout << "It's time to get off social media and find love the old fashion way" << endl;
	cout<< "in a REALITY TV SHOW"<<endl;
	cout << " " << endl;
	cout << " " << endl;
	cout << "WELCOME TO LOVE ISLAND !!! <3" << endl;;
	cout << " " << endl;
	cout << " " << endl;
	cout << "Starting with the nitty gritty" << endl;
	cout<<"Babes, are ya a bird or a lad? " << endl;
	cin >> gender;

	

	string lad = "lad";
	string bird = "bird";
	string name;
	string maType;

	if (lad == gender) {
		player.intro();
		cout << "Alight babes now then what's ya type?" <<endl;
		cin >> maType;
		cout << "You're a cheeky one aren't ya." << endl;
		cout << " " << endl;
		cout << "Alright Islander it's time to meet the girls" << endl;
		cout << " " << endl;
		cout << "*The ladies walk through the door*" << endl;
	}
	else if (bird == gender) {
		player.intro();
		cout << "Now darling whats ya type? Mine's tall dark and handsome." << endl;
		cin >> maType;
		cout << "OOoh ya, now that's nice" << endl;
		cout << " " << endl;
		cout << "Alright Islander it's time to meet the lads" << endl;
		cout << " " << endl;
		cout << "*The lads file in*" << endl;

	}
	else {
		cout << "Uh Oh babes I just don't get it, which one is ya?" << endl;
		cout << " If you're tryna say you're non-binary that's fine darling, this is a place for love not hate." << endl;
		cin >> gender;
	/*	Flaw doesnt execute the rest of the code if you input the wrong choice */
	}

	
	/*
	srand((unsigned)time(0));
	flirt = (rand() % 6) + 1;
	cout << "*As they all walk in " << names[flirt] << " casts quite the apprieciative glance at ya*" << endl;
	cout << " " << endl;
	*/

	

	

}
  
  
