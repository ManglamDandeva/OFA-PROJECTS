# 🎓 Student Attendance Dashboard

## 👋 About The Project
Taking attendance on paper or clunky spreadsheets is a pain. For this hackathon, I aimed to create something that not only looks visually appealing but also makes the process of tracking students feel modern and effortless.

This is a **front-end prototype** for an Attendance Management System. The goal was to create a UI that is intuitive for faculty members—allowing them to mark attendance, manage courses, and visualise stats without getting lost in menus.

## 📂 What's Inside?
Here is a breakdown of the files in this repository so you know where to look:

*  project.html: The Login page. I designed this to be the entry point. It mimics a secure authentication screen.
* mainpage.html:  The main Dashboard. This is where the user lands after logging in. It gives a quick "at a glance" view of daily stats (who is present vs. absent today).
* attendancepage.html: The core feature. A clean table interface where you can toggle status (Present/Absent/Late) for students.
* courses.html: A management view to see which courses are active and how many students are enrolled in each.
* reportpage.html: The analytics hub. I used **Chart.js** here to turn the raw numbers into visual graphs, making it easier to spot attendance trends.
* settings.html:  A preferences page to tweak the admin profile and toggle themes.

## 🛠️ Built With
I kept the tech stack lightweight and streamlined for speed. No heavy frameworks—just the essentials to show off the fundamental skills.

* HTML5: For semantic structure.
* CSS3: Everything is styled from scratch (no Bootstrap!). I used CSS Variables (`: root`) for consistent theming and Flexbox/Grid for the layout.
* JavaScript: Used to power the interactive charts and handle simple UI logic.
* Chart.js: An external library used for the Pie and Bar charts in the reports section.

## 🚀 How to Run It
Since this is a front-end project, it's super easy to test:

1.  Make sure you have an internet connection (so the Chart.js library can load).
2.  Download or clone this folder.
3.  Open project.html in your browser (Chrome, Edge, Firefox, etc.).
4.  Click "Login" to explore the dashboard.

*(Note: Ensure the image assets included in the folder stay in the same directory as the HTML files so the icons load correctly!)*

## 🔮 What I'd Build Next (Future Scope)
If I had more time, here is what I would add:
* Backend Connection: Hooking this up to a database (like MongoDB or MySQL) so the attendance records actually save.
* Face Recognition: Using Python/OpenCV to mark attendance automatically via camera.
* Student View: A separate login for students to check their own percentage.

## 👨‍💻 Author
*Manglam Dandeva*                                                                                                                                                                                                   
*Raghav Satija*                                                                                                                                                                                                     
*Aditya Chitoria*                                                                                                                                                                                                   
*Ishant*                                                                                                                                                                                                            
First Year, CSE Students IIIT Sonepat
