CSS Flexbox

overview of flex container in row direction
    horizontal is main-axis and vertical is cross-axis

=============PROPERTIES FOR FLEX - CONTAINER===============
* set the display property of container to flex
* flex-direction : row by default {row,column,row-reverse,column-reverse}
* flex-wrap : {wrap,no-wrap,wrap-reverse} by default the child containers inside flex   squeezes flex-wrap doesnot shrinks or squeezes the size rather it brings the contents into new line 
* justify-content : aligns items according to the main-axis
                    values :{center,space-between,space-around,space-evenly}
* align-item : aligns items according to the cross-axis
                    values :{start,center,end}
* align-content : while wrapping up how to align the contents
                    values:{start , center , end}

=============PROPERTIES FOR FLEX - ITEM==================
* order : takes a numeric value for sequence of the items 
* flex-shrink : how fast an item should shrink when the viewport size decreases
* flex-grow :  how fast an item should grow when the viewport size increases
* flex-basis : sets the dimensions of an item
* align-self : items aligns itself within the container based on the cross-axis