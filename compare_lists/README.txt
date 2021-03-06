README
compare_lists

Contact Sarah Flanagan (sflanagan@bio.tamu.edu) for more information.

This program takes two lists and extracts the matches
What it requires:
1. two text files, each containing a list of strings

What it outputs:
1. one file with all of the strings that are the same between the two input lists.

Installation and Usage:
Windows:
Put the executable (compare_lists.exe) in a useful folder. It is easiest (the path you must provide is shortest) if you put it in your desired output directory.

Ubuntu:
Put the executable in a useful folder. It is easiest (the path you must provide is shortest) if you put it in your desired output directory.
**You may need to alter file permissions for it to run:
chmod u+x compare_lists

To run the file in interactive mode: 
./compare_lists

To run the file with arguments:
./compare_lists -a list1.txt -b list2.txt -o output.txt

For help:
./compare_lists -h 

Other operating systems:
Compile the source code using the g++ compiler.
For example:
g++ compare_lists.cpp -o compare_lists -std=c++0x


Arguments:
-a: first list of scaffolds (include path)
-b: second list of scaffolds (include path)
-o: output file name (include path)
-h: prints a help message
no arguments: interactive mode