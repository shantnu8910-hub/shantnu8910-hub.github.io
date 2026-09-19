# shantnu8910-hub.github.io
My personal website, built at GDG Jammu
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shantnu Deval - Resume</title>
    <style>
        /* BASE STYLES & MOBILE FIRST */
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }
        
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            background-color: #f4f7f6;
            color: #222222;
            line-height: 1.6;
            padding: 15px;
        }
        
        .container {
            max-width: 800px;
            margin: 0 auto;
        }
        
        h1, h2, h3 {
            color: #111111;
        }
        
        a {
            color: #0056b3;
            text-decoration: none;
            font-weight: 500;
        }
        
        a:hover {
            text-decoration: underline;
        }
        
        /* HEADER SECTION STYLES */
        header {
            background-color: #ffffff;
            text-align: center;
            padding: 40px 20px;
            border-radius: 8px;
            margin-bottom: 20px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.05);
        }
        
        header h1 {
            font-size: 2.2rem;
            margin-bottom: 5px;
        }
        
        header p {
            font-size: 1.1rem;
            color: #555555;
        }
        
        /* CONTENT SECTION STYLES */
        section {
            background-color: #ffffff;
            padding: 25px 20px;
            border-radius: 8px;
            margin-bottom: 20px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.05);
        }
        
        .section-title {
            font-size: 1.5rem;
            border-bottom: 2px solid #eeeeee;
            padding-bottom: 10px;
            margin-bottom: 20px;
        }
        
        ul {
            list-style-type: none;
        }
        
        ul li {
            background-color: #f9f9f9;
            margin-bottom: 10px;
            padding: 12px 15px;
            border-radius: 5px;
            border-left: 4px solid #333333;
        }
        
        .contact-info p {
            margin-bottom: 10px;
            font-size: 1.05rem;
        }
        
        /* DESKTOP MEDIA QUERY */
        @media (min-width: 768px) {
            body {
                padding: 40px 20px;
            }
            
            header {
                padding: 60px 40px;
            }
            
            section {
                padding: 40px;
            }
            
            header h1 {
                font-size: 3rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        
        <!-- HEADER SECTION -->
        <header>
            <h1>Shantnu Deval</h1>
            <p>Final year BA Student</p>
        </header>

        <!-- ABOUT SECTION -->
        <section id="about">
            <h2 class="section-title">About</h2>
            <p>I am a final year BA Student currently pursuing my degree at GDC Sunderbani.</p>
        </section>

        <!-- SKILLS SECTION -->
        <section id="skills">
            <h2 class="section-title">Skills</h2>
            <ul>
                <li>AI (Artificial Intelligence)</li>
                <li>Video Editing</li>
                <li>Audio Production & Editing</li>
            </ul>
        </section>

        <!-- PROJECTS SECTION -->
        <section id="projects">
            <h2 class="section-title">Projects</h2>
            <ul>
                <li><strong>College Fest</strong> - Participated in organizing and managing events for the annual college festival.</li>
                <li><strong>NSS Winter Camp</strong> - Volunteered and contributed to community service initiatives during the National Service Scheme camp.</li>
            </ul>
        </section>

        <!-- CONTACT SECTION -->
        <section id="contact">
            <h2 class="section-title">Contact</h2>
            <div class="contact-info">
                <p><strong>Email:</strong> <a href="mailto:shantnu8910@gmail.com">shantnu8910@gmail.com</a></p>
                <p><strong>GitHub:</strong> <a href="https://github.com/shantnu8910-hub" target="_blank">github.com/shantnu8910-hub</a></p>
            </div>
        </section>

    </div>
</body>
</html>

