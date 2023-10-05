# My-Cpp-Code

//Pattern Question
#include <iostream>
using namespace std;

int main() {




  //pattern printing 1

 /*int n;
  cin >> n;

  int i = 1;

  while(i<=n) {
    int j=1;
    while(j<=n ){
        cout<< n-j+1;
        j=j+1;
    }
    cout<<endl;
    i=i+1;*/




    //pattern printing 2

    /*int n;
    cin>>n;
    int i=1;
    int count = 1;
    while(i<=n){
      int j =1;
      while(j<=n) {
        cout<<count<<" ";
        count = count + 1;
        j=j+1;
      }
      cout<<endl;
      i = i+1; */





      //Triangle pattern

   /*int n;
cin>>n;
 int row = 1;
 while(row<=n){
  int col = 1 ;
  while(col<=n){
    char ch = 'A' + row - 1;
    cout<<ch;
    col = col + 1;
  }
  cout<<endl;
  row = row + 1 ;
 } */





      //pattern column

      /*int n;
      cin>>n;

      int row = 1;

      while(row<=n) {
        int col = 1;
        while(col<=row) {
          cout<<col;
          col = col + 1;
        }
        cout<<endl;
        row=row+1;
    }  */




// pattern 5

/*int n;
cin>>n;

int row = 1;
while(row<=n) {
  int col=1;
  int value = row;
  while(col<=row) {
    cout<<value;
    value = value + 1;
    col = col + 1;
  }
  cout<<endl;
  row = row +1;
} */




//pattern 6 using i-j+1

/*int n;
cin>>n;

int i = 1;

while(i <=n){
  int j = 1;
  while(j <= i){
    cout<<(i-j+1)<<" ";
    j = j + 1;
  }
  cout<<endl;
  i=i+1;
} */



//Pattern 7 AAA BBB  CCC Square  type (using 'A' + i -1)

/* int n;
cin>>n;
 int row = 1;
 while(row<=n){
  int col = 1 ;
  while(col<=n){
    char ch = 'A' + row - 1;
    cout<<ch;
    col = col + 1;
  }
  cout<<endl;
  row = row + 1 ;
 }  */



// Pattern 8 ABC  ABC  ABC Type(using 'A' + j-1)

/*int n;
cin>>n;

int row = 1;

while(row<=n){
  int col = 1;
  while(col<=n){
    char ch = 'A' + col -1;
    cout<<ch;
    col = col + 1;
  }
  cout<<endl;
  row = row + 1;
}  */




// Pattern of type ABCDEF

/*int n;
    cin>>n;
    int i=1;
    char value = 'A';
    char start = 'A';
    while(i<=n){
      int j =1;
      while(j<=n) {
        cout<<start<<" ";
        start = start+ 1;
        j=j+1;
      }
      cout<<endl;
      i = i+1;
} */



// Pattern type ABC  BCD  CDE  (using 'A' + i + j -2)

/*int n;
cin>>n;
 int row = 1;
 while(row<=n){
  int col = 1 ;
  while(col<=n){
    char ch = 'A' + row + col - 2;
    cout<<ch;
    col = col + 1;
  }
  cout<<endl;
  row = row + 1 ;
 }*/



 // Triangular pattern (using 'A' +row - 1)

 int n;
cin>>n;
 int row = 1;
 while(row<=n)
 {
  int col = 1 ;
  while(col<=row)
  {
    char ch = 'A' + row - 1;
    cout<<ch;
    col = col + 1;
  }
  cout<<endl;
  row = row + 1 ;
 }


 // reverse triangular 


/*int n;
 cin>>n;

 int row = 1;
 while(row <= n){
  //space
  int space = n - row;
  while(space){
    cout<<" ";
    space = space - 1;
  } 
// stars
int col = 1 ;
while(col <= row){
  cout<<"*";
  col = col + 1;

}
cout<<endl;
row = row + 1;

 }*/



 // Pattern reverse of above

/* int n;
 cin>>n;

 int row = 1;
 while(row <= n){

// stars
int col = 1  ;
while(col <= n - row + 1){
  cout<<"*";
  col = col + 1;

}
cout<<endl;
row = row + 1;

 } */ 
 


 //reverse triangle

/*int n;
 cin>>n;

 int row = 1;
 while(row <= n){
  //space
  int space = row - 1;
  while(space){
    cout<<" ";
    space = space - 1;
  } 
// stars
int col = 1 ;
while(col <= n-row+1){
  cout<<"*";
  col = col + 1;

}
cout<<endl;
row = row + 1;

 }*/



//3 triangle pattern 


/*int n;
cin>>n;
int i = 1;

while(i <= n){

  //print space (first triangle)
  int space = n-i;
  while(space){
    cout<<" ";
    space=space-1;
  }

  // print 2nd triangle
  int j = 1;
  while(j<= i){
    cout<<j;
    j = j + 1;
  }

  // print 3rd triangle
  int start = i-1;
  while(start){
    cout<<start;
    start = start - 1;
  }
  cout<<endl;
  i = i + 1;
}  */
}

