# Final Report
## Safe Eats

**Team members:** Michelle Namkung, Aisha Koroma, Jason Jiang, Ayesha Shafquat, Japheth Mulugeta and Myles Lane

The app can be found running [Here](https://inst377-team17.herokuapp.com/index.html "Safe Eats").

**Information Problem:** Unable to locate health information about various food facilities in an area you may not be familiar with. The stakeholders and target users for our app include first-time travelers and locals to the Prince George’s County Area looking for a sanitary place to eat.

The app will be pulling data from the Prince George’s County Food Inspection Dataset found [on their website](https://data.princegeorgescountymd.gov/Health/Food-Inspection/umjn-t2iz). The dataset contains information on the compliance of food service facilities across PG County and is a reliable data source that is updated daily.

The solution to the information problem was to build a web application that allows rapid searching and filtering through categories to find food service facilities that are in compliance with the health code in Prince Georges County.
The technical system decision rationale was to build something similar to Google Maps and Yelp that would allow the user to look at restaurants nearby based on the category they want and help them avoid facilities that have health code violations.

The app will help address the problem by displaying a list of restaurants based on category and excluding any facilities that have failed their health code inspections.

### Challenges

**Back End:**
- Using/connecting to Heroku
- Accessing the server and passing specific information through
- Pinpointing location for user on maps and getting all of the restaurants implemented
- Determining how to filter the dataset 

**Front End:**
- Color Scheme styling issues
- Add animations successfully
- Cleaning the code in styles.css sheet so it is easy to understand

The issues arrised from teammembers lack of experience in develpoping apps. While it was easy to brainstorm ideas, it took a   significant amount of time to research and code. This could have been avoided by planning better, and implementing time in the schedule to research on how to implement some items.

Many changes were made from the original wireframes. At first, when the user would filter through what place they would like to eat. Every option would appear after clicking “Apply” and those that did not pass health code violations, had a red dot next to it and those that passed had a green dot. We found this as not necessarily and we did not believe that the user needs to know of the locations/restaurants that are not sanitary and because of that we omitted the places that did not pass. So if the user chooses to eat at a bakery, only those that passed health code inspections would appear. This also helps the establishments that did not pass inspection be free from bad press. Another change was the map. In the original wireframes, the map was to display all places in the category that was selected, although due to time and lack of understanding maps API the map does not function like we first planned. Now, the map displays users current location and allows the user to enter the name of the place to get the address. 

### For the Future

One possible direction our team considered for the future is allowing anonymous users or employees to leave reviews or tips about the facilities they are at. This would be something like a "tip-line", a Yelp-like feature that will give users information thorugh the app ahead of time. In the future, we will continue to develop the map and make the list of establishments clickable so they will accuratley display on the map. 

### Acknowledgements
- Professor Leitch 
- Codepen.io, helped with inspiration and ideas
- Charlie Walter: https://codepen.io/cjonasw/pen/nFdvw
- Jack Fitzgibbon: https://codepen.io/jackfitzgibbon/pen/BHxoa
- Felice Gattuso: https://codepen.io/felicegattuso/pen/MegJpg
- Katherine Kato: https://codepen.io/kathykato/pen/MoZJom

