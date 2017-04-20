## Sorting
```#include <algorithm> //include this```
### Vector Container
``` c++
vector<int> v = {4,2,5,3,5,8,3};
sort(v.begin(),v.end());
```
### Array Primitive
``` c++
int n = 7; // array size
int t[] = {4,2,5,3,5,8,3};
sort(t,t+n);
```
### String
``` c++
string s = "monkey";
sort(s.begin(), s.end());
cout << s << endl; // output "ekmnoy"
```