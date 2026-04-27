# Ex01 Portfolio
## Date:

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
.html
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kurapati Vishnu Vardhan Reddy | Portfolio</title>
    <meta name="description"
        content="Portfolio of Kurapati Vishnu Vardhan Reddy, a Computer Science student passionate about Data Structures, Algorithms, and Web Development.">
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <header>
        <nav>
            <div class="logo">KVVR</div>
            <ul class="nav-links">
                <li><a href="#about">About</a></li>
                <li><a href="#experience">Experience</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="hero">
            <div class="hero-content">
                <h1>Kurapati Vishnu Vardhan Reddy</h1>
                <p class="subtitle">Computer Science Student & Web Developer</p>
                <div class="hero-actions">
                    <a href="#contact" class="btn">Get in touch</a>
                </div>
            </div>
            <div class="hero-image">
                <img src="hero.jpeg" alt="Hero Image" loading="lazy">
            </div>
        </section>

        <section id="about" class="about-section">
            <div class="about-content">
                <h2>About Me</h2>
                <p>Computer Science student with strong skills in Python, Java, HTML, CSS, and web technologies like
                    React and Django. Passionate about Data Structures and Algorithms, with a keen interest in solving
                    complex problems and building scalable solutions. Eager to contribute to innovative projects.</p>
                <h3>Education</h3>
                <div class="education-item">
                    <h4>Saveetha Engineering College</h4>
                    <p>B.E. Computer Science and Engineering | 2023–2027 | GPA: 8.2</p>
                </div>
            </div>

        </section>

        <section id="experience">
            <h2>Work Experience</h2>
            <div class="experience-item">
                <h3>Zybeak Technologies Pvt Ltd</h3>
                <p class="date">Intern | Dec 2024 – Jan 2025</p>
                <ul>
                    <li>Learned the basics of ethical hacking, including networking fundamentals, types of hackers, and
                        core security concepts.</li>
                    <li>Gained hands-on exposure to security tools and techniques used to identify vulnerabilities in
                        systems and websites.</li>
                    <li>Participated in a Capture The Flag (CTF) challenge focused on system and service exploitation.
                    </li>
                </ul>
            </div>
            <div class="experience-item">
                <h3>Trios Technologies</h3>
                <p class="date">In-plant Training | Dec 2024</p>
                <ul>
                    <li>Gained foundational knowledge in web development, including HTML, CSS, and essential concepts of
                        website structure and design.</li>
                </ul>
            </div>
        </section>

        <section id="projects">
            <h2>Projects</h2>
            <div class="project-item">
                <h3>Schedit: Genetic Algorithm Timetable Scheduler</h3>
                <p class="tech-stack"><strong>Tech Stack:</strong> Python, Django, JavaScript, Genetic Algorithm, HTML,
                    CSS, Chrome Extension</p>
                <ul>
                    <li>Developed a full-stack web application that generates clash-free academic timetables using a
                        Genetic Algorithm.</li>
                    <li>Built a Django-based backend to parse and manage course data extracted via a custom Chrome
                        extension.</li>
                    <li>Implemented session-based state management to preserve user selections during navigation and
                        reset data when starting a new timetable.</li>
                    <li>Designed a responsive UI with features like dynamic course selection, credit-limit enforcement,
                        timetable regeneration, and export functionality.</li>
                </ul>
                <a href="https://github.com/CynthiaMehul/SchedIt-Timetable-Scheduler" class="link" target="_blank"
                    rel="noopener noreferrer">GitHub Repo</a>
            </div>
        </section>

        <section id="skills">
            <h2>Skills & Certifications</h2>
            <div class="skills-grid">
                <div class="skill-category">
                    <h3>Languages</h3>
                    <p>Python, Java, C, HTML, CSS, JavaScript</p>
                </div>
                <div class="skill-category">
                    <h3>Databases</h3>
                    <p>SQL</p>
                </div>
                <div class="skill-category">
                    <h3>Frameworks</h3>
                    <p>Django, React</p>
                </div>

            </div>
            
        </section>
        <div class="certifications">
                    <h3>Certifications</h3>
                    <ul class="cert-list">
                        <li>Getting Started With JavaScript, v3 – FrontEnd Masters</li>
                        <li>Interactivity with JavaScript – Coursera</li>
                        <li>Data Analytics with Python – NPTEL</li>
                        <li>Foundations and Core Concepts of PyTorch – Coursera</li>
                        <li>Google Data Analytics – Coursera</li>
                    </ul>
                </div>

        <section id="contact">
            <h2>Contact</h2>
            <p>I am always open to discussing new projects, creative ideas, or opportunities to be part of your visions.
            </p>
            <ul class="contact-links">
                <li><a href="mailto:kurapativishnu17@gmail.com">kurapativishnu17@gmail.com</a></li>
                <li>Phone: 6382857272</li>
                <li><a href="https://www.linkedin.com/in/kurapativishnu/" target="_blank"
                        rel="noopener noreferrer">LinkedIn</a></li>
                <li><a href="https://github.com/vishhnu-17" target="_blank" rel="noopener noreferrer">GitHub</a>
                </li>
                <li><a href="https://leetcode.com/u/kurapativishnu/" target="_blank"
                        rel="noopener noreferrer">LeetCode</a></li>
            </ul>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 Kurapati Vishnu Vardhan Reddy. All rights reserved.</p>
    </footer>
