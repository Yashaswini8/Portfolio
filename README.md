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

<!-- ABOUT -->
<section id="about" class="section">
    <h2>About Me</h2>

    <div class="about-icons">
        <span>🤖</span>
        <span>💻</span>
        <span>📊</span>
        <span>🧠</span>
        <span>🚀</span>
    </div>

    <p>
Hello! I'm <strong>Yashaswini</strong>, a 2nd-year B.Tech Information Technology student at Saveetha Engineering College. 
I have a strong interest in Artificial Intelligence and modern technologies. 
I enjoy building projects that solve real-world problems and improve user experiences. 
I am continuously learning and enhancing my technical skills in programming and development. 
My goal is to become a successful entrepreneur and create innovative solutions that make an impact. 
I am passionate, curious, and always ready to take on new challenges.
    </p>
</section>

<!-- SKILLS -->
<section id="skills" class="section">
    <h2>Skills</h2>
    <div class="card-container">
        <div class="card">C</div>
        <div class="card">Python</div>
        <div class="card">DBMS</div>
        <div class="card">HTML</div>
        <div class="card">AI & ML</div>
        <div class="card">Deep Learning</div>
    </div>
</section>

<!-- PROJECTS -->
<section id="projects" class="section">
    <h2>Projects</h2>

    <div class="project-card">
        <h3>TrustAI</h3>
        <p>
            TrustAI is an AI-based system developed to enhance safety and trust by analyzing data and identifying potential risks. 
            It detects unusual patterns using intelligent algorithms and provides insights for better decision-making. 
            The system is designed for real-world applications and focuses on improving reliability and security. 
            It ensures a smooth and user-friendly experience through smart automation.
        </p>

        <div class="tags">
            <span>Python</span>
            <span>AI</span>
            <span>Machine Learning</span>
        </div>
    </div>

    <div class="project-card">
        <h3>Resume Analyzer</h3>
        <p>
            Resume Analyzer is a smart application that evaluates resumes and provides suggestions for improvement. 
            It extracts key skills and compares them with job requirements to determine suitability. 
            The system helps users identify missing skills and improve their resumes effectively. 
            It includes a clean interface with visual insights for better understanding.
        </p>

        <div class="tags">
            <span>Python</span>
            <span>Streamlit</span>
            <span>NLP</span>
        </div>
    </div>

</section>

<!-- CERTIFICATIONS -->
<section id="certifications" class="section">
    <h2>Certifications</h2>

    <ul class="cert-list">
        <li><a href="https://coursera.org/share/fc1eb6f100e33f406250d964e49ef28a" target="_blank">PyTorch Ultimate 2024</a></li>
        <li><a href="https://coursera.org/share/e54873e65c5dc7438bbb27d9202d9784" target="_blank">IBM Data Analyst</a></li>
        <li><a href="https://coursera.org/share/fa3fce8eca52b82fc0f5c7ca61d75b0f" target="_blank">Interactivity with JavaScript</a></li>
        <li><a href="https://coursera.org/share/7a61f533dc8fc7f9e747f34c9d97617f" target="_blank">Python for Data Science</a></li>
    </ul>
</section>
<hr class="section-divider">
<!-- CONTACT -->
<section id="contact" class="section contact-section">
    <h2>Get In Touch</h2>

    <p class="contact-text">
        Ready to discuss the next innovation in AI and Cloud.
    </p>

    <p><strong>Direct:</strong> +91 9042983773</p>

    <a href="https://www.linkedin.com/in/yashaswini-s-36b9bb327" target="_blank" class="linkedin-btn">
        Connect on LinkedIn →
    </a>

    <p class="footer-text">© 2026 Yashaswini S. All rights reserved.</p>
</section>

</body>
</html>
```
## CSS:
```
/* RESET */
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
    align-items: center;
    box-shadow: 0 2px 10px rgba(0,0,0,0.5);
    z-index: 1000;
}

header h1 {
    font-size: 22px;
    font-weight: 600;
}

nav a {
    margin-left: 20px;
    text-decoration: none;
    color: #cbd5f5;
    transition: 0.3s;
}

