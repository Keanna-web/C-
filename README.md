#include <iostream>
using namespace std;

int main(){
    string search;
    cout<<"Choose a dog breed: ";
    cin>>search;

    if (search == "labrador"){
        cout<<"Friendly";
    }
    else if (search == "husky"){
        cout<<"Energetic";
    }
    else if (search == "bulldog"){
        cout<<"Loyal";
    }
    else if (search == "poodle"){
        cout<<"Intelligent";
    }
    else if (search == "chihuahua"){
        cout<<"Bold";
    }
    else{
        cout<<"Unknown breed";
    }
    
    return 0;
}