</body>

</html>
```
.css
```
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600&display=swap');

:root {
    --bg-color: #000000;
    --text-color: #ededed;
    --text-muted: #888888;
    --border-color: #222222;
    --accent-color: #ffffff;
    --hover-bg: #111111;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
    background-color: var(--bg-color);
    color: var(--text-color);
    line-height: 1.6;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
}

html {
    scroll-behavior: smooth;
}

a {
    color: var(--text-color);
    text-decoration: none;
    transition: all 0.3s ease;
}

a:hover {
    color: var(--text-muted);
}

h1, h2, h3, h4, h5, h6 {
    font-weight: 500;
    color: var(--accent-color);
    margin-bottom: 1rem;
    letter-spacing: -0.02em;
}

/* Header & Nav */
header {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    background-color: rgba(0, 0, 0, 0.8);
    backdrop-filter: blur(12px);
    border-bottom: 1px solid var(--border-color);
    z-index: 100;
    transition: transform 0.3s ease;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    max-width: 900px;
    margin: 0 auto;
    padding: 1.5rem 2rem;
}

.logo {
    font-size: 1.1rem;
    font-weight: 600;
    letter-spacing: 0.05em;
}

.nav-links {
    display: flex;
    list-style: none;
    gap: 2.5rem;
}

.nav-links a {
    font-size: 0.85rem;
    color: var(--text-muted);
}

.nav-links a:hover {
    color: var(--accent-color);
}

/* Main Layout */
main {
    max-width: 900px;
    margin: 0 auto;
    padding: 0 2rem;
    padding-top: 100px;
}

section {
    padding: 5rem 0;
    border-bottom: 1px solid var(--border-color);
}

section:last-of-type {
    border-bottom: none;
}

h2 {
    font-size: 1.75rem;
    margin-bottom: 2.5rem;
}

/* Hero Section */
#hero {
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 4rem;
    min-height: 85vh;
    border-bottom: none;
    padding-bottom: 0;
}

.hero-content {
    flex: 1.5;
}

.hero-image {
    flex: 1;
    display: flex;
    justify-content: center;
}

.hero-image img {
    width: 100%;
    max-width: 350px;
    object-fit: cover;
    border-radius: 8px;
    filter: grayscale(100%);
    transition: filter 0.5s ease, transform 0.5s ease;
}

.hero-image img:hover {
    filter: grayscale(0%);
    transform: scale(1.02);
}

.hero-content h1 {
    font-size: 3.5rem;
    line-height: 1.1;
    margin-bottom: 1.5rem;
    letter-spacing: -0.04em;
    font-weight: 600;
}

.subtitle {
    font-size: 1.2rem;
    color: var(--text-muted);
    margin-bottom: 3rem;
    max-width: 600px;
}

.hero-actions {
    display: flex;
    gap: 1rem;
}

.btn {
    display: inline-block;
    padding: 0.8rem 1.8rem;
    border: 1px solid var(--border-color);
    border-radius: 4px;
    font-weight: 500;
    font-size: 0.9rem;
    background-color: transparent;
    transition: all 0.3s ease;
}

.btn:hover {
    background-color: var(--accent-color);
    color: var(--bg-color);
    border-color: var(--accent-color);
}

/* About Section */
.about-section {
    display: flex;
    align-items: center;
    gap: 4rem;
}

.about-content {
    flex: 1.5;
}

.about-content p {
    font-size: 1rem;
    color: var(--text-muted);
    margin-bottom: 2.5rem;
}

