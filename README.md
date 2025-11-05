Author: Yusuf Mohamed
Course: INFR3120 - Web and Script Programming

Overview

This website is my personal portfolio, built with JavaScript, EJS, and CSS3/Bootstrap 5. It uses node.js as a backend runtime environment and FontAwesome for Icons. 

My project consists of four main pages:

Home  – Intro and overview of site content, with buttons that redirect the user to the corresponding pages.

About Me  – Personal introduction with image and embedded video. 

Projects – A showcase of 3 projects I have worked on.

Contact Me – A functional contact form with validation.
Technologies Used: 
Node.js and Express.js 
EJS templating 
Bootstrap and FortAwesome (Sample codes, icons, and fonts)
CSS (Color gradient and formatting)
GitHub (Commit tracking)
Render (Cloud Deployment)

File Structure
/public – Contains assets, content, and script files. All the images and CSS design are within the public file. It also includes the JavaScript event listener that starts and loads the website. 
/views – Contains all the EJS files for the main pages of the website, along with the footer, header, and error handling. These codes were built using the help of the sample codes on the Bootstrap website. 
/routes – Include routing logic for each page. Coded by following the instructions of lecture 7. 
/node_modules – Contains many resources like the Fontawesome fonts

Version Tracking – GitHub
I used GitHub and made frequent commits to monitor my progress. 
I made a second repository while experimenting with render, as it didn’t work right away
Unfortunately, while making my render, most of my 10+ commits vanished, in front of me and the TAs' eyes, for reasons beyond my understanding.
(She did say she would count it in my project grade because she saw them before they disappeared)

GitHub Link(s): https://github.com/ymoha3/Assignment-2/commits/main/
		 https://github.com/ymoha3/A-2/commits/main/ 

Render – Cloud Deployment
As per the assignment, I uploaded my website to render, allowing it to run without terminal commands on VS Code.
Live Site Link: https://a-2-qnqo.onrender.com/ 


File Structure:

├── A-2

├── hooks

├── info

├── logs

├── node_modules

├── public
	├── asset
		├── assets/images
animation.MP4
htmlpic.jpg
Image.png
Intro.mp4
network.jpg
profile.jpg
video-poster.jpg
video-poster2.jpg
website.png
zen.png

├── content
	app.css
  
├── script
	app.js
  
├── routes
index.js
users.js
      
├── views        
 	├── partials
		footer.ejs
		header.ejs
		main_nav.ejs
		└── 
	
	aboutme.ejs
	contactus.ejs
		error.ejs
		home.ejs
		Index.ejs

projects.ejs

├── app.js           
├── package-lock.json          
├── package.json          
└── server.js                       



