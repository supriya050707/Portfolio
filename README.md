# Ex01 Portfolio
## Date:30/10/2026

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
HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Supriya S J - Engineering Student and Web Developer Portfolio">
    <title>Supriya S J | Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header class="navbar">
        <a href="#home" class="logo">Supriya<span>.</span></a>

        <nav>
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#skills">Skills</a>
            <a href="#education">Education</a>
            <a href="#projects">Projects</a>
            <a href="#experience">Experience</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <main>
        <section id="home" class="hero section">
            <div class="hero-content">
                <p class="eyebrow">WELCOME TO MY PORTFOLIO</p>
                <h1>Hi, I'm <span>Supriya S J</span></h1>
                <h2>Engineering Student & Web Developer</h2>
                <p>
                    I enjoy creating websites, learning new technologies,
                    and developing practical solutions through programming.
                </p>

                <div class="hero-buttons">
                    <a href="#projects" class="btn primary">View My Projects</a>
                    <a href="#contact" class="btn secondary">Contact Me</a>
                </div>
            </div>

            <div class="hero-card">
                <div class="profile-circle">
                    <img src="profile.jpg" alt="Photo of Supriya"
                         onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">
                    <div class="photo-fallback">SS</div>
                </div>
                <h3>Creative Thinker</h3>
                <p>Learning · Building · Improving</p>
                <div class="hero-tags">
                    <span>Web Development</span>
                    <span>Python</span>
                    <span>Problem Solving</span>
                </div>
            </div>
        </section>

        <section id="about" class="section">
            <div class="section-heading">
                <p class="eyebrow">GET TO KNOW ME</p>
                <h2>About <span>Me</span></h2>
            </div>

            <div class="about-card">
                <p>
                    I am an engineering student interested in web development,
                    programming, and emerging technologies. I enjoy exploring
                    new tools and applying my knowledge to projects.
                </p>
                <p>
                    My goal is to improve my technical skills, gain practical
                    experience, and build useful, user-friendly applications.
                </p>
            </div>
        </section>

        <section id="skills" class="section">
            <div class="section-heading">
                <p class="eyebrow">WHAT I WORK WITH</p>
                <h2>My <span>Skills</span></h2>
            </div>

            <div class="skills-grid">
                <article class="skill-card">
                    <div class="skill-icon">🌐</div>
                    <h3>Web Development</h3>
                    <p>HTML, CSS, JavaScript, Bootstrap</p>
                </article>

                <article class="skill-card">
                    <div class="skill-icon">🐍</div>
                    <h3>Programming</h3>
                    <p>Python, C, basic problem solving</p>
                </article>

                <article class="skill-card">
                    <div class="skill-icon">🗄️</div>
                    <h3>Database</h3>
                    <p>SQL and database fundamentals</p>
                </article>

                <article class="skill-card">
                    <div class="skill-icon">🎨</div>
                    <h3>Design & Tools</h3>
                    <p>Figma, Git, GitHub, VS Code</p>
                </article>
            </div>
        </section>

        <section id="education" class="section">
            <div class="section-heading">
                <p class="eyebrow">MY LEARNING JOURNEY</p>
                <h2>My <span>Education</span></h2>
            </div>

            <div class="timeline">
                <article class="timeline-card">
                    <span class="timeline-dot"></span>
                    <p class="timeline-date">Currently Pursuing</p>
                    <h3>Bachelor's Degree in Engineering</h3>
                    <p>Saveetha Engineering College</p>
                    <p>Building knowledge in software development and technology.</p>
                </article>

                <article class="timeline-card">
                    <span class="timeline-dot"></span>
                    <p class="timeline-date">Completed in 2024</p>
                    <h3>Higher Secondary Education</h3>
                    <p>Completed Class 12</p>
                </article>
            </div>
        </section>

        <section id="projects" class="section">
            <div class="section-heading">
                <p class="eyebrow">WHAT I'VE BUILT</p>
                <h2>My <span>Projects</span></h2>
            </div>

            <div class="projects-grid">
                <article class="project-card">
                    <div class="project-number">01</div>
                    <h3>Zayra E-Commerce Website</h3>
                    <p>
                        An e-commerce website concept with product browsing,
                        shopping cart, and customer-focused pages.
                    </p>
                    <div class="project-tags">
                        <span>HTML</span><span>CSS</span>
                        <span>JavaScript</span><span>Django</span>
                    </div>
                </article>

                <article class="project-card">
                    <div class="project-number">02</div>
                    <h3>LuminaZ</h3>
                    <p>
                        A project concept focused on identifying dark data
                        and recommending ways to reduce storage energy use
                        and associated carbon emissions.
                    </p>
                    <div class="project-tags">
                        <span>Python</span><span>Data Analysis</span>
                        <span>Dashboard</span>
                    </div>
                </article>

                <article class="project-card">
                    <div class="project-number">03</div>
                    <h3>Personal Portfolio</h3>
                    <p>
                        A responsive portfolio website to present my skills,
                        education, projects, and contact information.
                    </p>
                    <div class="project-tags">
                        <span>HTML</span><span>CSS</span>
                        <span>JavaScript</span>
                    </div>
                </article>
            </div>
        </section>

        <section id="experience" class="section">
            <div class="section-heading">
                <p class="eyebrow">PRACTICAL EXPERIENCE</p>
                <h2>Internship <span>Experience</span></h2>
            </div>

            <article class="experience-card">
                <p class="timeline-date">July 2025</p>
                <h3>Web Development Intern</h3>
                <h4>Velandev Solutions Pvt. Ltd.</h4>
                <p>
                    Worked on the Zeyra e-commerce web application prototype.
                    Contributed to frontend development, supported product,
                    order, payment, and vendor modules, and used Figma for
                    interface design and GitHub for version control.
                </p>
                <div class="project-tags">
                    <span>HTML</span><span>CSS</span>
                    <span>JavaScript</span><span>Figma</span><span>GitHub</span>
                </div>
            </article>
        </section>

        <section id="certifications" class="section">
            <div class="section-heading">
                <p class="eyebrow">CONTINUOUS LEARNING</p>
                <h2>My <span>Certifications</span></h2>
            </div>

            <article class="certificate-card">
                <div class="certificate-icon">🏅</div>
                <div>
                    <h3>Cybersecurity for Everyone</h3>
                    <p>University of Maryland · Coursera</p>
                </div>
            </article>
        </section>

        <section id="contact" class="section">
            <div class="section-heading">
                <p class="eyebrow">LET'S CONNECT</p>
                <h2>Contact <span>Me</span></h2>
            </div>

            <div class="contact-card">
                <p>
                    Feel free to contact me for opportunities,
                    collaborations, or professional connections.
                </p>

                <a href="mailto:supriyasenthilj577@gmail.com" class="contact-link">
                    ✉ supriyasenthilj577@gmail.com
                </a>

                <a href="https://github.com/supriya050707"
                   target="_blank" rel="noopener noreferrer"
                   class="contact-link">
                    GitHub: github.com/supriya050707
                </a>

                <a href="https://www.linkedin.com/"
                   target="_blank" rel="noopener noreferrer"
                   class="contact-link">
                    LinkedIn Profile
                </a>
            </div>
        </section>
    </main>

    <footer>
        <p>© <span id="year"></span> Supriya S J. All rights reserved.</p>
        <a href="#home">Back to top ↑</a>
    </footer>

    <script src="script.js"></script>
