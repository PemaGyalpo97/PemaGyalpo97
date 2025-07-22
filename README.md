<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pema Gyalpo - GitHub Profile Preview</title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
            background: #0d1117;
            color: #c9d1d9;
            margin: 0;
            padding: 20px;
            line-height: 1.6;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            background: #161b22;
            border-radius: 8px;
            padding: 32px;
            border: 1px solid #30363d;
        }
        h1 {
            text-align: center;
            font-size: 2.5rem;
            margin-bottom: 20px;
            background: linear-gradient(45deg, #58a6ff, #f85149);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
        h2 {
            font-size: 1.8rem;
            margin: 2rem 0 1rem 0;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        h3 {
            font-size: 1.3rem;
            margin: 1.5rem 0 1rem 0;
            color: #58a6ff;
        }
        .center {
            text-align: center;
        }
        .badges {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 10px;
            margin: 20px 0;
        }
        .badge {
            background: linear-gradient(45deg, #58a6ff, #f85149);
            color: white;
            padding: 8px 16px;
            border-radius: 20px;
            text-decoration: none;
            font-weight: bold;
            transition: transform 0.3s;
        }
        .badge:hover {
            transform: translateY(-2px);
        }
        .tech-badges {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 8px;
            margin: 15px 0;
        }
        .tech-badge {
            background: #21262d;
            border: 1px solid #30363d;
            color: #c9d1d9;
            padding: 6px 12px;
            border-radius: 6px;
            font-size: 0.9rem;
            font-weight: 500;
        }
        .stats-section {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin: 30px 0;
        }
        .stat-card {
            background: #21262d;
            border: 1px solid #30363d;
            border-radius: 8px;
            padding: 20px;
            text-align: center;
        }
        .profile-gif {
            max-width: 400px;
            width: 100%;
            border-radius: 10px;
            margin: 20px 0;
        }
        .divider {
            border: none;
            height: 2px;
            background: linear-gradient(90deg, transparent, #30363d, transparent);
            margin: 2rem 0;
        }
        .about-section {
            display: grid;
            grid-template-columns: 1fr auto;
            gap: 30px;
            align-items: center;
            margin: 30px 0;
        }
        .about-content {
            font-size: 1.1rem;
        }
        .about-gif {
            max-width: 300px;
            border-radius: 10px;
        }
        .code-block {
            background: #0d1117;
            border: 1px solid #30363d;
            border-radius: 8px;
            padding: 20px;
            margin: 20px 0;
            font-family: 'SF Mono', Consolas, monospace;
            font-size: 0.9rem;
            overflow-x: auto;
        }
        .quote-card {
            background: linear-gradient(135deg, #21262d, #161b22);
            border: 1px solid #30363d;
            border-radius: 12px;
            padding: 24px;
            margin: 20px 0;
            text-align: center;
            font-style: italic;
            font-size: 1.1rem;
        }
        .contact-info {
            list-style: none;
            padding: 0;
        }
        .contact-info li {
            margin: 10px 0;
            font-size: 1.1rem;
        }
        .social-links {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin: 20px 0;
        }
        .social-link {
            background: #21262d;
            border: 1px solid #30363d;
            padding: 10px 20px;
            border-radius: 8px;
            color: #c9d1d9;
            text-decoration: none;
            transition: all 0.3s;
        }
        .social-link:hover {
            background: #30363d;
            transform: translateY(-2px);
        }
        .trophy-section {
            text-align: center;
            margin: 30px 0;
        }
        .trophy-placeholder {
            background: linear-gradient(45deg, #ffd700, #ffed4e);
            color: #000;
            padding: 40px;
            border-radius: 12px;
            font-size: 1.2rem;
            font-weight: bold;
        }
        .activity-graph {
            background: #21262d;
            border: 1px solid #30363d;
            border-radius: 8px;
            padding: 20px;
            margin: 20px 0;
            text-align: center;
        }
        .snake-animation {
            background: #0d1117;
            border: 1px solid #30363d;
            border-radius: 8px;
            padding: 20px;
            margin: 20px 0;
            text-align: center;
            font-size: 1.1rem;
        }
        @media (max-width: 768px) {
            .about-section {
                grid-template-columns: 1fr;
                text-align: center;
            }
            .stats-section {
                grid-template-columns: 1fr;
            }
            .container {
                padding: 20px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Hi there! 👋 I'm Pema Gyalpo</h1>
        
        <div class="center">
            <img src="https://hackernoon.com/hn-images/1*ck6cRbbe3uaelEG2JPsIMw.gif" alt="Coding GIF" class="profile-gif">
            
            <div class="badges">
                <span class="badge">Profile Views: 1,234</span>
                <span class="badge">Followers: 89</span>
                <span class="badge">Portfolio Live</span>
            </div>
        </div>

        <hr class="divider">

        <h2>🚀 About Me</h2>
        <div class="about-section">
            <div class="about-content">
                <ul class="contact-info">
                    <li>🌍 <strong>A passionate Software Engineer from Bhutan</strong></li>
                    <li>🎯 <strong>Goal:</strong> Becoming a fully on-site/remote <strong>DevSecOps Engineer</strong></li>
                    <li>💼 <strong>Open to:</strong> Remote collaboration opportunities</li>
                    <li>📧 <strong>Contact:</strong> pemagyalpo74@gmail.com</li>
                    <li>🌐 <strong>Portfolio:</strong> pemagyalpo97.github.io</li>
                </ul>
            </div>
            <img src="https://cdn.dribbble.com/users/1162077/screenshots/3848914/programmer.gif" alt="Coding Animation" class="about-gif">
        </div>

        <hr class="divider">

        <h2>🌐 Connect with Me</h2>
        <div class="social-links">
            <a href="#" class="social-link">Dev.to</a>
            <a href="#" class="social-link">Twitter</a>
            <a href="#" class="social-link">LinkedIn</a>
            <a href="#" class="social-link">Gmail</a>
        </div>

        <hr class="divider">

        <h2>💻 Tech Stack & Tools</h2>

        <h3>🚀 Programming Languages</h3>
        <div class="tech-badges">
            <span class="tech-badge">Python</span>
            <span class="tech-badge">JavaScript</span>
            <span class="tech-badge">Java</span>
            <span class="tech-badge">HTML5</span>
            <span class="tech-badge">CSS3</span>
        </div>

        <h3>🔧 Frameworks & Libraries</h3>
        <div class="tech-badges">
            <span class="tech-badge">React</span>
            <span class="tech-badge">Next.js</span>
            <span class="tech-badge">Django</span>
            <span class="tech-badge">Express.js</span>
            <span class="tech-badge">Node.js</span>
            <span class="tech-badge">Spring</span>
            <span class="tech-badge">TailwindCSS</span>
        </div>

        <h3>🗄️ Databases</h3>
        <div class="tech-badges">
            <span class="tech-badge">PostgreSQL</span>
            <span class="tech-badge">MongoDB</span>
            <span class="tech-badge">MySQL</span>
            <span class="tech-badge">MariaDB</span>
        </div>

        <h3>☁️ DevOps & Cloud</h3>
        <div class="tech-badges">
            <span class="tech-badge">AWS</span>
            <span class="tech-badge">Docker</span>
            <span class="tech-badge">Kubernetes</span>
            <span class="tech-badge">Jenkins</span>
            <span class="tech-badge">Git</span>
            <span class="tech-badge">Linux</span>
        </div>

        <h3>🔍 API & Others</h3>
        <div class="tech-badges">
            <span class="tech-badge">GraphQL</span>
            <span class="tech-badge">Postman</span>
        </div>

        <hr class="divider">

        <h2>📊 GitHub Statistics</h2>
        <div class="stats-section">
            <div class="stat-card">
                <h3>📈 GitHub Stats</h3>
                <p>Total Commits: 500+</p>
                <p>Public Repos: 25</p>
                <p>Stars Received: 150+</p>
            </div>
            <div class="stat-card">
                <h3>💻 Top Languages</h3>
                <p>JavaScript: 35%</p>
                <p>Python: 30%</p>
                <p>Java: 20%</p>
                <p>Others: 15%</p>
            </div>
        </div>

        <div class="stat-card">
            <h3>🔥 GitHub Streak</h3>
            <p>Current Streak: 42 days</p>
            <p>Best Streak: 89 days</p>
            <p>Total Contributions: 1,200+</p>
        </div>

        <hr class="divider">

        <h2>🏆 GitHub Trophies</h2>
        <div class="trophy-section">
            <div class="trophy-placeholder">
                🏆 GitHub Trophies Display Here 🏆
            </div>
        </div>

        <hr class="divider">

        <h2>📈 Activity Graph</h2>
        <div class="activity-graph">
            <h3>📊 Contribution Activity</h3>
            <p>Interactive contribution graph would appear here showing your daily GitHub activity</p>
        </div>

        <hr class="divider">

        <h2>🎯 Current Focus</h2>
        <div class="code-block">
<pre><code>const pemaGyalpo = {
    location: "Bhutan 🇧🇹",
    currentFocus: "DevSecOps Engineering",
    learningGoals: ["Cloud Security", "Infrastructure as Code", "CI/CD Pipelines"],
    askMeAbout: ["Web Development", "DevOps", "Cloud Computing"],
    technologies: {
        frontEnd: ["React", "Next.js", "TailwindCSS"],
        backEnd: ["Node.js", "Django", "Spring Boot"],
        databases: ["PostgreSQL", "MongoDB", "MySQL"],
        devOps: ["Docker", "Kubernetes", "Jenkins", "AWS"],
        tools: ["Git", "Linux", "GraphQL"]
    },
    funFact: "I love building scalable applications and automating workflows!"
};</code></pre>
        </div>

        <hr class="divider">

        <h2>💡 Random Dev Quote</h2>
        <div class="quote-card">
            "Code is like humor. When you have to explain it, it's bad." - Cory House
        </div>

        <hr class="divider">

        <div class="center">
            <h2>🌟 Thanks for visiting! Let's connect and build something amazing together! 🌟</h2>
            
            <div class="snake-animation">
                🐍 GitHub Contribution Snake Animation 🐍
                <br><small>(Animated snake eating your contributions would appear here)</small>
            </div>

            <p><strong>⭐ From PemaGyalpo97 with ❤️</strong></p>
        </div>
    </div>
</body>
</html>
