/*
Date: 03/03/2020
Class: CS55541
Assignment: Cache Simulator
Author: Mukesh Viswanathan
*/

Compile/Run:

1.gcc -o cache cache_simulator.c

Compiler would generate cache.

2. ./cache <s,E, b, t> < traces/<trace filename> >

Like:

1. ./cache -s 1 -E 1 -b 1 -t traces/yi2.trace
2. ./cache -s 4 -E 2 -b 4 -t traces/yi.trace
3. ./cache -s 2 -E 1 -b 4 -t traces/dave.trace
4. ./cache -s 2 -E 1 -b 3 -t traces/trans.trace
5. ./cache -s 2 -E 2 -b 3 -t traces/trans.trace
6. ./cache -s 2 -E 4 -b 3 -t traces/trans.trace
7. ./cache -s 5 -E 1 -b 5 -t traces/trans.trace
8. ./cache -s 5 -E 1 -b 5 -t traces/long.tr

references:
https://www.youtube.com/watch?v=A5Rc4AwdaOA
https://sellfy.com/p/jhZr/
http://www.cs.cmu.edu/afs/cs/academic/class/15213-f14/www/recitations/rec7.pdf

  




