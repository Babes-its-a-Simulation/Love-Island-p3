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
	string connection;
	string Alex, Adrian, Taylor, Morgan, Jamie, Blake;
	string answer;
	string chattinPlace;
	string snog;
	string dayBed, couchSwing, firepit, beanBags;
	
	


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
		cout << "*We have Alex, Adrian, Taylor, Morgan, Jamie, and Blake in the game.*" << endl;
		cin >> connection;

		if (connection == Adrian || connection == Taylor || connection == Morgan || connection == Jamie || connection == Blake) {
			cout << "Ooooh " << connection << " is a great choice babes. They've got some good banter haven't they? Why don't you pull them for a chat?" << endl;
			cout << "< Enter yes if you want to pull " << connection << " for a chat or no if you want to think about it more >" << endl;
			cin >> answer;

			if (answer == yes) {
				cout << "Sparks are absolutely flyin!" << endl;
				cout << "Where do you want to go to chat?" << endl;
				cout << "*The day bed, couch swing, firepit, and the bean bags are open*" << endl;
				cin >> chattinPlace >> endl;
				
				if (chattinPlace ==day bed || chattinPlace == couch swing || chattinPlace == firepit || chattinPlace ==bean bags) {
					cout << "Great choice! Bring " << connection << " over to the " << chattinPlace << "." << endl;
					cout << connection << ": I think we have a great connection, we get on so well and babes you already know you're fit as." << endl;
					cout << "Eeeeeee! Fanny flutters!" << endl;
					cout << "*They're charming the socks off ya! Do you want to go in for a cheeky snog?*" << endl;
					cout << "Enter yes if you want to snog " << connection << " and no if you don't think you two are there yet." << endl;
					cin >> snog >> endl;
					
					if (snog == yes) {
						cout << "What an amazing kisser!" << endl;
					}
					
					if (snog == no) {
						cout << "It's not the right time babes, and that's ok!" << endl;
					}
					
					cout << connection << ": Let's go rejoin the group! I'm sure they've been wondering where we've been." << endl;
				}
			}
			else if (answer == no) {
				cout << "No harm in that! Lets go grab a drink babes." << endl;
			}
		}
		else if (connection == Alex) {
			cout << "Alex: Oh babes, I'm shocked to be honest" << endl;

		}
			else {
				cout << "Babes, who is that? Are you still crushing on someone from back home?" << endl;
			}
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
  
  
