<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Curriculum Vitae - Anirudh Singh</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #e9ecef;
            display: flex;
            justify-content: center;
            padding: 20px;
            margin: 0;
            color: #333;
        }

        /* A4 Page Styling */
        .cv-container {
            width: 210mm;
            min-height: 297mm;
            background-color: white;
            padding: 40px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
            position: relative;
            box-sizing: border-box;
        }

        /* Top Center Title */
        .cv-heading {
            text-align: center;
            font-size: 20px;
            font-weight: bold;
            text-decoration: underline;
            text-underline-offset: 4px;
            margin-bottom: 25px;
            color: #000;
            letter-spacing: 1px;
        }

        /* Header Layout: Info Left, Photo Right */
        .header-section {
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
            border-bottom: 2px solid #2c3e50;
            padding-bottom: 15px;
            margin-bottom: 20px;
        }

        .personal-details {
            flex: 1;
        }

        .name {
            font-size: 36px;
            font-weight: 800;
            margin: 0 0 10px 0;
            color: #2c3e50;
            text-transform: uppercase;
        }

        .contact-line {
            margin: 4px 0;
            font-size: 14px;
        }

        .contact-line a {
            color: #0066cc;
            text-decoration: none;
        }

        /* Photo Box Styling */
        .photo-frame {
            width: 150px;
            height: 170px;
            border: 1px solid #ccc;
            background-color: #f8f9fa;
            display: flex;
            align-items: center;
            justify-content: center;
            overflow: hidden;
            margin-left: 20px;
            border-radius: 4px;
        }
        
        .photo-frame img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            display: block;
        }

        /* Section Styling */
        .section-title {
            font-size: 16px;
            font-weight: bold;
            background-color: #f2f4f8;
            padding: 5px 10px;
            margin-top: 15px;
            margin-bottom: 10px;
            border-left: 4px solid #2c3e50;
            text-transform: uppercase;
        }

        /* Content Styling */
        .entry {
            margin-bottom: 10px;
        }

        .entry-header {
            display: flex;
            justify-content: space-between;
            font-weight: bold;
            font-size: 15px;
        }

        .entry-sub {
            font-style: italic;
            color: #555;
            font-size: 14px;
            margin-bottom: 2px;
        }

        p {
            margin: 0 0 8px 0;
            font-size: 14px;
            line-height: 1.5;
            text-align: justify;
        }

        ul {
            margin: 2px 0 8px 0;
            padding-left: 20px;
        }

        li {
            font-size: 14px;
            margin-bottom: 3px;
            line-height: 1.4;
        }

        /* Skills Table Layout */
        .skills-table {
            width: 100%;
            font-size: 14px;
            border-collapse: collapse;
        }
        .skills-table td {
            padding: 3px 0;
            vertical-align: top;
        }
        .skill-label {
            font-weight: bold;
            width: 140px;
            color: #444;
        }

        /* Print Optimization */
        @media print {
            body { background: white; padding: 0; }
            .cv-container { box-shadow: none; width: 100%; margin: 0; padding: 20px; }
        }
    </style>
