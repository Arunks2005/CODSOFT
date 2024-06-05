<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Arun K Sathish - Portfolio</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" integrity="sha512-..." crossorigin="anonymous" />
    <style>
        /* General Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: "Helvetica Neue","Helvetica" ;
}

body {
    background-color: #f8f8f8;
    color: #333;
    line-height: 1.6;
}

/* Header Styles */
header {
    background: linear-gradient(to right, darkgray, darkcyan);
    color: #fff;
    padding: 20px;
    text-align: center;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    position: relative;
}

header h1 {
    font-size: 2.5rem;
    margin-bottom: 10px;
    color: #000;
    font-family: "Ink Free" Uppercase;
}

header p {
    font-size: 1.2rem;
}

nav {
    display: flex;
    justify-content: center;
    background-color: rgba(255, 255, 255, 0.1);
    padding: 10px;
    border-radius: 5px;
    margin-top: 20px;
}

nav a {
    color: #fff;
    text-decoration: none;
    padding: 10px 20px;
    transition: background-color 0.3s ease;
    border-radius: 5px;
}

nav a:hover {
    background-color: rgba(255, 255, 255, 0.2);
}

/* Main Styles */
main {
    max-width: 1200px;
    margin: 40px auto;
    padding: 30px;
    background-color: #fff;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    border-radius: 5px;
}

section {
    margin-bottom: 40px;
}

h1 {
    font-size: 2rem;
    color: darkcyan;
    margin-bottom: 20px;
    text-transform: uppercase;
    letter-spacing: 2px;
}

#about img {
    max-width: 300px;
    border-radius: 50px;
    margin-right: 30px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
}

#about p {
    text-align: justify;
    line-height: 1.8;
}

/* Skills Section */
#skills ul {
    list-style: none;
    display: flex;
    flex-wrap: wrap;
}

#skills li {
    background-color: #f1f1f1;
    color: darkcyan;
    padding: 10px 20px;
    margin: 10px;
    border-radius: 20px;
    font-weight: bold;
    transition: background-color 0.3s ease;
}

#skills li:hover {
    background-color: darkcyan;
    color: #fff;
}

/* Projects Section */
.portfolio {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 30px;
}

.portfolio-item {
    background-color: #f4f4f4;
    padding: 20px;
    border-radius: 5px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.portfolio-item img {
    max-width: 100%;
    height: auto;
    border-radius: 5px;
    margin-bottom: 10px;
}

.portfolio-item h3 {
    font-size: 1.5rem;
    color: darkcyan;
    margin-bottom: 10px;
}

.portfolio-item p {
    margin-bottom: 10px;
}

.portfolio-item a {
    color: #e67e22;
    text-decoration: none;
    transition: color 0.3s ease;
}

.portfolio-item a:hover {
    color: #d35400;
}

.portfolio-item:hover {
    transform: translateY(-5px);
    box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
}

/* Contact Section */
#contact ul {
    list-style: none;
}

#contact li {
    margin-bottom: 10px;
    display: flex;
    align-items: center;
}

#contact i {
    color: darkcyan;
    font-size: 2rem;
    margin-right: 10px;
}

#contact a {
    color: #333;
    text-decoration: none;
    transition: color 0.3s ease;
}

/* Footer Styles */
footer {
    background-color: darkcyan;
    color: #fff;
    text-align: center;
    padding: 20px;
    margin-top: 40px;
    box-shadow: 0 -2px 5px rgba(0, 0, 0, 0.1);
}

footer p {
    margin-bottom: 10px;
}

footer a {
    color: #fff;
    text-decoration: none;
    margin: 0 10px;
    transition: color 0.3s ease;
}

footer a:hover {
    color: #f1f1f1;
}

.social-icons i {
    font-size: 2rem;
}s

/* Responsive Styles */
@media (max-width: 768px) {
    header h1 {
        font-size: 2rem;
    }

    header p {
        font-size: 1rem;
    }

    #about {
        flex-direction: column;
        align-items: center;
    }

    #about img {
        margin-right: 0;
        margin-bottom: 20px;
    }

    .portfolio {
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    }
}

