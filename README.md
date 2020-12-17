#include <iostream>
  using namespace std;
  
  
  class Islander{
  
  public:
  
  
	string name;
	string maybeSexyPJs;
	string yes = yes;
	string no = no;
	int sexy;
  
  
	void intro() {
		cout << " " << endl;
		cout << "Well you're proper fit luv I'll tell ya that." << endl;
		cout << " " << endl;
		cout << "What's ya name darling." << endl;
		cin >> name;
		cout << "Gorgeous name "<< name<<". I bet ya make ya mum proud with it" << endl;
	}
  
  void firstCoupling(){
  
  }
  
  void bitaBanter(){
  
  }
  
  void muggedOff(){
  
  }
  
  void Chat(){

  }
  
  void sexyPJS(){
	 	cout << "*Aridan walks into the changing room*" << endl;
		cout << "Adrian wants to know whether or not to put on some sexy PJs for alex tonight" << endl;
		cout << "Taylor says there's never a time not to wear some sexy PJs" << endl;
		cout << "Do you think Aridan should wear some sexy PJs ?" << endl;
		cout << "Please enter yes or no." << endl;
		cin >> maybeSexyPJs;

		if (maybeSexyPJs == yes) {
			cout << "Aridan: OOH HOO babes I knew you liked to have some fun. Imma go all out for alex." << endl;
			int sexy = 1;
		}
		else(maybeSexyPJs == no){
			cout << "Aridan: hmm maybe you're right. I'll keep it a surprise for later." << endl; 
			int sexy = 2;
		}
  
  }
  
  void dumbMoment(){
  
  }
  
  void recoupling(){
  
  }
  
  
  };
  
  
 int main() {


	string gender;

	cout << "Finding Love can be tough, life is nothing but work, eat, sleep, repeat." << endl;
	cout << "It's time to get off social media and find love the old fashion way" << endl;
	cout<< "in a REALITY TV SHOW"<<endl;
	cout << " " << endl;
	cout << " " << endl;
	cout << "WELCOME TO LOVE ISLAND !!! <3" << endl;;
	cout << " " << endl;
	cout << " " << endl;
	cout << "Starting with the nitty gritty" << endl;
	cout<<"babes are ya a bird or a mate? " << endl;
	cin >> gender;
	
	

	string mate = "mate";
	string bird = "bird";
	string name;
	string maType;

	if (mate == gender) {
		player.intro();
		cout << "Alight babes now then what's ya type?" <<endl;
		cin >> maType;
		cout << "You're a cheeky one aren't ya." << endl;
		cout << " " << endl;
		cout << "Alright Islander it's time to meet the girls" << endl;
	}
	else if (bird == gender) {
		player.intro();
		cout << "Now darling whats ya type? Mine's tall dark and handsome." << endl;
		cin >> maType;
		cout << "OOoh ya, now that's nice" << endl;
		cout << " " << endl;
		cout << "Alright Islander it's time to meet the lads" << endl;
	}
	else {
		cout << "Uh Oh babes I just don't get it, which one is ya?" << endl;
		cin >> gender;
		/*Flaw doesnt execute the rest of the code if you input the wrong choice*/
	}



}
  
  
  
  
  
  
