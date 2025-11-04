## Project Title
**Football Scoreboard Tracker**

---

## Objective
The goal of this project is to develop a web-based football scoreboard tracker that displays real-time scores, match details, and team information by consuming data from a public and free football API.  
This project uses HTML, CSS, and JavaScript with an external API to dynamically update live content on a website. CSS design will play a major role, as we aim to create a layout that stands out visually compared to other football score websites.

---

## Requirements
1. **Frontend Technologies:**
   - HTML for structure definition
   - CSS for controlling visual design, colors, and layout
   - JavaScript for handling dynamic API interactions and user interaction
   - We will be using HTML5, CSS3, and JavaScript(ES6)
 

2. **API Integration:**
   - Use a **free football/sports API** (e.g., [API-Football](https://www.api-football.com), [TheSportsDB](https://www.thesportsdb.com))
   - Display real-time or recent football scores and data

3. **Functionality:**
   - Fetch live or scheduled match data
   - Display team names, scores, and match status (winner and loser)
   - Automatically refresh scores throughout the day
   - Handle API loading and error states

4. **Development Tools:**
   - Text editor (VS Code)
   - Web browser (Chrome)
   - Possibly an API testing tool (optional)

---

## User Stories
1. As a **football fan**, I want to view live scores so I can stay updated on ongoing matches.
2. As a **casual user**, I want a clean, easy-to-read interface that clearly displays team names, scores, and records.  
3. As a **developer**, I want the code to be modular and well-documented so I can extend it to other sports or leagues.  
4. As a **student**, I want to demonstrate my understanding of APIs and front-end programming by creating a responsive, visually appealing web page.  
5. As a **researcher**, I want well documented scores and updates on all football games to help me write articles.

---

## Implementation Details
1. **HTML Structure**
   - Create a simple layout with a header and a section to display scores.
   - Use a `<div id="scores"></div>` element for dynamically loaded data.

2. **CSS Styling**
   - Use Flexbox or Grid for a responsive layout.
   - Apply team colors and clear visual contrast.
   - Include hover effects and subtle animations for engagement.

3. **JavaScript Functionality**
   - Use `fetch()` to request data from the football API. Explained in step 4.
   - Implement `setInterval()` to refresh data.

4. **Data Fetching**
   fetch("https://api-football-v1.p.rapidapi.com/v3/fixtures?live=all", {
     method: "GET",
     headers: {
       "x-rapidapi-key": "YOUR_API_KEY_HERE",
       "x-rapidapi-host": "api-football-v1.p.rapidapi.com"
     }
   })

### Deployment
**Platform:** GitHub Pages  

The project will be deployed using **GitHub Pages**. 
After completing development, the project files (HTML, CSS, and JavaScript) will be pushed to a public GitHub repository. 

---

## Deliverables
1. **HTML File (`index.html`)**  
   - Defines the main structure of the webpage and includes the container for displaying live football scores.

2. **CSS File (`styles.css`)**  
   - Handles all visual styling, including layout, team colors, and responsive design.

3. **JavaScript File (`script.js`)**  
   - Manages data fetching from the football API, processes JSON responses, and dynamically updates the DOM. Also handles user interaction.

4. **README File (`README.md`)**  
   - Provides instructions, explains how the API integration works, and describes project functionality.

5. **UI Mockups/Design:**  
   - Make wireframes illustrating the intended layout, color scheme, and responsive design structure using FIGMA.
