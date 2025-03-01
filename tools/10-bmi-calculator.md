**Title: BMI Calculator**

**Tool Details:**
- **Backend:** Node.js with Express.js
- **Frontend:** Web Components (Vanilla JS)
- **Database:** Not required (processing is done in-memory)

**Goal:**  
By completing this assignment, candidates will learn how to develop a backend API using Express.js, integrate it with a WebComponent-based frontend, handle form submissions, process input data, and return dynamic results.

**Assignment Description:**  
Develop a BMI Calculator where users input their weight (kg) and height (m). The frontend form will send this data to the backend via an API call. The backend processes the request, calculates the BMI, classifies it (underweight, normal, overweight, obese), and returns the result. The frontend then displays the classification dynamically.

---

### **Tasks & Steps:**

#### **Backend Development (Express.js)**  
1. **Initialize a Node.js project** – Set up an Express.js server.
2. **Create an API route** – Define a `POST` endpoint (`/calculate-bmi`) to receive user input.
3. **Extract and validate input** – Ensure weight and height values are provided and valid.
4. **Perform BMI Calculation** – Apply the BMI formula to determine the result.
5. **Classify BMI** – Categorize the result into standard BMI ranges.
6. **Return response** – Send the BMI value and classification as JSON.

#### **Frontend Development (Web Components)**  
1. **Create a Web Component** – Develop a `bmi-calculator` component.
2. **Build an HTML form** – Include input fields for weight and height and a submit button.
3. **Handle form submission** – Capture user input and send a `fetch` request to the backend API.
4. **Process API response** – Extract and display the BMI value and category.
5. **Style the component** – Use basic CSS for layout and usability.

---

### **Mathematical Calculation/Steps:**
**BMI Formula:**
\[ BMI = \frac{weight (kg)}{height (m)^2} \]

**Classification:**
- **BMI < 18.5** – Underweight
- **18.5 ≤ BMI < 24.9** – Normal weight
- **25 ≤ BMI < 29.9** – Overweight
- **BMI ≥ 30** – Obese

---

### **Third-Party Packages (if required):**
- `express` – To set up the backend server.
- `body-parser` (built into Express v4.16+) – To parse JSON input.
- `cors` – To allow cross-origin requests from the frontend.

---

### **Acceptance Criteria:**
- The backend must correctly receive, validate, and process input.
- The BMI calculation must be accurate and classified correctly.
- The frontend must successfully interact with the backend via API.
- The Web Component should dynamically update the UI with the calculated BMI and classification.

---

### **Submission Guidelines:**
1. Fork the provided GitHub repository.
2. Create a new folder named `your-name-bmi-calculator`.
3. Implement the backend and frontend within the folder.
4. Push your code and create a pull request.

### **Reference :**
1.	https://www.calculator.net/

Ensure the backend correctly handles requests, processes data, and integrates seamlessly with the frontend.

