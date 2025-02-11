# Boy-or-Girl
#include<iostream>
#include<string>
using namespace std;
int main(){
    string name;
    cin>>name;
    int count=0;
    bool seen[256]={false};
    for(int i=0;i<name.length();i++){
        if(!seen[name[i]]){
        seen[name[i]]=true;
        count++;
    }}
    if(count%2==0){
        cout<<"CHAT WITH HER!";
    }
    else{
        cout<<"IGNORE HIM!";
    }
}
