Freelancer Portfolio
A simple portfolio website for a Python/Django freelancer, built with HTML, CSS, and Tailwind CSS. Host it on GitHub Pages to showcase your skills and attract freelance work.
Setup Instructions

Clone the Repository:
git clone <your-repo-url>
cd freelancer-portfolio


Customize the Content:

Open index.html and replace "Ashish Kekaan" with your actual name.
Update the About section with your experience (e.g., replace "[X] years").
Add more projects or modify existing ones in the Projects section.
Replace your-form-id in the contact form's action attribute with your Formspree ID (see below).


Set Up Formspree for Contact Form:

Go to formspree.io and sign up.
Create a new form and copy the form ID.
Update the form action in index.html:<form action="https://formspree.io/f/your-form-id" method="POST">




Host on GitHub Pages:

Create a new repository on GitHub named your-username.github.io (or any name for a project-specific site).
Push the project files:git add .
git commit -m "Initial portfolio site"
git push origin main


Go to the repository settings on GitHub, scroll to "Pages", and set the source to the main branch.
Your site will be live at https://your-username.github.io (or https://your-username.github.io/repo-name).


Test the Site:

Open the live URL in a browser.
Test the contact form to ensure submissions reach your Formspree dashboard or email.



Notes

The site uses Tailwind CSS via CDN for simplicity. For production, consider downloading Tailwind for better performance.
Add more projects or skills as needed in index.html.
Ensure the contact form is secure by using HTTPS with Formspree.

