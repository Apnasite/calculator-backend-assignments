**Title:** Calorie Calculator

**Tool Details:**

- **Backend:** Express.js (Node.js)
- **Frontend:** WebComponent-based UI
- **Database (Optional):** JSON file or in-memory storage

**Goal:**\
Candidates will learn how to develop a backend using Express.js, integrate it with a WebComponent-based frontend, handle HTTP requests, process user input dynamically using AI-generated data, and return results in a structured format.

**Assignment Description:**\
Develop a calorie calculator tool that allows users to input details like age, gender, weight, height, and activity level. The backend should process this data, calculate the Basal Metabolic Rate (BMR) and Total Daily Energy Expenditure (TDEE), and return the results to the frontend. The frontend should dynamically display the calculated results.

**Tasks & Steps:**

1. **Backend Development (Express.js API):**

   - Set up an Express.js server.
   - Create an API endpoint to receive user input.
   - Implement logic to calculate BMR and TDEE based on user input.
   - Use AI to generate estimated calorie needs dynamically based on trends and patterns.
   - Send the calculated results back as JSON response.

2. **Frontend Development (WebComponent-based UI):**

   - Design a form with fields for age, gender, weight, height, and activity level.
   - Implement form validation to ensure proper user input.
   - Make an API call to the Express.js backend upon form submission.
   - Display the received calorie calculation results dynamically within the WebComponent.

3. **Result Display & Enhancements:**

   - Ensure a seamless UI experience by updating results dynamically.
   - Provide meaningful messages or suggestions based on calculated values.
   - Style the UI with CSS for a clean and professional look.

**Mathematical Calculation/Steps:**

- **BMR Calculation:** (Mifflin-St Jeor Equation)
  - For Men: `BMR = (10 * weight in kg) + (6.25 * height in cm) - (5 * age) + 5`
  - For Women: `BMR = (10 * weight in kg) + (6.25 * height in cm) - (5 * age) - 161`
- **TDEE Calculation:**\
  `TDEE = BMR * Activity Level Factor`
  - Sedentary (little to no exercise): `1.2`
  - Light exercise (1-3 days/week): `1.375`
  - Moderate exercise (3-5 days/week): `1.55`
  - Heavy exercise (6-7 days/week): `1.725`
  - Very heavy exercise (twice/day, intense): `1.9`

**Third-Party Packages (if required):**

- **Express.js** - Backend framework
- **cors** - Handle cross-origin requests
- **body-parser** - Parse incoming request bodies
- **dotenv** (Optional) - Manage environment variables

**Acceptance Criteria:**

- The backend API should correctly process user input and return accurate BMR & TDEE calculations.
- The frontend should dynamically capture user input, send it to the backend, and display the processed results.
- The application should handle invalid inputs gracefully and provide appropriate error messages.
- The integration between frontend and backend should work seamlessly without issues.

**Submission Guidelines:**

1. Fork the provided repository.
2. Create a folder named `calorie-calculator_<your_name>`.
3. Implement the solution within this folder.
4. Push the code to your forked repository.
5. Submit a pull request with a brief description of your solution.

Reference:

1\.	https\://www\.calculator.net/

Ensure that your submission is well-structured, functional, and adheres to best coding practices.