.education-item h4 {
    margin-bottom: 0.25rem;
    font-size: 1.1rem;
}

.education-item p {
    font-size: 0.9rem;
    color: var(--text-muted);
    margin-bottom: 0;
}

.about-image {
    flex: 1;
    display: flex;
    justify-content: center;
}

.about-image img {
    width: 100%;
    max-width: 250px;
    aspect-ratio: 1 / 1;
    object-fit: cover;
    border-radius: 50%;
    border: 1px solid var(--border-color);
    filter: grayscale(100%);
    transition: filter 0.5s ease, transform 0.5s ease;
}

.about-image img:hover {
    filter: grayscale(20%);
    transform: scale(1.02);
}

/* Experience & Projects */
.experience-item, .project-item {
    margin-bottom: 3.5rem;
    padding: 2rem;
    border: 1px solid var(--border-color);
    border-radius: 8px;
    background-color: var(--hover-bg);
    transition: transform 0.3s ease, border-color 0.3s ease;
}

.experience-item:hover, .project-item:hover {
    transform: translateY(-2px);
    border-color: #444;
}

.experience-item:last-child, .project-item:last-child {
    margin-bottom: 0;
}

.experience-item h3, .project-item h3 {
    font-size: 1.25rem;
    margin-bottom: 0.25rem;
}

.date, .tech-stack {
    font-size: 0.85rem;
    color: var(--text-muted);
    margin-bottom: 1.5rem;
}

ul {
    padding-left: 1.2rem;
    color: var(--text-muted);
    font-size: 0.95rem;
}

ul li {
    margin-bottom: 0.75rem;
}

.link {
    display: inline-block;
    margin-top: 1.5rem;
    font-size: 0.9rem;
    color: var(--accent-color);
    border-bottom: 1px solid var(--border-color);
    padding-bottom: 2px;
}

.link:hover {
    color: var(--text-muted);
    border-bottom-color: var(--text-muted);
}

/* Skills */
.skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 2.5rem;
}

.skill-category h3 {
    font-size: 1.05rem;
    margin-bottom: 1rem;
    color: var(--accent-color);
}

.skill-category p {
    color: var(--text-muted);
    font-size: 0.9rem;
}

.cert-list {
    list-style: none;
    padding-left: 0;
}

.cert-list li {
    padding-left: 1rem;
    position: relative;
    font-size: 0.9rem;
    margin-bottom: 0.5rem;
}

.cert-list li::before {
    content: "•";
    position: absolute;
    left: 0;
    color: var(--text-muted);
}

/* Contact */
#contact p {
    color: var(--text-muted);
    margin-bottom: 2rem;
    max-width: 600px;
}

.contact-links {
    list-style: none;
    padding-left: 0;
    display: flex;
    flex-wrap: wrap;
    gap: 1.5rem;
}

.contact-links li {
    font-size: 0.9rem;
}

.contact-links a {
    color: var(--accent-color);
    border-bottom: 1px solid transparent;
}

.contact-links a:hover {
    border-bottom-color: var(--accent-color);
}

/* Footer */
footer {
    text-align: center;
    padding: 3rem 2rem;
    font-size: 0.85rem;
    color: var(--text-muted);
}

/* Responsive */
@media (max-width: 768px) {
    .nav-links {
        display: none;
    }
    #hero {
        flex-direction: column-reverse;
        justify-content: center;
        text-align: center;
        gap: 3rem;
        padding-top: 4rem;
    }
    
    .hero-actions {
        justify-content: center;
    }

    .hero-content h1 {
        font-size: 2.5rem;
    }
    
    .hero-image img {
        max-width: 250px;
    }
    
    .about-section {
        flex-direction: column-reverse;
        gap: 3rem;
        text-align: center;
    }
    
    .about-image img {
        max-width: 200px;
    }
    
    .experience-item, .project-item {
        padding: 1.5rem;
    }
}

.certifications {
    margin: 30px 0;
    padding-bottom: 30px;
    border-bottom: 1px solid var(--border-color);
}
```

## OUTPUT
<img width="1914" height="935" alt="image" src="https://github.com/user-attachments/assets/d47d6002-7b95-4f5c-b07d-20d0c4df990a" />
<img width="1913" height="939" alt="image" src="https://github.com/user-attachments/assets/e5c42372-db28-4ae5-a160-4e237261aeac" />
<img width="1559" height="932" alt="image" src="https://github.com/user-attachments/assets/03e0b561-5051-42c1-aa71-f92510dfa3a2" />


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
