# Freelancer Portfolio

A modern, responsive portfolio website for a Python/Django freelancer, built with HTML, CSS, Tailwind CSS, and JavaScript. This site showcases your skills, projects, and contact information, making it ideal for attracting freelance work. Host it on GitHub Pages for a professional online presence.

## Features

- **Responsive Design**: Optimized for desktop, tablet, and mobile devices.
- **Smooth Navigation**: Fixed navbar with smooth scrolling to sections.
- **Interactive Elements**: Hover animations, form validation, and a subtle circuit-board background pattern.
- **Contact Form**: Integrated with Formspree for secure message submissions.
- **Customizable**: Easily update content to reflect your personal brand and projects.

## Setup Instructions

### 1. Clone the Repository
```bash
git clone <your-repo-url>
cd freelancer-portfolio
```

### 2. Customize the Content
- Open `index.html` and replace "Ashish Kekaan" with your name.
- Update the "About" section with your experience (e.g., replace "3 years").
- Modify the "Projects" section to include your own projects, adding descriptions and titles as needed.
- Replace the profile image path (`images/profile.png`) with your own image, ensuring the file is placed in an `images/` directory.
- Update the contact form's `action` attribute with your Formspree form ID (see below).

### 3. Set Up Formspree for Contact Form
- Sign up at [formspree.io](https://formspree.io).
- Create a new form and copy the provided form ID.
- Update the form action in `index.html`:
  ```html
  <form id="contact-form" action="https://formspree.io/f/your-form-id" method="POST">
  ```

### 4. Host on GitHub Pages
- Create a GitHub repository named `your-username.github.io` for a personal site or any name for a project-specific site.
- Push the project files:
  ```bash
  git add .
  git commit -m "Initial portfolio site"
  git push origin main
  ```
- Navigate to the repository settings on GitHub, go to the "Pages" section, and set the source to the `main` branch.
- Your site will be live at `https://your-username.github.io` (or `https://your-username.github.io/repo-name` for project-specific sites).

### 5. Test the Site
- Visit the live URL in a browser.
- Test the contact form to confirm submissions appear in your Formspree dashboard or linked email.
- Verify responsiveness across different devices and screen sizes.

## Project Structure
```
freelancer-portfolio/
├── index.html          # Main HTML file
├── css/
│   └── styles.css      # Custom CSS with unique circuit pattern
├── js/
│   └── scripts.js      # JavaScript for form validation
├── images/
│   └── profile.png     # Placeholder for profile image
└── README.md           # Project documentation
```

## Notes
- **Tailwind CSS**: Loaded via CDN for simplicity. For production, consider installing Tailwind locally or using a build process for better performance.
- **Images**: Ensure `images/profile.png` exists or update the path in `index.html`.
- **Security**: The contact form uses HTTPS with Formspree for secure submissions.
- **Customization**: Add more skills, projects, or sections by editing `index.html` and styling in `styles.css`.
- **JavaScript**: The `scripts.js` file includes enhanced form validation with email format checking.

## License
© 2025 Ashish Kekaan. All rights reserved.

## Contact
For questions or collaboration, use the contact form on the live site or reach out via your preferred platform.