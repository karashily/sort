# Sort
Different sorting algorithms (insertion, selection, merge, quick and hybrid) implemented in C++.
Input is read from file and output is written to a file, which names is given from the terminal.

(optional) Time is calculated for the operation and is appended to a file, which name is given from the terminal too :v

example:
"g++ sort.cpp -o sort"
"./sort insertion data.txt out.txt (time.txt)"


Hybrid Sort: 
a mix between insertion and merge sorts to exploit the strength of both; 
insertion sort works best with ordered and almost-ordered lists,
while merge sort works best in the rest of the cases.