</body>
</html>
```
CSS 

```
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap');

:root {
    --navy: #09214a;
    --deep-navy: #021837;
    --cyan: #55d6e8;
    --white: #ffffff;
    --muted: #b8c7dc;
    --card: #102b50;
    --border: rgba(85, 214, 232, 0.2);
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    scroll-behavior: smooth;
}

body {
    font-family: 'Inter', sans-serif;
    background: var(--deep-navy);
    color: var(--white);
    line-height: 1.7;
}

a {
    color: inherit;
    text-decoration: none;
}

.navbar {
    position: sticky;
    top: 0;
    z-index: 100;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 18px 8%;
    background: rgba(2, 24, 55, 0.96);
    border-bottom: 1px solid var(--border);
    backdrop-filter: blur(12px);
}

.logo {
    font-size: 1.7rem;
    font-weight: 800;
}

.logo span,
h1 span,
h2 span {
    color: var(--cyan);
}

nav {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
}

nav a {
    color: var(--muted);
    font-size: 0.9rem;
    transition: color 0.3s;
}

nav a:hover,
footer a:hover {
    color: var(--cyan);
}

.section {
    padding: 90px 8%;
    scroll-margin-top: 75px;
}

.hero {
    min-height: 85vh;
    display: grid;
    grid-template-columns: 1.4fr 1fr;
    align-items: center;
    gap: 55px;
    background:
        radial-gradient(circle at 10% 20%, #123361 0, transparent 40%),
        var(--deep-navy);
}

.eyebrow {
    color: var(--cyan);
    font-size: 0.8rem;
    font-weight: 700;
    letter-spacing: 2px;
    margin-bottom: 12px;
}

.hero h1 {
    font-size: clamp(2.4rem, 5vw, 4.4rem);
    line-height: 1.2;
    margin-bottom: 15px;
}

.hero h2 {
    font-size: clamp(1.2rem, 2.5vw, 1.8rem);
    color: var(--muted);
    margin-bottom: 20px;
}

.hero-content > p:not(.eyebrow) {
    color: var(--muted);
    max-width: 600px;
}

.hero-buttons {
    display: flex;
    flex-wrap: wrap;
    gap: 15px;
    margin-top: 30px;
}

.btn {
    display: inline-block;
    padding: 12px 22px;
    border-radius: 8px;
    font-weight: 700;
    transition: transform 0.3s, background 0.3s;
}

.btn:hover {
    transform: translateY(-3px);
}

.primary {
    background: var(--cyan);
    color: var(--deep-navy);
}

.secondary {
    border: 1px solid var(--cyan);
    color: var(--cyan);
}

.hero-card,
.about-card,
.skill-card,
.timeline-card,
.project-card,
.experience-card,
.certificate-card,
.contact-card {
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: 18px;
    padding: 28px;
}

.hero-card {
    text-align: center;
    box-shadow: 0 20px 60px rgba(0, 0, 0, 0.2);
}

.profile-circle {
    position: relative;
    width: 160px;
    height: 160px;
    margin: 0 auto 22px;
    border-radius: 50%;
    overflow: hidden;
    border: 5px solid var(--cyan);
    box-shadow: 0 0 25px rgba(85, 214, 232, 0.3);
    background: var(--navy);
}

.profile-circle img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    object-position: center;
    display: block;
}

