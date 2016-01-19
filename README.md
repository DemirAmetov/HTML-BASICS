# HTLML-BASICS
The basic syntax for HTML

!DOCTYPE html>                                          #This is standard
<html>                                                  #This is standard
  <head>                                                #This is standard 
    <link rel="stylesheet" href="main.css">             #This is done to link the html to the css file with name "main".
  </head>                                               #This is standard 
  
  <body>                                                #This is standard (Everything is written in between the body tag)
    <div class="nav">                                   #Dividing this into a class that I can then atribute CSS to.
      <ul>                                              #Open List
        <li><a href="#">Airbnb logo</a></li>            #Make line in list, and a hyperlink
        <li><a href="#">Browse</a></li>                 #Make line in list, and a hyperlink
      </ul>                                             #Close list
      <h1>Find a place to stay.</h1>                    #This is a heading
      <h2>Travel</h2>					                          #This is also a heading but less important, this means if there are no styles applied to it then by default browsers will put styles that are smaller than the styles on h1
      <p><a href="#">See how to travel</a></p>		#This is a paragraph
      <p>Rent from people in over 34,000 cities</p>	#This is a paragraph
    </div>                                              #Close Class
  </body>
</html>
