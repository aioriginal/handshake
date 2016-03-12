# handshake
https://www.hackerrank.com/challenges/handshake
#include <iostream>
using namespace std;

#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
     int  t,n;
     std::cin >> t;
     
    for(int i=0; i<=t; i++);
   {
        std::cin >> n;
        int y;
        y= n*(n-1)/2;
        //printf("%d\n", y);
        std::cout << y << std::endl;
    }
	return 0;
}
