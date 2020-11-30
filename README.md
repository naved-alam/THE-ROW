#include<iostream.h>
#include<conio.h>
#include<stdlib.h>
void main()
{


			randomize();
			int n;
			cout<<"Ramdom Number Swastic-:";
			//n=random(10);
			//cout<<n<<endl;
			cin>>n;

			for(int i=1;i<=(2*n)-1;i++)
			{
				 if(i==1)
				 {
						cout<<"*";
						for(int m=1;m<=n-2;m++)
						{
								cout<<" ";
						}
						for(int b=1;b<=n;b++)
						{
								cout<<"*";
						}
				 }
				 if(i>1&&i<n)
				 {
						cout<<"*";
						for(int m=1;m<=n-2;m++)
						{
								cout<<" ";
						}
						cout<<"*";
				 }
				 if(i==n)
				 {
						for(int a=1;a<=(2*n)-1;a++)
						{
								cout<<"*";
						}
				 }
				 if(i>n)
				 {
						if(i<((2*n)-1))
						{
								for(int g=1;g<n;g++)
								{
										cout<<" ";
								}
						cout<<"*";
						}
						else
						{
								for(int h=1;h<=n;h++)
								{
									  cout<<"*";
								}
						}
						for(int t=1;t<n-1;t++)
						{
								cout<<" ";
						}
						cout<<"*";
				 }
				 cout<<endl;
			}
			getch();
}
