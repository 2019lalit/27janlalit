                        -----------------top c++ program for interview------------


//check the number is prime or not
#include<bits/stdc++.h>
using namespace std;
string prime(int n){
    if(n<=1){
        return "not prime";
    }
    for(int i=2;i<n;i++){
        if(n%i==0){
            return "not prime";
        }
    } return "prime";
}
int main(){
    int n;
    cout<<"please enter a number"<<endl;
    cin>>n;
    cout<<prime(n);
    return 0;
}
     ---------------------------------------------------------------------------------------------
//c++ program using function to find fibonacci series given range

#include<bits/stdc++.h>
using namespace std;
void lalit(int range){
    int a=0;int b=1; int next;
    cout<<"print"<<range<<" fibonaaci series ";
    for(int i=1;i<=range;i++){
        if(i==1){
            cout<<a<<" ";
            continue;
        }if(i==2){
            cout<<b<<" ";
            continue;
        }
        next=a+b;
        cout<<next<<" ";
        a=b;
        b=next;
    }
    cout<<endl;
    
    
}
int main(){
    int range;
    cout<<"plese enter a range :"<<endl;
    cin>>range;
    lalit(range);
    return 0;
}
-----------------------------------------------------------------------------------------------------------------------------------
// write a c++ program swap two variable without using third variable;
#include<bits/stdc++.h>
using namespace std;
int lalit(int a,int b){
          a=a+b;
          b=a-b;
          a=a-b;
          cout<<"the value of a is "<<a<<endl;
          cout<<"the value of b is "<<b<<endl;
          return 0;
}
int main(){
    int a; int b;
    cout<<"please enter a value "<<endl;
    cin>>a;
        cout<<"please enter b value"<<endl;
        cin>>b;
    
    cout<<lalit(a,b);
    return 0;
}
--------------------------------------------------------------------------------------------------------------------------------------------------
//factorial of given input number:
#include<bits/stdc++.h>
using namespace std;
int lalit(int n){
    int fact=1;
    for(int i=1;i<=n;i++){
        fact=fact*i;
    }
    return fact;
}
int main(){
    int n;
    cout<<"please enter a factorial number "<<endl;
    cin>>n;
    cout<<lalit(n);
    return 0;
}

--------------------------------------------------------------------------------------------------------------------------------------------------
