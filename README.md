#include<iostream>
#include<cstdlib>
#include<ctime>
using namespace std;
int main(){
srand(time(0));
int n=rand()%100+1,g;
cout<<"guess the number between 1 to 100 :";
while(cin>>g&&g!=n)
{
	cout<<(g<n ?"too low....":"tooo high....")<<"  try again.";
	
}
cout<<"correct!! the number was"<<n<<endl;
return 0;
}
