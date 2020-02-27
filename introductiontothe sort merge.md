    to sort an ordered collection of size n :
    if n<= 1, finished
    otherwise                        left       right
    divide into 2 collection of size [n/2], n- [n/2]
    sort left collection                recursion
   
    sort right collection               recursion
   
    creat empty merged collection 
    while any in left and any in right
    move lower of first item in left first item in right to merged
    move all remainder to merged 