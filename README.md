# Codeforcescpp-239A
#include <bits/stdc++.h>
using namespace std;

int main() {
	int y,k,n,flag(0);
  cin >> y >> k >> n;
  int tmp = k - y%k;
  while(tmp+y<=n){
    cout << tmp << " ";
    tmp+=k;
    flag = 1;
  }
  if(flag==0)
    cout << -1;
	return 0;
}
