

# Letter-Shuffle
  <h3 class="shuffle"> Just a simple letter shuffle.</h3>
  
  <link type="text/javascript" src="js/jquery.shuffle.js"

In this jquery script, this allows you to scramble letters into a word that is pre stated in your javascript file. If you want to edit what kind of letters, or just numbers, just clone or download the file. Then in the js file where it says 
	

		if (type == "lowerLetter"){
			
			pool = "letters and number string lowercase";
		}
		
		else if (type == "upperLetter"){
			
			pool = "LETTERS AND NUMBER STRING UPPERCASE";
		}
		
		else if (type == "symbol"){
			
			pool = "['5p3c14L Ch@r@c73r5']";
		} 
   
   
   
   just change the lettering in the `pool =` section.
   
   Then add the class to a header tag like so:
   
   `<h1 class= "shuffle">Shuffle this</h1>`
or even a normal paragraph tag.

