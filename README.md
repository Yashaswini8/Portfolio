# Ex01 Portfolio
## Name:Yashaswini S
## Reg No:212224220123
## Date:27-04-2026

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
## HTML:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yashaswini Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<!-- NAVBAR -->
<header>
    <h1>Yashaswini</h1>
    <nav>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#certifications">Certifications</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<!-- HERO -->
<section class="hero-top">
    <div class="hero-text">
        <h1>
            Yashaswini <br>
            <span>S</span>
        </h1>

        <p class="hero-subtitle">
            B.Tech IT | AI & Machine Learning Developer | Python Programmer
        </p>

        <p class="hero-tags">
            BUILDING AI-POWERED APPLICATIONS • SCALABLE SOLUTIONS
        </p>

        <a href="#projects" class="hero-btn">View My Work</a>
    </div>
</section>

<!-- PREMIUM DIVIDER -->
<div class="premium-divider">
    <span>ABOUT ME</span>
</div>

<!-- ABOUT -->
<section id="about" class="section">
    <h2>About Me</h2>

    <p>
Hello! I'm <strong>Yashaswini</strong>, a 2nd-year B.Tech Information Technology student at Saveetha Engineering College. 
I have a strong interest in Artificial Intelligence and modern technologies. 
I enjoy building projects that solve real-world problems and improve user experiences. 
I am continuously learning and enhancing my technical skills in programming and development. 
My goal is to become a successful entrepreneur and create innovative solutions that make an impact. 
I am passionate, curious, and always ready to take on new challenges.
    </p>
</section>


<!-- PROJECTS -->
<section id="projects" class="section">
    <h2>Projects</h2>

    <div class="project-card">
        <h3>TrustAI</h3>
        <p>
            TrustAI is an AI-based system developed to enhance safety and trust by analyzing data and identifying potential risks. 
            It detects unusual patterns using intelligent algorithms and provides insights for better decision-making.
        </p>
    </div>

    <div class="project-card">
        <h3>Resume Analyzer</h3>
        <p>
            Resume Analyzer is a smart application that evaluates resumes and provides suggestions for improvement. 
            It extracts key skills and compares them with job requirements to determine suitability.
        </p>
    </div>
</section>

<section id="certifications" class="section">
    <h2>Certifications</h2>

    <div class="cert-container">

        <div class="cert-card">
            <h3>PyTorch Ultimate 2024 – From Basics to Cutting-Edge</h3>
            <a href="https://coursera.org/share/fc1eb6f100e33f406250d964e49ef28a" target="_blank">
                View Certificate →
            </a>
        </div>

        <div class="cert-card">
            <h3>IBM Data Analyst</h3>
            <a href="https://coursera.org/share/e54873e65c5dc7438bbb27d9202d9784" target="_blank">
                View Certificate →
            </a>
        </div>

        <div class="cert-card">
            <h3>Interactivity with JavaScript</h3>
            <a href="https://coursera.org/share/fa3fce8eca52b82fc0f5c7ca61d75b0f" target="_blank">
                View Certificate →
            </a>
        </div>

        <div class="cert-card">
            <h3>Python for Data Science, AI & Development</h3>
            <a href="https://coursera.org/share/7a61f533dc8fc7f9e747f34c9d97617f" target="_blank">
                View Certificate →
            </a>
        </div>

    </div>
</section>
<!-- CONTACT -->
<section id="contact" class="section contact-section">
    <h2>Get In Touch</h2>

    <p class="contact-text">
        Ready to discuss the next innovation in AI and Cloud.
    </p>

    <div class="contact-details">

        <div class="contact-item">
            <span class="icon">📧</span>
            <span>yashaswinisatheesh@gmail.com</span>
        </div>

        <div class="contact-item">
            <span class="icon">📱</span>
            <span>+91 9042983773 (WhatsApp)</span>
        </div>

        <div class="contact-item">
            <span class="icon">🔗</span>
            <a href="https://www.linkedin.com/in/yashaswini-s-36b9bb327" target="_blank">
                LinkedIn Profile
            </a>
        </div>

    </div>

    <p class="footer-text">© 2026 Yashaswini S. All rights reserved.</p>
</section>

</body>
</html>
```
## CSS:
```
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', sans-serif;
    scroll-behavior: smooth;
}

body {
    background: #020617;
    color: #f1f5f9;
}

/* NAVBAR */
header {
    position: fixed;
    width: 100%;
    top: 0;
    background: #020617;
    padding: 20px 60px;
    display: flex;
    justify-content: space-between;
    z-index: 1000;
}

nav a {
    margin-left: 20px;
    text-decoration: none;
    color: #cbd5f5;
}

nav a:hover {
    color: #38bdf8;
}

