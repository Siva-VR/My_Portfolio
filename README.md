<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My_portfolio</title>
</head>

<body>
    <!DOCTYPE html>
    <html lang="en">

    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Professional Portfolio</title>
        <style>
            * {
                margin: 0;
                padding: 0;
                box-sizing: border-box;
            }

            body {
                font-family: 'Inter', sans-serif;
                line-height: 1.6;
                color: #333;
                background-color: #f5f5f5;
            }

            /* Header Styles */
            header {
                background-color: #fff;
                box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
                padding: 1rem 2rem;
                position: fixed;
                width: 100%;
                top: 0;
                z-index: 1000;
                display: flex;
                justify-content: space-between;
                align-items: center;
            }

            .logo {
                font-size: 1.5rem;
                font-weight: bold;
                color: #2c3e50;
            }

            nav ul {
                display: flex;
                list-style: none;
                gap: 2rem;
            }

            nav a {
                text-decoration: none;
                color: #2c3e50;
                font-weight: 500;
                transition: color 0.3s ease;
            }

            nav a:hover {
                color: #3498db;
            }

            /* Layout Container */
            .container {
                display: grid;
                grid-template-columns: 250px 1fr 250px;
                gap: 2rem;
                max-width: 1400px;
                margin: 80px auto 0;
                padding: 2rem;
                min-height: calc(100vh - 160px);
            }

            /* Sidebar Styles */
            .sidebar-left,
            .sidebar-right {
                background: #fff;
                padding: 1.5rem;
                border-radius: 8px;
                box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            }

            .profile {
                text-align: center;
                margin-bottom: 2rem;
            }

            .profile-img {
                width: 150px;
                height: 150px;
                border-radius: 50%;
                margin-bottom: 1rem;
            }

            .skills ul {
                list-style: none;
                margin-top: 1rem;
            }

            .skills li {
                background: #f0f2f5;
                padding: 0.5rem 1rem;
                margin-bottom: 0.5rem;
                border-radius: 4px;
            }

            /* Main Content Styles */
            .main-content {
                background: #fff;
                padding: 2rem;
                border-radius: 8px;
                box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            }

            .work-grid {
                display: grid;
                grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
                gap: 1.5rem;
                margin-top: 2rem;
            }

            .work-item {
                background: #f0f2f5;
                padding: 2rem;
                border-radius: 8px;
                text-align: center;
                transition: transform 0.3s ease;
            }

            .work-item:hover {
                transform: translateY(-5px);
            }

            /* Contact Info Styles */
            .contact-info,
            .social-links {
                margin-bottom: 2rem;
            }

            .social-links a {
                display: block;
                color: #2c3e50;
                text-decoration: none;
                margin: 0.5rem 0;
                transition: color 0.3s ease;
            }

            .social-links a:hover {
                color: #3498db;
            }

            /* Footer Styles */
            footer {
                background: #2c3e50;
                color: #fff;
                text-align: center;
                padding: 1.5rem;
                margin-top: 2rem;
            }

            /* Responsive Design */
            @media (max-width: 1024px) {
                .container {
                    grid-template-columns: 200px 1fr;
                }

                .sidebar-right {
                    display: none;
                }
            }

            @media (max-width: 768px) {
                .container {
                    grid-template-columns: 1fr;
                }

                .sidebar-left {
                    display: none;
                }

                header {
                    padding: 1rem;
                }

                nav ul {
                    gap: 1rem;
                }
            }
        </style>
    </head>

    <body>
        <header>
            <div class="logo">Shiva</div>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#portfolio">Portfolio</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </header>

        <div class="container">
            <aside class="sidebar-left">
                <div class="profile">
                    <img src="img1.png" alt="Profile" class="profile-img">
                    <h2>Shiva</h2>
                    <p>Web Developer</p>
                </div>
                <div class="skills">
                    <h3>Skills</h3>
                    <ul>
                        <li>HTML5</li>
                        <li>CSS3</li>
                        <li>JavaScript</li>
                        <li>React</li>
                    </ul>
                </div>
            </aside>

            <main class="main-content">
                <section id="home">
                    <h1>Welcome to My Portfolio</h1>
                    <!-- <p>I create beautiful and functional websites that deliver results.</p> -->
                </section>

                <section id="featured-work">
                    <h2>Featured Work</h2>
                    <div class="work-grid">
                        <div class="work-item">Project 1</div>
                        <div class="work-item">Project 2</div>
                        <div class="work-item">Project 3</div>
                    </div>
                </section>
            </main>

            <aside class="sidebar-right">
                <div class="contact-info">
                    <h3>Contact Info</h3>
                    <p>Email: shiva@example.com</p>
                    <p>Location: Madhapur, HYD</p>
                </div>
                <div class="social-links">
                    <h3>Social Media</h3>
                    <a href="#">LinkedIn</a>
                    <a href="#">GitHub</a>
                    <a href="#">Twitter</a>
                </div>
            </aside>
        </div>

        <footer>
            <p>&copy; 2024 Shiva Portfolio. All rights reserved.</p>
        </footer>
    </body>

    </html>
</body>

</html>
