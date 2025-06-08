  
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Jane Doe</h1>
            <p>Web Developer & Designer</p>
        </div>
    </header>

    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <section id="about" class="section">
        <div class="container">
            <h2>About Me</h2>
            <div class="about-content">
                <img src="https://via.placeholder.com/300" alt="Profile Picture" class="profile-img">
                <div class="about-text">
                    <p>Hello! I'm a passionate web developer with 5 years of experience creating beautiful, functional websites. I specialize in front-end development with a focus on user experience.</p>
                    <p>When I'm not coding, you can find me hiking, reading sci-fi novels, or experimenting with new recipes in the kitchen.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="projects" class="section">
        <div class="container">
            <h2>My Projects</h2>
            <div class="projects-grid">
                <div class="project-card">
                    <img src="https://via.placeholder.com/400x250" alt="Project 1">
                    <h3>E-commerce Website</h3>
                    <p>A fully responsive online store with shopping cart functionality.</p>
                    <a href="#" class="btn">View Project</a>
                </div>
                <div class="project-card">
                    <img src="https://via.placeholder.com/400x250" alt="Project 2">
                    <h3>Task Management App</h3>
                    <p>Web application for organizing and tracking daily tasks.</p>
                    <a href="#" class="btn">View Project</a>
                </div>
                <div class="project-card">
                    <img src="https://via.placeholder.com/400x250" alt="Project 3">
                    <h3>Portfolio Website</h3>
                    <p>Custom portfolio design for a freelance photographer.</p>
                    <a href="#" class="btn">View Project</a>
                </div>
            </div>
        </div>
    </section>

    <section id="skills" class="section">
        <div class="container">
            <h2>Skills</h2>
            <div class="skills-container">
                <div class="skill-category">
                    <h3>Front-end</h3>
                    <ul>
                        <li>HTML5 & CSS3</li>
                        <li>JavaScript (ES6+)</li>
                        <li>React.js</li>
                        <li>Vue.js</li>
                        <li>Responsive Design</li>
                    </ul>
                </div>
                <div class="skill-category">
                    <h3>Back-end</h3>
                    <ul>
                        <li>Node.js</li>
                        <li>Express</li>
                        <li>Python</li>
                        <li>PHP</li>
                    </ul>
                </div>
                <div class="skill-category">
                    <h3>Tools</h3>
                    <ul>
                        <li>Git & GitHub</li>
                        <li>Webpack</li>
                        <li>Figma</li>
                        <li>Adobe Creative Suite</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="section">
        <div class="container">
            <h2>Get In Touch</h2>
            <div class="contact-container">
                <form class="contact-form">
                    <input type="text" placeholder="Your Name" required>
                    <input type="email" placeholder="Your Email" required>
                    <textarea placeholder="Your Message" required></textarea>
                    <button type="submit" class="btn">Send Message</button>
                </form>
                <div class="contact-info">
                    <p><i class="fas fa-envelope"></i> jane.doe@example.com</p>
                    <p><i class="fas fa-phone"></i> (123) 456-7890</p>
                    <div class="social-links">
                        <a href="#"><i class="fab fa-github"></i></a>
                        <a href="#"><i class="fab fa-linkedin"></i></a>
                        <a href="#"><i class="fab fa-twitter"></i></a>
                        <a href="#"><i class="fab fa-instagram"></i></a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2023 Jane Doe. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
