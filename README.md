<div align="center">

## rotating password


</div>

### Description

what this program does is ask for a password then if the password is right it displays the message you want it to if it is wrong it changes the value of the password and asks again this will continue till the correct password is entered.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[hypnosses](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/hypnosses.md)
**Level**          |Beginner
**User Rating**    |4.5 (27 globes from 6 users)
**Compatibility**  |C\+\+ \(general\), Microsoft Visual C\+\+, Borland C\+\+, UNIX C\+\+
**Category**       |[Security](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/security__3-14.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/hypnosses-rotating-password__3-8699/archive/master.zip)





### Source Code

```
#include <iostream>
#include <stdio.h>
#include <string.h>
using namespace std;
int main(int argc, char* argv[])
{
string a;
string b("your secret message here");
string c;
string d("password1");
string e("password2");
cout<<"password:" << endl;
again:
cin>>a;
if (a==d)
{
cout << b <<endl;
}
if (a!=d)
{
cout<<"password:" << endl;
cin>>c;
if (c==e)
{
cout<<b << endl;
return 0;
}
if (c!=e)
{
goto again;
}
}
return 0;
}
```