/* HERO */
.hero-top {
    padding: 180px 80px 100px;
}

.hero-text h1 {
    font-size: 55px;
}

.hero-text span {
    color: #38bdf8;
}

.hero-subtitle {
    margin: 20px 0;
    color: #94a3b8;
}

.hero-tags {
    font-size: 12px;
    letter-spacing: 2px;
    color: #64748b;
}

.hero-btn {
    display: inline-block;
    margin-top: 20px;
    padding: 12px 25px;
    background: #38bdf8;
    color: black;
    border-radius: 8px;
    text-decoration: none;
}
.hero-top {
    padding-bottom: 40px;   /* reduce huge gap */
}

.premium-divider {
    margin: 30px auto;      /* bring closer to hero */
}

/* DIVIDER */
.premium-divider {
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 60px auto;
    width: 80%;
}

.premium-divider::before,
.premium-divider::after {
    content: "";
    flex: 1;
    height: 1px;
    background: linear-gradient(to right, transparent, #38bdf8, transparent);
}

.premium-divider span {
    margin: 0 15px;
    color: #38bdf8;
    font-size: 12px;
    letter-spacing: 3px;
}

/* SECTIONS */
.section {
    padding: 80px;
}
<header>...</header>

<section class="hero-top">...</section>

<div class="premium-divider">
    <span>ABOUT ME</span>
</div>

<section id="about" class="section">

/* ABOUT SECTION */
#about {
    padding: 40px 80px;   /* reduce top gap → moves it visually up */
}

/* ABOUT HEADING */
#about h2 {
    font-size: 42px;      
    margin-bottom: 25px;
    color: #38bdf8;
}

/* ABOUT PARAGRAPH */
#about p {
    font-size: 22px;      
    line-height: 2;
    color: #cbd5f5;
    width: 100%;
}
/* SKILLS */
.card-container {
    display: flex;
    flex-direction: column;
    gap: 10px;
}

.card {
    background: #1e293b;
    padding: 12px;
    width: fit-content;
}

/* PROJECTS */
.project-card {
    background: #1e293b;
    padding: 20px;
    margin-top: 15px;
    border-radius: 10px;
}

.cert-container {
    display: flex;
    flex-direction: column;
    gap: 20px;
    margin-top: 20px;
}

.cert-card {
    background: #1e293b;
    padding: 20px;
    border-radius: 10px;
    transition: 0.3s;
}

.cert-card h3 {
    margin-bottom: 10px;
}

.cert-card a {
    color: #38bdf8;
    text-decoration: none;
    font-weight: 500;
}

.cert-card:hover {
    transform: translateY(-5px);
}
/* CONTACT */
.contact-section {
    text-align: center;
}

.contact-details {
    margin-top: 20px;
    display: flex;
    flex-direction: column;
    gap: 15px;
    align-items: center;
}

.contact-item {
    display: flex;
    gap: 10px;
    background: #1e293b;
    padding: 12px 18px;
    border-radius: 8px;
}

.contact-item a {
    color: #38bdf8;
    text-decoration: none;
}

.footer-text {
    margin-top: 20px;
    font-size: 12px;
    color: #64748b;
}
/* SKILLS SECTION LAYOUT */
.skills-wrapper {
    display: flex;
    justify-content: space-between;
    gap: 60px;
    margin-top: 40px;
    padding-left: 80px;
    padding-right: 80px;
}

/* LEFT SIDE (LIST) */
.skills-list {
    width: 55%;
}

/* BIGGER ORDERED LIST */
.skills-list ol {
    font-size: 22px;          
    line-height: 2.2;
    color: #f1f5f9;
    padding-left: 25px;
}

/* EACH ITEM STYLE */
.skills-list li {
    margin-bottom: 10px;
    transition: 0.3s;
}

/* HOVER EFFECT */
.skills-list li:hover {
    color: #38bdf8;
    transform: translateX(8px);
}

/* RIGHT SIDE (VISUAL BOX) */
.skills-visual {
    width: 45%;
    background: #1e293b;
    padding: 35px;
    border-radius: 12px;
    font-size: 18px;
    line-height: 2;
    color: #cbd5f5;
    transition: 0.3s;
}

.skills-visual:hover {
    transform: scale(1.02);
}






```
## OUTPUT

<img width="1911" height="1147" alt="image" src="https://github.com/user-attachments/assets/96f48790-594f-4729-a7d7-9ec01eaef64f" />
<img width="1911" height="1082" alt="image" src="https://github.com/user-attachments/assets/56b36484-fb7a-453d-9266-64c5d7b7521c" />
<img width="1915" height="1198" alt="image" src="https://github.com/user-attachments/assets/08f933aa-1437-4464-8227-408776f41323" />



## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
