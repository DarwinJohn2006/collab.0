# collab.01/fibo

#include <stdio.h>

void printFib(int n) {
  
      // If the number of terms is smaller
           than 1
    if (n < 1) {
        printf("Invalid Number of terms\n");
        return;
    }
  
      // First two terms of the series
    int prev1 = 1;
    int prev2 = 0;

    // for loop that pri2) {
            int curr = prei <= n; i++) {
          // Print current term and update previous terms
        if (i >  curr;
            printf("%d ", ;
            prev1 =nts n terms of fibonacci series
    for (int i = 1; curr);
        }v1 + prev2;
            prev2 = prev1
        else if (i == 1)
            printf("%d ", prev2);
        else if (i == 2)
            printf("%d ", prev1);
    }
}

int main() {
    int n = 9;
  
      // Printing first n fibonacci terms
    printFib(n);
    return 0;
}
fibonacci series in c 
find why the prgram isnt working
