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
	int firstKiss;
	


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
		cout << " " << endl;
		cout << "*Your options are Alex, Adrian, Taylor, Morgan, Jamie, or Blake.*" << endl;
		cin >> connection;

		if (connection == Alex) {
			cout << "Oh um well you see babes I don't think I'm feeling quite the same things you are at the moment" << endl;
			cout << "*Alex awkwardly leaves" << endl;
			cout << " " << endl;
			cout << "*Uh oh babes, it looks like you made things weird between alex and ya" << endl;
		}

		else {

			cout << "Ooooh " << connection << " is a great choice babes. They've got some good banter haven't they? Why don't you pull them for a chat?" << endl;
			cout << "< Enter yes if you want to pull " << connection << " for a chat or no if you want to think about it more >" << endl;
			cin >> answer;
			
			cout << answer<<endl;

			
			if (answer == "yes") {
				cout << "Sparks are absolutely flyin!" << endl;
				cout << "Where do you want to go to chat?" << endl;
				cout << "*The day bed, couch swing, firepit, and the bean bags are open*" << endl;
				cin >> chattinPlace;
				cout << "Great choice! Bring " << connection << " over to the " << chattinPlace << "." << endl;
				cout << connection << ": I think we have a great connection, we get on so well and babes you already know you're fit as." << endl;
				cout << "Eeeeeee! Fanny flutters!" << endl;
				cout << "*They're charming the socks off ya! Do you want to go in for a cheeky snog?*" << endl;
				cout << "Enter yes if you want to snog " << connection << " and no if you don't think you two are there yet." << endl;
				cin >> snog;

				if (snog == "yes") {
					cout << "What an amazing kisser!" << endl;

					cout << connection << ": I'm proper blushing right now ya." << endl;
					firstKiss = 1;
				}

				else {
					cout << "It's not the right time babes, and that's ok!" << endl;
					firstKiss = 2;
				}

				cout << " " << endl;
				cout << connection << ": Let's go rejoin the group! I'm sure they've been wondering where we've been." << endl;
			}
			else {
				cout << "Thats alright Babes" << endl;
				cout << " " << endl;
				cout << connection << ": Let's go rejoin the group! I'm sure they've been wondering where we've been." << endl;
				firstKiss = 3;
			}

		}


		
		
		}
	

	void sexyPJS() {
		cout << "*Adrian walks into the changing room*" << endl;
		cout << "Adrian: Shall I wear some sexy PJs tonight? Maybe give a lil show?" << endl;
		cout << "Taylor: there's never a time not to wear some sexy PJs" << endl;
		cout << "Do you think Aridan should wear some sexy PJs?" << endl;
		cout << "Please enter yes or no" << endl;
		cin >> maybeSexyPJs;

		if (maybeSexyPJs == "yes") {
			cout << "Aridan: OOH HOO babes I knew you liked to have some fun. Fashion Fashion Diva baby" << endl;
			int sexy = 1;
		}
		else if(maybeSexyPJs == "no"){
			cout << "Aridan: hmm maybe you're right. I'll keep it a surprise for later." << endl; 
			int sexy = 2;
		}
		else {
			cout << "Well babes you're just no help huh?" << endl;
			int sexy = 3;
		}
		

	}

	void dumbMoment() {

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
	cout<<"babes are ya a bird or a lad? " << endl;
	cin >> gender;

	

	string lad = "lad";
	string bird = "bird";
	string name;
	string maType;
	string job;
	int firstKiss =0;
	string connection;

	if (lad == gender) {
		player.intro();
		cout << "Alight babes now then what's ya type?" <<endl;
		cin >> maType;
		cout << "You're a cheeky one aren't ya." << endl;
		cout << " " << endl;
	
	}
	else if (bird == gender) {
		player.intro();
		cout << "Now darling whats ya type? Mine's tall dark and handsome." << endl;
		cin >> maType;
		cout << "OOoh ya, now that's nice" << endl;
		cout << " " << endl;
		

	}
	else {
		cout << "Uh Oh babes I just don't get it, which one is ya?" << endl;
		cout << " If you're tryna say you're non-binary that's fine darling, this is a place for love not hate." << endl;
		cin >> gender;
		cout << "Anyways luv its time to meet the other Islanders!!" << endl;
	/*	Flaw doesnt execute the rest of the code if you input the wrong choice */
	}

	
	/*
	srand((unsigned)time(0));
	flirt = (rand() % 6) + 1;
	cout << "*As they all walk in " << names[flirt] << " casts quite the apprieciative glance at ya*" << endl;
	cout << " " << endl;
	*/
	/*Islander names: Alex, Adrian, Taylor, Morgan, Jamie, Blake */

	cout << "*One by one the rest of the Islanders enter the Vila. It's a filth fest of hotties*" << endl;
	cout << "*As you all mingle, you discover Taylor works as a Body Builder, Adrian is a french model, and Alex is currently unemployed*" << endl;
	cout << "*Morgan aprroaches you*" << endl;
	cout << "Morgan: hi " << name << " it's so nice to meet you. it's bloody crazy that we're all here right now." << endl;
	cout << " I had to take so much leave from my daycare. So babes, what is it you do?" << endl;
	cin >> job;


	cout << "Morgan: Really?! that sounds like a lot of fun luv" << endl;
	cout << "I heard that Jamie is an Instagram model and Blake works as an assistant to the assitant of Adele's manager." << endl;
	cout << "Anyways Babe, I'll tell ya right now that blake has a smokin' body. I think I'll go see if I can find their type. Wish me luck babes" << endl;

	cout << " " << endl;


	cout<<"*You see Alex heading to the day beds and decide to tag along" << endl;
	cout << "*You guys settle into the day beds and reflect on the night*" << endl;


	player.Chat();

	if (firstKiss == 1) {
		cout << "*As you head back to the rest of the group you can't stop thinking about the kiss. it was proper magical." << endl;
		cout << "You decide to chance a glance at " << connection << " and catch him staring right back at you" << endl;
		cout << "INSTANT BLUSH" << endl;
		
		

	}
	else if (firstKiss == 2) {
		cout << "You walk back towards the rest of the islanders wondering if " << connection << " is feeling the same butterflies you are." << endl;
		cout << "You can't help how giddy you feel about where things will go" << endl;
		cout << "As you're smiling to yourself, you chance a peek at " << connection << " and realize they're staring at Alex" << endl;
		cout << "*This bothers you slightly but you don't say anything yet. It's still just early days." << endl;
		
	}
	else if (firstKiss == 3) {
		cout << "You and Alex finish up resting and decide to make your way back to everyone else." << endl;
	}
	else {

	}

	cout << " " << endl;
	cout << "*Everyone is buzzing. Our Love Island Journey has taken it's first steps*" << endl;
	cout << "^As the excitement of the first day wears off, you head to the bathroom to get ready for bed." << endl;

	if (gender == "lad "&& connection != "Taylor" && connection != "Adrian") {
		player.sexyPJS();
		
	}
		
	


	


	

	

}

