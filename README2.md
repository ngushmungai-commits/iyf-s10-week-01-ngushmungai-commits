# Week 01: Web foundation

## Author

- **Name:** Wayne Mungai Ngure
- **GitHub:** @ngushmungai-commits https://github.com/ngushmungai-commits/ngushmungai-commits
- **Date:** 02/24/2026

## Project Description

### Why I Created This Project

I built this project as my very first milestone in web development to bridge the gap between theory and practice.This project allowed me to master the core fundamentals of HTML5 and Tailwind CSS while learning how to structure a multi-page site and deploy a live product to the web. It represents the starting point of my journey to create clean, responsive, and user-friendly digital experiences.

### What I created this project for.

This project is a responsive, multi-page professional portfolio website designed to showcase my journey and technical capabilities as a Junior Web Developer. It serves as a central digital hub where visitors can explore my background, technical skill set, and past projects while providing a direct channel for professional communication.

### How to use this:

1. # How to use index.HTML
   Local Viewing: Open your project folder on your computer and double-click the index.html file. It will launch in your default web browser (like Chrome or Safari), allowing you to see your home page and navigate to other pages like about.html or contact.html.

Editing: To change the text or images (like "Wayne Mungai"), right-click the file and select "Open with" then choose a code editor like VS Code or Notepad.

Entry Point: In web development, the file named index.html is automatically recognized by web servers and browsers as the "Home" or starting page of your website.

2. # How to use README.md
   Project Documentation: This file is used to tell others (and your future self) what your project is about. You should write your "Why I built this" and "Challenges faced" sections here.

GitHub Display: When you upload your project to GitHub, the content of this file is automatically displayed on your repository's main page, acting as the front door for anyone viewing your code.

Markdown Formatting: The .md extension stands for Markdown. Use symbols like # for headings and \* for bullet points to make the text look professional and easy to read.

## Technologies Used

- HTML5
- CSS3
- JavaScript

## Features

- **Fully Responsive Design** - Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX** - Clean design with smooth transitions and animations
- **Multiple Pages** - Home, About, Projects, and Contact pages
- **Mobile Navigation** - Hamburger menu for mobile devices
- **Contact Form** - Functional contact form with validation
- **Project Showcase** - Grid layout displaying portfolio projects
- **Skills Display** - Visual skill bars showing proficiency levels
- **Social Media Links** - Connect via GitHub, LinkedIn, and Twitter

## How to Run

1. Clone this repository
2. Open `index.html` in your browser
   OR
   Run `npm install` then `npm start`

## Lessons Learned

### **Technical Skills & Proficiency Levels**

- **HTML5 (Intermediate)**
- **What I did:** You moved beyond basic tags to use semantic HTML5 elements like `<nav>`, `<section>`, `<header>`, and `<footer>`.
- **Level:** You have mastered page structure and the ability to organize content logically for both users and search engines.

- **CSS Styling via Tailwind (Intermediate)**
- **What I did:** You implemented a utility-first workflow using the Tailwind CDN to handle complex layouts, spacing (`py-16`, `px-6`), and modern design trends like gradients (`from-purple-900 to-indigo-800`).
- **Level:** You can rapidly build professional-grade interfaces without writing custom CSS from scratch.

- **Responsive Web Design (Advanced Beginner)**
- **What I did:** You utilized Tailwind’s grid system (`grid-cols-1 md:grid-cols-2`) to ensure your "Skills" and "Projects" sections automatically adapt from mobile phones to desktop screens.
- **Level:** You understand how to create "mobile-first" designs that work across different devices.

- **Form Development & Validation (Intermediate)**
- **What I did:** You built a functional contact form using specific input types (`type="email"`) and the `required` attribute to ensure data integrity.
- **Level:** You are capable of handling basic user input and client-side data validation.

- **Deployment & Version Control (Intermediate)**
- **What I did:** You learned the workflow of initializing a Git repository, committing code, and hosting a live site via GitHub Pages.
- **Level:** You understand the full lifecycle of a web project from local development to public launch.

- **UI/UX Design Principles (Advanced Beginner)**
- **What I did:** You applied consistent navigation across multiple pages, high-contrast color palettes for readability, and interactive hover effects (`hover:scale-105`) to improve user engagement.
- **Level:** You have a solid grasp of creating intuitive and visually appealing user experiences.

## Challenges Faced

### **1. Rendering Styles and Library Integration**

- **Challenge:** Initially, the HTML document was using Tailwind CSS classes like `bg-indigo-900` and `text-pink-400`, but the browser was rendering them as plain text without any styling.
- **Solution:** I integrated the **Tailwind CSS CDN** within the `<head>` section of my documents. This allowed the browser to fetch the necessary CSS framework before rendering the body, ensuring all utility classes were applied correctly.

### **2. Transitioning from Single-Page to Multi-Page Architecture**

- **Challenge:** Moving from a single-file structure to a four-page site (`index.html`, `about.html`, `projects.html`, `contact.html`) required maintaining a consistent user experience and navigation.
- **Solution:** I implemented **Semantic Navigation** by creating a unified `<nav>` component used across all pages. I also updated local anchor links (e.g., `#about`) to absolute file paths (e.g., `about.html`) to ensure the menu worked correctly from any page on the site.

### **3. Layout Responsiveness and Grid Logic**

- **Challenge:** Displaying "Skills" and "Projects" in a way that looked good on both mobile phones and desktop monitors was difficult with standard CSS.
- **Solution:** I utilized **Tailwind’s Responsive Grid System**. By applying classes like `grid-cols-1 md:grid-cols-2`, I solved the layout issue by forcing a single column on small screens and automatically expanding to multiple columns on larger screens.

### **4. Syntax Errors and Browser Parsing**

- **Challenge:** Small errors in HTML syntax, such as using incorrect tags like `<title h1>` or leaving stray characters like `|` outside of the body, could cause unpredictable rendering or SEO issues.
- **Solution:** I performed a **Code Audit and Cleanup**, fixing the `<title>` tags and removing stray symbols to ensure the HTML was "well-formed" and followed W3C standards.

### **5. Data Integrity and User Input**

- **Challenge:** Creating a contact form that could potentially be submitted empty or with invalid email addresses.
- **Solution:** I implemented **Client-Side Validation** by adding the `required` attribute and using specific HTML5 input types like `type="email"`. This ensures the browser warns the user to fix their input before the form is ever sent.

### **6. Asset Management (Image Rendering)**

- **Challenge:** Getting the profile image (`GEEK.jpg`) to display correctly with professional styling (rounded borders and shadows).
- **Solution:** I applied **CSS Masking and Border Utilities**. By using classes like `rounded-full`, `border-4`, and `object-cover`, I ensured that even if the original image wasn't a perfect square, it would render as a professional, centered circular profile picture.

## Screenshots (optional)

![Screenshot description](path/to/screenshot.png)

## Live Demo (if deployed)

[View Live Demo](https://your-deployed-url.com)
