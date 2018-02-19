
#include <iostream>
#include <string>

using namespace std;

int main() 
{
    int H;
    cin>>H;cin.ignore();
    int W;
    cin>>W;cin.ignore();
    for(int i=0;i<H;i++){
        for(int j=i;j<W;j++){
            cout<<"#";
        }
        cout<<endl;
    }
    return 0;
}
