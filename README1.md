# Simple Registration Form

## 📌 Project Overview

This is a basic **Registration Form with Real-Time Validation** built
using HTML, CSS, and JavaScript.

The form validates user input fields (Name, Email, and Password)
dynamically.\
The submit button remains disabled until all inputs meet the required
validation rules.

------------------------------------------------------------------------

## 🚀 Features

-   Real-time input validation
-   Email format verification using Regex
-   Minimum password length validation (6 characters)
-   Disabled submit button until form is valid
-   Error messages displayed dynamically
-   Clean and beginner-friendly UI

------------------------------------------------------------------------

## 🛠️ Technologies Used

-   HTML5
-   CSS3
-   JavaScript (Vanilla JS)

------------------------------------------------------------------------

## 📂 Project Structure

Simple-Registration-Form/ │ ├── index.html ├── style2.css └── README.md

------------------------------------------------------------------------

## 💡 How It Works

1.  The script selects all input fields using `getElementById()`.
2.  An `input` event listener runs the `validateForm()` function
    whenever the user types.
3.  The function checks:
    -   Name field is not empty
    -   Email matches a valid pattern
    -   Password has at least 6 characters
4.  If all validations pass, the submit button becomes enabled.
5.  If any validation fails, error messages are displayed and the button
    stays disabled.

------------------------------------------------------------------------

## ▶️ How to Run

1.  Download or clone the project folder.
2.  Open `index.html` in your browser.
3.  Start filling out the form.
4.  The submit button will activate only when all fields are valid.

------------------------------------------------------------------------

## 🎯 Learning Purpose

This project helps beginners understand:

-   DOM manipulation
-   Form validation logic
-   Regular Expressions (Regex)
-   Event listeners
-   Dynamic UI updates
-   Enabling/Disabling buttons using JavaScript

------------------------------------------------------------------------

## 📈 Possible Improvements

-   Add success message after submission
-   Add confirm password field
-   Add password strength indicator
-   Improve UI with better styling
-   Store user data using LocalStorage
-   Connect to backend for real authentication

------------------------------------------------------------------------

## 👨‍💻 Author

Developed as a frontend validation practice project.

------------------------------------------------------------------------

## 📜 License

Free to use for learning and educational purposes.
