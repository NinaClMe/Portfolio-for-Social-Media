# Students application
Basic web application for demonstrating core client/server architecture concepts as well as the main technologies involved.

> Not supposed to be used in any production environment, only for educational purposes

## Project structure
It is a full web application
I've worked a lot with HTML and CSS, although some things (code) could probably be simplified or structured differently

The home page (under "Home) contains important information about the seminar Social Media - Einführung in das Gestalten von Online-Medien
Also a few pictures of things I do in my free time

Under "My curriculum vitae" you will find all the important information about me

Under "Curriculum"  you will find my timetable from the winter semester 2023/24

Under "My class contents" you will first find a list of the individual classes and their main topics. If you then go to one of the classes you will come to a summarized content of the class

### backend
Simple node application `backend/index.js` with a CRUD (Create, Read, Update, and Delete) operations exposed as a HTTP service. Manipulating a dummy file based data storage `backend/students.json`

### frontend
Plain HTML / CSS / Javascript project for creating an interface to manipulate the students API.

I have used various links that allow you to jump from one topic to the next on the page

In addition, other websites and YouTube videos were also linked

In aside there is some additional information about me and if you have any further questions you can send me an email

## Set up

Make sure you have [node.js](https://nodejs.org/en) installed.

Install project dependencies
```
npm install;
```

Starts backend service on port 3000
```
node backend/index.js
```

Start frontend application on port 8080 [open a new terminal instance]
```
npx http-server frontend

```