nav a:hover {
    color: #38bdf8;
}

/* HERO SECTION */
.hero-top {
    background: #020617;
    padding: 180px 80px 100px;
}

.hero-text {
    max-width: 800px;
}

.hero-text h1 {
    font-size: 55px;
    font-weight: 700;
    line-height: 1.1;
}

.hero-text span {
    color: #38bdf8;
}

.hero-subtitle {
    margin: 20px 0;
    font-size: 18px;
    color: #94a3b8;
}

.hero-tags {
    font-size: 12px;
    letter-spacing: 2px;
    color: #64748b;
    margin-bottom: 25px;
}

.hero-btn {
    display: inline-block;
    padding: 12px 25px;
    background: #38bdf8;
    color: black;
    text-decoration: none;
    border-radius: 8px;
    font-weight: bold;
    transition: 0.3s;
}

.hero-btn:hover {
    background: white;
}

/* SECTIONS */
.section {
    padding: 100px 80px;
}

/* HEADINGS */
h2 {
    color: #38bdf8;
    margin-bottom: 20px;
}

/* ABOUT SECTION FIX */
#about {
    max-width: 900px;
    margin: auto;
}

.about-icons {
    display: flex;
    gap: 12px;
    margin-bottom: 20px;
}

.about-icons span {
    background: #1e293b;
    padding: 10px;
    border-radius: 50%;
    font-size: 20px;
    transition: 0.3s;
}

.about-icons span:hover {
    background: #38bdf8;
    color: black;
}

#about p {
    line-height: 1.8;
    color: #cbd5f5;
    font-size: 16px;
}

/* SKILLS (VERTICAL) */
.card-container {
    display: flex;
    flex-direction: column;
    gap: 12px;
    margin-top: 20px;
}

.card {
    background: #1e293b;
    padding: 12px 18px;
    border-radius: 8px;
    width: fit-content;
    transition: 0.3s;
}

.card:hover {
    background: #38bdf8;
    color: black;
    transform: translateX(5px);
}

/* PROJECTS */
.project-card {
    background: #1e293b;
    padding: 20px;
    margin-top: 15px;
    border-radius: 12px;
    transition: 0.3s;
}

.project-card:hover {
    transform: translateY(-5px);
}

/* PROJECT TAGS */
.tags {
    margin-top: 10px;
}

.tags span {
    background: #334155;
    padding: 6px 12px;
    border-radius: 20px;
    margin-right: 5px;
    font-size: 12px;
}

/* CERTIFICATIONS */
.cert-list {
    list-style: none;
    margin-top: 20px;
}

.cert-list li {
    background: #1e293b;
    padding: 12px 18px;
    margin-bottom: 10px;
    border-radius: 8px;
    transition: 0.3s;
}

.cert-list li:hover {
    background: #38bdf8;
}

.cert-list a {
    text-decoration: none;
    color: #f1f5f9;
    font-weight: 500;
}

.cert-list li:hover a {
    color: black;
}

/* CONTACT */
.contact-section {
    text-align: center;
}

.contact-text {
    margin: 15px 0;
    color: #94a3b8;
}

.linkedin-btn {
    display: inline-block;
    margin-top: 10px;
    color: #38bdf8;
    text-decoration: none;
    font-weight: 600;
}

.linkedin-btn:hover {
    text-decoration: underline;
}

.footer-text {
    margin-top: 40px;
    font-size: 12px;
    color: #64748b;
}
.section-divider {
    border: none;
    height: 1px;
    width: 80%;
    margin: 0 auto;
    background: linear-gradient(to right, transparent, #38bdf8, transparent);
}
```
## OUTPUT

<img width="1919" height="1143" alt="image" src="https://github.com/user-attachments/assets/a377b15e-e111-4137-bb9e-d68adf89f459" />
<img width="1918" height="1151" alt="image" src="https://github.com/user-attachments/assets/b9c14292-d15b-45d4-9fb8-4c9d64e8ec44" />
<img width="1918" height="1140" alt="image" src="https://github.com/user-attachments/assets/0f2076d8-97d0-46cc-8486-4fa0637dfdb1" />


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
