Positioning Property in CSS 

values : {static , relative,absolute,fixed,sticky}

By default Positioning is static ( no z-index is allowed)

1. relative 
    * positioned wrt to the current window
    * have 4 properties {top,left,right,bottom}
    * the previously given gap is maintained
2. absolute
    * positioned wrt to the closest positioned neighbour in the dom tree
    * the container thats parent of the absolute positioned element must be postioned relative
    * the previously allocated space will be removed
3. fixed
    * remains fixed throught the webpage even if the parent container goes off the viewport
4. sticky
    * remains sticky at a particular disatance mentioned 
    * goes off if parent container goes off the viewport