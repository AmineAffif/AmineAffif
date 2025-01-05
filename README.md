<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Amine - Searching for a New Adventure</title>
  <style>
    /* GLOBAL STYLES */
    * {
      margin: 0; padding: 0; box-sizing: border-box; 
    }
    body {
      font-family: sans-serif; 
      background-color: #000; 
      color: #fff;
      line-height: 1.5;
    }
    a {
      color: #4FD1C5; 
      text-decoration: none;
    }

    /* WRAPPER */
    .container {
      max-width: 1200px;
      margin: 0 auto;
      padding: 2rem;
    }

    /* HEADER / INTRO */
    header {
      text-align: center;
      margin-bottom: 3rem;
    }
    header h1 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
    }
    header p {
      font-size: 1.1rem;
      color: #CBD5E0;
      margin-bottom: 1rem;
    }

    /* SECTION TITLES */
    .section-title {
      font-size: 2rem;
      margin: 2rem 0 1.5rem;
      color: #E2E8F0;
      text-align: center;
    }

    /* ABOUT SECTION */
    .about {
      text-align: center;
      margin-bottom: 2rem;
      color: #A0AEC0;
    }

    /* EXPERIENCES */
    .experiences-section {
      margin-top: 3rem;
    }
    .experiences-grid {
      display: flex;
      flex-wrap: wrap;
      gap: 1rem;
      justify-content: center;
    }
    .experience-card {
      flex: 0 1 350px; 
      background: linear-gradient(to bottom right, #2D3748, #1A202C);
      padding: 1.5rem;
      border-radius: 0.5rem;
      transition: all 0.3s ease;
      box-shadow: 0 0 10px rgba(0,0,0,0.3);
    }
    .experience-card:hover {
      transform: scale(1.02);
      background: linear-gradient(to bottom right, #4A5568, #2D3748);
    }
    .experience-card h3 {
      font-size: 1.2rem;
      margin-bottom: 0.5rem;
      color: #81E6D9;
    }
    .experience-card h4 {
      font-size: 1rem;
      margin-bottom: 0.2rem;
      color: #FBB6CE;
    }
    .experience-card .period {
      font-size: 0.9rem;
      color: #A0AEC0;
      margin-bottom: 1rem;
    }
    .experience-card p {
      font-size: 0.9rem;
      color: #E2E8F0;
      line-height: 1.4;
      margin-bottom: 1rem;
    }
    .experience-card ul {
      margin: 0.5rem 0 1rem 1.4rem;
      list-style-type: disc;
      color: #CBD5E0;
      font-size: 0.88rem;
    }
    .skills-list {
      display: flex;
      flex-wrap: wrap;
      gap: 0.5rem;
    }
    .skill {
      background-color: #4A5568;
      padding: 0.3rem 0.6rem;
      border-radius: 0.3rem;
      font-size: 0.8rem;
      color: #fff;
    }

    /* TOOLS SECTION */
    .tools-section {
      margin-top: 3rem;
    }
    .tools-grid-title {
      font-size: 1.25rem;
      font-weight: 600;
      margin: 1.5rem 0 1rem;
      text-align: left;
      color: #E2E8F0;
    }
    .tools-grid {
      display: flex;
      flex-wrap: wrap;
      gap: 1rem;
      justify-content: flex-start;
    }
    .tool-card {
      flex: 0 1 120px; 
      display: flex;
      flex-direction: column;
      align-items: center;
      text-align: center;
      padding: 1rem;
      border-radius: 0.5rem;
      background: linear-gradient(to bottom right, #2D3748, #1A202C);
      transition: all 0.2s ease-in-out;
    }
    .tool-card:hover {
      transform: scale(1.05);
      background: linear-gradient(to bottom right, #4A5568, #2D3748);
    }
    .tool-card img {
      width: 40px;
      height: 40px;
      object-fit: contain;
      margin-bottom: 0.5rem;
    }
    .tool-name {
      font-size: 0.875rem;
      color: #E2E8F0;
    }

    /* FOOTER */
    footer {
      margin-top: 3rem;
      text-align: center;
      font-size: 0.9rem;
      color: #A0AEC0;
    }
    footer a {
      color: #63B3ED;
    }
  </style>
</head>
<body>

  <div class="container">

    <!-- HEADER -->
    <header>
      <h1>Amine — Fullstack Developer</h1>
      <p>In search of a new adventure. Combining web/mobile dev, design, and marketing to build solutions that matter!</p>
    </header>

    <!-- ABOUT -->
    <div class="about">
      <p>
        Passionate about delivering end-to-end solutions: from <strong>front-end</strong> user experiences 
        to <strong>back-end</strong> logic, with a pinch of <strong>design and marketing</strong> thrown in. 
        Currently open to new opportunities (Freelance, Full-Time, Remote, or On-Site). 
        Let’s talk if you need a <em>do-it-all dev</em> who can handle challenges from 
        <strong>React Native</strong> to <strong>After Effects</strong>!
      </p>
    </div>

    <!-- EXPERIENCES SECTION -->
    <section class="experiences-section">
      <h2 class="section-title">My Experiences</h2>
      <div class="experiences-grid">

        <!-- EXPERIENCE 1: GYRA -->
        <div class="experience-card">
          <h3>Développeur Web/Mobile (Agency) - Stage</h3>
          <h4>GYRA</h4>
          <div class="period">2021</div>
          <p>
            Conception and deployment of React Native mobile apps and web platforms (React). 
            Drafting technical specs, engaging with clients, and managing multiple parallel projects.
          </p>
          <ul>
            <li>React Native apps (conception, testing, deployment)</li>
            <li>Business-oriented web platforms (React, Laravel)</li>
            <li>Technical proposals to clients</li>
            <li>Time management across parallel projects</li>
          </ul>
          <div class="skills-list">
            <span class="skill">React Native</span>
            <span class="skill">React</span>
            <span class="skill">Laravel PHP</span>
            <span class="skill">Conception technique</span>
            <span class="skill">Déploiement</span>
            <span class="skill">Gestion de projet</span>
            <span class="skill">Relation client</span>
          </div>
        </div>

        <!-- EXPERIENCE 2: StudyCall -->
        <div class="experience-card">
          <h3>Fullstack Developer (Callcenter 2.0) - Alternance</h3>
          <h4>StudyCall</h4>
          <div class="period">2023</div>
          <p>
            Building innovative web solutions (Ruby on Rails), integrating AI, 
            and optimizing infrastructure costs. 
            Handling incidents, training new hires, and refactoring for cost reduction.
          </p>
          <ul>
            <li>Ruby on Rails, HTML/CSS/JS</li>
            <li>Infrastructure cost optimization</li>
            <li>AI for automation & user simplification</li>
            <li>Incidents management & tasks</li>
            <li>Technical + functional trainings</li>
          </ul>
          <div class="skills-list">
            <span class="skill">Ruby on Rails</span>
            <span class="skill">Big Data</span>
            <span class="skill">Optimisation</span>
            <span class="skill">Automatisation</span>
            <span class="skill">GitHub Actions</span>
          </div>
        </div>

        <!-- EXPERIENCE 3: Cévidentia -->
        <div class="experience-card">
          <h3>Fullstack Developer (Optician 2.0) - Alternance</h3>
          <h4>Cévidentia</h4>
          <div class="period">2024</div>
          <p>
            Building & maintaining Rails + Next.js platforms, focusing on performance, 
            agile methods, and design patterns. 
            Working closely with senior devs and product teams.
          </p>
          <ul>
            <li>Ruby on Rails + Next.js</li>
            <li>Adaptation to fast business growth</li>
            <li>Agile dev cycle + CI/CD processes</li>
            <li>UX/UI collaboration</li>
          </ul>
          <div class="skills-list">
            <span class="skill">Ruby on Rails</span>
            <span class="skill">Next.js</span>
            <span class="skill">CI/CD</span>
            <span class="skill">UX/UI</span>
            <span class="skill">Production</span>
            <span class="skill">Agile</span>
          </div>
        </div>

        <!-- EXPERIENCE 4: L'Etudiant -->
        <div class="experience-card">
          <h3>Fullstack Dev (EdTech) - Alternance</h3>
          <h4>L'Étudiant - StudyAdvisor</h4>
          <div class="period">2022</div>
          <p>
            Dynamic solutions, technical & functional management, agile methods, user immersion. 
            Using Ruby on Rails + React Native to meet business and user needs.
          </p>
          <ul>
            <li>Rails + React Native, HTML/CSS/JS</li>
            <li>Agile + user feedback loops</li>
            <li>Project management across multiple teams</li>
          </ul>
          <div class="skills-list">
            <span class="skill">Ruby on Rails</span>
            <span class="skill">React Native</span>
            <span class="skill">JavaScript</span>
            <span class="skill">Gestion de projet</span>
            <span class="skill">User Immersion</span>
            <span class="skill">Agile</span>
          </div>
        </div>

        <!-- EXPERIENCE 5: DreamLocation (Freelance) -->
        <div class="experience-card">
          <h3>Web Dev ❤️ Freelance</h3>
          <h4>DreamLocation</h4>
          <div class="period">2025</div>
          <p>
            A full platform for a car rental company: secure payments, real-time availability, 
            loyalty systems, advanced automation (emails, CRON), and more.
          </p>
          <ul>
            <li>Stripe integration (down payments or full payments)</li>
            <li>Intelligent reservation system (live calendar)</li>
            <li>Modular loyalty program + RGPD compliance</li>
            <li>Photoshop design & landing pages</li>
          </ul>
          <div class="skills-list">
            <span class="skill">Next.js</span>
            <span class="skill">Firebase</span>
            <span class="skill">Stripe API</span>
            <span class="skill">Automations</span>
            <span class="skill">RGPD Compliance</span>
            <span class="skill">Design UI/UX</span>
            <span class="skill">Photoshop</span>
          </div>
        </div>

        <!-- EXPERIENCE 6: Evalawrens (Freelance) -->
        <div class="experience-card">
          <h3>Web Dev/Graphiste ❤️ Freelance</h3>
          <h4>Evalawrens</h4>
          <div class="period">2023</div>
          <p>
            Launched a facial cleansing brushes brand—covering branding, e-commerce (WordPress/WooCommerce + CRM), 
            video ads (After Effects), and marketing campaigns to reach break-even quickly.
          </p>
          <ul>
            <li>Creative branding, visuals akin to L'Oréal or Nivea</li>
            <li>Video production w/ After Effects</li>
            <li>Automated order flow connected to supplier</li>
            <li>Facebook Ads, TikTok, overall digital marketing</li>
          </ul>
          <div class="skills-list">
            <span class="skill">WordPress</span>
            <span class="skill">WooCommerce</span>
            <span class="skill">CRM</span>
            <span class="skill">Marketing</span>
            <span class="skill">Photoshop</span>
            <span class="skill">After Effects</span>
          </div>
        </div>

      </div>
    </section>

    <!-- TOOLS SECTION -->
    <section class="tools-section">
      <h2 class="section-title">My Tools</h2>

      <!-- Example Category: LANGUAGES -->
      <h3 class="tools-grid-title">Languages</h3>
      <div class="tools-grid">
        <!-- TypeScript Card -->
        <div class="tool-card">
          <img 
            src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-plain.svg"
            alt="TypeScript"
          />
          <span class="tool-name">TypeScript</span>
        </div>
        <!-- JavaScript Card -->
        <div class="tool-card">
          <img 
            src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg"
            alt="JavaScript"
          />
          <span class="tool-name">JavaScript</span>
        </div>
        <!-- Ruby Card -->
        <div class="tool-card">
          <img 
            src="https://raw.githubusercontent.com/devicons/devicon/master/icons/ruby/ruby-plain.svg"
            alt="Ruby"
          />
          <span class="tool-name">Ruby</span>
        </div>
        <!-- Python Card -->
        <div class="tool-card">
          <img 
            src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg"
            alt="Python"
          />
          <span class="tool-name">Python</span>
        </div>
        <!-- C++ Card -->
        <div class="tool-card">
          <img 
            src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-plain.svg"
            alt="C++"
          />
          <span class="tool-name">C++</span>
        </div>
        <!-- PHP Card -->
        <div class="tool-card">
          <img 
            src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg"
            alt="PHP"
          />
          <span class="tool-name">PHP</span>
        </div>
      </div>

      <!-- Example Category: FRAMEWORK -->
      <h3 class="tools-grid-title">Framework</h3>
      <div class="tools-grid">
        <!-- Next.js -->
        <div class="tool-card">
          <img
            src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nextjs/nextjs-original.svg"
            alt="Next.js"
          />
          <span class="tool-name">Next.js</span>
        </div>
        <!-- React -->
        <div class="tool-card">
          <img 
            src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg"
            alt="React"
          />
          <span class="tool-name">React</span>
        </div>
        <!-- Rails -->
        <div class="tool-card">
          <img 
            src="https://raw.githubusercontent.com/devicons/devicon/master/icons/rails/rails-plain.svg"
            alt="Ruby on Rails"
          />
          <span class="tool-name">Ruby on Rails</span>
        </div>
        <!-- React Native -->
        <div class="tool-card">
          <img 
            src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg"
            alt="React Native"
          />
          <span class="tool-name">React Native</span>
        </div>
        <!-- Laravel -->
        <div class="tool-card">
          <img 
            src="https://raw.githubusercontent.com/devicons/devicon/master/icons/laravel/laravel-plain.svg"
            alt="Laravel"
          />
          <span class="tool-name">Laravel</span>
        </div>
        <!-- NestJS -->
        <div class="tool-card">
          <img 
            src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nestjs/nestjs-plain.svg"
            alt="NestJS"
          />
          <span class="tool-name">NestJS</span>
        </div>
        <!-- Tailwind CSS -->
        <div class="tool-card">
          <img 
            src="https://raw.githubusercontent.com/devicons/devicon/master/icons/tailwindcss/tailwindcss-plain.svg"
            alt="Tailwind CSS"
          />
          <span class="tool-name">Tailwind CSS</span>
        </div>
      </div>

      <!-- Tools Category -->
      <h3 class="tools-grid-title">Tools</h3>
      <div class="tools-grid">
        <!-- Docker -->
        <div class="tool-card">
          <img 
            src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg"
            alt="Docker"
          />
          <span class="tool-name">Docker</span>
        </div>
        <!-- Git -->
        <div class="tool-card">
          <img 
            src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg"
            alt="Git"
          />
          <span class="tool-name">Git</span>
        </div>
        <!-- WordPress -->
        <div class="tool-card">
          <img 
            src="https://raw.githubusercontent.com/devicons/devicon/master/icons/wordpress/wordpress-plain.svg"
            alt="WordPress"
          />
          <span class="tool-name">WordPress</span>
        </div>
      </div>

      <!-- Design Category -->
      <h3 class="tools-grid-title">Design</h3>
      <div class="tools-grid">
        <!-- Photoshop -->
        <div class="tool-card">
          <img 
            src="https://res.cloudinary.com/dqhp7mt1b/image/upload/v1736116158/photoshop_logo_1_sdvvol.webp"
            alt="Photoshop"
          />
          <span class="tool-name">Photoshop</span>
        </div>
        <!-- After Effects -->
        <div class="tool-card">
          <img 
            src="https://res.cloudinary.com/dqhp7mt1b/image/upload/v1736116157/ae_logo_1_p63gd6.webp"
            alt="After Effects"
          />
          <span class="tool-name">After Effects</span>
        </div>
      </div>

      <!-- Cloud Category -->
      <h3 class="tools-grid-title">Cloud</h3>
      <div class="tools-grid">
        <!-- Firebase -->
        <div class="tool-card">
          <img 
            src="https://raw.githubusercontent.com/devicons/devicon/master/icons/firebase/firebase-plain.svg"
            alt="Firebase"
          />
          <span class="tool-name">Firebase</span>
        </div>
        <!-- Cloudinary -->
        <div class="tool-card">
          <img 
            src="https://raw.githubusercontent.com/devicons/devicon/master/icons/googlecloud/googlecloud-plain.svg"
            alt="Cloudinary placeholder"
          />
          <span class="tool-name">Cloudinary</span>
        </div>
        <!-- Vercel -->
        <div class="tool-card">
          <img 
            src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vercel/vercel-original.svg"
            alt="Vercel"
          />
          <span class="tool-name">Vercel</span>
        </div>
        <!-- Stripe -->
        <div class="tool-card">
          <img 
            src="https://res.cloudinary.com/dqhp7mt1b/image/upload/v1736116618/stripe_logo_1_fuqwrn.webp"
            alt="Stripe"
          />
          <span class="tool-name">Stripe</span>
        </div>
      </div>

      <!-- Other Category -->
      <h3 class="tools-grid-title">Other</h3>
      <div class="tools-grid">
        <!-- ESP32 -->
        <div class="tool-card">
          <img 
            src="https://raw.githubusercontent.com/devicons/devicon/master/icons/arduino/arduino-original.svg"
            alt="ESP32 placeholder"
          />
          <span class="tool-name">ESP32</span>
        </div>
        <!-- CI/CD -->
        <div class="tool-card">
          <img 
            src="https://raw.githubusercontent.com/devicons/devicon/master/icons/github/github-original.svg"
            alt="CI/CD placeholder"
          />
          <span class="tool-name">CI/CD</span>
        </div>
        <!-- Arduino -->
        <div class="tool-card">
          <img 
            src="https://raw.githubusercontent.com/devicons/devicon/master/icons/arduino/arduino-original.svg"
            alt="Arduino"
          />
          <span class="tool-name">Arduino</span>
        </div>
      </div>

    </section>

    <!-- FOOTER -->
    <footer>
      <p>© 2024 Amine - Fullstack Developer. 
        <br />
        <a href="https://www.linkedin.com/in/amine-affif/" target="_blank">LinkedIn</a> | 
        <a href="https://stackoverflow.com/users/13263501/amine-affif" target="_blank">Stack Overflow</a> | 
        <a href="https://www.behance.net/amineaffif" target="_blank">Behance</a> | 
        <a href="https://www.youtube.com/channel/UC4XMGyb4tcoei9U_K7BM5eA" target="_blank">YouTube</a>
      </p>
    </footer>

  </div> <!-- /container -->

</body>
</html>
