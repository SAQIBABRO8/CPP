
#include<iostream>
#include<string>    //for string
using namespace std;
 

//f(x)=x^2 + 2
int add(int a,int b)
{
	int c;
	c=a+b;
	return c;
	
	class Employee {
			public:
				string name;
				int salary;
		};
}


int main(){
	
	//cout<<"hello someone"<<endl;
	//cout<<"next line"; 
	//int a,b,c;
	//short sa =9;
	//cout<<sa;
	
	
//camel case notation

//[data types] 
   
	//int marksInMaths = 83;
    //cout<< marksInMaths;
    //cout<<"the marks of saqib in maths is " <<marksInMaths;
	
	//[variables]
	
	//string harry = "harry"
	//short a;
	//int b;
	//long c;
	//long long d; 
	
	//float const score = 45.32;
	//double score2 = 45.322;
	//long double score3 = 45.332;
	//score = 34.2;
	//cout<<"the score is "<<score ;

//inter user input
	
	//int a,b;
	//cout<<"enter first number "<<endl ;
	//cin>>a;
	
	//cout<<"enter second number "<<endl ;
	//cin>>b;
	
	//[operations]
	
	
	/*cout<<"the sum is "<< a+b <<endl;
	cout<<"the diff is "<< a-b <<endl;
	cout<<"the multi is "<< a*b <<endl;
	cout<<"the division is "<<(float) a/b <<endl;*/
	
	/*cout<<" a+b is " << a+b<<endl;
	cout<<" a-b is " << a-b<<endl;
	cout<<" a*b is " << a*b<<endl;
	cout<<" a/b is " <<(float) a/b<<endl;*/
	
	
	/*int age; 
	cout<<" enter your age " <<endl;
	cin>>age;
    
    //[SWITCH STATEMENT]
	 switch (age)
	 {
	case 12:
	 	cout<<" you are 12 years old "<<endl;
	 	break;
	 	
	case 18:
	 	cout<<" you are 18 years old "<<endl;
	 	break;
	 	
	default:
	cout<<"you are neither 12 nor 18 years old ";
	    
	 }
	

	//[if else statement]
	
	 if(age>150 ||age<1)
	{
		cout<<" Invalid age ";
	}
	
	 else if (age>=18){
		cout<<" you can vote ";
	}
	
	
	else
	{
		cout<<" you cannot vote ";
	}*/
	
	
	//[LOOPS STATEMENT]
	//int index = 0;
	/*1while(index<34)
	{
		cout<<" we are at index number "<<index<<endl;
		index = index + 1;
	} */
	
	/*2 do
	{
cout<<" we are at index number "<<index<<endl;
		index = index + 1;	
		
	}while(index<33)*/
	
	/*for (int i = 1; i <= 34; i++)
	{
		cout<<"the value of i is "<<i<<endl;
    }
	
	//[funtion]
	
	/*int a,b;
	cout<<"enter first number "<<endl ;
	cin>>a;
	
	cout<<"enter second number "<<endl ;
	cin>>b;
	cout<<"the function returned "<<add(a,b);*/
	
	//[ARRAYS]
	
	/*int arr[3] =  {1,3,6};
//array index     0, 1, 2
	//cout<<arr[1];
	int marks[6];
	for (int i=0; i<6; i++)
	{
		cout<<"enter the marks of "<<i<<"th student"<<endl;
		cin>>marks[i];
	}
	
	for (int i=0; i<6; i++)
	{
		cout<<"marks of "<<i<<"th student is "<<marks[i]<<endl;
		
	}	
       	
	/*int arr2d[2][3]={{1,2,3},
	                 {4,5,6}};
   for (int i=0; i<2; i++) 
   {
   	for (int j=0; j<3; j++)
   	{
   		cout<<"the value at " <<i<<","<<j<<"is" <<arr2d[i][j]<<endl;
	   }
   }*/
	
		//[type casting]// 
		
		 /*int a=353;
		 float b =87.94;
		 cout<<(float) a/34<<endl;
		 
		 cout<<(int)b;*/
		 
		 //[STRINGS]//
		 
		 /*string name = "SAQIB ABRO";
		 cout<<" The name is " <<name<<endl;
		 cout<<" The  length of name is " <<name.length()<<endl;
		 cout<<" The name is " <<name.substr(0,3)<<endl;
		 cout<<" The name is " <<name.substr(2,3)<<endl;*/
		 
		 
		 //[POINTERS CONCEPT]//
		 
		/* int a=34; //or use float
		 int* ptra; //or use float
		 ptra = & a;
		// cout<<ptra;
		 //cout<<*ptra;
		 cout<<"the value of a is "<<a<<endl;
		 cout<<"the value of a is "<<*ptra<<endl;
		 cout<<"the address of a is "<<&a<<endl;
	     cout<<"the value of a is "<<ptra<<endl;*/
		 
	
	    // [OBJECT & CLASSES]//
	    
 employee saq;
saq.name ="saqib";
saq.salary = 100;
cout<<"the name of our first employee is "<<saq.name<<" and his salary is "<<saq.salary<<endl;
	
		
		
		
		
       	
	return 0;
}
