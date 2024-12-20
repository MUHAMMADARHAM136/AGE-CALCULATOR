# AGE-CALCULATOR
### Short Introduction to the Age Calculator Code

This project is a **web-based Age Calculator** built using separate HTML, CSS, and JavaScript files for structure, design, and functionality.

 1. HTML (index.html)
The **HTML file** provides the structure of the Age Calculator. It includes:
- A **title** and links to external `style.css` and `script.js`.
- An input field (`<input type="date">`) for users to select their date of birth.
- A button (`<button>`) to trigger the age calculation.
- A `<div>` to display the result dynamically.

 2. CSS (style.css)
The **CSS file** handles the design and layout:
- Creates a **centered and responsive layout** for the Age Calculator.
- Adds styles for form elements like input fields and buttons for a clean, modern appearance.
- Applies hover effects for interactivity and box shadows for visual appeal.

 3. JavaScript (script.js)
The **JavaScript file** handles the age calculation:
- Listens for the button click and retrieves the input date of birth.
- Uses JavaScript's `Date` object to calculate the difference between today's date and the entered date.
- Accounts for incomplete years by checking month and day differences.
- Dynamically updates the result in the designated `<div>`.

 Key Features
- User-friendly UI**: Responsive and visually appealing interface.
- Dynamic Age Calculation**: Real-time output based on user input.
- Error Handling**: Displays a message if no date of birth is provided.

This modular approach ensures clarity, easy maintainability, and reusability of the code.
