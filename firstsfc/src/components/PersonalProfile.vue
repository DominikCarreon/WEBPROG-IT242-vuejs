<template>
<body>

  <header>
    <div class="nav">
      <div class="logo">
      <span class="doms">DOM'S</span> PORTFOLIO.
      </div>
      <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
      </nav>
    </div>
  </header>

  <section id="home" class="hero fade-up">
    <div class="hero-text">
      <h1>Hello, I'm <br><span>Dominik Carreon</span></h1>
      <p id="typing-desc" class="typing-cursor"></p>
      <a href="#contact" class="btn">Hire Me</a>
    </div>
    <div class="img-container">
      <img src="https://media.licdn.com/dms/image/v2/D4E03AQEAFJoPMNhcdQ/profile-displayphoto-shrink_800_800/B4EZWpOwHuGwAc-/0/1742300971993?e=1769040000&v=beta&t=euDLwqa6Zo3NQgEbIwNy1wC1a0PV43I0C-oigFPOCoc" alt="Dominik Carreon" class="profile-pic">
    </div>
  </section>

  <section id="about" class="about-section fade-up">
    <div class="section-header">
      <h2>About <span>Me</span></h2>
      <div class="line"></div>
    </div>

    <div class="about-container">
      <div class="about-left">
        <p class="bio-text">
          Motivated and creative Bachelor of Science in Information Technology student at Asia Pacific College, passionate about designing intuitive and visually engaging digital experiences. With a strong foundation in web technologies, user interface design, and user experience principles, I aim to bridge the gap between functionality and aesthetics in every project I work on.
        </p>

        <div class="details-grid">
          <div class="detail-item full-width">
            <h4>Name:</h4>
            <p>Dominik V Carreon</p>
          </div>
          <div class="detail-item">
            <h4>Location:</h4>
            <a href="https://www.google.com/maps?q=Pasay+City,+Malibay" target="_blank">Pasay City, Malibay</a>
          </div>
          <div class="detail-item">
            <h4>Availability:</h4>
            <p>Freelance</p>
          </div>
          <div class="detail-item full-width">
            <h4>Email:</h4>
            <p>Dominikcarreon123@gmail.com</p>
          </div>
        </div>
      </div>

      <div class="about-right">
        <div class="info-card">
          <h3>Education</h3>
          <ul>
            <li><span>📖</span> SHS Major in Information Technology, APC</li>
            <li><span>📖</span> B.S. Information in Technology, APC</li>
          </ul>
        </div>
        <div class="info-card">
          <h3>Certifications</h3>
          <ul>
            <li><span>★</span> Programming Foundations: Data Structures (2019)</li>
            <li><span>★</span> Python: Recursion</li>
            <li><span>★</span> Python Data Structures</li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <section id="skills" class="skills-section fade-up">
    <div class="skills-header">
      <h2>My <span>Skills</span></h2>
      <div class="line"></div>
      <p class="skills-description">
        I have growing experience in UI/UX design, prototyping, and web projects, using tools like Figma and Canva to create simple, user-friendly designs and layouts.
      </p>
    </div>

    <div class="skills-grid">
      <div class="card skill-card">
        <div class="icon-box red-glow"><span>&lt;/&gt;</span></div>
        <h3>Frontend Development</h3>
        <p class="tech-stack">HTML, CSS, JavaScript</p>
        <div class="progress-wrapper">
          <div class="progress-track"><div class="progress-fill" style="width: 50%"></div></div>
          <span class="percentage">50%</span>
        </div>
      </div>

      <div class="card skill-card">
        <div class="icon-box yellow-glow"><span>✒️</span></div>
        <h3>UI/UX Design</h3>
        <p class="tech-stack">Figma, Canva</p>
        <div class="progress-wrapper">
          <div class="progress-track"><div class="progress-fill" style="width: 50%"></div></div>
          <span class="percentage">50%</span>
        </div>
      </div>

      <div class="card skill-card">
        <div class="icon-box red-glow"><span>🗄️</span></div>
        <h3>Database Management</h3>
        <p class="tech-stack">MySQL, Firebase</p>
        <div class="progress-wrapper">
          <div class="progress-track"><div class="progress-fill" style="width: 50%"></div></div>
          <span class="percentage">50%</span>
        </div>
      </div>

      <div class="card skill-card">
        <div class="icon-box yellow-glow"><span>👥</span></div>
        <h3>Team Collaboration</h3>
        <p class="tech-stack">Git, Agile, Scrum, Project Management</p>
        <div class="progress-wrapper">
          <div class="progress-track"><div class="progress-fill" style="width: 50%"></div></div>
          <span class="percentage">50%</span>
        </div>
      </div>
    </div>
  </section>

  <section id="projects" class="projects-section fade-up">
    <div class="projects-header">
      <h2>My <span>Projects</span></h2>
      <div class="line"></div>
      <p class="projects-description">Explore my recent work across various domains and technologies.</p>
    </div>

    <div class="projects-grid">
      <div class="card project-card">
        <img src="Images/RamsResNow.png" alt="RamsResNow">
        <div class="project-header">
          <h3>RamsResNow</h3>
          <span class="badge">Web App</span>
        </div>
        <p class="project-desc">A simplified reservation system designed for everyone's use.</p>
        <div class="tags">
          <span>Figma</span><span>MySQL</span><span>Reservation</span><span>APC Admins</span>
        </div>
      </div>

      <div class="card project-card">
        <img src="Images/Sarisari.png" alt="Sari-Sari Trade">
        <div class="project-header">
          <h3>The Sari-Sari Trade</h3>
          <span class="badge">Web App</span>
        </div>
        <p class="project-desc">The Sari-Sari Trade System allows residents to trade food items.</p>
        <div class="tags">
          <span>Figma</span><span>Canva</span><span>Brgy's</span><span>Firebase</span>
        </div>
      </div>
    </div>
  </section>

  <section id="contact" class="contact-section fade-up">
    <div class="contact-header">
      <h2>Get In <span>Touch</span></h2>
      <div class="line"></div>
      <p class="contact-desc">Have a project in mind or want to collaborate? Feel free to reach out!</p>
    </div>

    <div class="contact-info-row">
      <div class="contact-item">
        <div class="icon-box red-box"><span>📍</span></div>
        <div class="contact-text">
          <h4>Location</h4>
          <a href="https://www.google.com/maps?q=Pasay+City,+Malibay" target="_blank">Pasay City, Malibay</a>
        </div>
      </div>
      <div class="contact-item">
        <div class="icon-box yellow-box"><span>✉️</span></div>
        <div class="contact-text">
          <h4>Email</h4>
          <a href="mailto:dvcarreon@student.apc.edu.ph">dvcarreon@student.apc.edu.ph</a>
        </div>
      </div>
      <div class="contact-item">
        <div class="icon-box orange-box"><span>📞</span></div>
        <div class="contact-text">
          <h4>Phone</h4>
          <p>+69 0911223345</p>
        </div>
      </div>
    </div>

    <div class="social-section">
      <h4>Follow Me</h4>
      <div class="social-icons">
        <a href="https://www.facebook.com/dominik.carreon" target="_blank" class="social-circle">f</a>
        <a href="https://x.com/" target="_blank" class="social-circle">𝕏</a>
        <a href="https://www.linkedin.com/in/dominik-carreon-9990012aa/" target="_blank" class="social-circle">in</a>
        <a href="https://github.com/DominikCarreon" target="_blank" class="social-circle">Git</a>
      </div>
    </div>
  </section>

  <footer>
    © 2026 Dominik Carreon. All rights reserved.
  </footer>

  <script>

    document.querySelectorAll('nav a[href^="#"]').forEach(anchor => {
        anchor.addEventListener('click', function (e) {
            e.preventDefault();
            const targetId = this.getAttribute('href');
            const targetSection = document.querySelector(targetId);
            
            if (targetSection) {
                targetSection.scrollIntoView({
                    behavior: 'smooth',
                    block: 'start'
                });
            }
        });
    });

    const observer = new IntersectionObserver((entries) => {
      entries.forEach((entry) => {
        if (entry.isIntersecting) {
          entry.target.classList.add('visible');
        }
      });
    }, {
      threshold: 0.1 
    });

    document.querySelectorAll('.fade-up').forEach((el) => observer.observe(el));
  </script>


  <script>
    document.addEventListener("DOMContentLoaded", function() {
        
        document.querySelectorAll('nav a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const targetId = this.getAttribute('href');
                const targetSection = document.querySelector(targetId);
                if (targetSection) {
                    targetSection.scrollIntoView({ behavior: 'smooth', block: 'start' });
                }
            });
        });

        const observer = new IntersectionObserver((entries) => {
            entries.forEach((entry) => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('visible');
                }
            });
        }, { threshold: 0.1 });

        document.querySelectorAll('.fade-up').forEach((el) => observer.observe(el));

        const typingElement = document.getElementById('typing-desc');

        if (typingElement) {
            const textPart1 = "Student at Asia Pacific College with passion for frontend development,";
            const textPart2 = " UI/UX design, and modern web technologies.";
            const fullText = textPart1 + textPart2;
            
            let charIndex = 0;

            function typeWriter() {
                if (charIndex < fullText.length) {
                    if (charIndex === textPart1.length) {
                        typingElement.innerHTML += "<br>";
                    }
                    
                    typingElement.innerHTML += fullText.charAt(charIndex);
                    charIndex++;
                    setTimeout(typeWriter, 25); 
                }
            }

            setTimeout(typeWriter, 500);
        }
    });
</script>
</template>


<script>

document.querySelectorAll('nav a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
        e.preventDefault();

        const targetId = this.getAttribute('href');
        const targetSection = document.querySelector(targetId);

        if (targetSection) {
            targetSection.scrollIntoView({
                behavior: 'smooth',
                block: 'start'
            });
        }
    });
});

</script>

<style src="./css/PersonlProfile.css"></style>
  