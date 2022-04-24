# CS103a PA3

This is PA03 project of our team

# Team Member
Zheng Zheng<br/>Qishi Xing<br/>Zixin Zhang<br/>Nan Wang<br/>Danqiu Fu

# Task Assignment
Zheng Zheng:<br/>
Modify the model to add strTimes field which will contain the list of strings 
strTimes: [String],<br/>
Modify the  '/upsertDB' route so that it sets the course.strTimes field, just as it did for course.num and course.suffix which are the components of course.coursenum<br/>
Qishi Xing: <br/>
Modify the course.ejs and courselist.ejs, so they use the course.strTimes field<br/>
Zixin Zhang: <br/>
Modify the '/courses' and '/course' routes so they don't pass times2str into res.locals<br/>
Nan Wang: <br/>
Add a new form on the index.ejs which asks the user for a keyword and searches for all courses that have that keyword in their course.name. Then create the app.post route which will take that keyword and find those courses and send them to courselist.ejs<br/>
Danqiu Fu: <br/>
Modify the schedule.ejs so that it uses flexboxes as we did in the api-final branch rather than an ol list, and put in more information into the flexboxes (similar to the course.ejs pages)<br/>

# Movie Link
Qishi Xing: https://brandeis.zoom.us/rec/share/yrqLo_a75BCogsygcHLlbZuz9WBx1R0gWneLqtT88NueaC-iDLeb8Y3T24S5v45A.8uEl8E5Omo5Lhxkr?startTime=1650766678000




## Installation
Download the project from github and download nodejs and npm from https://nodejs.org
and cd into the folder

Install the packages with
``` bash
npm install
```
Start the project with
``` bash
node app.js
```
or install nodemon (the node monitoring app) with
``` bash
npm install -g nodemon
```
and start the project with
``` bash
nodemon
```
