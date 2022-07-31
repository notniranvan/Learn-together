## Programming language
#### C

##### Standard lib
###### stdio.h
* int **scanf**(const char *restrict format,...);
* int **printf**(const char *restrict format,...);
* int **sprintf**(char \*restrict buffer, const char\*restrict format,...);
%-escape charater
c - charater
s - string 
d,i - signed integer, decimal
u - unsigned
x, X - hexadecimal
f - floating point
<br>
File access
* FILE ***fopen**(con char *restrict **filename**, const char *restrict **mode**);
  -> return a FILE handle on success, or NULL on failure
* mode: {r,w,a,r+,w+,a+}