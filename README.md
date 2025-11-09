# Hassaan Muhammad – ExpressJS Portfolio (Assignment 2)

This repository contains my **Assignment 2: ExpressJS Portfolio Website** for Ontario Tech University.  
It is a continuation of **Assignment 1 (HTML Portfolio)**, rebuilt using **Node.js**, **Express**, and **EJS templates**.

---

## Live Deployment
**Render Link:** https://<your-app-name>.onrender.com  
**GitHub Repo:** https://github.com/hassaanmuhammad-prog/express-portfolio

---

## Project Overview
This project converts my static HTML portfolio into a dynamic **Express web application**.  
It demonstrates routing, EJS templating, partials (header & footer), static assets, and deployment to a live server.

**Pages / Routes:**
| Route | Description |
|--------|--------------|
| `/` | Home page introducing me and my portfolio |
| `/about` | About Me page with profile photo and video |
| `/projects` | Portfolio Projects page with images and report links |
| `/contact` | Contact Me page with social links and form |

---


## Tech Stack
- **Node.js** + **Express.js**
- **EJS** templating engine with partials (`_header.ejs`, `_footer.ejs`)
- **Bootstrap 5 (CDN)** for styling and responsive layout
- **Font Awesome (CDN)** for icons
- **CSS** in `public/stylesheets/style.css`
- Static files stored in `/public` (`images/`, `videos/`, `documents/`)

---

## Folder Structure
express-portfolio/
├── app.js
├── routes/
│ └── index.js
├── views/
│ ├── index.ejs
│ ├── about.ejs
│ ├── projects.ejs
│ ├── contact.ejs
│ └── partials/
│ ├── _header.ejs
│ └── _footer.ejs
└── public/
├── stylesheets/
│ └── style.css
├── images/
├── videos/
└── documents/

---

# Citations / References

Bootstrap v5.3
 – used for grid layout and responsive design.

Font Awesome
 – used for social media icons.

Express Generator
 – used to scaffold the project structure.

All other content, media, and code authored by Hassaan Muhammad.

---

# Author

Hassaan Muhammad
 hassaan.muhammad@ontariotechu.net

 LinkedIn: https://www.linkedin.com/in/hassaan-muhammad-083742384

 GitHub: https://github.com/hassaanmuhammad-prog 

---

## Notes

This project fulfills all Assignment 2 requirements:

ExpressJS application with routes for all pages

Shared layout and partials using EJS

Bootstrap and Font Awesome integration

Public directory for static assets

Deployed live to Render

Proper documentation and citations

---

## Run Locally
To run this project locally:

```bash
git clone https://github.com/hassaanmuhammad-prog/express-portfolio.git
cd express-portfolio
npm install
npm start

---

**Render Link:** https://express-portfolio-jde7.onrender.com/

