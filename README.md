<div align="center">

## ascii\.cpp


</div>

### Description

Prints ascii table.
 
### More Info
 
No input!

just an ascii table.

prints ascii table!

none!


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Aaron M\. Ataman](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/aaron-m-ataman.md)
**Level**          |Beginner
**User Rating**    |3.7 (11 globes from 3 users)
**Compatibility**  |C\+\+ \(general\), Microsoft Visual C\+\+
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__3-1.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/aaron-m-ataman-ascii-cpp__3-1829/archive/master.zip)

### API Declarations

iostream.h


### Source Code

```
/*
Aaron M. Ataman
11jan01
ascii.cpp
	This simple program uses
	a nested for loop to format
	and display the ASCII standard
	of character values.
Input: None
Output: ASCII table
Processing:
	Nested for loop structure
	allows simple, efficent
	displaying and formatting
	of the ASCII table.
*/
#include <iostream.h> // necissary for i/o
void printASCII()
{ // begin printASCII
int i,j;
for (i=32;i<255;i+=7)
{
for(j=0;j<7;j++)
{
cout << i+j << ": " << char(i+j) << " ";
}
cout << endl; // carrige return (for formatting)
}// end printASCII
}
void main()
{
printASCII();
}
```

