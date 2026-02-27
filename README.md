Student Registration System
🏫 Student Registration System
A web‑based application to register students, manage their details, and display them in a responsive table.
Built with HTML5, CSS (Tailwind/Custom), and Vanilla JavaScript, with LocalStorage for persistent data.

📄 Project Description
The Student Registration System simplifies registering and managing student details in educational institutions or training centers.
Users can add, edit, delete, and search student records. All data is stored securely in the browser (no backend needed).
The system is fully responsive and works on all devices.

✨ Key Features
📝 Registration Form

Student Name (letters only)
Student ID (numbers only)
Email Id(valid format)
Contact no(min. 10 digits and start with 6,7,8,9 (Indian numbers only))

Address
All fields strictly validated before submission
💾 Persistent Browser Storage using localStorage

📊 Real‑time Table Display

View all registered students
🗑 Delete & ✏ Edit functionality with confirmation

🌐 Navigation
github link
index(html)
style(css)
script(javascript)
registered student in the same page access

📱 Responsive Layout
Looks perfect on desktop, tablet, and mobile
Modern styling

🛠 Technologies Used
Technology	Purpose
HTML5	Structure and semantic layout
CSS3 (Custom/Tailwind)	Styling & responsive design
JavaScript	DOM logic, form validation, storage
LocalStorage	Persistent browser-side data storage
FontAwesome	Icons (via CDN, no assets needed)

📂 File Structure
File	Purpose
index.html	Home page
styles.css	All styles and responsive design
script.js	All JavaScript logic (add/edit/delete/etc)
README.md	This documentation
Note: No nested folders — all files at the root (assignment rule).

🖥 How to Run
Clone or download this repo/ZIP.
Extract all files to the same folder.
Open index.html in your browser.
Use the top navigation to add students or view records.
All data is stored privately in your browser — nothing leaves your computer.
🧠 How I Made This Project
1. Planning
Wrote out app flow (register, store in localStorage, display, edit/delete).
2. HTML Structure
 Home (index.html), 
3. Styling (style.css)
Used responsive CSS and utility classes for spacing, color, and layout.
4. Registration Form Logic
Client-side validation for all fields, including min/max checks.
Prevents bad or empty input, only lets good records be stored.
5. Displaying & Managing Records
Loads from localStorage with JSON and shows in a sortable, filterable table.
Includes edit and delete .
Any change immediately updates localStorage.
6. Full Responsiveness
All forms, buttons, tables adjust for mobile/tablet/desktop.
Even the edit modal looks great on small screens.
7. Documentation & GitHub
This well-structured README.
Separate commits for each file.
Code comments for all complex logic.

💡 Use Cases
Small schools and coaching centers managing enrollments.
Academic projects for showing front-end form handling and data persistence.