.photo-fallback {
    display: none;
    position: absolute;
    inset: 0;
    align-items: center;
    justify-content: center;
    font-size: 2.5rem;
    font-weight: 800;
    color: var(--cyan);
}

.hero-card h3 {
    font-size: 1.4rem;
}

.hero-card > p,
.about-card p,
.skill-card p,
.timeline-card p,
.project-card p,
.experience-card p,
.contact-card p,
.certificate-card p {
    color: var(--muted);
}

.hero-tags,
.project-tags {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 8px;
    margin-top: 20px;
}

.hero-tags span,
.project-tags span {
    font-size: 0.78rem;
    padding: 5px 10px;
    border-radius: 20px;
    background: rgba(85, 214, 232, 0.1);
    color: var(--cyan);
    border: 1px solid var(--border);
}

.section-heading {
    text-align: center;
    margin-bottom: 40px;
}

.section-heading h2 {
    font-size: clamp(2rem, 4vw, 3rem);
}

.about-card {
    max-width: 850px;
    margin: auto;
}

.about-card p + p {
    margin-top: 15px;
}

.skills-grid,
.projects-grid {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 22px;
}

.skill-card,
.project-card {
    transition: transform 0.3s, border-color 0.3s;
}

.skill-card:hover,
.project-card:hover {
    transform: translateY(-6px);
    border-color: var(--cyan);
}