#include <iostream>
using namespace std;

int main() {




  //pattern printing 1

 /*int n;
  cin >> n;

  int i = 1;

  while(i<=n) {
    int j=1;
    while(j<=n ){
        cout<< n-j+1;
        j=j+1;
    }
    cout<<endl;
    i=i+1;*/




    //pattern printing 2

    /*int n;
    cin>>n;
    int i=1;
    int count = 1;
    while(i<=n){
      int j =1;
      while(j<=n) {
        cout<<count<<" ";
        count = count + 1;
        j=j+1;
      }
      cout<<endl;
      i = i+1; */





      //Triangle pattern

      /*int n;
cin>>n;
 int row = 1;
 while(row<=n){
  int col = 1 ;
  while(col<=n){
    char ch = 'A' + row - 1;
    cout<<ch;
    col = col + 1;
  }
  cout<<endl;
  row = row + 1 ;
 } */





      //pattern column

      /*int n;
      cin>>n;

      int row = 1;

      while(row<=n) {
        int col = 1;
        while(col<=row) {
          cout<<col;
          col = col + 1;
        }
        cout<<endl;
        row=row+1;
    }  */




// pattern 5

/*int n;
cin>>n;

int row = 1;
while(row<=n) {
  int col=1;
  int value = row;
  while(col<=row) {
    cout<<value;
    value = value + 1;
    col = col + 1;
  }
  cout<<endl;
  row = row +1;
} */




//pattern 6 using i-j+1

/*int n;
cin>>n;

int i = 1;

while(i <=n){
  int j = 1;
  while(j <= i){
    cout<<(i-j+1)<<" ";
    j = j + 1;
  }
  cout<<endl;
  i=i+1;
} */



//Pattern 7 AAA BBB  CCC Square  type (using 'A' + i -1)

/* int n;
cin>>n;
 int row = 1;
 while(row<=n){
  int col = 1 ;
  while(col<=n){
    char ch = 'A' + row - 1;
    cout<<ch;
    col = col + 1;
  }
  cout<<endl;
  row = row + 1 ;
 }  */



// Pattern 8 ABC  ABC  ABC Type(using 'A' + j-1)

/*int n;
cin>>n;

int row = 1;

while(row<=n){
  int col = 1;
  while(col<=n){
    char ch = 'A' + col -1;
    cout<<ch;
    col = col + 1;
  }
  cout<<endl;
  row = row + 1;
}  */




// Pattern of type ABCDEF

/*int n;
    cin>>n;
    int i=1;
    char value = 'A';
    char start = 'A';
    while(i<=n){
      int j =1;
      while(j<=n) {
        cout<<start<<" ";
        start = start+ 1;
        j=j+1;
      }
      cout<<endl;
      i = i+1;
} */



// Pattern type ABC  BCD  CDE  (using 'A' + i + j -2)

/*int n;
cin>>n;
 int row = 1;
 while(row<=n){
  int col = 1 ;
  while(col<=n){
    char ch = 'A' + row + col - 2;
    cout<<ch;
    col = col + 1;
  }
  cout<<endl;
  row = row + 1 ;
 }  */



 // Triangular pattern (using 'A' +row - 1)

 /*int n;
cin>>n;
 int row = 1;
 while(row<=n){
  int col = 1 ;
  while(col<=row){
    char ch = 'A' + row - 1;
    cout<<ch;
    col = col + 1;
  }
  cout<<endl;
  row = row + 1 ;
 }*/


 // reverse triangular 


/*int n;
 cin>>n;

 int row = 1;
 while(row <= n){
  //space
  int space = n - row;
  while(space){
    cout<<" ";
    space = space - 1;
  } 
// stars
int col = 1 ;
while(col <= row){
  cout<<"*";
  col = col + 1;

}
cout<<endl;
row = row + 1;

 }*/



 // Pattern reverse of above

/* int n;
 cin>>n;

 int row = 1;
 while(row <= n){

// stars
int col = 1  ;
while(col <= n - row + 1){
  cout<<"*";
  col = col + 1;

}
cout<<endl;
row = row + 1;

 } */ 
 
 //reverse triangle

int n;
 cin>>n;

 int row = 1;
 while(row <= n){
  //space
  int space = row - 1;
  while(space){
    cout<<" ";
    space = space - 1;
  } 
// stars
int col = 1 ;
while(col <= n-row+1){
  cout<<"*";
  col = col + 1;

}
cout<<endl;
row = row + 1;

 }


}


