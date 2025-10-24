DESCRIPTION: Overview
This React component creates a homepage for an e-learning platform. It includes a sidebar navigation, a welcome banner, a course browsing section, video previews, dashboard widgets, and login/register forms — all styled using Bootstrap.

LAYOUT STRUCTURE:

1. Sidebar Menu (Left Section)
A vertical sidebar is shown on the left side with navigation links to:
Home
Courses
Dashboard
Logout
It has a dark background and white text, styled like a typical dashboard sidebar.
2. Main Content (Right Section)
The rest of the screen is dedicated to interactive content, with a light background. It includes several key sections explained below.

WELCOME SECTION:

At the top, there's a colorful welcome box centered on the page. It greets the user and provides big, friendly buttons linking to:
Browse all courses
Watch a sample course
Login or register
Go to dashboard
This section is visually attractive and acts as the starting point for the user.

COURSES SECTION:

This area shows a list of available online courses like:
HTML & CSS
JavaScript Essentials
React Basics
Node.js
Python
Database Basics
Each course is shown as a card with its title and description. When a user clicks a course, it opens a video preview and shows a progress bar showing how far the user has progressed in that course. A "Back" button lets the user return to the full course list.
The video previews are embedded from YouTube based on the course selected.

DASHBOARD WIDGETS:

Below the courses, three small dashboard cards are shown:
Number of courses the user is enrolled in
Learning progress percentage (randomized each time)
Number of new course recommendations
Each widget is styled using cards for a clean and informative look.

LOGIN SECTION:

A login form is provided where users can:
Enter email
Enter password
Click a login button
It's placed in a centered card layout with subtle shadows for professional appearance.

REGISTER SECTION:

Below the login form, there’s a registration form for new users. It asks for:
Name
Email
Password
The form is also styled as a card, matching the login form.

INTERACTIVITY AND LOGIC:

When a user clicks a course card, the component shows the course details and embedded video.
Clicking “Back to Courses” resets the view to show the full course list.
A random number is used to simulate the user’s progress percentage every time the component loads.
The layout adjusts well to screen size due to responsive Bootstrap classes.

SUMMARY:

This is a fully functional and interactive homepage for an e-learning platform built using React. It combines navigation, course browsing, video previews, user progress display, and authentication forms — all in a single, structured component.

OUTPUT:

![Screenshot 2025-07-09 163903](https://github.com/user-attachments/assets/729cfafd-aa2e-4adf-861c-5d73afe95e17)

![Screenshot 2025-07-09 163940](https://github.com/user-attachments/assets/8b252367-5a1c-4c22-9876-8983a9365f5b)

![Screenshot 2025-07-09 164002](https://github.com/user-attachments/assets/b52c07e7-fd39-4c43-ab06-fafff2789eb0)

![Screenshot 2025-07-09 164016](https://github.com/user-attachments/assets/a7f3084f-17b4-4138-ad82-35825b1f4698)






