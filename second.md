#include<iostream>

using namespace std;

class myclass1
{

public:
	void disp1()
  
	{
		
		cout<<"in disp1";
	}

};

class myclass2
{

public:

	void disp2(myclass1 &ref)
  
	{    
	
		cout<<"in disp 2";
		ref.disp1();
	}
};

int main()
{
	
	myclass2 m2;
	myclass1 m1;
	m2.disp2(m1);	
	return 0;
}

Output:
