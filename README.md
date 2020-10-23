This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

---

SOME STEPS NECESSARY TO LOAD THE BOT
This is a react project so expect normal react dependencies
These instructions are for running this application on your local machine.

This project also uses flask so input "pip install flask"
Replace all of the keys to the respective enviorment variables.IE funtranslation,etc
so please use NPM start to start the server along with the python script in directory

input>

"npm start"
"python app.py"

all changes are temporary as long as the server runs



Issue 1: Background image wont load locally.
 After fumbling around for a bit i figured that using a locally sourced image would make the project heavier and more prone to misrepresentation. so i used an external url link to an adress of space.

Issues 2: styling was not working
I moved all the of the styling from the app.css to the index.css. some w3 schools links really helped. i figured this might be due to my comprehension of how react works. so this quick workarounds was a life saver

Issue 3: bot class issues 

i was trying to write my bot functions all inline on the main python file, so i figured to just write it in javascript for functionality. instead of refering constantly to python file, ill exlusivily call the class functions in bot.jsx

Upgrade 1: One update i would like if the page would pair up users to have 1 on 1 conversations. i would like to create a huge dictionary list of responses that cooralte between 2 users. then randomly drop a bot with that directory to spit out keys to users. This would imitate a simple ai.

Upgrade 2: i would like to create multiple rows of existing msgs that would never wipe, so the entire page would essentially be a world wide graphhiti den. This would be a place where random chat streams would be littered with random msgs from random people around the world anonomosly.

Upgrade 3: chat encrypter: users who join at the same time will use the prior msg on the server at that time to encrpy their msgs from that point on. if a user joined after a msg was said, then the msg to be used as encryption to read msgs would be moved up the que. this way you can only chat with people who joined the server at the same time as you.
