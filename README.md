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
4. Prepare *User Menu*.
5. A tutorial classmate suggested to add some animation effect to the year bar in CoverPage, i.e., small -> big -> small. (opt.)
6. Accessibility: Adjust content display for narrow screens.

***For Susan***
Interactive buttons:
1. Dairy -> upload image (done)
2. Dairy -> save dairy button -> save the content in window.localStorage. (done)
3. Dairy -> allow 3 image upload -> infinite upload, 3 preview & store allowed. (done)

4. './FirstSchedule/FirstSchedule.js' -> auto loadJSON when enter the page. (done)
5. './FirstSchedule/FirstSchedule.js' -> save & load JSON in localStorage.


**Only Problem!!!**
1. Since we are using the trial version of MindFusion.Schedule library, the missing of license may let the header of planner turn to a warning of trial version. When encountering this, you can just *save and refresh* the page.
2. To upload image, you must put the target image to the folder './Project/Dairy/images'. Otherwise, the function will crash.
