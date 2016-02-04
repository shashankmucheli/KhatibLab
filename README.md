Developing and maintaining Dr. Khatib's lab website at UMass Dartmouth.
======================================================================= 

Two ways to get access to the web pages:
----------------------------------------- 
Logging onto Uranium server and downloading the code:

1. Get access to the uranium server (the server which hosts the website) from either Paul R. Naylor or Dr. Khatib himself. (logins for fkhatib@www.cis.umassd.edu) 
	
2. Navigate to the web directory inside the home directory to download/modify the web pages.
	
Git pull from my github repo: 
	Pull the code using this link: https://github.com/shashankmucheli/KhatibLab.git

Modifying the website:
---------------------- 
The website is pretty much static and hence there is no need create anything on the fly. I have used Flat-ui package for the styling. There almost zero JS used so, there is no need to worry about the JavaScripts (whatever JS is used, is obtained from the flat-ui package).

CSS: Apart from the default styling that we get, I have defined some rules specific to our requirements, I have stored all these rules in a CSS file named fkhatib.css in the CSS directory.
Each webpage is divided into three sections: 

Navbar or Headers: This section takes care of the redirections and the menu bar that appear on the top of each page. 

The container div: This contains the web page data. All the divs are styled according to the guidelines specified by flat-ui, more details can be found here: http://designmodo.github.io/Flat-UI/

The footer Section: It contains the links and logos in the footer section.

Uploading the modified data back to the server:
----------------------------------------------- 

Windows: Use tools like WinSCP or Filezilla to SSH into the server, navigate to the web directory and upload the changes. 

Mac OSX/ Linux: SSH into fkhatib@www.cis.umassd.edu, navigate to the web directory and upload the changes.

and

Git: Push the changes to https://github.com/shashankmucheli/KhatibLab.git 
	
email me at shashank AT mucheli DOT com for any further details. 
	
	
