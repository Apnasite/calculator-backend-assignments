Full Stack Development Assignment
Title: Date Calculator
Tool Details:
•	Backend: Node.js with Express.js
•	Frontend: Web Components
•	Database: Not required (data processing only)
Goal:
By completing this assignment, candidates will learn how to:
•	Develop a RESTful API using Express.js.
•	Integrate a WebComponent-based frontend with a backend service.
•	Handle user input, process data on the server, and return the result.
•	Implement AI-generated dynamic responses.
Assignment Description:
Develop a Date Calculator where users input a start date and a number of days to add or subtract. The backend will process the request, perform the calculation, and return the updated date. AI should dynamically generate user prompts, instructions, or additional date-related insights.
Tasks & Steps:
Backend Development (Express.js API)
1.	Set up an Express.js server to handle HTTP requests.
2.	Create an API endpoint (/calculate-date) to receive a start date and a day count (positive for addition, negative for subtraction).
3.	Process the request by computing the new date.
4.	Implement AI-based dynamic responses (e.g., generate a fun fact about the resulting date).
5.	Return the calculated date and the AI-generated message in JSON format.
Frontend Development (Web Components)
6. Create a WebComponent with a form containing:
•	An input field for the start date.
•	A numeric input for days to add/subtract.
•	A submit button.
7.	Capture user input and send a request to the backend using fetch().
8.	Display the response (new date and AI-generated message) dynamically within the WebComponent.
Mathematical Calculation/Steps:
•	New Date = Start Date ± Days
•	Use JavaScript's Date object: 
o	Convert input to a Date instance.
o	Add/subtract the given number of days using setDate().
o	Format the final date before returning the result.
Third-Party Packages (if required):
•	express – for backend API development.
•	cors – to enable frontend-backend communication.
•	openai or similar AI API – for generating dynamic insights (optional).
Acceptance Criteria:
•	The API correctly processes requests and returns accurate results.
•	The frontend effectively collects user input and displays the processed result.
•	AI dynamically enhances user experience with generated insights.
•	The system is functional without requiring a database.
Submission Guidelines:
1.	Fork the provided GitHub repository.
2.	Create a folder with your name inside the repository.
3.	Implement the backend API and frontend WebComponent in your folder.
4.	Push the completed code to your forked repository.
5.	Submit a pull request with a brief explanation of your implementation.

### **Reference :**
1.	https://www.calculator.net/
