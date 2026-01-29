<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Personal Portfolio</title>
    
    <link href="https://fonts.googleapis.com/css2?family=Fredoka:wght@300;400;600&display=swap" rel="stylesheet">

    <style>
        /* --- CSS VARIABLES (Easy to change colors here!) --- */
        :root {
            --primary-color: #FF6B6B; /* Coral Red */
            --secondary-color: #4ECDC4; /* Teal */
            --accent-color: #FFE66D; /* Yellow */
            --dark-text: #2F2F2F;
            --light-text: #ffffff;
            --bg-color: #F7FFF7;
        }

        /* --- GLOBAL STYLES --- */
        * {
            box-sizing: border-box; /* Makes sizing elements easier */
        }

        body {
            font-family: 'Fredoka', sans-serif; /* Using our fun font */
            margin: 0;
            padding: 0;
            background-color: var(--bg-color);
            color: var(--dark-text);
            scroll-behavior: smooth; /* This makes the page scroll smoothly! */
        }

        /* --- NAVIGATION BAR --- */
        nav {
            position: fixed; /* Sticks to the top */
            top: 20px;
            left: 50%;
            transform: translateX(-50%);
            background-color: var(--dark-text);
            padding: 15px 30px;
            border-radius: 50px; /* Fully rounded edges */
            z-index: 1000;
            box-shadow: 0 10px 20px rgba(0,0,0,0.1);
            display: flex;
            gap: 20px;
        }

        nav a {
            color: var(--light-text);
            text-decoration: none;
            font-weight: 600;
            padding: 10px 20px;
            border-radius: 30px;
            transition: background 0.3s;
        }

        nav a:hover {
            background-color: var(--primary-color);
            transform: scale(1.1); /* Slightly grows on hover */
        }

        /* --- SECTIONS (The "Pages") --- */
        section {
            min-height: 100vh; /* Each section takes up full screen height */
            padding: 100px 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            text-align: center;
        }

        h1 {
            font-size: 3rem;
            color: var(--primary-color);
            margin-bottom: 10px;
        }

        h2 {
            font-size: 2.5rem;
            color: var(--secondary-color);
            margin-bottom: 30px;
        }

        p {
            font-size: 1.2rem;
            line-height: 1.6;
            max-width: 700px;
        }

        /* --- ABOUT ME SECTION STYLES --- */
        .profile-pic {
            width: 200px;
            height: 200px;
            background-color: var(--accent-color);
            border-radius: 50%; /* Makes it a circle */
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 4rem;
            margin-bottom: 20px;
            border: 5px solid var(--primary-color);
        }

        /* --- PROJECTS SECTION STYLES --- */
        .project-container {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }

        .card {
            background: white;
            border-radius: 20px;
            padding: 20px;
            width: 300px;
            box-shadow: 0 10px 15px rgba(0,0,0,0.1);
            border-bottom: 5px solid var(--secondary-color);
            transition: transform 0.3s;
        }

        .card:hover {
            transform: translateY(-10px); /* Floats up on hover */
        }

        /* --- RESUME SECTION STYLES --- */
        .resume-block {
            background: white;
            padding: 30px;
            border-radius: 30px;
            text-align: left;
            width: 100%;
            max-width: 600px;
            box-shadow: 0 10px 15px rgba(0,0,0,0.05);
        }

        .resume-item {
            margin-bottom: 20px;
            border-bottom: 2px dashed #ddd;
            padding-bottom: 10px;
        }

        /* --- CONTACT FORM STYLES --- */
        form {
            background: white;
            padding: 40px;
            border-radius: 30px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
            display: flex;
            flex-direction: column;
            gap: 15px;
            width: 100%;
            max-width: 400px;
        }

        input, textarea {
            padding: 15px;
            border-radius: 15px;
            border: 2px solid #ddd;
            font-family: 'Fredoka', sans-serif;
            font-size: 1rem;
        }

        button {
            background-color: var(--primary-color);
            color: white;
            border: none;
            padding: 15px;
            border-radius: 15px;
            font-size: 1.2rem;
            cursor: pointer;
            font-family: 'Fredoka', sans-serif;
        }

        button:hover {
            background-color: var(--secondary-color);
        }

    </style>
