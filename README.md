# Acha
Nothing 
#include <iostream>
using namespace std;
int main()
{
	double lenght, width, area_sq, kanal;
	cout<<"Enter Lenght:";
	cin>>lenght;
	cout<<"\nEnter Widht:";
	cin>>width;
	area_sq=lenght*width;
	kanal=area_sq/505.857;
	cout<<"The area in SQ meter is:"<<area_sq<<"n^2\n";
	cout<<"Area in Kanal is:"<<kanal;
	return 0;
}
