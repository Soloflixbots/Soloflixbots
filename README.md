<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Soloflix Bots - GitHub Profile</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #0f0f0f, #1a1a2e, #16213e);
            color: #ffffff;
            line-height: 1.6;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        /* Header Styles */
        .header {
            text-align: center;
            padding: 50px 0;
            background: rgba(0, 0, 0, 0.7);
            border-radius: 20px;
            margin-bottom: 30px;
            border: 1px solid #00ff00;
        }

        .typing-animation {
            font-size: 2.5em;
            font-weight: bold;
            color: #00ff00;
            margin-bottom: 20px;
        }

        .profile-title {
            font-size: 3em;
            background: linear-gradient(45deg, #00ff00, #0080ff);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            margin-bottom: 10px;
        }

        /* Profile Section */
        .profile-section {
            display: flex;
            align-items: center;
            gap: 40px;
            margin-bottom: 40px;
            padding: 30px;
            background: rgba(0, 0, 0, 0.6);
            border-radius: 15px;
            border-left: 5px solid #00ff00;
        }

        .profile-image {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            border: 3px solid #00ff00;
            object-fit: cover;
        }

        .profile-content {
            flex: 1;
        }

        .section-title {
            font-size: 2em;
            color: #00ff00;
            margin-bottom: 20px;
            border-bottom: 2px solid #00ff00;
            padding-bottom: 10px;
        }

        /* Tech Stack */
        .tech-stack {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            margin-bottom: 40px;
        }

        .tech-card {
            background: rgba(0, 255, 0, 0.1);
            padding: 20px;
            border-radius: 10px;
            text-align: center;
            border: 1px solid #00ff00;
            transition: transform 0.3s ease;
        }

        .tech-card:hover {
            transform: translateY(-5px);
            background: rgba(0, 255, 0, 0.2);
        }

        /* Projects Section */
        .projects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 25px;
            margin-bottom: 40px;
        }

        .project-card {
            background: rgba(0, 0, 0, 0.7);
            padding: 25px;
            border-radius: 15px;
            border: 1px solid #0080ff;
            transition: all 0.3s ease;
        }

        .project-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0, 128, 255, 0.3);
        }

        .project-title {
            color: #0080ff;
            font-size: 1.5em;
            margin-bottom: 15px;
        }

        /* Stats Section */
        .stats-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-bottom: 40px;
        }

        .stat-card {
            background: rgba(255, 255, 255, 0.1);
            padding: 25px;
            border-radius: 10px;
            text-align: center;
            backdrop-filter: blur(10px);
        }

        /* Contact Section */
        .contact-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 30px;
        }

        .contact-btn {
            display: inline-block;
            padding: 12px 25px;
            background: linear-gradient(45deg, #00ff00, #0080ff);
            color: white;
            text-decoration: none;
            border-radius: 25px;
            font-weight: bold;
            transition: all 0.3s ease;
        }

        .contact-btn:hover {
            transform: scale(1.05);
            box-shadow: 0 5px 15px rgba(0, 128, 255, 0.4);
        }

        /* Footer */
        .footer {
            text-align: center;
            padding: 30px;
            margin-top: 50px;
            border-top: 1px solid #00ff00;
            background: rgba(0, 0, 0, 0.8);
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .profile-section {
                flex-direction: column;
                text-align: center;
            }
            
            .typing-animation {
                font-size: 1.8em;
            }
            
            .profile-title {
                font-size: 2em;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Header -->
        <header class="header">
            <div class="typing-animation">
                Welcome to My GitHub Profile
            </div>
            <h1 class="profile-title">Soloflix Bots</h1>
            <p>Python Developer & HTML Enthusiast</p>
        </header>

        <!-- Profile Section -->
        <section class="profile-section">
            <img src="https://graph.org/file/fdc47d088a48eb981c713.jpg" alt="Profile" class="profile-image">
            <div class="profile-content">
                <h2 class="section-title">About Me</h2>
                <p>I'm a passionate developer focused on Python and HTML. I love building practical applications and contributing to open source projects. Always eager to learn new technologies and take on challenging projects.</p>
            </div>
        </section>

        <!-- Tech Stack -->
        <section>
            <h2 class="section-title">Tech Stack</h2>
            <div class="tech-stack">
                <div class="tech-card">
                    <h3>Python</h3>
                    <p>Backend Development</p>
                </div>
                <div class="tech-card">
                    <h3>HTML</h3>
                    <p>Web Development</p>
                </div>
                <div class="tech-card">
                    <h3>Git</h3>
                    <p>Version Control</p>
                </div>
                <div class="tech-card">
                    <h3>VS Code</h3>
                    <p>Development Environment</p>
                </div>
            </div>
        </section>

        <!-- GitHub Stats -->
        <section>
            <h2 class="section-title">GitHub Statistics</h2>
            <div class="stats-container">
                <div class="stat-card">
                    <h3>Total Repositories</h3>
                    <p>15+</p>
                </div>
                <div class="stat-card">
                    <h3>Projects</h3>
                    <p>10+</p>
                </div>
                <div class="stat-card">
                    <h3>Contributions</h3>
                    <p>50+</p>
                </div>
            </div>
        </section>

        <!-- Projects -->
        <section>
            <h2 class="section-title">Featured Projects</h2>
            <div class="projects-grid">
                <div class="project-card">
                    <h3 class="project-title">File Store Bot</h3>
                    <p>A powerful file storage and management bot built with Python for efficient file handling.</p>
                </div>
                <div class="project-card">
                    <h3 class="project-title">Auto Rename Bot</h3>
                    <p>Automated file renaming bot that simplifies batch file processing tasks.</p>
                </div>
                <div class="project-card">
                    <h3 class="project-title">Links Share Bot</h3>
                    <p>Bot designed for easy sharing and management of links across platforms.</p>
                </div>
            </div>
        </section>

        <!-- Contact -->
        <section>
            <h2 class="section-title">Get In Touch</h2>
            <div class="contact-links">
                <a href="https://t.me/cosmic_freak" class="contact-btn">Telegram</a>
                <a href="mailto:soloflix.bot@gmail.com" class="contact-btn">Email</a>
            </div>
        </section>

        <!-- Footer -->
        <footer class="footer">
            <p>&copy; 2024 Soloflix Bots. All rights reserved.</p>
            <p>Thanks for visiting! Feel free to explore my repositories.</p>
        </footer>
    </div>

    <script>
        // Simple typing animation effect
        document.addEventListener('DOMContentLoaded', function() {
            const typingElement = document.querySelector('.typing-animation');
            const text = typingElement.textContent;
            typingElement.textContent = '';
            let i = 0;
            
            function typeWriter() {
                if (i < text.length) {
                    typingElement.textContent += text.charAt(i);
                    i++;
                    setTimeout(typeWriter, 100);
                }
            }
            
            typeWriter();
        });
    </script>
</body>
</html>
