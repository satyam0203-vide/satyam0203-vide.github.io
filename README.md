# satyam_portfolio<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="final.css">
</head>
<body>

    <header>
        <div class="container">
            <h1>My Portfolio</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="#about.html">About</a></li>
                    <li><a href="skills.html">Skills</a></li>
                    <li><a href="projects.html">Projects</a></li>
                    <li><a href="contact.html">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section class="hero">
        <h2>Welcome to My Portfolio</h2>
        <p>A showcase of my skills, achievements, and projects.</p>
    </section>

    <section class="about">
        <h2>About Me</h2>
        <img src="satyam.png" alt="My Photo">
        <p><strong>Name:</strong>Satyam Anil Phalke</p>
        <p><strong>Email:</strong> satyamphalke2006@gmail.com</p>
        <p><strong>Mobile:</strong> +918459080237</p>
    </section>
    
    <section class="education">
        <h2>Education</h2>
        <ul>
            <li><strong>HSC</strong> - Y.C.I.S., Satara (2023-2024)</li>
            <li><strong>SSC</strong> – Shri Chh. A.B.V. Sonawadi-Gajawadi, Satara (2021-2022)</li>
        </ul>
    
        <div class="certificate-links">
            <a href="#certificate1">SSC</a>
            <a href="#certificate2">HSC</a>
        </div>
    </section>
    
    <!-- Fullscreen Certificate Viewer -->
    <div id="certificate1" class="fullscreen">
        <a href="#" class="close">×</a>
        <img src="satyam-10.png" alt="10th Certificate">
    </div>
    
    <div id="certificate2" class="fullscreen">
        <a href="#" class="close">×</a>
        <img src="Anushka-12.jpeg" alt="12th Certificate">
    </div>
    

    <section class="skills">
        <h2>Technical Skills</h2>
        <ul>
            <li><img src="html.png" alt="HTML"> HTML</li>
            <li><img src="css.png" alt="CSS"> CSS</li>
            <li><img src="java.png" alt="JavaScript"> JavaScript</li>
			<li><img src="c.png" alt="C Programming"> C Programming </li>
        </ul>
    </section>
    
    <section class="hobbies">
        <h2>Hobbies</h2>
        <p>Drawing, Coding, Gaming, Travelling</p>
    </section>

    <section class="projects">
        <h2>My Projects</h2>
        <ul>
            <li><strong>Portfolio Website</strong> – A responsive personal portfolio</li>
            <li><strong>Online Quiz App</strong> – A JavaScript-based quiz application</li>
        </ul>
    </section>
    
    <section class="certifications">
        <h2>Certifications</h2>
        <p>Certified in Web Development</p>
        <a href="images/certificate.pdf" target="_blank">View Certificate</a>
    </section>

    <section class="contact">
        <h2>Contact Me</h2>
        <form>
            <label>Name:</label>
            <input type="text" required>
            <label>Email:</label>
            <input type="email" required>
            <label>Message:</label>
            <textarea required></textarea>
            <button type="submit">Send</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 My Portfolio | Designed by Me</p>
    </footer>

</body>
</html>