#include <iostream>
#include <math.h>
#include<climits>
using namespace std;
/* prime b/w 2 no.s


bool isPrime(int num)
{
  for(int i = 2; i <=sqrt(num); i++)
    {
      if(num%i == 0)
      {
        return false;
      }
    }
  return true;
}
  int main()
{
  int a , b;
  cin>>a>>b;
  for(int i = a; i<=b; i++)
    {
      if(isPrime(i)){
        cout<<i<<endl;
      }
    }
    return 0 ;
  }
*/

/*Fibonacci series
void fib(int n)
{
  int t1=0;
  int t2=1;
  int nextTerm;

  for(int i = 1; i<=n; i++)
    {
      cout<<t1<<endl;
      nextTerm = t1+t2;
      t1=t2;
      t2=nextTerm;
    }
  return ;
}
int main()
{
  int n;
  cin>>n;

  fib(n);
  return 0;
}
*/

// Factorial of a number
/*
int fact(int n)
{
  int factorial = 1;
  for(int i = 2; i<=n ; i++)
    {
      factorial = factorial * i;
    }
  return factorial;
}

int main()
{
  int n;
  cin>>n;
  int ans = fact(n);
  cout<<ans<<endl;
  return 0;
}
*/

// Calculate nCr
/*

int fact(int n)
{
  int factorial = 1;
  for(int i = 2; i<=n ; i++)
    {
      factorial = factorial * i;
    }
  return factorial;
}
int main()
{
int n,r;
cin>>n>>r;

int ans = fact(n)/((fact(r)*fact(n-r)));
cout<<ans<<endl;
return 0;
}
*/

// Pascal Triangle

/*
int fact(int n)
{
  int factorial = 1;
  for(int i = 2; i<=n; i++)
    {
      factorial = factorial*i;
    }
  return factorial;
}
int main()
{
  int n;
  cin>>n;
  for(int i = 0; i<n; i++)
    {
      for(int j=0; j<=i; j++)
        {
          cout<<fact(i)/fact(j)*fact(i-j)<<" ";
        }
      cout<<endl;
    }
  return 0;
}
*/

// Sum of n natural no.

