# API Python

# Description
In this simple project we will be using an API, which is a set of tools and protocols that allows different software applications to communicate with each other. In this case, we can use an API provided by iTunes to find an artist catalog. To use the API, we would need to send a request to the iTunes API server, providing specific information about the artist we are interested in. This information could include the artist's name, genre, or other relevant details.

<h2>Step 1</h2>
Ensure to run this command "pip install requests".

<br>
<img src="https://imgur.com/xv2CEm8.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</br>

<h3>Step 2</h3>
Go to your web browser and write this url " https://itunes.apple.com.search/?entity=song&limit=1&term=weezer ". This should download a text file, then open the text file

<br>
<img src="https://imgur.com/sN66RvC.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</br>

<h4>Step 3</h4>
We are going to write a code to grab this same data. First we want to write "import requests" this will allow us to make http request  and write "import sys" allow us to use Command line arguements. The "if" statement is used if the user doesn't provide the name of the file they want and the name of the artist or band the code stops running. Create variabel called response and use the key "requests.get" to make that http request for the specific artist on itune.

<br>
<img src="https://imgur.com/iVLp5bT.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</br>
 
 
 <h5>Step 4</h5>
 End results
 
<br>
<img src="https://imgur.com/NFWyocD.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</br>
<br>
<img src="https://imgur.com/1QIuwxe.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</br>


<h6>Step 5</h6>
If you want a json format for the results and only include the track name from the artist you would "import json" and include a for loop. As well as increase the the limit of how many songs displays.

<br>
<img src="https://imgur.com/75UTJt0.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</br>

<br>
<img src="https://imgur.com/Yhep27d.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</br>
