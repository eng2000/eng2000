#include <iostream>
#include <string>
using namespace std;
string  theword (string w,char b) {
    string ch1;
    for(int i=0;i<w.length();i++){
        if (w.at(i)!=b){
            ch1+=w.at(i);
        }
    }
    return ch1;
}


int main() {
    string word;
    getline(cin,word);
    char c;
    cout <<"enter char went remove";
    cin>>c;
    string ch1=theword(word,c);
    cout<<ch1;
    

    return 0;
}
