# Lab-21.40
#include <iostream>
using namespace std;

double func ( double n1 ) {
  cout << " 2  4  3 " << endl;
  return n1;
} 
double func (double n1, double n2) {
  cout << " 3  1.1  2.3 " << endl;
  return n2;
}
double func (double n1, double n2, double n3) {
  cout << " 2  4  2.3" << endl;
  return n3;
}
double func (double n1, double n2, double n3, double n4) {
  cout << " 2  1.1  3 " << endl;
  return n4;
}

int main() {

  func(2.0);
  func(2.0, 3.0);
  func(2.0, 3.0, 4.0);
  func(2.0, 3.0, 4.0, 5.0);

}


