Task 3 · Temperature Converter Website
Project Overview
This project is part of the Oasis Infobyte Internship Program (Level 1, Task 3).
The objective is to build an interactive web tool that converts temperature values between Celsius, Fahrenheit, and Kelvin, with real-time input validation and a clean, responsive UI.

Objectives
Create a numeric input field for temperature values.
Validate input: reject non-numeric entries with an error message.
Provide a unit selector (dropdown or radio buttons) for input unit (Celsius / Fahrenheit / Kelvin).
Display converted values in all units simultaneously.
Include a Convert button to trigger calculations.
Show results with correct unit labels.
Handle edge cases: display a user-friendly message for absolute zero violations (e.g., below −273.15°C).
Maintain a clean, centered UI layout with clear labels and spacing.
Tech Stack
HTML5 → Structure & semantic markup
CSS3 → Styling, layout, responsiveness
JavaScript (Vanilla) → Conversion logic & input validation
Folder Structure
Temperature-Converter/ │── README.md
│── index.html
│── style.css
│── script.js

Feature Checklist
 Numeric input field with validation
 Unit selector (C/F/K)
 Convert button
 Result display area with labels
 Edge case handling (absolute zero)
 Responsive, clean UI
Self-Sourcing Guideline
Conversion formulas:

Celsius → Fahrenheit: (C × 9/5) + 32
Fahrenheit → Celsius: (F − 32) × 5/9
Celsius → Kelvin: C + 273.15
Kelvin → Celsius: K − 273.15
Learning Resources:

YouTube: “Temperature Converter JavaScript Tutorial”
MDN Web Docs: HTML input validation
Preview
()