/*

int sum (int n)
{
  int ans = 0;
  for(int i=1; i<=n; i++)
     ans = ans +i;
  return ans;
}
int main()
{
  int n;
  cin>>n;
cout<< sum(n) <<endl;
}
*/

// Binary to decimal
/*
int binaryToDecimal(int n)
{
  int ans = 0;
  int x = 1;
  while(n>0)
    {
      int y = n%10 ;
      ans += x*y;
      x*= 2;
      n /=10;
    }
  return ans;
}
int main()
{
  int n;
  cin>>n;
  cout<<binaryToDecimal(n) <<endl;
}
*/

// octal to decimal
/*
int octalToDecimal(int n)
{
  int ans = 0;
  int x = 1;
  while(n>0)
    {
      int y = n%10 ;
      ans += x*y;
      x*= 8;
      n /=10;
    }
  return ans;
}
int main()
{
  int n;
  cin>>n;
  cout<<octalToDecimal(n) <<endl;
}
*/

// Decimal to Binary

/*
int decimalToBinary(int n)
{
  int x = 1;
  int ans = 0;
  while(x <=n)
    x=x*2;
  while(x>0)
    {
      int lastDigit= n/x;
      n -= lastDigit*x;
      x/=2;
      ans = ans*10 + lastDigit;

    }
  return ans;
}
int main()
{
  int n;
  cin>>n;
  cout<<decimalToBinary(n) <<endl;
}
*/

// Add two binary no.s
/*
int reverse(int n) {
  int ans = 0;
  while (n > 0) {
    int lastDigit = n % 10;
    ans = ans * 10 + lastDigit;
    n /= 10;
  }
  return ans;
}

int addBinary(int a, int b) {
  int ans = 0;
  int prevCarry = 0;

  while (a > 0 && b >0)
    {
      if (a%2 == 0 && b%2 ==0)
      {
    ans = ans * 10 + prevCarry;
    prevCarry = 0;
  }
  else if((a%2 == 0 && b%2 == 1) || (a%2 == 1 && b%2 == 0)) 
  {
    if (prevCarry == 1) {
      ans = ans * 10 = 0;
      prevCarry = 1;
    } else {
      ans = ans % 10 + 1;
      prevCarry = 0;
    }
    else {
      ans = ans * 10 + (b % 2);
    }
    b /= 10;
  }
  if (prevCarry == 1) {
    ans = ans * 10 + 1;
  }
  ans = ans(reverse)
}

int main() {
  int a, b;
  cin >> a >> b;
  cout << addBinary(a, b) << endl;
}
}
*/

//Array (initializing)
/*
int main()
{
  int n;
  cin>>n;
  int array[5];
  for(int i=0 ;i<n; i++)
    {
      cin>>array[i];
    }
  for(int i=0; i<n; i++)
    {
      cout<<array[i]<<" "<<endl;
    }
  return 0;
}
*/

//finding min and max in an array
/*
int main()
{
  int n;
  cin>>n;
  int arr[5];
  for(int i=0 ;i<n; i++)
    {
      cin>>arr[i];
    }
  int MaxNo=INT_MIN;
  int MinNo =INT_MAX;
  for(int i=0 ;i<n; i++)
    {
      if(arr[i]>MaxNo)
      {
        MaxNo = arr[i];
      }
      if(arr[i]<MinNo)
      {
        MinNo = arr[i];
      }
      cout<<MaxNo<<" "<<MinNo<<" "<<endl;
      return 0;
    }
}
*/


#include <iostream>
#include <math.h>
#include<string>
#include<algorithm>
#include<climits>
using namespace std;
/* prime b/w 2 no.s


bool isPrime(int num)
{
  for(int i = 2; i <=sqrt(num); i++)
    {
      if(num%i == 0)
      {
        return false;
      }
    }
  return true;
}
  int main()
{
  int a , b;
  cin>>a>>b;
  for(int i = a; i<=b; i++)
    {
      if(isPrime(i)){
        cout<<i<<endl;
      }
    }
    return 0 ;
  }
*/

