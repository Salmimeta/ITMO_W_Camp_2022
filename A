#include <iostream>

using namespace std;

int main(){
    int t,n,a,q,on=0;   cin >> t;
    string s,ans;

    while (t--){
        on=0;
        cin >> n >> a >> q >> s ;

        for (int i=0;i<q;i++){
            if (s[i]=='+'){
                on++;
            }else {
                on--;
            }
        }
        if (a==n || a+on>=n){
            ans=ans+"YES"+"\n";
        }else if (!on){
            ans=ans+"MAYBE"+"\n";
        }else {
            ans=ans+"NO"+"\n";
        }
    }

    cout << ans;

 return 0;
 }
