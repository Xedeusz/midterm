Dexter's Domain - Personal Website
Welcome to Dexter's Domain, a personal portfolio website showcasing Dexter John M. De Guzman's journey as an aspiring IT professional. This project features a futuristic, neon-themed design with interactive elements, highlighting skills, projects, educational background, personal interests, and a contact form.
Table of Contents

Overview
Features
Technologies Used
Setup Instructions
File Structure
Usage
Contributing
License
Contact

Overview
Dexter's Domain is a single-page application with an introductory landing page (index.html) and a main portfolio page (main.html). The website is designed to provide a professional yet engaging user experience, featuring a sidebar navigation, animated shooting star background, and sections for About, Work Samples, Life Chapters, Core Competencies, and Contact. The project also references a gallery page (photos.html) and a messages page (messages.html), though these are not included in the provided files.
The website uses a combination of HTML, CSS, JavaScript, and external libraries to create a responsive, visually appealing interface with smooth animations and interactive elements.
Features

Introductory Landing Page: A welcoming page with a profile photo, animated title, and a call-to-action button linking to the main portfolio.
Responsive Sidebar Navigation: A fixed sidebar with smooth scrolling to sections (Home, About, Contact, Gallery) that toggles on mobile devices.
Hero Section: A full-screen hero section with a profile image, name, and professional tagline, enhanced with AOS animations.
About Section:
Detailed biography of Dexter John, including career goals and technical skills.
A grid of personal interests with images (e.g., Music, Coding, Cars).
Educational timeline showcasing academic background.


Work Samples: A link to GitHub repositories showcasing web development projects.
Life Chapters: A preview of personal moments with links to a gallery page.
Core Competencies: Skill bars displaying proficiency in HTML, PHP/MySQL, JavaScript, and CSS/Bootstrap.
Contact Form: A form that submits user input to messages.html with SweetAlert2 feedback.
Futuristic Design: Neon purple color scheme, shooting star animations, and electric crackle effects.
Responsive Design: Optimized for desktops, tablets, and mobile devices with media queries.
Animations: AOS library for scroll-based animations and custom CSS animations for interactive elements.

Technologies Used

HTML5: Structure of the website.
CSS3: Styling with custom animations, gradients, and responsive design.
JavaScript: Interactivity for navigation, form handling, and smooth scrolling.
Bootstrap 5: Grid system and responsive utilities (used in main.html).
AOS (Animate on Scroll): Scroll-based animations for dynamic content reveal.
SweetAlert2: Pop-up notifications for form submission feedback.
Bootstrap Icons: Icons for content cards and navigation.
Google Fonts: Orbitron and Montserrat fonts for typography.
External CDNs:
Bootstrap CSS/JS
AOS CSS/JS
SweetAlert2


Assets: Images for profile, interests, education, and personal moments (stored in assets/ folder).

Setup Instructions
To run the project locally, follow these steps:

Clone or Download the Repository:
git clone https://github.com/Xedeusz/dexters-domain.git

Alternatively, download the project files as a ZIP and extract them.

Navigate to the Project Directory:
cd dexters-domain


Serve the Website: Since this is a static website, you can serve it using a local server. Options include:

Using Python:
python -m http.server 8000

Then, open http://localhost:8000/index.html in your browser.

Using Node.js (with http-server):
npm install -g http-server
http-server

Open http://localhost:8080/index.html.

Using VS Code: Use the Live Server extension to serve the files.



Ensure Internet Connectivity: The project relies on external CDNs for Bootstrap, AOS, SweetAlert2, and Google Fonts. Ensure you have an internet connection for these resources to load.

File Dependencies:

Ensure the assets/ folder with images (e.g., me.jpg, spotify.jpg, etc.) is present in the project root.
The photos.html and messages.html pages are referenced but not provided. You may need to create these files or adjust links if they are not part of the project.



File Structure
dexters-domain/
├── assets/
│   ├── me.jpg
│   ├── spotify.jpg
│   ├── coding.jpg
│   ├── porsche.jpg
│   ├── coffee.jpg
│   ├── dota2.jpg
│   ├── anime.jpg
│   ├── billiards.jpg
│   ├── mlbb.jpg
│   ├── bball.jpg
│   ├── csgo.jpg
│   ├── Lumbang.png
│   ├── afg.png
│   ├── nu.png
│   ├── pl2.jpg
│   ├── tourna11.jpg
│   ├── sc1.jpg
├── index.html
├── main.html
├── photos.html (referenced, not provided)
├── messages.html (referenced, not provided)
└── README.md


index.html: The landing page with an introductory hero section.
main.html: The main portfolio page with detailed sections.
assets/: Folder containing images for profile, interests, education, and moments.
photos.html: Gallery page (not provided, assumed to display photos/videos).
messages.html: Page to display contact form submissions (not provided).
README.md: This file.

Usage

Landing Page (index.html):
View the introductory hero section with a profile photo and a CTA button.
Click "Enter My Main Domain" to navigate to main.html.
Use the top navigation to access other sections or pages.


Main Portfolio (main.html):
Explore sections via the sidebar or by scrolling.
Click the "View Projects" button to visit GitHub repositories.
Click "View Gallery" to access the gallery page (if available).
Submit the contact form to send a message (redirects to messages.html).


Responsive Navigation:
On mobile devices, click the hamburger menu to toggle the sidebar.
Links support smooth scrolling to sections within main.html.



Contributing
Contributions are welcome! To contribute:

Fork the repository.
Create a new branch (git checkout -b feature/your-feature).
Make your changes and commit (git commit -m "Add your feature").
Push to the branch (git push origin feature/your-feature).
Open a Pull Request.

Please ensure your code follows the existing style and includes appropriate documentation.
License
This project is licensed under the MIT License. See the LICENSE file for details.
Contact
For questions or feedback, reach out to Dexter John M. De Guzman:

LinkedIn: Dexter John De Guzman
GitHub: Xedeusz
Instagram: ndexcz
Facebook: (https://facebook.com/Dexter John De Guzman)

You can also use the contact form on the website to send a message.

© 2025 Xedeusz. All Rights Reserved.
