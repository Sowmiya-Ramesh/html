## media queries ##
to deal with mobile responsiveness

# type of media query selector #
  1. screen: _desktop, phone_
     a. orientation: landscape (width is wider than height)
     b. orientation: portrait (height is wider)
  2. print device: _when printing_
  3. speech device: _screen reader_
  4. all: (default)
  
 **Case 1**
 @media all and (max-width: 500px){

 }
 <!-- or -->
 @media (max-width: 500px){

 }

 **Case 2**
 @media print{

 }

 **Case 3**

@media (max-width: 500px){
    body{
        color: red;
    }
}
body{
    color: blue;
} 
<!-- top to bottom approch -->

**Case 4**
@media (orientation: landscape){

}

**Case 5**
@media (orientation: potrait){
    
}

**Case 6**
@media (orientation: landscape) and (max-width:500px){
    
}

**Case 7**
@media (orientation: landscape) , (max-width:500px){
    
}


### Bootstrap ###
  => developing responsive websites.
  => faster and easier
https://getbootstrap.com/docs/5.2/getting-started/introduction/

