MP1 – Online Resume Website

Project Overview
----------------
This project is a mini web portfolio based on my most recent resume.
It demonstrates use of HTML, CSS, and JavaScript to build a responsive multi-page website, including a JavaScript calculator project.

The website is organized into multiple internal webpages representing different sections of a resume.

Folder Structure
----------------
mp1/
│
├── credits/
│   ├── yash-credits.html
│   └── yash-credits.css
│
├── education/
│   ├── yash-education.html
│   └── yash-education.css
│
├── project/
│   ├── yash-project-cal.html
│   ├── yash-project-cal.css
│   └── yash-project-cal.js   # JavaScript calculator
│
├── references/
│   ├── yash-references.html
│   └── yash-references.css
│
├── skills/
│   ├── yash-skills.html
│   └── yash-skills.css
│
├── work/
│   ├── yash-work.html
│   └── yash-work.css
│
├── index.html   # Home page
└── index.css    # Styles for homepage

Features
--------
- Responsive Design:
  * Uses Flexbox and media queries to adapt between desktop and mobile layouts.
  * Nav bar is vertical on large screens, horizontal on small screens.

- Multi-page Resume:
  * Sections: Home, Education, Work Experience, Skills, Projects, References, and Credits.

- JavaScript Calculator (Projects Page):
  * Two input fields.
  * Six buttons: +, -, *, /, power, Clear.
  * Output displayed dynamically.
  * Negative results shown in red.
  * power() implemented with a for loop (not Math.pow()).

- Footer:
  * Contains copyright text with © symbol and a Credits link.

Deployment
----------
1. Initialize Git repository:
   git init
   git add .
   git commit -m "Initial commit"

2. Push to GitHub:
   git remote add origin https://github.com/YOUR_USERNAME/mp1.git
   git branch -M main
   git push -u origin main

3. Deploy with Vercel:
   - Connect GitHub repo.
   - Import project mp1.
   - Click Deploy.

Requirements (from assignment)
------------------------------
- Minimum 6 internal webpages.
- All pages must include: <header>, <nav>, <main>, <footer>.
- Calculator with inputs, buttons, and styled output.
- Responsive CSS with margins and paddings.
- Deployment on GitHub and Vercel.

Links
-----
- Live Demo (Vercel): https://mp-1-delta-eosin.vercel.app/

Author
------
Name: Yash Kedia
Course: CS 391 – Mini Project 1
