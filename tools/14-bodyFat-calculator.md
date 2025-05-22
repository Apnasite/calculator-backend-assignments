## **Title: Body Fat Calculator**

### **Tool Details:**

- **Backend:** Express.js
- **Frontend:** WebComponent-based UI
- **Data Handling:** AI-generated user input and responses

### **Goal:**

Candidates will learn how to develop and integrate a full-stack web application by:

- Building a RESTful API with Express.js
- Creating a WebComponent-based frontend for user interaction
- Handling form submission and displaying dynamically generated AI results

### **Assignment Description:**

Candidates will develop a **Body Fat Calculator**, where users input their details (e.g., weight, height, age, gender, and measurements). The backend will process the data using AI-generated details and return body fat percentage calculations. The frontend will dynamically display the result based on API responses.

### **Tasks & Steps:**

#### **Backend Development (Express.js)**

1. Set up an Express.js server.
2. Create an API endpoint (`/calculate-bodyfat`) that accepts user input via a POST request.
3. Implement logic to process the input using AI-generated responses.
4. Use a mathematical formula to calculate body fat percentage.
5. Send the calculated result as a JSON response.

#### **Frontend Development (WebComponent-based UI)**

1. Create a WebComponent containing a form for user input fields (weight, height, etc.).
2. Capture form submission and send data to the backend API.
3. Handle the API response and dynamically display the calculated body fat percentage.

#### **Integration & Display**

1. Ensure smooth communication between frontend and backend.
2. Validate inputs before sending them to the API.
3. Display results in a user-friendly format.

### **Mathematical Calculation/Steps:**

Use any scientifically accepted body fat formula, such as:

**For Males:**

$$
BF\% = (1.20 \times BMI) + (0.23 \times Age) - 16.2
$$

**For Females:**

$$
BF\% = (1.20 \times BMI) + (0.23 \times Age) - 5.4
$$

Where BMI is calculated as:

$$
BMI = \frac{Weight (kg)}{Height (m)^2}
$$

### **Third-Party Packages (if required):**

- `express` (for server setup)
- `cors` (to enable cross-origin requests)
- `body-parser` (for handling form data)

### **Acceptance Criteria:**

- The backend correctly handles requests and processes user data.
- The frontend effectively captures and submits user input.
- API responses are accurately displayed in the frontend.
- The UI is responsive and user-friendly.

### **Submission Guidelines:**

1. Fork the provided GitHub repository.
2. Create a folder named `<yourname>-bodyfat-calculator`.
3. Implement the backend and frontend as per the assignment.
4. Push your code and submit a pull request.

**Reference:**

1\.	[https://www.calculator.net/](https://www.calculator.net/)

