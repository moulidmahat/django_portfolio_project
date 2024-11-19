# Django Portfolio Website

This project is a Django-based portfolio website developed as part of an assessment. The website showcases skills, projects, and professional background, with a functional contact form that stores user messages in a database.

---

## Project Features

### Contact Form
- Fields:
  - Name (Full name of the user)
  - Email (Validated email format)
  - Phone (Valid phone number)
  - Message (Minimum of 100 characters)
- **Validations:**
  - All fields are required.
  - Error messages are displayed for invalid input.
- **Functionality:**
  - Submitted data is stored in the database for easy management.
  - Users receive a success message upon submission.

### Pages
- **Home Page:** Highlights personal skills, key projects, and a brief introduction.
- **About Page:** Provides professional background and detailed experience.
- **Projects Page:** Showcases completed projects with descriptions and links.
- **Contact Page:** Includes the contact form for user submissions.

### Design and Responsiveness
- Fully responsive across desktop, tablet, and mobile devices.
- Designed using **modern CSS techniques** and **Bootstrap/Tailwind**.
- Includes a navigation bar and footer for seamless navigation.
- Interactive user experience with hover effects and transitions.

---

## Technologies Used
- **Backend:** Django 4.x
- **Frontend:** HTML5, CSS3, Bootstrap/Tailwind CSS
- **Database:** SQLite
- **Version Control:** Git & GitHub
- **Tools:** PyCharm IDE (or other preferred editors)

---

## Installation and Setup

Follow these steps to set up the project locally:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/moulidmahat/portfolio-django.git
   cd portfolio-django
