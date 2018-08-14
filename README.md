# PathFinder
A* is a simple path finding algorithm. 
Goal is to find the shortest path from S to E. 

Code submission Rules

1. Code must be written in Java
2. Push your code to your own github.com account
3. Send the github link to us
7. Your code must output the original map and solution map 
8. Solution map must mark visited cells and actual path taken using the relevant symbols given below 
9. Submit the solution within one week 

Algorithm Rules:
1. you may move only to cell denoted by '.'
2. cost for any single valid move is 1 
3. no diagonal moves
4. read map from a file 
5. code will be tested against several maps 
6. one example map and solution is given below

W - Obstacle or Wall
. - Clear Path, ie one can move to this cell
S - Start
E - End
* - Path taken
" - Visited

Map Sample

. . . . . . . . . . . . W . . . . . . . 
. . . . . . . . . . . . W . . . . . . . 
. . . . . . . W . . . . W . . . . . . . 
W . W W . . . W . . . . W . W . . . . . 
S . . W . . . W W W W w W . W . . . . E 
W . W . W . . . . . . . W . W . . . . . 
. . . . W . . . . . . . W . W . . . . . 
. . . . W . . . . . . . . . W . . . . . 
. . . . . W . . . . . . . . W . . . . . 
. . . . . . W . . . . . . . W . . . . . 



One possible path to E

" " " " " " " " " " " " W . . . . . . . 
" " " " " " " " " " " " W " " " . . . . 
" * * * * * * W " " " " W * * * * * " " 
W * W W " " * W " " " " W * W " " * * * 
S * " W " " * W W W W w W * W " . " . E 
W " W " W " * * * * * * W * W . . . . . 
" " " " W " " " " " " * W * W . . . . . 
" " " " W " " " " " " * * * W . . . . . 
" " " " " W " " " " " " " " W . . . . . 
" " " " " " W " " " " " " " W . . . . .

=====================================================

V1.0

Issues
- Traverse soloution tried, unable to solve maze.txt
- DPS to be implemented
