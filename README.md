# css

MY CSS CODING:



#wrap	{
	width: 100%; /* Spans the width of the page */
	height: 50px; 
	margin: 0; /* Ensures there is no space between sides of the screen and the menu */
	z-index: 99; /* Makes sure that your menu remains on top of other page elements */
	position: fixed; 
	background-color: #00ccff;
	}
	
.navbar	{
	height: 50px;
        padding: 0;
	margin: 0;
	position: absolute; /* Ensures that the menu doesn’t affect other elements */
	border-right: 1px solid #00ccff; 
	}
	
.navbar li 	{
			height: auto;
			width: 150px;  /* Each menu item is 150px wide */
			float: left;  /* This lines up the menu items horizontally */
			text-align: center;  /* All text is placed in the center of the box */
			list-style: none;  /* Removes the default styling (bullets) for the list */
			font: normal bold 12px/1.2em Arial, Verdana, Helvetica;  
			padding: 0;
			margin: 0;
			background-color: #00ccff;
                        }
.navbar a	{							
		padding: 18px 0;  /* Adds a padding on the top and bottom so the text appears centered vertically */
		border-left: 1px solid #ffffff; /* Creates a border in a slightly lighter shade of blue than the background.  Combined with the right border, this creates a nice effect. */
		border-right: 1px solid #ffffff; /* Creates a border in a slightly darker shade of blue than the background.  Combined with the left border, this creates a nice effect. */
		text-decoration: white;  /* Removes the default hyperlink styling. */
		color: white; /* Text color is white */
		display: block;
		}
.navbar li ul 	{
		display: none;  /* Hides the drop-down menu */
		height: auto;									
		margin: 0; /* Aligns drop-down box underneath the menu item */
		padding: 0; /* Aligns drop-down box underneath the menu item */			
		}				

.navbar li:hover ul 	{
                        display: block; /* Displays the drop-down box when the menu item is hovered over */
                        }
.navbar li ul li {background-color: #00ccff;} 
.navbar li ul li a 	{
		border-left: 1px solid #ffffff; 
		border-right: 1px solid #ffffff; 
		border-top: 1px solid #ffffff; 
		border-bottom: 1px solid #ffffff; 
		}
				
.navbar li ul li a:hover	{background-color: #00ccff;}



body {
  background: #F8A434;
  font-family: 'Lato', sans-serif;
  color: #FDFCFB;
  text-align: center;
}


form {
  width: 450px;
  margin: 17% auto;
}


.header {
  font-size: 35px;
  text-transform: uppercase;
  letter-spacing: 5px;
}


.description {
  font-size: 14px;
  letter-spacing: 1px;
  line-height: 1.3em;
  margin: -2px 0 45px;
}


.input {
  display: flex;
  align-items: center;
}


.button {
  height: 44px;
  border: none;
}

  
#email {
  width: 75%;
  background: #FDFCFB;
  font-family: inherit;
  color: #737373;
  letter-spacing: 1px;
  text-indent: 5%;
  border-radius: 5px 0 0 5px;
}


#submit {
  width: 25%;
  height: 46px;
  background: #E86C8D;
  font-family: inherit;
  font-weight: bold;
  color: inherit;
  letter-spacing: 1px;
  border-radius: 0 5px 5px 0;
  cursor: pointer;
  transition: background .3s ease-in-out;
}
  

#submit:hover {
  background: #d45d7d;
}
  

input:focus {
  outline: none;
  outline: 2px solid #E86C8D;
  box-shadow: 0 0 2px #E86C8D;
}
