# Safe Eats
## INST377 Team17

With this app, we are trying to solve the information problem of locating specific facilities faster and helping individuals find places they feel more comfortable eating at. Someone who is not familiar with an area could have difficulty locating certain food facilities that meet their needs. Modern society is fast-paced and places a lot of emphasis on efficiency, and people are always looking for a way to get useful information as quickly as possible. Our system will have a filter feature which will allow users to look for restaurants that meet specific requirements.

The target browsers for this app are Google Chrome and iOS.

Link to the application: [Safe Eats](https://inst377-team17.herokuapp.com/)

### Need Help? 
Read the [User Manual](https://github.com/mnamkung107/INST377_Team17/blob/master/docs/user.md)

### Interested in our Process?
Read the [Final Report](https://github.com/mnamkung107/INST377_Team17/blob/master/docs/final.md)


---


# Developers

## Running the App through Heroku:
**Connect the repository to Heroku**
1. Make a Heroku account
2. Create a new app and connect it to the Github where you stored the appropriate repository
3. Turn on Automatic Deploy or click “Deploy Branch” in Manual Deployment
4. Once the build finishes, a button to view your app should appear
5. If you click that, a new page to your new app should open
    - This new url will be the name you chose when you created the app on Heroku, followed by herokuapp.com
    - In our case, it was INST377-Team17


## Running the app on your personal machine with a personal server (Not Connecting to Heroku):
1. Download the [INST377_Team17](https://github.com/mnamkung107/INST377_Team17) repository into whatever folder you want
2. In Terminal (on Mac) or Command Prompt (on Windows), navigate to the folder where you downloaded the repository
3. Enter the command: `npm install`
    - Once it has downloaded, run: `npm start`
    - *This command will start a server on your personal machine on port 3000*
4. Open a browser and navigate to localhost:3000. The app should open there.
5. This page will update in **real-time**. Every time you make changes to the code, save it, then refresh the page
- *This is ideal for testing code and seeing the results update in real time*

### API Endpoint:
The GET command in our server.js file accesses our dataset at https://data.princegeorgescountymd.gov/resource/umjn-t2iz.json 

### Current known bugs:
- There are almost 33,000 separate entities in the entire dataset, but our current code only contains 1,000
MAP.
- Some of the site styling could use some work :)
