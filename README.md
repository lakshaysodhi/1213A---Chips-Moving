# 1213A---Chips-Moving
#include <bits/stdc++.h>
using namespace std;

int main() {

    int n;
    cin>>n;
    vector<int> A(n);
    int even=0,odd=0;
    for(int i=0;i<n;i++){
        cin>>A[i];
        if(A[i]%2==0) even++;
        else odd++;
    }
    if(even<odd){
        cout<<even;
    }else cout<<odd;
    return 0;



}

