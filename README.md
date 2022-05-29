# cs130_project_Susan-Katrina
The project of cs130 in Spring 2022, made by Susan and Kartina

Link to project proposal: https://docs.google.com/document/d/1j_2QL0s6CK0N_TUS7r0z7NV3tF4dhRm2/edit?usp=sharing&ouid=105952895589161903315&rtpof=true&sd=true

Changes for 2nd deliverable are as follows:
1. The old folder named 'Calendar' is abandoned. The content will be moved to 'FirstSchedule', and all links are changed accordingly. The function of daily planner is removed. 
2. Users can enter the daily dairy by select a single day and input a text containing 'dairy'.
3. Users can save and reload the content of monthly schedule by click 'save JSON' and 'load JSON'.

***For Katrina***
Consistent the style and format of 
1. './FirstSchedule/common/sample.css', which is the format of monthly planner.
2. './Dairy/style.css', which is the format of dairy.
3. './CoverPage/style.css', click effect of each month. (#month:click{})
4. A tutorial classmate suggested to add some animation effect to the year bar in CoverPage, i.e., small -> big -> small. (opt.)
5. Prepare *User Menu*.

***For Susan***
Interactive buttons:
1. Dairy -> upload image
2. Dairy -> save dairy button -> save the content in window.localStorage or JSON by id=date.
3. Dairy -> allow 5 image upload

4. './FirstSchedule/FirstSchedule.js' -> auto loadJSON when enter the page.
5. './FirstSchedule/FirstSchedule.js' -> change path to read & load JSON. (default to be download path? or another button to allow user to set it?)