</head>
<body>

    <nav>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#resume">Resume</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="about">
        <div class="profile-pic">👋</div>
        <h1>Hello, I'm Prithvie!</h1>
        <p>
            In the future, I aspire to be a software engineer at a Fortune 500 company. I plan to achieve this goal by doing my own personal projects on the side while taking advanced computer science courses. I plan to major in computer science in college and participate in many internships that will help catch the eye of a recruiter from a Fortune 500 company. I chose this career because I have always been surrounded by computer scientists my whole life since both of my parents are computer scientists. The final reason I chose this career is because I have always found computer science to be a really interesting topic to dive deep into during my free time.
	
Some personalities and characteristics that I possess that relate to this career are relentlessness and punctuality. This is shown in school because I like to spend time on complex topics in math and science even if I do not understand it at first. I also think I am very punctual because I am always on time to classes and family events, I try to always stay prepared. For example, in school, I do not procrastinate on assignments and I always turn it in on time and by the deadline. One of my extracurricular activities is tennis and I think it shows how relentless I can be when I want to achieve something. I have been playing tennis for around a decade now so I always make sure I try my best point after point and I never give up until the very last second of the match. 

One of my major achievements from high school was being on the Emerald High School varsity tennis team that went on to win the BVAL championships last year. My whole life I have always seen tennis as a solo, one person sport but the varsity team showed me how important each person is to a team. I learned about the cooperation and sacrifice each and every person on the team needed to make for us to win in the end. If one person on the team was slacking off, we would all take the hit since our performance as a team is the only thing that matters in high school tennis. This made me realize how difficult and important it is to be able to excel while working in a team since I will rarely be working on my own later in my life when I enter the workforce. 

In conclusion, I am a relentless and punctual future software engineer that will succeed in whatever endeavors I choose to embark on. I thank you for reading this far and I hope you enjoy the rest of my site. 

        </p>
        <br>
        <p><strong>My Hobbies:</strong> 🎮 Gaming, 🏀 Basketball, and 🍕 Eating Pizza.</p>
    </section>

    <section id="projects" style="background-color: #f0f7f4;">
        <h2>My Projects</h2>
        <div class="project-container">
            <div class="card">
                <h3>🚀 Baez Coding Squad </h3>
                <p>https://drive.google.com/file/d/1DDdAgJsfKmvMuXZxKyFtRLv6BoDWZnP8/view?usp=sharing</p>
            </div>
            <div class="card">
                <h3>📸 Photography Club</h3>
                <p>https://docs.google.com/videos/d/1gzsAQqMv2lGFOnfmUnunAWWH5vcg1NGSbrxt971C1F0/play?pli=1#scene=id.p</p>
            </div>
            
            </div>
        </div>
    </section>

    <section id="resume">
        <h2>My Resume</h2>
        <div class="resume-block">
            <div class="resume-item">
                <h3>🎓 Education</h3>
                <p><strong>Sunnydale High School</strong> | 2022 - Present</p>
                <p>Focusing on Math, Science, and Computer Science principles.</p>
            </div>
            
            <div class="resume-item">
                <h3>🏆 Skills</h3>
                <p>• HTML & CSS (Learning!)</p>
                <p>• Teamwork & Leadership</p>
                <p>• Microsoft Office / Google Docs</p>
            </div>

            <div class="resume-item">
                <h3>🌟 Activities</h3>
                <p><strong>Robotics Club Member</strong> - Helped build chassis for competition robot.</p>
            </div>
        </div>
    </section>

    <section id="contact" style="background-color: var(--accent-color);">
        <h2>Get In Touch</h2>
        <p>Want to work on a project together? Send me a message!</p>
        
        <form>
            <input type="text" placeholder="Your Name">
            <input type="email" placeholder="Your Email">
            <textarea rows="5" placeholder="Write your message here..."></textarea>
            <button type="button">Send Message ✉️</button>
        </form>
    </section>

</body>
</html>
