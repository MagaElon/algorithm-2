# algorithm-2
alg 2
Text-Segment- Pair(A,B)
1. Use a table T[0..n]; T[0].value = True; and T[i].value = False for i = 1, . . . ,n;
2. for i = 1 to n do
3.         for j = 0 to i − 1 do
4.                  if IsWord(A[j + 1, i]) and IsWord(B[j+1, i]) and T[j].value = True then
5.                      T[i].value = True;
6. return T[n].value;
