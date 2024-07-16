#include<iostream>
using namespace std;
class stack
{
    int a[10];
    int top;
    public:
     stack()
    {
        top=0;
    }
    void push()
    {
        if (top==10)
        {
            cout<<"The stack is full";
            return;
        }
        else{
            top=top+1;
            cout<<"\n Enter the number to insert:";
            cin>>top[a];
        }
    }
    void pop()
    {
        if(top==0)
        {
            cout<<" \n The stack is empty";
            return;
        }
        else
        {
            cout<<"\n The deleted number is :"<<top[a];
            top=top-1;
        }
    }
    void display()
    {
        int i ;
        if(top==0)
        {
            cout<<" \n The stack is empty";
            return;
        }
        else
        {
            cout<<"\n The stack elements are \n";
            for(i=top;i>0;i--)
            {
                cout<<"\n"<<a[i];
            }
        }
    }
};

int main()
{
    stack ob;
    int ch;
    do
    {
        cout<<"\n 1.push \n 2.pop  \n 3.display \n 4.exit \n";
        cout<<"Enter your choice :";
        cin>>ch;
    
        switch(ch)
        {
            case 1:
            ob.push();
            break;
            case 2: ob.pop();
            break;
            case 3: ob.display();
            break;
        }
      
        }
          while(ch!=4);
    
}   