/*Fibonacci series
void fib(int n)
{
  int t1=0;
  int t2=1;
  int nextTerm;

  for(int i = 1; i<=n; i++)
    {
      cout<<t1<<endl;
      nextTerm = t1+t2;
      t1=t2;
      t2=nextTerm;
    }
  return ;
}
int main()
{
  int n;
  cin>>n;

  fib(n);
  return 0;
}
*/

// Factorial of a number
/*
int fact(int n)
{
  int factorial = 1;
  for(int i = 2; i<=n ; i++)
    {
      factorial = factorial * i;
    }
  return factorial;
}

int main()
{
  int n;
  cin>>n;
  int ans = fact(n);
  cout<<ans<<endl;
  return 0;
}
*/

// Calculate nCr
/*

int fact(int n)
{
  int factorial = 1;
  for(int i = 2; i<=n ; i++)
    {
      factorial = factorial * i;
    }
  return factorial;
}
int main()
{
int n,r;
cin>>n>>r;

int ans = fact(n)/((fact(r)*fact(n-r)));
cout<<ans<<endl;
return 0;
}
*/

// Pascal Triangle

/*
int fact(int n)
{
  int factorial = 1;
  for(int i = 2; i<=n; i++)
    {
      factorial = factorial*i;
    }
  return factorial;
}
int main()
{
  int n;
  cin>>n;
  for(int i = 0; i<n; i++)
    {
      for(int j=0; j<=i; j++)
        {
          cout<<fact(i)/fact(j)*fact(i-j)<<" ";
        }
      cout<<endl;
    }
  return 0;
}
*/

// Sum of n natural no.

/*

int sum (int n)
{
  int ans = 0;
  for(int i=1; i<=n; i++)
     ans = ans +i;
  return ans;
}
int main()
{
  int n;
  cin>>n;
cout<< sum(n) <<endl;
}
*/

// Binary to decimal
/*
int binaryToDecimal(int n)
{
  int ans = 0;
  int x = 1;
  while(n>0)
    {
      int y = n%10 ;
      ans += x*y;
      x*= 2;
      n /=10;
    }
  return ans;
}
int main()
{
  int n;
  cin>>n;
  cout<<binaryToDecimal(n) <<endl;
}
*/

// octal to decimal
/*
int octalToDecimal(int n)
{
  int ans = 0;
  int x = 1;
  while(n>0)
    {
      int y = n%10 ;
      ans += x*y;
      x*= 8;
      n /=10;
    }
  return ans;
}
int main()
{
  int n;
  cin>>n;
  cout<<octalToDecimal(n) <<endl;
}
*/

// Decimal to Binary

/*
int decimalToBinary(int n)
{
  int x = 1;
  int ans = 0;
  while(x <=n)
    x=x*2;
  while(x>0)
    {
      int lastDigit= n/x;
      n -= lastDigit*x;
      x/=2;
      ans = ans*10 + lastDigit;

    }
  return ans;
}
int main()
{
  int n;
  cin>>n;
  cout<<decimalToBinary(n) <<endl;
}
*/

// Add two binary no.s
/*
int reverse(int n) {
  int ans = 0;
  while (n > 0) {
    int lastDigit = n % 10;
    ans = ans * 10 + lastDigit;
    n /= 10;
  }
  return ans;
}

int addBinary(int a, int b) {
  int ans = 0;
  int prevCarry = 0;

  while (a > 0 && b >0)
    {
      if (a%2 == 0 && b%2 ==0)
      {
    ans = ans * 10 + prevCarry;
    prevCarry = 0;
  }
  else if((a%2 == 0 && b%2 == 1) || (a%2 == 1 && b%2 == 0)) 
  {
    if (prevCarry == 1) {
      ans = ans * 10 = 0;
      prevCarry = 1;
    } else {
      ans = ans % 10 + 1;
      prevCarry = 0;
    }
    else {
      ans = ans * 10 + (b % 2);
    }
    b /= 10;
  }
  if (prevCarry == 1) {
    ans = ans * 10 + 1;
  }
  ans = ans(reverse)
}

int main() {
  int a, b;
  cin >> a >> b;
  cout << addBinary(a, b) << endl;
}
}
*/

