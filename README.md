# class
#include<iostream>
using namespace std;
class first
{
private:
    int a,b,c;
public:
    int d,e;
    void setdata(int a1 , int b1 , int c1);
    void getdata(){
        cout<<"the value of a is "<<a<<endl;
        cout<<"the value of b is "<<b<<endl;
        cout<<"the value of c is "<<c<<endl;
        cout<<"the value of d is "<<d<<endl;
        cout<<"the value of e is "<<e<<endl;
    }
  
};
void first :: setdata(int a1 , int b1 , int c1){
    a = a1;
    b = b1;
    c = c1;
}

int main(){
    first s;
    s.setdata(2,4,6);
    s.d = 8;
    s.e = 12;
    s.getdata();
    return 0;
}
