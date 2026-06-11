Instances of the Obnoxious _p_-median problem
=============================================

This archive contains the instances of the obnoxious _p_-median
problem that were solved as part of the article "A branch-and-cut
method for the obnoxious _p_-median problem" by P. Belotti, M. Labbé,
F. Maffioli, and M. Ndiaye.

The format can be Euclidean or Table. For both formats, the value of
_n_ (number of cities), _m_ (number of facilities), and _p_ (number of
facilities to be opened) are given. For Euclidean, here's an example
(note that the number of dimensions of all Cartesian coordinates of
all points should be specified):

```
type=euclidean
n=10
m=14
p=4
dim=2

clients = {
Kansas_Topeka		{39.50, 95.6666},
Kentucky_Frankfort		{38.166, 84.8833},
[...]
Michigan_Lansing		{42.733, 85.5666}}

facilities = {
Milwaukee		{43.33, 87.9000},
Minnesota_St_Paul		{44.933, 93.833},
[...]
New_York_Albany		{42.666, 73.8166}}
```

Table instances instead refer to those where coordinates are not
given, but rather a table with all distances between cities and
potential facilities.

```
type = TABLE
m = 8
n = 12
p = 4
sense = MIN
clients = {A,B,C,D,E,F,G,H,I,J,K,L}
facilities = {a,b,c,d,e,f,g,h}
table = {{10,33,28,29,32,49,54,64},
         {10,24,33,25,30,46,42,60},
         {12,24,11,12,37,32,47,47},
         {27, 7,36,23,13,40,25,48},
         {15, 8,21, 8,21,29,33,43},
         {31, 8,37,24, 5,33,17,41},
         {34,27,11,11,40,10,41,29},
         {35,12,26,13,17,21,22,29},
         {42,15,38,25, 6,33,10,31},
         {41,24,28,18,30, 9,24,17},
         {51,28,42,29,20,24, 9,17},
         {54,37,41,31,31,22,20, 6}}
```
