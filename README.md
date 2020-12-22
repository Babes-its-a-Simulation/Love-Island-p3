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
	string couple1;
	string banter;
	string banternight;
	string geography;


	/*Islander names: Alex, Adrian, Taylor, Morgan, Jamie, Blake */

	void intro() {
		cout << " " << endl;
		cout << "Well you're proper fit luv I'll tell ya that." << endl;
		cout << " " << endl;
		cout << "What's ya name darling." << endl;
		cin >> name;
		cout << "Gorgeous name "<< name<<". I bet ya make ya mum proud with it" << endl;
	}


	void bitaBanter() {

		/* for this function its between the player and couple1 . these are both strings with names*/
		// couple1 = your love choice
		// name = your name that you put in

		cout << " " << endl;
		cout << "* It's time for some banter with you chosen mate <3. " << endl;

		if (couple1 == Alex) {
			cout << " " << endl;
			cout << "*Alex comes to sit next to ya* " << endl;
			cout << "Alex: Hey" << name << endl;
			cout << "* You and Alex begin having a chat. The banter is fairly dry.*"
			cout << " " << endl;
			cout << "Alex: Right, I don't know about this chat. " << endl;
			cout << "I don't think we're clicking very well eh?" << endl;
			cout << "I think I'd rather go for chat with another Islander right abouts now. " << endl;
			cout << " " << endl;
			cout << "*Alex leaves and you're feeling a bit dodgy about them.* " << endl;
	
		}

		else {
			cout << " " << endl;
			cout << couple1 << " comes to sit next to ya at the pool." << endl;
			cout << couple1 <<": Hey " << name << endl;
			cout << "*" << couple1 << " and ya begin having a chat. The banter is starting off fairly nice. " << endl;
			cout << " " << endl;
			cout << couple1 << ": I'm quite happy with our chat. " << endl;
			cout << " It's quite nice talking to ya, innit? " << endl;
			cout << " Would you like to talk by the fire? *yes or no?*" << endl;
			cin >> banter;

			if (banter == yes) {
				cout << " " << endl;
				cout << couple1 << ": I'm glad we moved over here, away from everyone. " << endl;
				cout << " It's mighty fine to have a chat with someone as fit as yaself. " << endl;
				cout << "* You and " << couple1 << "have a fine chat by the fire.*" << endl;
				cout << "* The chat continues for what feels like hours.*" << endl;
				
				}
			
			else {
				cout << " " << endl;
				cout << "*" << couple1 << " and ya stay talking by the pool.* " << endl;
				cout << "*The chat turns out very nice. You and " << couple1 << " have a nice bit of banter between you." << endl;


			}
			
			cout << "* You and " << couple1 << " learn more details about each others lives before the island." << endl;
			cout << "*Both of ya leave feeling very chuffed, and happy with the coupling." << endl;



		}
		cout << " " << endl;
		cout << "* It's the end of a long day on Love Island. *" << endl;
		cout << "* Islander, are you ready for bed? Reply yes* " << endl;
		cin >> banternight
		cout << "* You and the other Islanders fall asleep, awaiting the new day" << endl;


	}

		void muggedOff() {
		cout << " " << endl;
		cout << " " << endl;
		cout << "* It's a new day on Love Island after last night's banter. *" << endl;
		cout << "* Its a hot, sunny day at the villa, and tempers could start flaring* " << endl;
		cout << " " << endl;
		cout << "* Press any key to continue * " << endl;
		cin >> mugged;
		cout << " " << endl;

		if (couple1 == Alex) {
			cout << "*You and Alex had quite a bad chat last night* " << endl;
			cout << "* You figure you might go have another chat with them* " << endl;
			cout << "* Entering their room, you notice Alex is already awake" << endl;
			cout << "Alex: Right its about time I figure we have a chat." << endl;
			cout << "Where do you want to have this chat? In me room or by the pool?" << endl;
			cout << " " << endl;
			cout << "*Reply with room or pool* " << endl;
			cin >> muggedOne;
			if (muggedOne == room) {
				cout << " " << endl;
				cout << "Alex: Right I guess we will stay in here then. " << endl;
				cout << "I wish we coulda gone out by the pool. It looks lovely out there. " << endl;
				cout << "We can't even agree on the weather. Its like we hardly see eye to eye on anything. " << endl;
				cout << " Do you think we got a connection between us?" << endl;
				cin >> muggedThree 
					if (muggedThree == yes) {
						cout << " " << endl;
						cout << "Alex: Well I just don't think we do. " << endl;
					}

					else {
						cout << " " << endl;
						cout << "Right, well at least we agree on something. " << endl;
					}
				cout << " I think its best just for you to bugger off now. " << endl;

				}
			
			else {
				cout << " " << endl;
				cout << "*You and Alex make your way to the pool* " << endl;
				cout << "Alex: Its bloody hot out here. I wish we coulda stayed inside. " << endl;
				cout << "We can't even agree on the weather. Its like we hardly see eye to eye on anything. " << endl;
				cout << " Do you think we got a connection between us?" << endl;
				cin >> muggedThree;
					if (muggedThree == yes) {
						cout << " " << endl;
						cout << "Alex: Well I just don't think we do. " << endl;
					}

					else {
						cout << " " << endl;
						cout << "Right, well at least we agree on something. " << endl;
					}
				cout << " I think its best just for you to bugger off now. " << endl;
				cout << " " << endl;

			}

		}

		else {
			cout << "*You go and find " << couple1 << " to pull them for a chat.*" << endl;
			cout << couple1 << ": Good morning " << name << "." << endl;
			cout << " " << endl;
			cout << "*Reply with your next statment to " << couple1 << ". A simple good morning works the best!" << endl;
			cin >> muggedTwo
			cout << " " << endl;
			cout << couple1 <<  ": Mighty fine morning we got here today. " << endl;
			cout << "Theres soemthing bothering me about Alex. " << endl;
			cout << "Do you feel the same? " << endl;
			cin >> muggedFour;
				if (muggedFour == yes) {
					cout << " " << endl;
					cout << couple1 << ": Right, I'm glad someone else noticed it too. " << endl;
				}
				
				else {
					cout << " " << endl;
					cout << couple1 << ": Oh thats a bit strange. They've been quite brash to me. " << endl;
					cout << "Let me tell ya why they're a twat. " << endl;
				}
			cout << "Alex has got me quite mugged off. " << endl;
			cout << "They're rude to the other Islanders, and they've not been my fancy. " << endl;
			cout << "I'll tell you what, I'd want them off the Island eventually. " << endl;
			cout << "I'm glad I could get some of this off me chest with ya. " << endl;
			cout << " " << endl;

		}

		cout << "------------------------------------------- " << endl;
		cout << " " << endl;
		cout << "* It's been quite a day so far at the villa. *" << endl;
		cout << "* Keep playing to find love, and see where Love Island takes you. " << endl;
		cout << " " << endl;
		cout << "* Press any key to continue *" << endl;
		cout << " " << endl;
		cin >> muggedFive;
		cout << " " << endl;

	}

	void Chat() {
			cout << "Blake: It's such a nice night out, I wonder what connections everyone is making." << endl;
		cout << "So babes, is there anyone that your feeling a connection with?" << endl;
		cout << " " << endl;
		cout << "*Your options are Alex, Adrian, Taylor, Morgan, Jamie, or Blake.*" << endl;
		cin >> connection;

		if (connection == Alex) {
			cout << "Oh um well I don't know why you'd pick me after our morning" << endl;
			cout << "*Alex awkwardly leaves" << endl;
			cout << " " << endl;
			cout << "*Uh oh babes, it looks like you made things even more weird between alex and ya" << endl;
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
			cout << "Adrian: OOH HOO babes I knew you liked to have some fun. Fashion Fashion Diva baby" << endl;
			int sexy = 1;
		}
		else if(maybeSexyPJs == "no"){
			cout << "Adrian: hmm maybe you're right. I'll keep it a surprise for later." << endl; 
			int sexy = 2;
		}
		else {
			cout << "Well babes you're just no help huh?" << endl;
			int sexy = 3;
		}
		

	}

	void dumbMoment() {

		cout << "Good morning islander!" << endl; 
		cout << " " << endl; 
		cout << "It looks some of the islanders are in a heated discussion over by the bean bags, why don't you go join them?" << endl; 
		cout << "<It seems that Alex is confused about some things! Can you help them?>" << endl; 
		cout << " " << endl; 
		cout << "<Can you help Alex? Yes or no?>" << endl; 
		cin >> geography;

		if (geography == "yes") {
			cout << " " << endl; 
			cout << "Let's see what they're saying!" << endl;
		}

		else {
			cout << " " << endl;
			cout << "Well let's listen to what they're saying anyways." << endl;
		}

		cout << " " << endl; 
		cout << "Alex: So Essex is a continent right?" << endl;
		cout << "Hmmmm I'm not sure if that sounds right." << endl;
		cout << " " << endl; 
		cout << "<What do you think islander? Is Essex a continent or is it county?" << endl;
		cin >> geography;
		cout << " " << endl; 

		if (geography == "continent") {
			cout << "Last time I checked, it was a county! You need to brush up on your geography islander." << endl;
		}

		else if (geography == "county") {
			cout << "Nice job islander! Maybe you lot are smarter than the public gives ya credit for!" << endl;
		}

		cout << " " << endl; 
		cout << "Alex: So if I go in a plane for holiday, that's still the United Kingdom isn't it?" << endl;
		cout << "Morgan: Well it depends on where you want to go." << endl;
		cout << "Alex: So Spain?" << endl;
		cout << " " << endl;
		cout << "<Islander, is Spain in the United Kingdom?>" << endl;
		cin >> geography;

		if (geography == "yes") {
			cout << "Oh no darlin'. That's just not right is it." << endl;
		}
		else if (geography == "no") {
			cout << "Thank god that at least one of you lot has common sense." << endl;
		}

		cout << " " << endl; 
		cout << "These are some pretty silly questions from Alex, maybe it was a good thing that you two didn't work together." << endl;



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


	/*Game Introduction*/
	

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
	int firstKiss = 0;
	string connection;
	int sexy;
	string couple1;

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

	
	/*		heres the code to generate a random person
	* 
	srand((unsigned)time(0));
	flirt = (rand() % 6) + 1;
	cout << "*As they all walk in " << names[flirt] << " casts quite the apprieciative glance at ya*" << endl;
	cout << " " << endl;
	*/
	/*Islander names: Alex, Adrian, Taylor, Morgan, Jamie, Blake */



	/*Characters Introduction and job selection*/

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

	/*First Coupling*/

	cout << "'All ISLANDERS PLEASE GATHER AROUND THE FIREPLACE.'" << endl;
	cout << "It's time to form our first couples." << endl;
	cout << " " << endl;
	cout << "* As you look out into the villa, you begin to wonder how the night will play out." << endl;
	

	
	if (gender == lad) {
		cout << "* You're informed you're the first one to step out and jitters travel up your spine*" << endl;
		cout << "You make your way to the group and stand in front of them, right next to our Love Island Host Laura Whitmore" << endl;
		cout << "Laura: Alright Islanders, you know the deal, if you fancy this young lad take a step forward" << endl;
		cout << "Nobody moves, you start sweating your socks off" << endl;
		cout << " " << endl;
		cout << " " << endl;
		/*next lines generate a random person to step forward*/
		srand((unsigned)time(0));
		flirt = (rand() % 6) + 1;
		cout << "Finally, " << names[flirt] << " takes a step forward" << endl;
		cout << " " << endl;
		cout << "Laura: " << names[flirt] << " what made you step forward?" << endl;
		cout << names[flirt] << ": well, you see, there's just something about him that I really like. Maybe it's the shorts." << endl;
		cout << " " << endl;
		cout << "Laura: ok " << name << ", even though " << names[flirt] << "stepped forward for you. You can still choose to couple up with any of the girls here." << endl;
		cout << " Who would you like to couple up with?" << endl;
		cout << "Currently standing in front of you is Alex, Morgan, Adrian, Taylor, Jamie, and Blake." << names[flirt] << " has taken a fancy towards ya." << endl;
		cin >> couple1;
		cout << "Fabulous choice darling, you and " << couple1 << " look adorable together!" << endl;
		cout << " " << endl;
		cout << " Islanders, we have our first couple!!" << endl;

	}
	else {

		cout << "*You're informed you're the first one to step out and jitters travel up your spine*" << endl;
		cout << "You make your way to the group and stand in front of them, right next to our Love Island Host Laura Whitmore" << endl;
		cout << "Laura: Alright Islanders, you know the deal, if you fancy this pretty lady take a step forward" << endl;
		cout << "Nobody moves, you start sweating your socks off" << endl;
		cout << " " << endl;
		cout << " " << endl;
		/*next lines generate a random person to step forward*/
		srand((unsigned)time(0));
		flirt = (rand() % 6) + 1;
		cout << "Finally, " << names[flirt] << " takes a step forward" << endl;
		cout << " " << endl;
		cout << "Laura: " << names[flirt] << " what made you step forward?" << endl;
		cout << names[flirt] << ": well, you see, there's just something about them that I really like. Maybe it's the shorts." << endl;
		cout << " " << endl;
		cout << "Laura: ok " << name << ", even though " << names[flirt] << "stepped forward for you. You can still choose to couple up with any of the girls here." << endl;
		cout << " Who would you like to couple up with?" << endl;
		cout << "Currently standing in front of you is Alex, Morgan, Adrian, Taylor, Jamie, and Blake." << names[flirt] << " has taken a fancy towards ya." << endl;
		cin >> couple1;
		cout << "Fabulous choice darling, you and " << couple1 << " look adorable together!" << endl;
		cout << " " << endl;
		cout << " Islanders, we have our first couple!!" << endl;

	}

	cout << "*You and " << couple1 << " Head over towards the pool to wait while the others couple up." << endl;
	/*Have they got a bit a banter between them?*/

	player.bitaBanter();
	
	/*Second Scene*/


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
	cout << "*End of Day 1*" << endl;
	cout << " " << endl;
	cout << " " << endl;
	cout << "*Everyone is buzzing. Our Love Island Journey has taken it's first steps*" << endl;
	cout << "^As the excitement of the first day wears off, you head to the bathroom to get ready for bed." << endl;

	
	if (gender == "lad "&& connection != "Taylor" && connection != "Adrian") {
		player.sexyPJS();

		if (sexy == 1 || sexy == 2) {
			cout << "As you and the lads head into the bed chamber, you  realize" << endl;

		}
		
	}
	
		
	


	


	

	

}


