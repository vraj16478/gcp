<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    
    <style>
        body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: brown;
}

header {
    background: #515151;
    color: #fff9f9;
    padding: 10px 0;
    text-align: center;
}

header h1 {
    margin: 0;
}
nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: #b66c6c;
    text-decoration: none;
}
nav ul li a:hover{
    color:darkred;
    
}
h4{
    color: chocolate;
    font-family:'Times New Roman', Times, serif;
}

section {
    padding: 20px;
    margin: 20px;
    background: #d7c4c4;
    border-radius: 30px;
}
    
        .v2{
            background-image: url(vraj.jpeg);height: 100px;width: 100px;
        background-repeat: no-repeat;background-size: 100px 100px;
        border: 2px solid crimson;
        border-radius: 50px;
        }

        .v2:hover{
            transition: all;
            transition-duration:100ms;
         transform: scale(1.2);
         cursor:crosshair;
        }
    </style>
    
</head>
<body>
    <header>
        <h1>My Portfolio</h1>
        <nav id="v">
            <ul>
                <li><a href="#about">About Me</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>About Me</h2>
       <div class="v2"> </div>
       <h4><b> <p> Hey!! I'm <u> vraj sutariya(vk)</u>, a btech-cse student with a <u> passion for photography</u>. i love to listen <u>music</u>. i like to read <u>books(novels) </u>also.</p></b></h4>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <div class="project-gallery">
            <div class="project">
                <a href="index.html"><h1> first intro</h1></a>
                <h3><b>my first web</b></h3>
                <i><p> I have added some of my info and tried new tags.</p></i>             
        </div>
            <div class="project">
                    <a href="form.html"><h1>my second web </h1></a>
                <h3>form demostration</h3>
                <i><p>i have created Simple form page with background Image. </p></i>
            </div>
            <div class="project">
                <a href="prac.html"><h1>practice web </h1></a>
                <h3>completed </h3>
               <i> <p>i have created a web page with all the tags i have learned.</p></i>
            </div>
           
        </div>
    </section>

    <section id="skills">
        <h2>Skills</h2>
        <ul class="skills-list">
            <li>HTML</li>
            <li>CSS</li>
            <li>photography</li>
        

        </ul>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <form action="submit-form.php" method="POST">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required><br><br>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required><br><br>

            <label for="message">Message:</label>
            <textarea id="message" name="message" rows="4" required></textarea><br>

            <button type="submit">Send Message</button>
        </form>
        <div class="social-links">
            <h3>Connect with me:</h3>
            <a href="https://www.linkedin.com/in/vraj-sutariya-893710311?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app" target="_blank">linkedin</a>||
            <a href="https://github.com/vraj16478" target="_blank">GitHub</a>||
            <a href="https://x.com/vraj_16" target="_blank">Twitter</a>
        </div>
    </section>

    <footer>
       <b> <p>&copy; 2025 vraj sutariya. All rights reserved.</p></b>
    </footer>
</body>
</html>
