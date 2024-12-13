<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        :root {
            --bg-color: #121212;
            --card-color: #1e1e1e;
            --text-color: #e0e0e0;
            --highlight-color: #00bcd4;
            --border-color: #333;
            --hover-color: #0097a7;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Poppins', sans-serif;
            background-color: var(--bg-color);
            color: var(--text-color);
            line-height: 1.6;
            margin: 0;
        }

        header {
            background: var(--card-color);
            padding: 20px 0;
            text-align: center;
            font-size: 2.5rem;
            font-weight: bold;
            color: var(--highlight-color);
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.5);
        }

        main {
            padding: 20px;
            display: flex;
            flex-direction: column;
            gap: 30px;
            max-width: 1100px;
            margin: 30px auto;
        }

        section {
            background: var(--card-color);
            border: 1px solid var(--border-color);
            border-radius: 8px;
            padding: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.4);
        }

        section h2 {
            color: var(--highlight-color);
            margin-bottom: 10px;
            font-size: 1.8rem;
        }

        .about p {
            text-align: center;
        }

        .about img {
            display: block;
            width: 150px;
            height: 150px;
            border-radius: 50%;
            margin: 20px auto;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.5);
            transition: cubic-bezier(0.47, 0, 0.745, 0.715);
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 20px;
        }

        .grid-item {
            text-align: center;
            background: var(--highlight-color);
            color: var(--bg-color);
            padding: 15px;
            border-radius: 8px;
            font-weight: bold;
        }

        .grid-item img {
            width: 50px;
            height: 50px;
            margin-bottom: 10px;
        }

        .grid-item:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.6);
        }

        .contact a {
            color: var(--highlight-color);
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s;
        }

        .contact a:hover {
            color: var(--hover-color);
        }

        footer {
            text-align: center;
            padding: 10px 0;
            background: var(--card-color);
            color: var(--text-color);
            border-top: 1px solid var(--border-color);
        }
    </style>
</head>
<body>
    <header>
        Student Portfolio
    </header>
    <main>
        <section class="about">
            <h2>About Me</h2>
            <p>Hi there! I'm Tremonti and a student from Computer Science, and my curiosity for technology has sparked an exciting journey. I'm eager to learn programming, problem-solving, and system design while tackling real-world challenges and collaborating with amazing people. Thanks for stopping by my portfolio, and I can't wait to share this journey with you!</p>

            <img src="/Users/marvi/Pictures/Images/Pics.jpg" alt="Profile Picture">

        </section>

        <section class="skills">
            <h2>Skills</h2>
            <p>As a college student and a beginner in learning HTML, CSS, and C++, I've gained experience in building and styling websites while developing efficient code. Each challenge has sharpened my skills, making the journey deeply rewarding and exciting.</p>
            
            <div class="grid">
                <div class="grid-item">
                    <img src="/Users/marvi/Downloads/Folder ni Monay/IT Finals/HTML.png" alt="HTML Logo">
                    <center> HTML </center>
                </div>
                <div class="grid-item">
                    <img src="/Users/marvi/Downloads/Folder ni Monay/IT Finals/CSS.png" alt="CSS Logo">
                    <center> CSS </center>
                </div>
                <div class="grid-item">
                    <img src="/Users/marvi/Downloads/Folder ni Monay/IT Finals/C++.png" alt="C++ Logo">
                    <center> C++ </center>
                </div>
            </div>
        </section>

        <section class="projects">
            <h2>Projects</h2>
            <p>These are the projects I did last time, they were interesting and confusing but the result was smooth and successful. You just have to follow the directions and explore more.</p>
            <div class="grid">
                <div class="grid-item">CRUD Operations</div> 
                <div class="grid-item">Interactive Portfolio Webpage</div>
                <div class="grid-item">Macro-Enabled Excel Request Slip</div>
            </div>
        </section>

        <section class="contact">
            <h2>Contact Me</h2>
            <p>Feel free to reach out to me via email for any inquiries, collaborations, or just to connect. You can also find me on social media for professional networking and. I'm always excited to meet new people and explore interesting opportunities together.</p>
            <p>Email: <a href="https://mail.google.com/mail/u/1/#inbox">tremonticcc@gmail.com</a> </p>
            <p>Social Media: <a href="https://www.facebook.com/montszsz">Monts</a></p>
            <p>Contacts: 09770925214 </p> 
        </section>
    </main>
    <footer>
        &copy; 2024 Batangas State University. All Rights Reserved.
    </footer>
</body>
</html> 
