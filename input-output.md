## Input 
### Integer based 
* Input : ```1 2 3 4 5 6 7 8 9``` or
```
1 2 3
4 5 6
7 8 9
```

``` c++
for(int i=0; i < n; i++){
    int x;
    cin >> x;
    // save it to 1D or 2D array (for matrix)
    // use nested loop for 2D array
    data[i] = x;
}
```

### String Based
* Input : ``` Hello this is string with space! ```
``` c++
string text;
getline(cin, text, '\n');
cout << text << endl;
```

### Infinite Case (Unknown Case)
```
while (cin >> x) {
// code
}
```

## Output
### Precision (Point)
``` c++
// #include <iomanip>
// fixed identifier from import
cout << fixed << setprecision(2) << OUTPUT_VAR_DOUBLE << "\n";
```
or 
``` c++
    // import #include <stdio.h>
    double x = 123.45678
    printf("%.2f\n", x); // ouptut 123.46
```

## IO Redirection
* input.txt // test case code
* output.txt // empty file, filled with program
```
$ g++ program.cpp -o program
$ ./program < input.txt // for read case from file
$ ./program > output.txt // save output to file
$ ./program < input.txt > output.txt // read from & save to files
```

or at the program
```
freopen("input.txt", "r", stdin);
freopen("output.txt", "w", stdout);
```