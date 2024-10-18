# Calculator

A simple Calculator App built with HTML, CSS, and JavaScript. It also has a Dark Mode.

![Calculator Preview Image](https://user-images.githubusercontent.com/44538497/169086855-bd20e6e0-3675-4db6-b086-0298005973f4.png)

Purpose of the Project:
The primary goal of this project is to create a simple, interactive calculator that can perform basic arithmetic operations (addition, subtraction, multiplication, division) while allowing users to switch between dark and light themes for better visual comfort. It serves as an educational tool for developers to practice web development skills in HTML, CSS, and JavaScript.

Detailed Components:
1. HTML Structure:
Document Type and Language: The document begins with a declaration (<!DOCTYPE html>) and specifies the language as English (<html lang="en">).
Head Section:
Meta Tags: These define the character set, compatibility with Internet Explorer, viewport settings for responsiveness, and a brief description of the application.
Favicon: A small icon that appears in the browser tab.
Stylesheets: Links to a CSS file for styling (dark.css) and Google Fonts for typography, ensuring a clean and modern look.
2. Body Section:
Wrapper and Container: The main structure of the calculator is enclosed in a wrapper and container for layout purposes.
Header:
Contains the title "Calculator" and icons for GitHub and theme toggling. The GitHub link can direct users to the project's repository, providing access to the source code.
The theme button allows users to switch between dark and light modes, enhancing usability in different lighting conditions.
3. Calculator Interface:
Input Display: A read-only text input (<input type="text" name="result" id="result" placeholder="Result" readonly />) shows the current calculation or result.
Clear Button: A button labeled "C" to clear the display.
Buttons for Digits and Operations: Organized in rows for user-friendly interaction:
First Row: Contains the display and clear button.
Second to Fifth Rows: Each row contains buttons for numbers (0-9), basic operations (+, -, x, /), and a button for calculating the result (=).
Dot Button: Allows the entry of decimal numbers.
4. JavaScript Functionality:
The project relies on external JavaScript (scripts/script.js) to handle the functionality:
liveScreen(value): Updates the display with the value of the button clicked.
calculate(expression): Evaluates the expression shown in the display when the "=" button is clicked.
changeTheme(): Toggles the CSS class to switch between dark and light modes.
Additional Features:
Responsive Design: The layout is designed to be responsive, making it usable on various devices, from desktops to mobile phones.
User Experience: The calculator's interface is intuitive, ensuring that users can perform calculations easily without any complex navigation.
Learning Outcomes:
This project not only demonstrates practical coding skills but also highlights the importance of UI/UX design, responsive layouts, and accessibility in web applications. It’s an excellent example for beginners to understand how HTML, CSS, and JavaScript can work together to create interactive web applications.
