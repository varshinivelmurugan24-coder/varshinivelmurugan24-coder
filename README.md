<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Varshini Velmurugan | Data Analyst</title>

    <link rel="stylesheet" href="style.css">
</head>

<body>

    <!-- Navigation -->
    <nav>
        <h2>Varshini</h2>

        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#experience">Experience</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>


    <!-- Home Section -->
    <section id="home" class="hero">

        <div class="hero-content">

            <p class="small-title">HELLO, I'M</p>

            <h1>Varshini Velmurugan</h1>

            <h2>Data Analyst</h2>

            <p>
                Python | SQL | Excel | Power BI
            </p>

            <p class="description">
                Final-year Computer Science and Engineering student
                passionate about data analytics, visualization,
                dashboards, and business insights.
            </p>

            <div class="buttons">
                <a href="#projects" class="btn">View Projects</a>
                <a href="#contact" class="btn secondary">Contact Me</a>
            </div>

        </div>

    </section>


    <!-- About Section -->
    <section id="about">

        <h2 class="section-title">About Me</h2>

        <div class="about-box">

            <p>
                I am a final-year B.E. Computer Science and Engineering
                student with hands-on experience in data cleaning,
                exploratory data analysis, dashboard development,
                KPI reporting, and data visualization.
            </p>

            <p>
                I have worked with Python, SQL, Microsoft Excel,
                and Power BI to analyze data and generate meaningful
                business insights.
            </p>

        </div>

    </section>


    <!-- Skills Section -->
    <section id="skills">

        <h2 class="section-title">Technical Skills</h2>

        <div class="skills-container">

            <div class="skill-card">
                <h3>Programming</h3>
                <p>Python</p>
            </div>

            <div class="skill-card">
                <h3>Database</h3>
                <p>SQL</p>
            </div>

            <div class="skill-card">
                <h3>Data Analysis</h3>
                <p>Excel</p>
            </div>

            <div class="skill-card">
                <h3>Visualization</h3>
                <p>Power BI</p>
            </div>

            <div class="skill-card">
                <h3>Analytics</h3>
                <p>EDA & Data Cleaning</p>
            </div>

            <div class="skill-card">
                <h3>Development</h3>
                <p>Git & VS Code</p>
            </div>

        </div>

    </section>


    <!-- Projects Section -->
    <section id="projects">

        <h2 class="section-title">Projects</h2>

        <div class="project-container">

            <!-- Project 1 -->
            <div class="project-card">

                <h3>IPL Tournament Analysis Dashboard</h3>

                <p class="tools">
                    Power BI | Excel
                </p>

                <p>
                    Interactive dashboard analyzing IPL match,
                    team, and player statistics to identify
                    performance trends.
                </p>

                <a href="#" class="project-link">
                    View Project →
                </a>

            </div>


            <!-- Project 2 -->
            <div class="project-card">

                <h3>Retail Sales Performance Dashboard</h3>

                <p class="tools">
                    Power BI | Excel
                </p>

                <p>
                    Retail dashboard tracking revenue, growth trends,
                    category performance, products, and regions.
                </p>

                <a href="#" class="project-link">
                    View Project →
                </a>

            </div>


            <!-- Project 3 -->
            <div class="project-card">

                <h3>SQL-Based Data Analysis</h3>

                <p class="tools">
                    SQL
                </p>

                <p>
                    SQL analysis using joins, aggregation,
                    filtering, and window functions to extract
                    useful business trends.
                </p>

                <a href="#" class="project-link">
                    View Project →
                </a>

            </div>

        </div>

    </section>


    <!-- Experience Section -->
    <section id="experience">

        <h2 class="section-title">Experience</h2>

        <div class="experience-box">

            <h3>Data Analyst Intern</h3>

            <h4>Unified Mentor</h4>

            <p class="date">
                March 2026 - June 2026
            </p>

            <ul>
                <li>Worked on the end-to-end data analytics workflow.</li>
                <li>Performed data cleaning and preprocessing.</li>
                <li>Created interactive dashboards and reports.</li>
                <li>Designed data visualizations for business insights.</li>
            </ul>

        </div>

    </section>


    <!-- Education -->
    <section id="education">

        <h2 class="section-title">Education</h2>

        <div class="education-box">

            <h3>B.E. Computer Engineering</h3>

            <p>
                JCT Institutions
            </p>

            <p>
                2023 - 2027
            </p>

        </div>

    </section>


    <!-- Contact -->
    <section id="contact">

        <h2 class="section-title">Contact Me</h2>

        <div class="contact-box">

            <p>
                <strong>Email:</strong>
                varshinivelmurugan24@gmail.com
            </p>

            <p>
                <strong>LinkedIn:</strong>
                <a href="https://linkedin.com/in/varshinivelmurugan"
                   target="_blank">
                    LinkedIn Profile
                </a>
            </p>

            <p>
                <strong>GitHub:</strong>
                <a href="https://github.com/varshinivelmurugan24-coder"
                   target="_blank">
                    GitHub Profile
                </a>
            </p>

        </div>

    </section>


    <!-- Footer -->
    <footer>

        <p>
            © 2026 Varshini Velmurugan | Data Analyst
        </p>

    </footer>