</head>
<body>

    <div class="cv-container">
        
        <div class="cv-heading">CURRICULUM VITAE</div>

        <div class="header-section">
            <div class="personal-details">
                <h1 class="name">Anirudh Singh</h1>
                <div class="contact-line">📍 Phagwara, Punjab</div>
                <div class="contact-line">📞 +91-6386486263</div>
                <div class="contact-line">📧 <a href="mailto:anirudh953singh@gmail.com">anirudh953singh@gmail.com</a></div>
                <div class="contact-line">🔗 <a href="https://www.linkedin.com/in/anirudh-singh-215895353" target="_blank">linkedin.com/in/anirudh-singh-215895353</a></div>
            </div>
            
            <div class="photo-frame">
                <img src="cv photo.jpeg" alt="Anirudh Singh">
            </div>
        </div>

        <div class="section-title">Career Objective</div>
        <p>
            Ambitious first-year B.Tech CSE student passionate about transforming ideas into code. With a solid foundation in Python, Web Development, and API integration, I am eager to collaborate on innovative projects and solve complex technical challenges in a dynamic software engineering environment.
        </p>

        <div class="section-title">Education</div>
        <div class="entry">
            <div class="entry-header">
                <span>Lovely Professional University</span>
                <span>Phagwara, Punjab</span>
            </div>
            <div class="entry-sub">B.Tech in Computer Science Engineering | 2025 – Present</div>
        </div>
        <div class="entry">
            <div class="entry-header">
                <span>S.J.S Public School</span>
                <span>Lalganj</span>
            </div>
            <div class="entry-sub">Class XII (Higher Secondary) - CBSE | 2023</div>
            <ul><li>Percentage: <strong>79%</strong></li></ul>
        </div>
        <div class="entry">
            <div class="entry-header">
                <span>S.J.S Public School</span>
                <span>Lalganj</span>
            </div>
            <div class="entry-sub">Class X (Secondary Education) - CBSE | 2021</div>
            <ul><li>Percentage: <strong>85%</strong></li></ul>
        </div>

        <div class="section-title">Technical Skills</div>
        <table class="skills-table">
            <tr>
                <td class="skill-label">Languages/Core:</td>
                <td>Python, JavaScript (ES6), HTML5, CSS3</td>
            </tr>
            <tr>
                <td class="skill-label">Technologies:</td>
                <td>REST APIs (OMDb), DOM Manipulation, File Handling</td>
            </tr>
            <tr>
                <td class="skill-label">Tools:</td>
                <td>VS Code, MS Excel, Canva, Git (Basic)</td>
            </tr>
        </table>

        <div class="section-title">Academic Projects</div>
        
        <div class="entry">
            <div class="entry-header">
                <span>Dynamic Movie Search Application</span>
            </div>
            <div class="entry-sub">Tech: HTML, JavaScript, OMDb API</div>
            <ul>
                <li>Integrated OMDb API to fetch and display real-time movie data (ratings, plot, release date).</li>
                <li>Implemented asynchronous JavaScript (Fetch API) to handle data requests efficiently.</li>
            </ul>
        </div>

        <div class="entry">
            <div class="entry-header">
                <span>Personal Expense Tracker CLI</span>
            </div>
            <div class="entry-sub">Tech: Python, File I/O</div>
            <ul>
                <li>Developed a console-based application to log, view, and calculate daily expenses.</li>
                <li>Implemented File Handling to ensure data persistence across sessions.</li>
            </ul>
        </div>

        <div class="entry">
            <div class="entry-header">
                <span>Modern Web Calculator</span>
            </div>
            <div class="entry-sub">Tech: HTML5, CSS3, JavaScript</div>
            <ul>
                <li>Built a fully functional calculator with a responsive CSS Grid layout and glassmorphism styling.</li>
                <li>Utilized JavaScript DOM manipulation to handle arithmetic logic and event listeners.</li>
            </ul>
        </div>

        <div class="section-title">Certifications & Achievements</div>
        <ul>
            <li><strong>AI Hackathon Participant (Buildstorm)</strong> – Organized by PlaytoUnite & QubicSquare Technologies Pvt Ltd.</li>
            <li><strong>Mastering Leadership Skills</strong> – Certified by UniAthena.</li>
            <li><strong>Technical Workshops</strong> – Participated in Artificial Intelligence & Web Development workshops.</li>
            <li><strong>District Level Kabaddi Champion</strong> – Winner of the inter-district tournament.</li>
        </ul>

        <div class="section-title">Languages</div>
        <table class="skills-table">
            <tr>
                <td class="skill-label">English:</td>
                <td>Communicative / Intermediate</td>
            </tr>
            <tr>
                <td class="skill-label">Hindi:</td>
                <td>Fluent</td>
            </tr>
        </table>

    </div>

</body>
</html>
