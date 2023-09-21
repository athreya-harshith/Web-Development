CSS Size Units

values : {px, % , vh, vw,rem,em}

1. % - With respect to the parent element
2. vh - With respect to the viewport height
3. vw - with respect to viewport widht (block elements by default take 100vw)
4. em - with respect to the font-size mentioned in the parent container it gets modified 
        according to it . (parent -> font-size : 10px && child -> font-size :10em , then computed fontsize for child is 10*10 = 100px)
5. rem - with respect to the root element (the root element has 16px font-size by
        default ) hence the child gets computed font-size according to it