</body>
</html>

/* General */

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    font-family: Arial, sans-serif;
    background: #f5f7fb;
    color: #222;
    line-height: 1.6;
}


/* Navigation */

nav {
    position: sticky;
    top: 0;

    display: flex;
    justify-content: space-between;
    align-items: center;

    padding: 20px 8%;

    background: white;

    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.08);

    z-index: 1000;
}

nav h2 {
    font-size: 26px;
}

nav ul {
    display: flex;
    gap: 25px;
    list-style: none;
}

nav ul li a {
    text-decoration: none;
    color: #222;
    font-weight: 500;
}

nav ul li a:hover {
    color: #2563eb;
}


/* Hero */

.hero {
    min-height: 90vh;

    display: flex;
    justify-content: center;
    align-items: center;

    text-align: center;

    padding: 60px 20px;

    background: linear-gradient(
        135deg,
        #eef4ff,
        #ffffff
    );
}

.hero-content {
    max-width: 800px;
}

.small-title {
    font-size: 15px;
    letter-spacing: 3px;
    color: #2563eb;
    font-weight: bold;
}

.hero h1 {
    font-size: 55px;
    margin: 10px 0;
}

.hero h2 {
    font-size: 30px;
    color: #2563eb;
}

.hero .description {
    max-width: 650px;
    margin: 20px auto;
    color: #555;
}


/* Buttons */

.buttons {
    margin-top: 30px;
}

.btn {
    display: inline-block;

    padding: 12px 25px;
    margin: 5px;

    background: #2563eb;
    color: white;

    text-decoration: none;

    border-radius: 6px;

    font-weight: bold;
}

.btn:hover {
    background: #1d4ed8;
}

.btn.secondary {
    background: white;
    color: #2563eb;
    border: 2px solid #2563eb;
}


/* Sections */

section {
    padding: 80px 8%;
}

.section-title {
    text-align: center;
    font-size: 35px;
    margin-bottom: 40px;
}


/* About */

.about-box {
    max-width: 850px;
    margin: auto;

    background: white;

    padding: 30px;

    border-radius: 10px;

    box-shadow: 0 5px 20px rgba(0, 0, 0, 0.08);
}

.about-box p {
    margin-bottom: 15px;
}


/* Skills */

.skills-container {
    display: grid;

    grid-template-columns:
        repeat(auto-fit, minmax(200px, 1fr));

    gap: 20px;

    max-width: 1000px;

    margin: auto;
}

.skill-card {
    background: white;

    padding: 25px;

    text-align: center;

    border-radius: 10px;

    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.07);

    transition: 0.3s;
}

.skill-card:hover {
    transform: translateY(-5px);
}

.skill-card h3 {
    margin-bottom: 10px;
}


/* Projects */

.project-container {
    display: grid;

    grid-template-columns:
        repeat(auto-fit, minmax(280px, 1fr));

    gap: 25px;
}

.project-card {
    background: white;

    padding: 30px;

    border-radius: 10px;

    box-shadow: 0 5px 20px rgba(0, 0, 0, 0.08);

    transition: 0.3s;
}

.project-card:hover {
    transform: translateY(-7px);
}

.project-card h3 {
    margin-bottom: 10px;
}

.tools {
    color: #2563eb;
    font-weight: bold;
    margin-bottom: 15px;
}

.project-link {
    display: inline-block;

    margin-top: 20px;

    color: #2563eb;

    text-decoration: none;

    font-weight: bold;
}


/* Experience */

.experience-box,
.education-box,
.contact-box {
    max-width: 800px;

    margin: auto;

    padding: 30px;

    background: white;

    border-radius: 10px;

    box-shadow: 0 5px 20px rgba(0, 0, 0, 0.08);
}

.experience-box h3 {
    font-size: 25px;
}

.experience-box h4 {
    color: #2563eb;
}

.date {
    color: #777;
    margin-bottom: 15px;
}

.experience-box ul {
    padding-left: 20px;
}


/* Education */

.education-box {
    text-align: center;
}


/* Contact */

.contact-box p {
    margin: 12px 0;
}

.contact-box a {
    color: #2563eb;
    text-decoration: none;
}


/* Footer */

footer {
    text-align: center;

    padding: 25px;

    background: #111827;

    color: white;
}


/* Mobile */

@media (max-width: 768px) {

    nav {
        flex-direction: column;
        gap: 15px;
    }

    nav ul {
        flex-wrap: wrap;
        justify-content: center;
        gap: 15px;
    }

    .hero h1 {
        font-size: 40px;
    }

    .hero h2 {
        font-size: 25px;
    }

    section {
        padding: 60px 5%;
    }

    .section-title {
        font-size: 30px;
    }
}
