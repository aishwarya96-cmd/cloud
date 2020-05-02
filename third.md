# ***Display output using Virtual function***

```
#include<iostream>
using namespace std;
class myclass1
{
public:
    myclass1()
  {  
   
   }
  virtual void function()
  {
     
    cout << "in myclass1" << endl;
  }
  }
;
class myclass2 :public myclass1
{
public:
  myclass2()
  {}

void function()
{
  cout << "in myclass2" << endl;
    
    }
   };

int main()
{
       myclass1 m;
	m.function();
	myclass2 m1;
	myclass1 *m2 = &m1;
	m2->function();
}
```
## Output:
![3rd](https://user-images.githubusercontent.com/63540937/80867236-57ebcc00-8cbd-11ea-8444-e14f49cba088.jpg)