//Array (initializing)
/*
int main()
{
  int n;
  cin>>n;
  int array[5];
  for(int i=0 ;i<n; i++)
    {
      cin>>array[i];
    }
  for(int i=0; i<n; i++)
    {
      cout<<array[i]<<" "<<endl;
    }
  return 0;
}
*/

//finding min and max in an array
/*
int main()
{
  int n;
  cin>>n;
  int arr[5];
  for(int i=0 ;i<n; i++)
    {
      cin>>arr[i];
    }
  int MaxNo=INT_MIN;
  int MinNo =INT_MAX;
  for(int i=0 ;i<n; i++)
    {
      if(arr[i]>MaxNo)
      {
        MaxNo = arr[i];
      }
      if(arr[i]<MinNo)
      {
        MinNo = arr[i];
      }
      cout<<MaxNo<<" "<<MinNo<<" "<<endl;
      return 0;
    }
}
*/

//sorting of array
//selection sort
/*
int main()
{
  int n;
  cin>>n;
  int arr[n];
  for(int i=0; i<n; i++)
    {
      cin>>arr[i];
    }
  for(int i=0; i<n-1; i++)
    {
      for(int j =i+1; j<n; j++)
        {
          if(arr[j]<arr[i])
          {
            int temp=arr[j];
            arr[j]=arr[i];
            arr[i]=temp;
}        }
    }
  for(int i =0; i<n; i++)
    {
      cout<<arr[i]<<" ";
    }
  cout<<endl;
}
*/

//Bubble sort
/*
int main(){
  int n;
  cin>>n;
  int arr[n];
  for(int i=0; i<n; i++){
    cin>>arr[i];
  }
int counter=1;
while(counter<n)
  {
    for(int i=0; i<n-counter; i++)
      {
        int temp=arr[i];
        arr[i]=arr[i+1];
        arr[i+1]=temp;
      }
  }
  counter++;

for(int i = 0; i<n; i++)
  {
   cout <<arr[i]<<" ";
  }
cout<<endl;
}
*/

/*
  #include <iostream>
#include <cstdio>
using namespace std;

int main() {
    // Complete the code
    int n=3;
    long l= 12345678912345;
    char ch= 'a' ;
    float f = 334.230;
    double d = 14049.304930000;
    
    cout<<" "<<n<<endl<<" "<<l<<endl<<" "<<ch<<endl<<" "<<f<<endl<<" "<<d<<endl;
    return 0;
}
*/
/*
int main()
{
    int n;
    cin>>n;

    int arr[n];
    for(int i = 0 ; i<n; i++)
    {
        cin>>arr[i];
    }
    for(int i=1; i<n; i++)
    {
        int current = arr[i];
        int j = j-1;
        while(arr[j]>current && j>=0)
        {
            arr[j+1]=arr[j];
            j--;
        }
        arr[j+1]=current;
    }
    for(int i = 0; i<n; i++)
    {
        cout<<arr[i]<<" ";
    }
    cout<<endl;
}
*/

//Max of a Arrray
/*
int main()
{
  int mx = -1999999;
  int n;
  cin>>n;
  int a[n];

  for(int i=0; i<n; i++)
    {
      cin>>a[i];
    }
  for(int i = 0; i<n; i++)
    {
      mx = max(mx,a[i]);
      cout<<mx<<endl;
    }
  return 0;
}
*/

//sum of all subarrays
/*
int main()
{
  int n;
  cin>>n;
  int a[n];
  for(int i = 0; i<n; i++)
    {
      cin>>a[i];
    }
  int curr=0;
  for(int i=0; i<n ; i++)
        {
         curr = 0; 
          for(int j =1; j<n; j++)
            {
              curr += a[i];
              cout<<curr<<endl;
            }
          
        }
  return 0;
    }
*/

