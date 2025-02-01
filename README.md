<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <style>
        :root {
            --primary: #2563eb;
            --secondary: #4f46e5;
            --text: #1f2937;
            --bg: #ffffff;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            max-width: 800px;
            margin: 0 auto;
            padding: 2rem;
            color: var(--text);
            background: var(--bg);
            line-height: 1.6;
        }

        .header {
            text-align: center;
            margin-bottom: 3rem;
            animation: fadeIn 1s ease-in;
        }

        .name {
            font-size: 2.5rem;
            font-weight: bold;
            background: linear-gradient(45deg, var(--primary), var(--secondary));
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            margin-bottom: 1rem;
        }

        .title {
            font-size: 1.25rem;
            color: #4b5563;
            margin-bottom: 1rem;
        }

        .about-section {
            background: linear-gradient(to right, #f8fafc, #f1f5f9);
            border-radius: 12px;
            padding: 2rem;
            margin: 2rem 0;
            animation: slideIn 0.8s ease-out;
        }

        .about-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 2rem;
            margin-top: 1.5rem;
        }

        .about-item {
            display: flex;
            flex-direction: column;
            gap: 0.5rem;
        }

        .about-icon {
            font-size: 1.5rem;
            color: var(--primary);
        }

        .stats {
            display: flex;
            justify-content: center;
            gap: 2rem;
            margin: 2rem 0;
        }

        .stat-item {
            text-align: center;
            animation: slideIn 0.5s ease-out;
        }

        .stat-number {
            font-size: 1.5rem;
            font-weight: bold;
            color: var(--primary);
        }

        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            margin: 2rem 0;
        }

        .project-card {
            background: #f8fafc;
            border-radius: 8px;
            padding: 1.5rem;
            transition: transform 0.2s;
            animation: fadeIn 0.5s ease-out;
        }

        .project-card:hover {
            transform: translateY(-5px);
        }

        .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
            margin: 2rem 0;
        }

        .skill-tag {
            background: #e0e7ff;
            color: var(--primary);
            padding: 0.5rem 1rem;
            border-radius: 9999px;
            font-size: 0.875rem;
            animation: scaleIn 0.3s ease-out;
        }

        .connect {
            text-align: center;
            margin-top: 3rem;
        }

        .social-links {
            display: flex;
            justify-content: center;
            gap: 1.5rem;
            margin-top: 1rem;
        }

        .social-link {
            color: var(--text);
            text-decoration: none;
            transition: color 0.2s;
        }

        .social-link:hover {
            color: var(--primary);
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        @keyframes slideIn {
            from { transform: translateX(-20px); opacity: 0; }
            to { transform: translateX(0); opacity: 1; }
        }

        @keyframes scaleIn {
            from { transform: scale(0.8); opacity: 0; }
            to { transform: scale(1); opacity: 1; }
        }
    </style>
</head>
<body>
    <div class="header">
        <div class="name">John Doe</div>
        <div class="title">Full Stack Developer | Open Source Enthusiast</div>
        <p>🚀 Building innovative solutions with modern technologies</p>
    </div>

    <div class="about-section">
        <h2>About Me</h2>
        <p>Passionate software engineer with 5+ years of experience in building scalable web applications and microservices. I specialize in JavaScript/TypeScript ecosystem and cloud technologies. Currently focused on creating developer tools that improve productivity and code quality.</p>
        
        <div class="about-grid">
            <div class="about-item">
                <span class="about-icon">🎯</span>
                <h3>Focus</h3>
                <p>Full-stack development, Cloud architecture, and Developer tooling</p>
            </div>
            <div class="about-item">
                <span class="about-icon">🌱</span>
                <h3>Learning</h3>
                <p>Currently exploring Rust and WebAssembly</p>
            </div>
            <div class="about-item">
                <span class="about-icon">💡</span>
                <h3>Interests</h3>
                <p>Open source, System design, Developer experience</p>
            </div>
        </div>
    </div>

    <div class="stats">
        <div class="stat-item">
            <div class="stat-number">15+</div>
            <div>Projects</div>
        </div>
        <div class="stat-item">
            <div class="stat-number">5+</div>
            <div>Years Experience</div>
        </div>
        <div class="stat-item">
            <div class="stat-number">500+</div>
            <div>Contributions</div>
        </div>
    </div>

    <div class="projects">
        <div class="project-card">
            <h3>🌟 Project Alpha</h3>
            <p>A revolutionary app that helps developers track their coding habits.</p>
            <div class="skill-tag">React</div>
            <div class="skill-tag">Node.js</div>
        </div>
        <div class="project-card">
            <h3>💡 Project Beta</h3>
            <p>AI-powered code review assistant used by 1000+ developers.</p>
            <div class="skill-tag">Python</div>
            <div class="skill-tag">Machine Learning</div>
        </div>
    </div>

    <div class="skills">
        <div class="skill-tag">JavaScript</div>
        <div class="skill-tag">TypeScript</div>
        <div class="skill-tag">React</div>
        <div class="skill-tag">Node.js</div>
        <div class="skill-tag">Python</div>
        <div class="skill-tag">Docker</div>
        <div class="skill-tag">AWS</div>
        <div class="skill-tag">GraphQL</div>
    </div>

    <div class="connect">
        <h2>Let's Connect! 👋</h2>
        <div class="social-links">
            <a href="https://linkedin.com/in/johndoe" class="social-link">LinkedIn</a>
            <a href="https://twitter.com/johndoe" class="social-link">Twitter</a>
            <a href="mailto:john@example.com" class="social-link">Email</a>
        </div>
    </div>
</body>
</html>
