# index.html<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Muzamil Hussain | Full Stack Developer</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        :root {
            --primary: #3498db;
            --dark: #1a1a1a;
            --light: #f4f4f4;
            --grey: #888;
        }

        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; }
        body { background-color: var(--dark); color: white; line-height: 1.6; }

        /* Navigation */
        nav { padding: 20px 10%; display: flex; justify-content: space-between; align-items: center; background: rgba(26,26,26,0.95); position: sticky; top: 0; z-index: 1000; }
        .logo { font-size: 1.5rem; font-weight: bold; color: var(--primary); }
        .nav-links a { color: white; text-decoration: none; margin-left: 20px; font-size: 0.9rem; transition: 0.3s; }
        .nav-links a:hover { color: var(--primary); }

        /* Hero Section */
        header { height: 80vh; display: flex; flex-direction: column; justify-content: center; align-items: center; text-align: center; padding: 0 10%; }
        header h1 { font-size: 3.5rem; margin-bottom: 10px; }
        header p { color: var(--grey); font-size: 1.2rem; max-width: 600px; }
        .cta-btn { margin-top: 30px; padding: 12px 30px; background: var(--primary); color: white; text-decoration: none; border-radius: 5px; font-weight: bold; transition: 0.3s; }
        .cta-btn:hover { background: #2980b9; transform: translateY(-3px); }

        /* Section Styling */
        section { padding: 80px 10%; }
        h2 { font-size: 2rem; margin-bottom: 40px; border-left: 5px solid var(--primary); padding-left: 15px; }

        /* Skills Grid */
        .skills-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(150px, 1fr)); gap: 20px; }
        .skill-card { background: #252525; padding: 20px; border-radius: 10px; text-align: center; transition: 0.3s; border: 1px solid transparent; }
        .skill-card:hover { border-color: var(--primary); transform: translateY(-5px); }
        .skill-card i { font-size: 2rem; color: var(--primary); margin-bottom: 10px; }

        /* Projects */
        .project-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 30px; }
        .project-card { background: #252525; border-radius: 10px; overflow: hidden; transition: 0.3s; }
        .project-card:hover { transform: scale(1.02); }
        .project-info { padding: 20px; }
        .project-info h3 { margin-bottom: 10px; color: var(--primary); }
        .project-info p { font-size: 0.9rem; color: #ccc; margin-bottom: 15px; }
        .tags { display: flex; gap: 10px; flex-wrap: wrap; }
        .tag { font-size: 0.7rem; background: #333; padding: 5px 10px; border-radius: 3px; color: var(--primary); }

        /* Contact */
        .contact-info { display: flex; gap: 30px; flex-wrap: wrap; justify-content: center; }
        .contact-item { text-decoration: none; color: white; display: flex; align-items: center; gap: 10px; font-size: 1.1rem; }
        .contact-item:hover { color: var(--primary); }

        footer { text-align: center; padding: 40px; color: var(--grey); font-size: 0.8rem; border-top: 1px solid #333; }

        @media (max-width: 768px) {
            header h1 { font-size: 2.5rem; }
            nav { flex-direction: column; gap: 15px; }
        }
    </style>
</head>
<body>

    <nav>
        <div class="logo">Muhammad Muzammil Hussain</div>
        <div class="nav-links">
            <a href="#about">About</a>
            <a href="#skills">Skills</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </div>
    </nav>

    <header>
        <h1>Muhammad Muzamil Hussain</h1>
        <p>Full Stack Web Developer specialized in building scalable applications with Python, Django, and React.</p>
        <a href="#projects" class="cta-btn">View My Work</a>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <p style="max-width: 800px; color: #bbb;">
            Passionate Software Engineering student at NFC-IET Multan (Exp. 2025). I focus on clean code and seamless frontend-backend integration. My goal is to build user-friendly web applications that solve real-world problems.
        </p>
    </section>

    <section id="skills" style="background: #111;">
        <h2>Technical Expertise</h2>
        <div class="skills-grid">
            <div class="skill-card"><i class="fab fa-react"></i><p>React</p></div>
            <div class="skill-card"><i class="fab fa-python"></i><p>Python / Django</p></div>
            <div class="skill-card"><i class="fab fa-js"></i><p>JavaScript</p></div>
            <div class="skill-card"><i class="fas fa-database"></i><p>SQLite</p></div>
            <div class="skill-card"><i class="fab fa-git-alt"></i><p>Git / GitHub</p></div>
            <div class="skill-card"><i class="fas fa-code"></i><p>REST APIs</p></div>
        </div>
    </section>

    <section id="projects">
        <h2>Key Projects</h2>
        <div class="project-grid">
            <div class="project-card">
                <div class="project-info">
                    <h3>Course Management System</h3>
                    <p>A full-stack CRUD application for students and teachers. Features robust database relationships and RESTful APIs.</p>
                    <div class="tags">
                        <span class="tag">Django</span>
                        <span class="tag">React</span>
                        <span class="tag">SQLite</span>
                    </div>
                </div>
            </div>
            <div class="project-card">
                <div class="project-info">
                    <h3>Wembley Downs Clone</h3>
                    <p>A complete website clone focusing on high-fidelity UI and seamless frontend-to-backend data flow.</p>
                    <div class="tags">
                        <span class="tag">Django</span>
                        <span class="tag">React</span>
                        <span class="tag">CSS Grid</span>
                    </div>
                </div>
            </div>
            <div class="project-card">
                <div class="project-info">
                    <h3>E-commerce Frontend</h3>
                    <p>Designed a responsive product catalog with smooth navigation and user-friendly filtering interfaces.</p>
                    <div class="tags">
                        <span class="tag">React</span>
                        <span class="tag">JavaScript</span>
                        <span class="tag">UI/UX</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Get In Touch</h2>
        <div class="contact-info">
            <a href="mailto:raomuzamil480@gmail.com" class="contact-item"><i class="fas fa-envelope"></i> raomuzamil480@gmail.com</a>
            <a href="tel:03196531093" class="contact-item"><i class="fas fa-phone"></i> 03196531093</a>
            <a href="https://www.linkedin.com/in/rao-muzamil-52a733281/" class="contact-item"><i class="fab fa-linkedin"></i> LinkedIn</a>
            <a href="https://github.com/raomuzamil480" class="contact-item"><i class="fab fa-github"></i> GitHub</a>
        </div>
    </section>

    <footer>
        &copy; 2026 Muhammad Muzamil Hussain | Multan, Pakistan
    </footer>

    <script>
        // Simple Smooth Scroll
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>