//Longest arthimetic subarrray
//Saraswati has an array of N non negative integers. The i-th integer of an array is A. She wants to choose a contiguous arthimetic subarray from her array that has the maximum length. please help her to determine the length of the longest contiguous arthimetic subarray/
/*
int main()
{
  int n;
  cin>>n;
  int a[n];
  for(int i =0; i<n; i++)
    {
      cin >> a[i];
    }
  int ans = 2;
  int pd = a[1]-a[0];
  int j = 2;
  int curr = 2;
  while(j<n)
  {
    if(pd == a[j] - a[j-1])
    {
     curr++; 
    }
    else
    {
      pd = a[j]-a[j-1];
      curr = 2;
      
    }
    ans = max(ans , curr);
    j++;
  }
  cout<<ans<<endl;
  return 0;
}
*/

//***Strings***
/*int main()
{
  /*string str;
  str ="BXHXJKSHXX";

  //convert into upper case
  /*
  for(int i=0; i<str.size(); i++)
    {
      if (str[i] >='a' && str[i] <= 'z')
      {
        str[i]-= 32;
      }
      cout<<str<<endl;
  }
  */
  
  //another way
  /*
string   s = "ddtyrury";
transform(s.begin() , s.end(), s.begin() , ::toupper);
  cout<<s<<endl;



  //convert into LOWER case
/*
   for(int i=0; i<str.size(); i++)
    {
      if (str[i] >='A' && str[i] <= 'Z')
      {
        str[i]+= 32;
      }
      cout<<str<<endl;
    }
*/
  //another way
  /*
 string   s = "AARUSHI";
transform(s.begin() , s.end(), s.begin() , ::tolower);
  cout<<s<<endl; 
  */

  //greater from a numeric string
  /*
  string s ="12357";
  sort(s.begin(), s.end(), greater<int>());
  cout<<s<<endl;
  */


//bit Manipulation  

/*
  int getBit(int n, int pos)
  {
    return((n & (1<<pos))!=0);
  }
  int main()
  {
  cout<<getBit(5,2)<<endl;
  return 0;
}
*/

//set bit
/*
  int setBit(int n, int pos)
  {
    return(n | (1<<pos));
  }
 int main()
  {
  cout<<setBit(5,1)<<endl;
  return 0;
}
*/

//clear bit
/*
int clearBit(int n, int pos)
  {
    int mask =~(1<<pos);
    return(n & mask);
  }
 int main()
  {
  cout<<clearBit(5,2)<<endl;
  return 0;
}
*/

//update bit=(clearBit + setBit)
/*
int updateBit(int n, int pos, int value)
  {
    int mask =~(1<<pos);
    n = n & mask;
     return(n | (value<<pos));
  }
int main()
{
  cout<< updateBit(5,1,1)<<endl;
  return 0;
}
*/
//how to check a no is power of 2 using bit manipulation
/*
bool ispowerof2(int n)
{
  return (n && !(n & n-1));
}
int main()
{
  cout<<ispowerof2(6)<<endl;
  return 0;
}
*/

// WAP to count the no of ones in binary rep of a no
/*
int numberofOnes(int n)
{
  int count = 0;
  while (n)
    {
      n = n & (n-1);
      count ++;
    }
  return count;
  
}
int main()
{
  cout<<numberofOnes(19)<<endl;
  return 0 ;
}
*/

//WAP to generate all possible subsets of a set{a,b,c}
/*
void subsets(int arr[], int n)
{
  for(int i=0; i<(1<<n); i++)
    {
     for(int j = 0;j<n; j++)
       {
         if(i&(1<<j))
         {
           cout<<arr[j]<<" ";
         }
       }
      cout<<endl;
    }
}
int main()
{
  int arr[4]={1,2,3,4};
  subsets(arr, 4);
  return 0;
}
*/


