# Similar-rectangles-on-a-larger-rectangle---2D-binpacking-solver
A Python program to find the number of small rectangles that would fit a large rectangle.<br />Logic Used:<br /> Assuming length is greater than the breadth 
for both the rectangles  (smaller and larger ones), following cases will occur while you try to pack  smaller rectangles on the larger one.
Let the length of larger rectangle be L,  its breadth be B and length and breadth of smaller rectangles be l and b  respectively. 
<br />Case 1. Pack the smaller rectangles such 
that their lengths  are parallel to the breadth of the larger rectangle until you fall short of space.  
Then try the other way round (Length of larger rectangle parallel to Lengths of  smaller one) on the available space. <br />
Case 2: Pack the smaller rectangles such  that their lengths are parallel to the length of the larger rectangle until you 
fall short of space. Then try the other way round (Length of larger rectangle  parallel to breadths of smaller one) on the
available space. Take the maximum  of case 1 and case 2 to get the maximum no of smaller rectangles that can be  packed on a larger one.
<br />Find the python 3 code of the implementation and let me know if you have any issues
