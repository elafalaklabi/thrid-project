# weather-journal-app - expalintion

## Files Included With This Project:

- node_modules folder
- website folder (app.js - index.html - style.css)
- server.js
- package-lock.json
- package.json

## what you need to run the website:

- browser
- local server
- website files
  -package (Node.js)

## functionality :

- in the [server.js] first we prepared our local server [the envoirment] we installed diffrent packages (express - body-parser - cors ) and need a get and post route to get and post the data and ofcourse I have the endpoint [projectData].

- the prpouse of this website is to get the tempruter from api.openweathermap website with key, I have created my key from the website which is 88dcd292232a3ee0d58367aad3726dc2 with this we will constrcut the url so we can fetch the needed data.

- what we used in [app.js] first we preapred our needed varibales, the we started with (eventlistener) which from it all the other functions will start by the click of submit, the event listener function is (Submit) this function, will take the zip and feeling values and it will call async asynchronous(getInfo) function will get the data from the api. also we need to use promiese in (Submit) function so we excute the other functions somthly and they wait for each other, other than (getInfo) function we have other asynchronous function (post) we have a url that is spcified from the post route in the server and the data object will contain the date, temprature and the feeling, to be posted. and (updateUI) this function will take the data and show it dynmically, in the three asynchronous function we used the three key words await, try, and catch it gives more smoothness in the excution and handles the error too.
