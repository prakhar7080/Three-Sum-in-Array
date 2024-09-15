//# Three-Sum-in-Array
#include<iostream>
using namespace std;
int main(){
    int a[5] = {10,5,20,15,30};
    int n =5;
    int i,j,k;
    int target = 20;
    bool check;
    for(i=0;i<n;i++){
        for(j=0;j<n;j++){
            for(k=0;k<n;k++){
                    if(a[i]+a[j]+a[k] == target){
                    check = true;
                    cout<<a[i]<<","<<a[j]<<","<<a[k]<<endl;
                }
            
            }
        }
    }
    if(check == true) cout<<"Triplet exists"<<endl;
    else cout<<"Triplet does not exists"<<endl;
    
    return 0;
}
