# 🌐 Personal Portfolio Website 

A fully responsive and animated personal portfolio website designed to showcase my skills, projects, and contact information. Built using modern web technologies including HTML, CSS, JavaScript, and Node.js with MongoDB for backend integration.


## 📁 Project Structure

├── index.html # Main HTML file <br>
├── style.css # CSS for styling and layout <br>
├── script.js # JavaScript for interactivity and animations <br>
├── server.js # Node.js backend server for form submission <br>
├── myproject # Contains images 

---

## 🛠️ Features

- 🎨 Responsive modern design with smooth animations
- 🧠 Typing animation using `Typed.js`
- 🌀 Scroll-based animations using `ScrollReveal.js`
- 🗂️ Project showcase gallery
- 📞 Contact form with backend storage using MongoDB
- 🔄 Mobile-friendly with toggle menu

---

## 🔧 Tech Stack

**Frontend:**
- HTML5, CSS3
- JavaScript (Vanilla)
- Boxicons, Typed.js, ScrollReveal.js

**Backend:**
- Node.js with Express.js
- MongoDB with Mongoose
- CORS, Body-parser

---

## 📬 Contact Form

The form sends user submissions to a MongoDB database using the `/submit-form` POST endpoint.

### To run the backend locally:

```bash
npm install
node server.js
