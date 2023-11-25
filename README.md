# CodSofttask2webdevelopment
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Portfolio</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            background-color: #f4f4f4;
            color: #333;
        }

        header {
            background-color: #007BFF;
            color: white;
            text-align: center;
            padding: 1em;
        }

        header h1 {
            margin: 0;
            font-size: 2em;
        }

        header p {
            font-size: 1.2em;
            margin-top: 0.5em;
        }

        .about {
            padding: 2em;
        }

        .about img {
            max-width: 100%;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .bio {
            margin-top: 1em;
        }

        .skills,
        .projects,
        .resume,
        .contact {
            padding: 2em;
            background-color: white;
            margin: 2em 0;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .projects img {
            max-width: 100%;
            border-radius: 8px;
            margin-bottom: 1em;
        }

        footer {
            text-align: center;
            padding: 1em;
            background-color: #007BFF;
            color: white;
        }
    </style>
</head>

<body>

    <header>
        <h1>Your Name</h1>
        <p>Web Developer | Designer | Creative Thinker</p>
    </header>

    <section class="about">
        <img src="your-image.jpg" alt="Your Name">
        <div class="bio">
            <h2>About Me</h2>
            <p>Write a short bio highlighting your skills and experience.</p>
        </div>
    </section>

    <section class="skills">
        <h2>Skills</h2>
        <ul>
            <li>HTML</li>
            <li>CSS</li>
            <li>JavaScript</li>
            <!-- Add more skills as needed -->
        </ul>
    </section>

    <section class="projects">
        <h2>Projects</h2>
        <div class="project">
            <img src="project1.jpg" alt="Project 1">
            <h3>Project Title 1</h3>
            <p>Project description goes here.</p>
        </div>
        <div class="project">
            <img src="project2.jpg" alt="Project 2">
            <h3>Project Title 2</h3>
            <p>Project description goes here.</p>
        </div>
        <!-- Add more projects as needed -->
    </section>

    <section class="resume">
        <h2>Resume</h2>
        <p>Download my <a href="your-resume.pdf" target="_blank">resume (PDF)</a>.</p>
    </section>

    <section class="contact">
        <h2>Contact</h2>
        <p>Email: your.email@example.com</p>
        <p>Phone: (123) 456-7890</p>
    </section>

    <footer>
        <p>&copy; 2023 Your Name. All rights reserved.</p>
    </footer>

</body>

</html>
