# task1

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aarohi Tapas | Portfolio</title>
</head>
<body>
    <!-- Header with Navigation -->
    <header>
        <div>
            <h1>Aarohi Tapas</h1>
            <p>Web Developer</p>
        </div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Main Content -->
    <main>
        <!-- Home Section -->
        <section id="home">
            <h2>Welcome to My Portfolio</h2>
            <figure>
                <img src="C:\Users\DELL\Pictures\ph1.jpeg" 
                     alt="Aarohi Tapas - Web Developer" width="300" height="300">
                <figcaption>Aarohi Tapas - Web Developer</figcaption>
            </figure>
            <p>I create responsive, user-friendly websites and applications with modern technologies.</p>
            <a href="#contact">Get In Touch</a>
        </section>

        <!-- About Section -->                                          
        <section id="about">
            <h2>About Me</h2>
            <article>
                <h3>Hello! I'm Aarohi Tapas</h3>
                <figure>
                    <img src="https://images.unsplash.com/photo-1521737711867-e3b97375f902?ixlib=rb-4.0.3&auto=format&fit=crop&w=400&q=80" 
                         alt="Aarohi Tapas working on laptop" width="400" height="300">
                    <figcaption>Working on web development projects</figcaption>
                </figure>
                <p>I'm a passionate web developer with over 7 months of experience creating digital solutions for businesses and individuals.</p>
                <p>My journey in web development started during my Information Technology  degree, and I've been hooked ever since.</p>
                
                <h4>Education</h4>
                <ul>
                    <li><strong>Bachelor of technology in IT</strong> - Priyadarshini college of Engineering (2021-2024)</li>
                </ul>
                
                <h4>Experience</h4>
                <ul>
                    <li><strong> Frontend Developer Intern</strong> at Hats off Private limited. (2024)</li>
                    <li><strong> Web Developer</strong> at Sai Compyusys Private limited (2023)</li>
                </ul>
            </article>
        </section>

        <!-- Skills Section -->
        <section id="skills">
            <h2>My Skills</h2>
            
            <article>
                <h3>Frontend Development</h3>
                <ul>
                    <li>HTML5 - Expert</li>
                    <li>CSS3 - Advanced</li>
                    <li>JavaScript - </li>
                    <li>React - Intermediate</li>
                    <li>Responsive Design - Expert</li>
                </ul>
            </article>
            
            <article>
                <h3>Backend Development</h3>
                <ul>
                    <li>Node.js - Advanced</li>
                    <li>Express.js - Intermediate</li>
                    <li>MongoDB - Intermediate</li>
                    <li>REST APIs - Advanced</li>
                    <li>Python - Basic</li>
                </ul>
            </article>
            
            <article>
                <h3>Tools & Others</h3>
                <ul>
                    <li>Git & GitHub - Advanced</li>
                    <li>VS Code - Expert</li>
                    <li>Figma - Intermediate</li>
                    <li>Web Performance - Intermediate</li>
                    <li>SEO - Basic</li>
                </ul>
            </article>
            
            <aside>
                <h4>Certifications</h4>
                <ul>
                    <li>Google Mobile Web Specialist</li>
                    <li>AWS Certified Developer Associate</li>
                    <li>Scrum Master Certification</li>
                </ul>
            </aside>
        </section>

        <!-- Projects Section (Bonus) -->
        <section id="projects">
            <h2>Recent Projects</h2>
            <article>
                <h3>E-Commerce Website</h3>
                <p>A full-featured online store with shopping cart and payment integration.</p>
                <p><strong>Technologies:</strong> HTML, CSS, Bootstrap, React, Node.js,</p>
            </article>
            
            <article>
                <h3>Portfolio Website Template</h3>
                <p>A responsive portfolio template for creative professionals.</p>
                <p><strong>Technologies:</strong> HTML5, CSS3, JavaScript</p>
            </article>
            
            <article>
                <h3>Task Management App</h3>
                <p>A collaborative task management application with real-time updates.</p>
                <p><strong>Technologies:</strong> Vue.js</p>
            </article>
        </section>

        <!-- Contact Section -->
        <section id="contact">
            <h2>Contact Me</h2>
            
            <div>
                <h3>Get In Touch</h3>
                <p>I'm currently available for freelance work and full-time opportunities.</p>
                
                <address>
                    <p><strong>Location:</strong> Pune Maharashtra </p>
                    <p><strong>Email:</strong> <a href="mailto:aarohiitapas17@gmail.com">aarohiitapas17@gmail.com</a></p>
                    <p><strong>Phone:</strong> <a href="tel:+919309804210">+919309804210</a></p>
                </address>
                
                <h4>Social Media</h4>
                <ul>
                    <li><a href="https://github.com" target="_blank">GitHub</a></li>
                    <li><a href="https://linkedin.com" target="_blank">LinkedIn</a></li>
                    <li><a href="https://twitter.com" target="_blank">Twitter</a></li>
                </ul>
            </div>
            
            <div>
                <h3>Send Me a Message</h3>
                <form id="contactForm" action="#" method="post">
                    <fieldset>
                        <legend>Contact Form</legend>
                        
                        <div>
                            <label for="name">Your Name:</label>
                            <input type="text" id="name" name="name" placeholder="Enter your name" required>
                        </div>
                        
                        <div>
                            <label for="email">Your Email:</label>
                            <input type="email" id="email" name="email" placeholder="Enter your email" required>
                        </div>
                        
                        <div>
                            <label for="subject">Subject:</label>
                            <input type="text" id="subject" name="subject" placeholder="Enter subject" required>
                        </div>
                        
                        <div>
                            <label for="message">Your Message:</label>
                            <textarea id="message" name="message" placeholder="Enter your message" rows="6" required></textarea>
                        </div>
                        
                        <div>
                            <label for="contact-method">Preferred Contact Method:</label>
                            <select id="contact-method" name="contact-method">
                                <option value="email">Email</option>
                                <option value="phone">Phone</option>
                            </select>
                        </div>
                        
                        <div>
                            <label>
                                <input type="checkbox" name="newsletter" checked>
                                Subscribe to newsletter
                            </label>
                        </div>
                        
                        <div>
                            <button type="submit">Send Message</button>
                            <button type="reset">ClearForm</button>
                        </div>
                    </fieldset>
                </form>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer>
        <div>
            <p>&copy; 2025 Aarohi Tapas. All rights reserved.</p>
            <p>Portfolio Website | Built with HTML5</p>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#skills">Skills</a></li>
                    <li><a href="#contact">Contact</a></li>
                    <li><a href="#projects">Projects</a></li>
                </ul>
            </nav>
            <p><a href="#home">Back to Top</a></p>
        </div>
    </footer>
</body>
</html>
