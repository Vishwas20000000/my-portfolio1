<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vishwas Gowda Ramesh - Portfolio</title>
    <style>
        :root {
            --primary-color: #1e3a8a;
            --secondary-color: #3b82f6;
            --accent-color: #f59e0b;
            --text-color: #333;
            --light-bg: #f8fafc;
            --dark-bg: #1e293b;
            --card-bg: #ffffff;
            --border-radius: 8px;
            --box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: var(--light-bg);
            color: var(--text-color);
            line-height: 1.6;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* Header Styles */
        header {
            background-color: var(--dark-bg);
            color: white;
            padding: 2rem 0;
            position: relative;
            overflow: hidden;
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0 2rem;
        }

        .logo {
            font-size: 1.5rem;
            font-weight: bold;
            animation: fadeInDown 1s ease-out;
        }

        .nav-links {
            display: flex;
            gap: 2rem;
        }

        .nav-links a {
            color: white;
            text-decoration: none;
            transition: color 0.3s;
            font-weight: 500;
        }

        .nav-links a:hover {
            color: var(--accent-color);
        }

        .hero {
            padding: 3rem 2rem;
            text-align: center;
            animation: fadeIn 1.2s ease-out;
        }

        .hero h1 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }

        .hero h2 {
            font-size: 1.2rem;
            font-weight: 400;
            max-width: 800px;
            margin: 0 auto 2rem;
            opacity: 0.9;
        }

        .location-info {
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 0.5rem;
            font-size: 1rem;
            margin-top: 1rem;
        }

        .contact-links {
            display: flex;
            justify-content: center;
            gap: 2rem;
            margin-top: 2rem;
        }

        .contact-links a {
            color: white;
            text-decoration: none;
            display: flex;
            align-items: center;
            gap: 0.5rem;
            transition: transform 0.3s, color 0.3s;
        }

        .contact-links a:hover {
            color: var(--accent-color);
            transform: translateY(-3px);
        }

        /* Main Content Styles */
        main {
            padding: 3rem 0;
        }

        section {
            margin-bottom: 4rem;
        }

        .section-title {
            font-size: 1.8rem;
            margin-bottom: 1.5rem;
            color: var(--primary-color);
            position: relative;
            display: inline-block;
        }

        .section-title::after {
            content: '';
            position: absolute;
            bottom: -10px;
            left: 0;
            width: 50%;
            height: 3px;
            background-color: var(--accent-color);
            animation: expandWidth 1s ease-out forwards;
        }

        @keyframes expandWidth {
            from { width: 0; }
            to { width: 50%; }
        }

        .about-content, .objective-content {
            background-color: var(--card-bg);
            padding: 2rem;
            border-radius: var(--border-radius);
            box-shadow: var(--box-shadow);
            animation: fadeIn 1s ease-out;
        }

        /* Skills Section */
        .skills-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }

        .skill-category {
            background-color: var(--card-bg);
            padding: 2rem;
            border-radius: var(--border-radius);
            box-shadow: var(--box-shadow);
            animation: fadeIn 1s ease-out;
            transition: transform 0.3s;
        }

        .skill-category:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
        }

        .skill-category h3 {
            margin-bottom: 1rem;
            color: var(--secondary-color);
        }

        .skill-item {
            margin-bottom: 0.8rem;
            position: relative;
            padding-left: 1.5rem;
        }

        .skill-item::before {
            content: '▹';
            position: absolute;
            left: 0;
            color: var(--accent-color);
        }

        /* Experience & Education */
        .timeline {
            position: relative;
            max-width: 1200px;
            margin: 0 auto;
        }

        .timeline::after {
            content: '';
            position: absolute;
            width: 4px;
            background-color: var(--secondary-color);
            top: 0;
            bottom: 0;
            left: 50%;
            margin-left: -2px;
        }

        .timeline-item {
            position: relative;
            width: 50%;
            padding: 0 40px 20px 0;
            animation: fadeIn 1s ease-out;
        }

        .timeline-item:nth-child(even) {
            left: 50%;
            padding: 0 0 20px 40px;
        }

        .timeline-content {
            background-color: var(--card-bg);
            padding: 1.5rem;
            border-radius: var(--border-radius);
            box-shadow: var(--box-shadow);
            position: relative;
            transition: transform 0.3s;
        }

        .timeline-content:hover {
            transform: translateY(-5px);
        }

        .timeline-item:nth-child(odd) .timeline-content::after {
            content: '';
            position: absolute;
            top: 20px;
            right: -15px;
            width: 0;
            height: 0;
            border-top: 15px solid transparent;
            border-bottom: 15px solid transparent;
            border-left: 15px solid var(--card-bg);
        }

        .timeline-item:nth-child(even) .timeline-content::after {
            content: '';
            position: absolute;
            top: 20px;
            left: -15px;
            width: 0;
            height: 0;
            border-top: 15px solid transparent;
            border-bottom: 15px solid transparent;
            border-right: 15px solid var(--card-bg);
        }

        .timeline-date {
            color: var(--secondary-color);
            font-weight: bold;
            margin-bottom: 0.5rem;
        }

        .timeline-title {
            margin-bottom: 0.5rem;
            font-size: 1.2rem;
        }

        .timeline-org {
            margin-bottom: 1rem;
            font-style: italic;
        }

        .timeline-details {
            margin-top: 1rem;
        }

        .timeline-details ul {
            padding-left: 1.5rem;
        }

        .timeline-details li {
            margin-bottom: 0.5rem;
        }

        /* Projects Section */
        .project-card {
            background-color: var(--card-bg);
            padding: 2rem;
            border-radius: var(--border-radius);
            box-shadow: var(--box-shadow);
            margin-bottom: 2rem;
            animation: fadeIn 1s ease-out;
            transition: transform 0.3s;
        }

        .project-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
        }

        .project-title {
            color: var(--primary-color);
            margin-bottom: 0.5rem;
            font-size: 1.4rem;
        }

        .project-date {
            color: var(--secondary-color);
            margin-bottom: 1rem;
            font-weight: 500;
        }

        .project-details ul {
            padding-left: 1.5rem;
            margin-top: 1rem;
        }

        .project-details li {
            margin-bottom: 0.5rem;
        }

        /* Certifications */
        .certifications-list {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
            margin-top: 1rem;
        }

        .certification-item {
            background-color: var(--card-bg);
            padding: 1rem;
            border-radius: var(--border-radius);
            box-shadow: var(--box-shadow);
            flex: 1 1 calc(50% - 1rem);
            min-width: 250px;
            animation: fadeIn 1s ease-out;
            transition: transform 0.3s;
        }

        .certification-item:hover {
            transform: translateY(-5px);
            background-color: var(--light-bg);
            border-left: 3px solid var(--accent-color);
        }

        /* Footer Styles */
        footer {
            background-color: var(--dark-bg);
            color: white;
            padding: 2rem 0;
            text-align: center;
        }

        .footer-content {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 1rem;
        }

        .footer-links {
            display: flex;
            gap: 2rem;
            margin: 1rem 0;
        }

        .footer-links a {
            color: white;
            text-decoration: none;
            transition: color 0.3s;
        }

        .footer-links a:hover {
            color: var(--accent-color);
        }

        .copyright {
            margin-top: 1rem;
            font-size: 0.9rem;
            opacity: 0.8;
        }

        /* Animations */
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        @keyframes fadeInDown {
            from { opacity: 0; transform: translateY(-20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .animated {
            opacity: 0;
            transform: translateY(20px);
        }

        /* Responsive Styles */
        @media (max-width: 768px) {
            .nav-links {
                display: none;
            }

            .hero h1 {
                font-size: 2rem;
            }

            .hero h2 {
                font-size: 1rem;
            }

            .skills-container {
                grid-template-columns: 1fr;
            }

            .timeline::after {
                left: 31px;
            }

            .timeline-item {
                width: 100%;
                padding-right: 0;
                padding-left: 70px;
            }

            .timeline-item:nth-child(even) {
                left: 0%;
                padding: 0 0 20px 70px;
            }

            .timeline-item:nth-child(odd) .timeline-content::after,
            .timeline-item:nth-child(even) .timeline-content::after {
                display: none;
            }

            .certification-item {
                flex: 1 1 100%;
            }
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <div class="logo">VGR</div>
            <div class="nav-links">
                <a href="#about">About</a>
                <a href="#skills">Skills</a>
                <a href="#experience">Experience</a>
                <a href="#education">Education</a>
                <a href="#projects">Projects</a>
                <a href="#certifications">Certifications</a>
                <a href="#contact">Contact</a>
            </div>
        </nav>
        <div class="hero">
            <h1>Vishwas Gowda Ramesh</h1>
            <h2>Master's Student in Supply Chain Management | SAP MM & Power BI | Logistics & Data-Driven Decision Making</h2>
            <div class="location-info">
                <span>📍 Hamm, North Rhine-Westphalia, Germany</span>
            </div>
            <div class="contact-links">
                <a href="mailto:vishwas.g.ramesh@gmail.com">📧 vishwas.g.ramesh@gmail.com</a>
                <a href="tel:+4915773646116">📞 +49 015773646116</a>
                <a href="https://www.linkedin.com/in/vishwasgowdaramesh/" target="_blank">🔗 LinkedIn</a>
            </div>
        </div>
    </header>

    <main class="container">
        <section id="about">
            <h2 class="section-title">About Me</h2>
            <div class="about-content">
                <p>I am an enthusiastic and driven Master's student in Supply Chain Management at SRH Hochschule, Hamm, specializing in logistics, inventory management, and data-driven decision-making. My goal is to enhance supply chain operations through digital transformation, data analytics, and process optimization. Equipped with hands-on experience in SAP, Power BI, I am passionate about leveraging technology to improve efficiency and reduce costs.</p>
                <br>
                <p>Currently, I am working as a Working Student at Picnic Fulfillment Center, where I assist in optimizing warehouse operations, analyzing data, and improving process workflows. Prior to this, I completed internships at Siemens and GTTC, Bangalore, where I contributed to product design, manufacturing optimization, and process improvement.</p>
                <br>
                <p>I am actively exploring opportunities in Supply Chain Analytics, Logistics Coordination, and Business Intelligence, where I can apply my technical expertise and drive for continuous improvement to contribute to organizational success.</p>
            </div>
        </section>

        <section id="objective">
            <h2 class="section-title">Career Objective</h2>
            <div class="objective-content">
                <p>I aim to leverage my expertise in supply chain optimization, data analytics, and Industry 4.0 technologies to drive efficiency, innovation, and process improvements in logistics and manufacturing. I am committed to helping organizations harness the power of data to make informed decisions and optimize their supply chain operations.</p>
            </div>
        </section>

        <section id="skills">
            <h2 class="section-title">Key Skills</h2>
            <div class="skills-container">
                <div class="skill-category">
                    <h3>Technical Skills</h3>
                    <div class="skill-item">Supply Chain Optimization & Process Improvement</div>
                    <div class="skill-item">SAP MM, Power BI, Microsoft Excel</div>
                    <div class="skill-item">Logistics, Inventory & Warehouse Management</div>
                    <div class="skill-item">Industry 4.0 Technologies (IoT, Smart Factories)</div>
                    <div class="skill-item">CAD & Product Design (AutoCAD, SolidWorks, CATIA)</div>
                </div>

                <div class="skill-category">
                    <h3>Analytical Skills</h3>
                    <div class="skill-item">Data Analytics & Visualization</div>
                    <div class="skill-item">Process Improvement & Lean Manufacturing</div>
                    <div class="skill-item">Predictive Maintenance & IoT Integration</div>
                </div>

                <div class="skill-category">
                    <h3>Soft Skills</h3>
                    <div class="skill-item">Problem-Solving & Critical Thinking</div>
                    <div class="skill-item">Teamwork & Collaboration</div>
                    <div class="skill-item">Project Management & Leadership</div>
                </div>

                <div class="skill-category">
                    <h3>Languages</h3>
                    <div class="skill-item">English: Fluent</div>
                    <div class="skill-item">German: Basic</div>
                    <div class="skill-item">Hindi: Native</div>
                </div>
            </div>
        </section>

        <section id="experience">
            <h2 class="section-title">Work Experience</h2>
            <div class="timeline">
                <div class="timeline-item">
                    <div class="timeline-content">
                        <div class="timeline-date">May 2024 – Present</div>
                        <h3 class="timeline-title">Working Student</h3>
                        <div class="timeline-org">Picnic Fulfillment Center, Hamm, Germany</div>
                        <div class="timeline-details">
                            <ul>
                                <li>Supported warehouse operations and inventory management, improving order fulfillment efficiency.</li>
                                <li>Analyzed data and workflows to identify bottlenecks and enhance process efficiency.</li>
                                <li>Collaborated across teams to ensure on-time delivery and seamless logistics coordination.</li>
                            </ul>
                        </div>
                    </div>
                </div>
                <div class="timeline-item">
                    <div class="timeline-content">
                        <div class="timeline-date">Jan 2021 – Mar 2021</div>
                        <h3 class="timeline-title">Intern</h3>
                        <div class="timeline-org">Government Tool Room & Training Centre (GTTC), Bangalore, India</div>
                        <div class="timeline-details">
                            <ul>
                                <li>Designed industrial components and prototypes using AutoCAD and 3D modeling tools.</li>
                                <li>Assisted in optimizing manufacturing processes to improve operational efficiency.</li>
                            </ul>
                        </div>
                    </div>
                </div>
                <div class="timeline-item">
                    <div class="timeline-content">
                        <div class="timeline-date">Sept 2021 – Nov 2021</div>
                        <h3 class="timeline-title">Intern</h3>
                        <div class="timeline-org">Siemens Centre, Bangalore, India</div>
                        <div class="timeline-details">
                            <ul>
                                <li>Developed CAD-based product designs and contributed to process optimization projects.</li>
                                <li>Gained experience in lean manufacturing and improving production efficiency.</li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section id="education">
            <h2 class="section-title">Education</h2>
            <div class="timeline">
                <div class="timeline-item">
                    <div class="timeline-content">
                        <div class="timeline-date">April 2024 – April 2026</div>
                        <h3 class="timeline-title">Master's in Supply Chain Management</h3>
                        <div class="timeline-org">SRH University of Applied Sciences, North Rhine-Westphalia</div>
                    </div>
                </div>
                <div class="timeline-item">
                    <div class="timeline-content">
                        <div class="timeline-date">2018 – 2022</div>
                        <h3 class="timeline-title">Bachelor of Engineering (B.E.), Mechanical Engineering</h3>
                        <div class="timeline-org">Visvesvaraya Technological University, India</div>
                    </div>
                </div>
            </div>
        </section>

        <section id="projects">
            <h2 class="section-title">Projects & Research</h2>
            <div class="project-card">
                <h3 class="project-title">Smart Factory Using Industry 4.0 Technologies</h3>
                <div class="project-date">Feb 2022 – July 2022</div>
                <div class="project-details">
                    <ul>
                        <li>Designed and implemented a Smart Factory prototype integrating IoT, automation, and data analytics to enhance manufacturing processes.</li>
                        <li>Developed predictive maintenance algorithms that significantly reduced equipment downtime.</li>
                        <li>Created a centralized HMI dashboard for real-time monitoring and decision-making.</li>
                    </ul>
                </div>
            </div>
        </section>

        <section id="certifications">
            <h2 class="section-title">Certifications</h2>
            <div class="certifications-list">
                <div class="certification-item">Lean Six Sigma White Belt & Yellow Belt</div>
                <div class="certification-item">Fresh Connection Business Simulation</div>
                <div class="certification-item">Blue Connection Business Simulation</div>
                <div class="certification-item">Autodesk Certified Professional (CAD)</div>
            </div>
        </section>

        <section id="contact">
            <h2 class="section-title">Contact</h2>
            <div class="about-content">
                <p>📧 Email: <a href="mailto:vishwas.g.ramesh@gmail.com">vishwas.g.ramesh@gmail.com</a></p>
                <p>📞 Phone: <a href="tel:+4915773646116">+49 015773646116</a></p>
                <p>🔗 LinkedIn: <a href="https://www.linkedin.com/in/vishwasgowdaramesh/" target="_blank">https://www.linkedin.com/in/vishwasgowdaramesh/</a></p>
            </div>
        </section>
    </main>

    <footer>
        <div class="container">
            <div class="footer-content">
                <h3>Vishwas Gowda Ramesh</h3>
                <p>Supply Chain Management Professional</p>
                <div class="footer-links">
                    <a href="mailto:vishwas.g.ramesh@gmail.com">Email</a>
                    <a href="tel:+4915773646116">Phone</a>
                    <a href="https://www.linkedin.com/in/vishwasgowdaramesh/" target="_blank">LinkedIn</a>
                </div>
                <div class="copyright">© 2025 Vishwas Gowda Ramesh. All rights reserved.</div>
            </div>
        </div>
    </footer>

    <script>
        // Animation for elements when they come into view
        document.addEventListener('DOMContentLoaded', function() {
            // Animate elements when they come into view
            const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.style.opacity = 1;
                        entry.target.style.transform = 'translateY(0)';
                    }
                });
            }, { threshold: 0.1 });

            // Target elements to animate
            const sections = document.querySelectorAll('section');
            sections.forEach(section => {
                section.classList.add('animated');
                observer.observe(section);
            });

            const skillCategories = document.querySelectorAll('.skill-category');
            skillCategories.forEach((category, index) => {
                category.style.animationDelay = `${index * 0.2}s`;
                observer.observe(category);
            });

            const timelineItems = document.querySelectorAll('.timeline-item');
            timelineItems.forEach((item, index) => {
                item.style.animationDelay = `${index * 0.3}s`;
                observer.observe(item);
            });

            const certItems = document.querySelectorAll('.certification-item');
            certItems.forEach((item, index) => {
                item.style.animationDelay = `${index * 0.15}s`;
                observer.observe(item);
            });
        });

        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>
