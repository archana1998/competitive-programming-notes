# Introduction

## Input and Output

* Newline "\n" works faster than endl because endl always causes a flush operation.
* Reading an entire line of input (with/without) spaces: `getline(cin,s)`
* If amount of input data is unknown: 
                            `while(cin>>x){
                            //code
                            }`
* When using long long, convert result to same dataype, don't leave it in int.
 
 
 ## Modular Arithmetic:
 * `x mod m` : remainder when x is divided by m.
 * Properties:
      * `(a+b) mod m = (a mod m + b mod m) mod m`
      * `(a-b) mod m = (a mod m - b mod m) mod m`
      * `(a.b) mod m = (a mod m . b mod m) mod m`

## Short Code:
Example:

`typedef long long ll;`
`typedef vector<int> vi;`
`typedef pair<int,int> pi;`

### Macros:
`#define PB push_back`
`#define MP make_pair`

## Math Theory
Things to know:
* AP. GP, HP
* Set Theory
* Logic:
    * A => B (if when A is true, B is true)
    * A <=> B (A and B are both positive or both negative)
* Functions: min, max, factorial, fibonnaci (f(n) = f(n-1) + f(n-2))
* Logarithms