.skill-icon {
    font-size: 2rem;
    margin-bottom: 12px;
}

.skill-card h3,
.project-card h3,
.timeline-card h3,
.experience-card h3,
.certificate-card h3 {
    margin-bottom: 8px;
}

.timeline {
    max-width: 800px;
    margin: auto;
    display: grid;
    gap: 22px;
}

.timeline-card {
    position: relative;
    border-left: 4px solid var(--cyan);
}

.timeline-date {
    color: var(--cyan) !important;
    font-size: 0.85rem;
    font-weight: 700;
    margin-bottom: 8px;
}

.project-number {
    color: var(--cyan);
    font-size: 1rem;
    font-weight: 800;
    margin-bottom: 15px;
}

.project-tags {
    justify-content: flex-start;
}

.experience-card {
    max-width: 850px;
    margin: auto;
}

.experience-card h4 {
    color: var(--cyan);
    margin-bottom: 15px;
}

.certificate-card {
    max-width: 650px;
    margin: auto;
    display: flex;
    align-items: center;
    gap: 20px;
}

.certificate-icon {
    font-size: 2.5rem;
}

.contact-card {
    max-width: 650px;
    margin: auto;
    text-align: center;
}

.contact-link {
    display: block;
    margin-top: 18px;
    color: var(--cyan);
    overflow-wrap: anywhere;
}

.contact-link:hover {
    text-decoration: underline;
}

footer {
    padding: 25px 8%;
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 12px;
    color: var(--muted);
    border-top: 1px solid var(--border);
}

footer a {
    color: var(--cyan);
}

@media (max-width: 900px) {
    .navbar {
        flex-direction: column;
        gap: 12px;
    }

    nav {
        justify-content: center;
        gap: 12px 18px;
    }

    .hero {
        grid-template-columns: 1fr;
        text-align: center;
    }

    .hero-content > p:not(.eyebrow) {
        margin: auto;
    }

    .hero-buttons {
        justify-content: center;
    }

    .hero-card {
        max-width: 420px;
        width: 100%;
        margin: auto;
    }
}

@media (max-width: 560px) {
    .section {
        padding: 65px 6%;
    }

    .navbar {
        padding: 16px 5%;
    }

    nav a {
        font-size: 0.8rem;
    }

    .skills-grid,
    .projects-grid {
        grid-template-columns: 1fr;
    }

    .hero-card,
    .about-card,
    .skill-card,
    .timeline-card,
    .project-card,
    .experience-card,
    .certificate-card,
    .contact-card {
        padding: 22px;
    }

    .certificate-card {
        align-items: flex-start;
    }

    footer {
        flex-direction: column;
        text-align: center;
    }
}
```
## OUTPUT

<img width="1907" height="1027" alt="image" src="https://github.com/user-attachments/assets/26359e52-b0b6-4c7a-a637-953f24db05b1" />

<img width="1897" height="1021" alt="image" src="https://github.com/user-attachments/assets/40a8cec3-d8ae-4b87-b2c8-9e8e17bb83ae" />

<img width="1896" height="1016" alt="image" src="https://github.com/user-attachments/assets/b21e9342-f829-411c-ae0f-756e0bd70f68" />

<img width="1915" height="1026" alt="image" src="https://github.com/user-attachments/assets/463694ac-ba60-4b64-bcc2-e0dea17a6cc5" />

<img width="1895" height="1012" alt="image" src="https://github.com/user-attachments/assets/33af715c-8e2a-4288-9412-77c8f4607837" />

<img width="1712" height="757" alt="image" src="https://github.com/user-attachments/assets/fc5995f4-0286-48ed-8b3c-dac1641b9c37" />

<img width="1917" height="1018" alt="image" src="https://github.com/user-attachments/assets/2d98734d-c28e-49aa-8c35-33b7fd5da1a3" />



## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
