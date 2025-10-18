# Student-Registration-Form
Student Registration Form

A simple web-based registration form built using HTML and JavaScript with real-time validation. This project demonstrates client-side form validation, error handling, and dynamic user interaction.

It ensures that users provide valid information before submitting the form and prevents incomplete or incorrect data submission.



📝 Features

Real-time validation: Checks user input as they type.

Name field validation: Ensures the field is not empty.

Email validation: Checks that the email follows a valid format (e.g., example@domain.com).

Password validation: Ensures the password is at least 6 characters long.

Dynamic error messages: Displays messages beside each input field when invalid.

Disabled submit button: Submit button remains disabled until all fields are valid.

Success alert: Shows a message when the registration is successful.



📌 Project Structure
student-registration-form/
│
├── registration.html       # Main HTML file containing the form
├── README.md               # This README file



⚙️ Technologies Used

HTML – For form structure

JavaScript – For real-time validation and interactivity

Inline CSS – For error message styling

Note: No external libraries are required.



🔍 How It Works

Name Validation

User must type a name.

If empty, an error message "Name can't be empty" appears.

Email Validation

The input must follow a proper email format using a regex pattern:

/^[^\s@]+@[^\s@]+\.[^\s@]+$/


If invalid, an error message "Invalid email format" is displayed.

Password Validation

Minimum length: 6 characters.

If shorter, an error message "Password must be at least 6 characters" is shown.

Submit Button Logic

Disabled by default.

Becomes enabled only when all fields are valid.

Clicking it triggers a "Registration successful!" alert.



📋 How to Use

Clone the Repository

git clone https://github.com/yashinipriya07/Student-Registration-Form.git


Open the Form

Navigate to the project folder.

Open registration.html in your web browser.

Fill in the Form

Enter your Name, Email, and Password.

Correct any errors based on the messages displayed.

Submit button will be enabled automatically when all fields are valid.

Submit

Click the Submit button.

A success alert will confirm your registration.



🔧 Example Validation
Field	Input Example	Valid / Invalid
Name	Yashini	✅ Valid
Name	(empty)	❌ Invalid
Email	yashini@example.com
	✅ Valid
Email	yashini.com	❌ Invalid
Password	123456	✅ Valid
Password	123	❌ Invalid



🎨 Optional Enhancements

Add green/red borders on valid/invalid input fields.

Use CSS frameworks like Bootstrap for responsive design.

Store the registered data in local storage or a database.

Add password confirmation and show/hide password functionality.



Author 
YASHINI PRIYA S
