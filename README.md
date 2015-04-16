# Quiz-9..2
#include<iostream>
using namespace std;

long superpower(int x, int y){
int i = 0;
long z = 1;

do{

i = i + 1;
z = z * x;

}while(i<y);

return z;
}

int main(){
int x, y;

cout << "Dame a^b"<< endl;
cout << "a"<<endl;
cin >> x;
cout <<"b"<< endl;
cin >> y;

cout << "La respuesta es = "<< superpower(x, y) << endl;

return 0;
}
