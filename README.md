#include<iostream>
#include<math.h>
  using namespace std;
  int main()
  {
  int nam;
  double tienvon,laisuat,tienkivong;
  double a,b;
  cout<<"so tien ban dau:";
  cin>>tienvon;
  cout<<"lai suat hang nam:";
  cin>>laisuat;
  cout<<"so tien ki vong:";
  cin>>tienkivong;
  if (tienvon >= tienkivong)
  {
  cout<<"so tien ki vong dang thap hon hoac bang von" << endl;
  }
  else
  {
  laisuat = double(laisuat/100);
  a = double(tienkivong/tienvon);
  b = double(1+laisuat);
  nam = double(log(a)/log(b));
  cout<<"so nam can thiet de co so tien ki vong :"<<nam;
  return 0;
  }
  }
  