@media (max-width: 480px) {
    header h1 {
        font-size: 1.8rem;
    }

    header p {
        font-size: 0.9rem;
    }

    nav {
        flex-direction: column;
    }

    nav a {
        margin-bottom: 5px;
    }

    .portfolio {
        grid-template-columns: 1fr;
    }
}
    </style>
</head>
<body>
    <header>
        <h1>Arun K Sathish</h1>
        <p>Full Stack Developer</p>
        <nav>
            <a href="#about">About</a>
            <a href="#skills">Skills</a>
            <a href="#portfolio">Portfolio</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <main>
        <section id="about">
            <p> <h1>About Me</h1> </p>
            <p> <img src="arun.jpg" alt="Arun K Sathish"> </p>
            <h3><p>Hello! I'm Arun K Sathish, currently pursuing 3rd year BCA (Honours/Honours with Research) at Christ University, Hosur Road, Bangalore. I specialize in Full Stack Development. Welcome to my portfolio website where you can view my latest projects and accomplishments.
            With years of experience at the College, I have honed my skills and developed a keen eye for detail. My passion for a Full Stack Developer drives me to continuously learn and grow, staying up-to-date with the latest trends and technologies.</p> </h3>
        </section>

        <section id="skills">
            <h1>Skills</h1>
            <ul>
                <li>HTML</li>
                <li>CSS</li>
                <li>JavaScript</li>
                <li>React</li>
                <li>Node.js</li>
                <li>Express</li>
                <li>MongoDB</li>
                <!-- Add more skills as needed -->
            </ul>
        </section>

        <section id="portfolio">
            <h2>Portfolio</h2>
            <div class="portfolio">
                <div class="portfolio-item">
                    <img src="blosom.png" alt="Project 1">
                    <h3>BLOSSOMS' 24</h3>
                    <p>The following web page as a set events organised by the college management team, so that college students can showcase their talents by performing in various events they are interested in.</p>
                    <p><a href="file:///C:/Users/HP/Desktop/CODSOFT/Landing%20page/landing.html#home">Blossoms' 24</a></p>
                </div>
                <div class="portfolio-item">
                    <img src="path/to/image2.jpg" alt="Project 2">
                    <h3>Project Title 2</h3>
                    <p>Short description of the project, highlighting its key features, technologies used, and the impact it had.</p>
                </div>
                <div class="portfolio-item">
                    <img src="path/to/image3.jpg" alt="Project 3">
                    <h3>Project Title 3</h3>
                    <p>Short description of the project, highlighting its key features, technologies used, and the impact it had.</p>
                </div>
                <!-- Add more portfolio items as needed -->
            </div>
        </section>

        <section id="contact">
            <h2>Contact</h2>
            <p>I'm always excited to discuss new opportunities and collaborate on projects. Feel free to reach out to me through the following methods:</p>
            <ul>
                <li><i class="fas fa-envelope"></i> <a href="mailto:your.email@example.com">arunsats.005@gmail.com</a></li>
                <li><i class="fab fa-linkedin"></i> <a href="https://www.linkedin.com/in/arun-k-sathish-3370642a6">linkedin.com/in/yourprofile</a></li>
                <li><i class="fab fa-twitter"></i> <a href="https://twitter.com/yourprofile">@yourprofile</a></li>
            </ul>
        </section>
    </main>

    <footer>
        <h2> <p>&copy; 2024 Arun K Sathish. All rights reserved.</p> </h2>
        <div class="social-icons">
            <a href="https://www.facebook.com/arun.ks.39142072"><i class="fab fa-facebook"></i></a>
            <a href="https://www.instagram.com/_iamnot_arun._/"><i class="fab fa-instagram"></i></a>
            <a href="https://github.com/Arunks2005"><i class="fab fa-github"></i></a>
    </footer>
</body>
</html>
