# EMI Calculator

## Tool Details

- **Backend:** Express.js  
- **Frontend:** WebComponent-based UI  
- **Database (Optional):** JSON or in-memory storage  
- **AI Integration:** Auto-generate test data for dynamic input validation  

---

## Goal

By completing this assignment, candidates will learn how to:

- Develop and deploy a backend API using Express.js
- Create a WebComponent-based frontend and integrate it with the backend
- Implement real-time form handling and dynamic data processing
- Ensure seamless communication between frontend and backend using REST APIs

---

## Assignment Description

The **EMI Calculator** tool allows users to enter loan details (principal amount, interest rate, and tenure) into a form. The backend processes these inputs, applies the EMI formula, and returns the calculated monthly installment. The frontend dynamically displays the result upon receiving the response. AI-generated test cases ensure robustness.

---

## Tasks & Steps

### Backend API Development (Express.js)

1. Set up an Express.js server and define a `/calculate-emi` POST endpoint.
2. Parse the request body to retrieve user inputs (**principal**, **rate**, **tenure**).
3. Implement the EMI calculation logic.
4. Send the computed EMI value as a JSON response.
5. Handle error cases (invalid input, missing parameters).

### Frontend (WebComponent-Based UI)

6. Create a WebComponent with an interactive form (input fields for principal, rate, and tenure).
7. Capture form submission and send a request to the backend using Fetch API.
8. Parse the API response and update the UI to display the EMI result.
9. Ensure responsive and accessible UI design.

### Integration & Result Display

10. Connect frontend and backend for seamless data flow.
11. Validate input fields dynamically and provide user-friendly feedback.
12. Display the calculated EMI prominently within the WebComponent.

---

## Mathematical Calculation

**EMI Formula:**

\[
EMI = \frac{P \times R \times (1+R)^N}{(1+R)^N - 1}
\]

Where:  
- **P** = Principal loan amount  
- **R** = Monthly interest rate (Annual Rate / 12 / 100)  
- **N** = Loan tenure in months  

---

## Third-Party Packages (if required)

- `express` (for backend server)
- `body-parser` (for handling JSON input)
- `cors` (for cross-origin requests)

---

## Acceptance Criteria

- The backend should successfully receive input and return the correct EMI calculation.
- The WebComponent frontend should correctly display the calculated EMI upon form submission.
- Error handling should provide meaningful feedback for invalid inputs.
- The API response should be in JSON format and accessible to the frontend.
- AI-generated test cases should validate various loan scenarios.

---

## Submission Guidelines

1. Fork the provided GitHub repository.
2. Create a new folder named `{your-name}-emi-calculator`.
3. Implement the backend (Express.js) and frontend (WebComponent) within the folder.
4. Ensure proper folder structure and code documentation.
5. Push your solution and submit a pull request for review.

---

### Reference

1. [https://www.calculator.net/](https://www.calculator.net/)
