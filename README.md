<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ravindra Reddy Tadipatri - Personal Webpage</title>
    <style>
        body {
            font-family: 'Helvetica Neue', Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            color: #333;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #FFD700;
            color: black;
        }
        section {
            padding: 20px;
            max-width: 800px;
            margin: auto;
            background-color: white;
            border: 1px solid #ddd;
            margin-top: 20px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        h2 {
            color: #4CAF50;
        }
        .button-container {
            text-align: center;
            margin: 20px 0;
        }
        .button-container a {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            margin: 5px;
        }
        .button-container a:hover {
            background-color: #FFD700;
            color: black;
        }
        .hidden {
            display: none;
        }
        .image-container {
            text-align: center;
            margin-bottom: 20px;
        }
        .image-container img {
            max-width: 100%;
            height: auto;
            border: 1px solid #aaa;
        }
    </style>
    <script>
        function showSection(sectionId) {
            const sections = document.querySelectorAll('section');
            sections.forEach(section => {
                section.classList.add('hidden');
            });
            document.getElementById(sectionId).classList.remove('hidden');
        }
    </script>
</head>
<body>

<header>
    <h1>Ravindra Reddy Tadipatri</h1>
    <p>Engineering Student</p>
</header>

<nav>
    <a href="javascript:showSection('about')">About Me</a>
    <a href="javascript:showSection('portfolio')">Portfolio</a>
    <a href="javascript:showSection('contact')">Contact</a>
    <a href="javascript:showSection('hobbies')">Hobbies</a>
    <a href="javascript:showSection('skills')">Skills</a>
    <a href="javascript:showSection('activities')">Activities</a>
    <a href="javascript:showSection('accomplishments')">Accomplishments</a>
    <a href="javascript:showSection('certifications')">Certifications</a>
</nav>

<section id="about">
    <h2>About Me</h2>
    <div class="image-container">
        <img src="https://drive.google.com/uc?id=1M7mN3dnZqdpwR5SXrafqC6wmjU5l_3I9" alt="Ravindra Reddy Tadipatri">
    </div>
    <p>Motivated and enthusiastic individual with a strong academic background and a passion for learning and growth. Possesses excellent communication skills and a keen interest in discussing ideas and receiving constructive feedback. Seeking a role where I can leverage my educational foundation while being mentored and nurtured to further develop my skills and advance my career.</p>
    <h3>Summary</h3>
    <p>Persuing 3rd Year in Computer Science And Information Technology Department at Marri Laxman Reddy Inst of Technology.</p>
    <p>CGPA : 7.00 | 2025</p>
</section>

<section id="portfolio" class="hidden">
    <h2>Portfolio</h2>
    <div class="image-placeholder">Image Placeholder</div>
    <p>Here are some of the projects I have worked on:</p>
    <ul>
        <li>Project 1: Description of project 1.</li>
        <li>Project 2: Description of project 2.</li>
        <li>Project 3: Description of project 3.</li>
        <!-- Add more projects as needed -->
    </ul>
</section>

<section id="contact" class="hidden">
    <h2>Contact</h2>
    <div class="image-placeholder">Image Placeholder</div>
    <p>You can reach me at:</p>
    <p>Phone: 7997555414</p>
    <p>Email: <a href="mailto:ravindraoptional@gmail.com">ravindraoptional@gmail.com</a></p>
</section>

<section id="hobbies" class="hidden">
    <h2>Hobbies and Interests</h2>
    <div class="image-placeholder">Image Placeholder</div>
    <ul>
        <li>Reading Books</li>
        <li>Listening to music</li>
        <li>Writing stories</li>
        <li>Editing</li>
    </ul>
</section>

<section id="skills" class="hidden">
    <h2>Skills</h2>
    <div class="image-placeholder">Image Placeholder</div>
    <ul>
        <li>Python Programmer</li>
        <li>Graphic Designing</li>
        <li>Beginner Photoshop</li>
        <li>Video Editing</li>
        <li>Writing stories</li>
    </ul>
</section>

<section id="activities" class="hidden">
    <h2>Activities and Honors</h2>
    <div class="image-placeholder">Image Placeholder</div>
    <p>Volunteer:</p>
    <ul>
        <li>Various NGO Events, Seva Bharathi, RUN FOR A GIRL CHILD</li>
        <li>Participated in various events organized by NGOs, contributing to community initiatives and social causes.</li>
    </ul>
    <p>Leadership Experience:</p>
    <ul>
        <li>College Club 64: Organized and led numerous events as a member of College Club 64, fostering teamwork and collaboration among members.</li>
    </ul>
    <p>Content Creation:</p>
    <ul>
        <li>YouTube Content Creator: Created engaging and informative content on ongoing issues and creating awareness on YouTube, building a subscriber base and engaging with viewers to promote discussion and learning.</li>
    </ul>
</section>

<section id="accomplishments" class="hidden">
    <h2>Accomplishments</h2>
    <div class="image-placeholder">Image Placeholder</div>
    <ul>
        <li>Best Startup Idea Award - Illuminate 2023 Event, conducted by E-Cell IIT Bombay</li>
        <li>Winner - E fest conducted by college management (E-fest is a great event where one can learn how to sell a product)</li>
    </ul>
</section>

<section id="certifications" class="hidden">
    <h2>Certifications</h2>
    <div class="image-placeholder">Image Placeholder</div>
    <ul>
        <li>Python Programmer</li>
        <li>Graphic Designing</li>
        <li>Beginner Photoshop</li>
        <li>Video Editing</li>
        <li>Writing stories</li>
        <li>C certificate from Hacker Rank</li>
        <li>C Essentials from Cisco</li>
        <li>Python Essentials from Cisco</li>
        <li>Data Management From TCS ion</li>
    </ul>
</section>

<footer>
    <p>&copy; 2024 Ravindra Reddy Tadipatri. All rights reserved.</p>
</footer>

</body>
</html>
