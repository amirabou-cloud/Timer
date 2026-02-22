⏱️ Timer Project

A responsive countdown / timer application built using HTML, CSS, and JavaScript.
This project helped me practice DOM manipulation, responsive design, and handling real-time updates with JavaScript.

🚀 Features

Start / Stop timer

Reset timer

Real-time updates

Responsive design (works on desktop, tablet, and mobile)

Clean and minimal UI

🛠️ Built With

HTML5 – Structure

CSS3 – Styling and responsive layout

JavaScript (Vanilla JS) – Timer logic and interactivity

📱 Responsive Design

The layout adapts to different screen sizes using:

Flexible units (%, rem)

Media queries

Scalable margins and spacing adjustments

🧠 JavaScript Logic (How the Timer Works)

The timer is based on incrementing time using setInterval().

Basic Formula Used:
let seconds = 0;

setInterval(() => {
seconds++;

let minutes = Math.floor(seconds / 60);
let remainingSeconds = seconds % 60;

console.log(minutes + ":" + remainingSeconds);
}, 1000);
Explanation:

setInterval() runs every 1000 milliseconds (1 second)

Math.floor(seconds / 60) calculates minutes

seconds % 60 calculates remaining seconds

The DOM updates dynamically to display the current time

⚠️ Challenges I Faced
1️⃣ Typo Issues in Code

Misspelled variable names

Incorrect class names

Small syntax mistakes causing JavaScript errors

What I learned:
Be consistent with naming and use browser console debugging tools.

2️⃣ Icon Problems

Icons were not displaying correctly

Incorrect icon class names

CDN link issues

Solution:

Verified the correct icon library link

Checked class names carefully

Ensured internet connection when using CDN

3️⃣ Margin & Scaling Issues (Responsive Problems)

The layout looked good on desktop but broke on:

Smaller phones

Larger screens

Problems included:

Margins too large on mobile

Buttons misaligned

Text overflow

How I fixed it:

Used flexbox

Applied media queries

Switched from fixed px units to rem and %

Tested on multiple screen sizes

Example:

@media (max-width: 600px) {
.container {
margin: 1rem;
font-size: 0.9rem;
}
}
🧪 What I Learned

How setInterval() works

How to manipulate the DOM dynamically

Debugging JavaScript errors in the browser console

Writing cleaner CSS for responsiveness

Importance of testing on multiple devices

📦 How to Run the Project

Clone the repository:

git clone https://github.com/your-username/Timer.git

Open the project folder

Open index.html in your browser

No installation required.

📌 Future Improvements

Add countdown functionality

Add sound notification when timer ends

Add dark/light mode toggle

Improve animations
