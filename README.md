# sweet-Code

#step to install from every folder on editor 

# step one using NPM ( just really simple 
:      **sudo npm i -g sass 

# step two , check the version : 
        **sass --version **

# generate the css file : 
   >> create your file for style ie wise.scss
   >> after using the command line to generate the css file like : 
   
   ****sass wise.scss style.css**
   
   >> after this generate the .css file like every modification we are doing inside the .scss file the .css have it to 
   
   **sass wise.scss style.css --watch**

############################################################ Code pour l'hamburger Menu #############################################################################
 .navbar-left.active {
        transition: all .2s ease;
        background-color: rgba($color: #000000, $alpha: .01);
        position: relative;
    }
    .navbar-left.active::before{
            transition: all .2s ease ;
            position: absolute;
            transform: rotate(45deg) translate(5px,5px);
            background-color: white;
    }

    .navbar-left.active::after {
            transition: all .4s ease ;
            transform: rotate(-45deg) translate(5px,-5px);
            background-color: white;
    }
######################################################################################################################################################################
