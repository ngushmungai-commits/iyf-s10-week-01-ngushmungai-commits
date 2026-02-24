# 🌐 Week 01: Web Foundation

> A responsive, multi-page professional portfolio website showcasing my journey as a Junior Web Developer

---

## 👤 Author

- **Name:** Wayne Mungai Ngure
- **GitHub:** [@ngushmungai-commits](https://github.com/ngushmungai-commits/ngushmungai-commits)
- **Date:** February 24, 2026

---

## 📖 Project Description

### Why I Created This Project

I built this project as my **very first milestone in web development** to bridge the gap between theory and practice. This project allowed me to master the core fundamentals of HTML5 and Tailwind CSS while learning how to structure a multi-page site and deploy a live product to the web. It represents the starting point of my journey to create clean, responsive, and user-friendly digital experiences.

### What I Created This Project For

This project is a **responsive, multi-page professional portfolio website** designed to showcase my journey and technical capabilities as a Junior Web Developer. It serves as a central digital hub where visitors can:

- Explore my background and experience
- Review my technical skill set
- Browse my past projects
- Contact me directly for professional opportunities

---

## 🚀 How to Use

### 1. Using `index.html`

**Local Viewing:**
- Open your project folder on your computer
- Double-click the `index.html` file
- It will launch in your default web browser (Chrome, Safari, etc.)
- Navigate to other pages like `about.html` or `contact.html`

**Editing:**
- Right-click the file
- Select "Open with" → Choose a code editor (VS Code, Notepad, etc.)
- Modify text, images, or any content

**Entry Point:**
- `index.html` is automatically recognized by web servers and browsers as the "Home" or starting page of your website

### 2. Using `README.md`

**Project Documentation:**
- Documents what your project is about
- Explains your development journey and challenges
- Serves as a reference for yourself and others

**GitHub Display:**
- When uploaded to GitHub, this file automatically displays on your repository's main page
- Acts as the front door for anyone viewing your code

**Markdown Formatting:**
- `.md` stands for Markdown
- Use `#` for headings
- Use `*` or `-` for bullet points
- Creates professional, easy-to-read documentation

---

## 🛠️ Technologies Used

- **HTML5** - Semantic structure and content
- **CSS3** - Styling and animations
- **Tailwind CSS** - Utility-first CSS framework
- **JavaScript** - Interactive elements and functionality

---

## ✨ Features

- ✅ **Fully Responsive Design** - Works perfectly on desktop, tablet, and mobile devices
- ✅ **Modern UI/UX** - Clean design with smooth transitions and animations
- ✅ **Multiple Pages** - Home, About, Projects, and Contact pages
- ✅ **Mobile Navigation** - Hamburger menu for mobile devices
- ✅ **Contact Form** - Functional contact form with validation
- ✅ **Project Showcase** - Grid layout displaying portfolio projects
- ✅ **Skills Display** - Visual skill bars showing proficiency levels
- ✅ **Social Media Links** - Connect via GitHub, LinkedIn, and Twitter

---

## 🏃 How to Run

### Option 1: Direct Browser Access
1. Clone this repository
2. Open `index.html` in your browser

### Option 2: Development Server (if applicable)
```bash
npm install
npm start
```

---

## 📚 Lessons Learned

### Technical Skills & Proficiency Levels

#### 🔹 HTML5 (Intermediate)
**What I Did:**
- Moved beyond basic tags to use semantic HTML5 elements like `<nav>`, `<section>`, `<header>`, and `<footer>`

**Level Achieved:**
- Mastered page structure and the ability to organize content logically for both users and search engines

---

#### 🔹 CSS Styling via Tailwind (Intermediate)
**What I Did:**
- Implemented a utility-first workflow using the Tailwind CDN
- Handled complex layouts, spacing (`py-16`, `px-6`)
- Applied modern design trends like gradients (`from-purple-900 to-indigo-800`)

**Level Achieved:**
- Can rapidly build professional-grade interfaces without writing custom CSS from scratch

---

#### 🔹 Responsive Web Design (Advanced Beginner)
**What I Did:**
- Utilized Tailwind's grid system (`grid-cols-1 md:grid-cols-2`)
- Ensured "Skills" and "Projects" sections adapt from mobile to desktop screens

**Level Achieved:**
- Understand how to create "mobile-first" designs that work across different devices

---

#### 🔹 Form Development & Validation (Intermediate)
**What I Did:**
- Built a functional contact form using specific input types (`type="email"`)
- Implemented the `required` attribute to ensure data integrity

**Level Achieved:**
- Capable of handling basic user input and client-side data validation

---

#### 🔹 Deployment & Version Control (Intermediate)
**What I Did:**
- Learned the workflow of initializing a Git repository
- Committed code and hosted a live site via GitHub Pages

**Level Achieved:**
- Understand the full lifecycle of a web project from local development to public launch

---

#### 🔹 UI/UX Design Principles (Advanced Beginner)
**What I Did:**
- Applied consistent navigation across multiple pages
- Used high-contrast color palettes for readability
- Added interactive hover effects (`hover:scale-105`) to improve user engagement

**Level Achieved:**
- Have a solid grasp of creating intuitive and visually appealing user experiences

---

## 🚧 Challenges Faced

### 1. Rendering Styles and Library Integration

**Challenge:**
- HTML document was using Tailwind CSS classes like `bg-indigo-900` and `text-pink-400`
- Browser was rendering them as plain text without any styling

**Solution:**
- Integrated the **Tailwind CSS CDN** within the `<head>` section
- Ensured the browser fetches the CSS framework before rendering the body
- All utility classes now apply correctly

---

### 2. Transitioning from Single-Page to Multi-Page Architecture

**Challenge:**
- Moving from a single-file structure to four pages required maintaining consistent user experience and navigation

**Solution:**
- Implemented **Semantic Navigation** by creating a unified `<nav>` component used across all pages
- Updated local anchor links (`#about`) to absolute file paths (`about.html`)
- Menu now works correctly from any page on the site

---

### 3. Layout Responsiveness and Grid Logic

**Challenge:**
- Displaying "Skills" and "Projects" sections to look good on both mobile phones and desktop monitors

**Solution:**
- Utilized **Tailwind's Responsive Grid System**
- Applied classes like `grid-cols-1 md:grid-cols-2`
- Single column on small screens, automatically expands to multiple columns on larger screens

---

### 4. Syntax Errors and Browser Parsing

**Challenge:**
- Small HTML syntax errors like incorrect tags (`<title h1>`) or stray characters (`|`) caused unpredictable rendering

**Solution:**
- Performed a **Code Audit and Cleanup**
- Fixed `<title>` tags and removed stray symbols
- Ensured HTML follows W3C standards for "well-formed" code

---

### 5. Data Integrity and User Input

**Challenge:**
- Contact form could potentially be submitted empty or with invalid email addresses

**Solution:**
- Implemented **Client-Side Validation**
- Added the `required` attribute
- Used specific HTML5 input types like `type="email"`
- Browser now warns users to fix input before submission

---

### 6. Asset Management (Image Rendering)

**Challenge:**
- Getting the profile image (`GEEK.jpg`) to display correctly with professional styling

**Solution:**
- Applied **CSS Masking and Border Utilities**
- Used classes like `rounded-full`, `border-4`, and `object-cover`
- Ensured images render as professional, centered circular profile pictures

---

## 📸 Screenshots


*Home page with hero section and skills preview*
<img width="746" height="382" alt="Home screenshot" src="https://github.com/user-attachments/assets/fba3d68d-7b02-4fe1-9ffe-4b8b22aeab75" />

*About page showcasing skills and experience*
<img width="1042" height="516" alt="About screenshot" src="https://github.com/user-attachments/assets/28234632-d02f-4120-b5fb-1969ac85e272" />

*Projects showcase with grid layout*
<img width="1188" height="544" alt="Projects screenshot" src="https://github.com/user-attachments/assets/bed1ea8e-a812-407d-a4b6-e11e41733309" />


*Contact form and information*
<img width="1074" height="533" alt="Contacts screenshot" src="https://github.com/user-attachments/assets/65dc0b67-3134-46d7-986c-ac17089608e9" />

---

## 🌐 Live Demo

> **Deployed Site:** [View Live Demo](https://ngushmungai-commits.github.io/iyf-s10-week-01-ngushmungai-commits)

---

## 📝 License

This project is free to use for personal and educational purposes.

---

## 🙏 Acknowledgments

- **Tailwind CSS** - For the amazing utility-first CSS framework
- **GitHub Pages** - For free hosting
- **MDN Web Docs** - For comprehensive web development documentation

---

## 📞 Connect With Me

- **GitHub:** [@ngushmungai-commits](https://github.com/ngushmungai-commits/ngushmungai-commits)
- **Portfolio:** [ngushmungai-commits.github.io](https://ngushmungai-commits.github.io)

---

<div align="center">

**⭐ Star this repo if you found it helpful!**

Made with ❤️ by Wayne Mungai Ngure

</div>
