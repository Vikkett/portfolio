<template>
  <div>
    <!-- NAV -->
    <nav>
      <a href="#hero" class="nav-logo">
        VV<span>.</span>
      </a>

      <ul class="nav-links">
        <li><a href="#projects">Projects</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>

    <!-- HERO -->
    <section
      id="hero"
      style="max-width: none; padding-top: 0;"
    >
      <canvas id="particles"></canvas>

      <div class="hero-inner">
        <div class="hero-tag">
          Available for new opportunities
        </div>

        <h1>
          Viktoriia<br>
          <span class="accent">Varennyk</span>
        </h1>

        <p class="hero-sub">
          Full-Stack Developer & AI Integration Engineer.
          I've been coding since I was 15 — building real
          products, working with real clients, and shipping
          code that actually lives on the internet.
        </p>

        <div class="hero-cta">
          <a href="#projects" class="btn btn-primary">
            See my work ↓
          </a>

          <a href="#contact" class="btn btn-ghost">
            Get in touch
          </a>
        </div>

        <div class="hero-stats">
          <div class="stat-item">
            <div class="stat-num">
              3<span>+</span>
            </div>
            <div class="stat-label">
              Years coding
            </div>
          </div>

          <div class="stat-item">
            <div class="stat-num">
              4<span>+</span>
            </div>
            <div class="stat-label">
              Languages spoken
            </div>
          </div>

          <div class="stat-item">
            <div class="stat-num">
              1<span>↗</span>
            </div>
            <div class="stat-label">
              Live site shipped
            </div>
          </div>

          <div class="stat-item">
            <div class="stat-num">∞</div>
            <div class="stat-label">
              Things to build
            </div>
          </div>
        </div>
      </div>
    </section>

    <hr class="full-divider">

    <!-- PROJECTS -->
    <section id="projects">
      <p class="section-label">
        What I've built
      </p>

      <h2>Projects</h2>

      <p class="section-intro">
        From AI-powered apps to 3D experiences and client
        websites — here's what I've shipped.
      </p>

      <div class="projects-grid">

        <div class="project-card">
          <span class="project-tag">
            AI · Full-Stack
          </span>

          <h3>AI Web Assistant</h3>

          <p>
            Full-stack web app with a real-time AI assistant.
            Integrated an LLM via API, engineered prompt
            management and streaming responses. Built solo —
            database, backend, frontend, and AI layer.
          </p>

          <div class="project-tech">
            <span class="tech-pill">JavaScript</span>
            <span class="tech-pill">REST API</span>
            <span class="tech-pill">SQL</span>
            <span class="tech-pill">CSS3</span>
          </div>
        </div>

        <div class="project-card">
          <span class="project-tag">
            3D · WebGL
          </span>

          <h3>Interactive 3D Web Component</h3>

          <p>
            Built interactive 3D elements rendered directly
            in the browser using WebGL and Three.js. Focused
            on performance optimisation and delivering smooth,
            visually engaging experiences.
          </p>

          <div class="project-tech">
            <span class="tech-pill">Three.js</span>
            <span class="tech-pill">WebGL</span>
            <span class="tech-pill">JavaScript</span>
          </div>
        </div>

        <div class="project-card">
          <span class="project-tag">
            Live · Client Work
          </span>

          <h3>Live Website</h3>

          <p>
            Designed, built, and deployed a fully functional
            website that's been online since 2023. Handles
            ongoing maintenance, performance updates, and
            feature iterations post-launch.
          </p>

          <div class="project-tech">
            <span class="tech-pill">HTML5</span>
            <span class="tech-pill">CSS3</span>
            <span class="tech-pill">JavaScript</span>
            <span class="tech-pill">Deployment</span>
          </div>

          <a href="#contact" class="project-link">
            Ask me about it →
          </a>
        </div>

        <div class="project-card">
          <span class="project-tag">
            CRM · Enterprise
          </span>

          <h3>Salesforce CRM Setup</h3>

          <p>
            Set up and maintained a Salesforce database for
            a large-scale organisation. Managed data quality,
            record structuring, and regular sync with
            end-users — at 16 years old.
          </p>

          <div class="project-tech">
            <span class="tech-pill">Salesforce</span>
            <span class="tech-pill">SQL</span>
            <span class="tech-pill">CRM</span>
          </div>
        </div>

      </div>
    </section>

    <hr class="full-divider">

    <!-- SKILLS -->
    <section id="skills">
      <p class="section-label">
        What I work with
      </p>

      <h2>Skills</h2>

      <p class="section-intro">
        I pick up new tools in days — here's what's
        currently in my stack.
      </p>

      <div class="skills-grid">

        <div class="skill-group">
          <div class="skill-group-icon">🌐</div>
          <h4>Frontend</h4>

          <div class="skill-list">
            <div class="skill-item">HTML5 & CSS3</div>
            <div class="skill-item">JavaScript</div>
            <div class="skill-item">Responsive Design</div>
            <div class="skill-item">Three.js / WebGL</div>
          </div>
        </div>

        <div class="skill-group">
          <div class="skill-group-icon">⚙️</div>
          <h4>Backend & Data</h4>

          <div class="skill-list">
            <div class="skill-item">SQL (Databases)</div>
            <div class="skill-item">C#</div>
            <div class="skill-item">Kotlin</div>
            <div class="skill-item">Apache Server</div>
          </div>
        </div>

        <div class="skill-group">
          <div class="skill-group-icon">🤖</div>
          <h4>AI & Integration</h4>

          <div class="skill-list">
            <div class="skill-item">LLM Integration</div>
            <div class="skill-item">Prompt Engineering</div>
            <div class="skill-item">REST APIs</div>
            <div class="skill-item">Salesforce CRM</div>
          </div>
        </div>

        <div class="skill-group">
          <div class="skill-group-icon">🛠</div>
          <h4>Tooling</h4>

          <div class="skill-list">
            <div class="skill-item">Git & Versioning</div>
            <div class="skill-item">Technical Support</div>
            <div class="skill-item">Infrastructure</div>
            <div class="skill-item">Client Communication</div>
          </div>
        </div>

      </div>
    </section>

    <hr class="full-divider">

    <!-- ABOUT -->
    <section id="about">
      <p class="section-label">
        My story
      </p>

      <h2>About me</h2>

      <p class="section-intro">
        I started coding at 15, driven by curiosity.
        Since then I haven't stopped — building things,
        learning fast, and working with real clients
        before most people finish school.
      </p>

      <div
        style="
          display: grid;
          grid-template-columns: 1fr 1fr;
          gap: 4rem;
        "
      >

        <div class="timeline">

          <div class="timeline-item">
            <div class="timeline-dot"></div>
            <div class="timeline-date">
              2024 – 2026
            </div>
            <div class="timeline-title">
              CFC Informaticienne — CPNV
            </div>
            <div class="timeline-sub">
              Application Development. Accelerated 2-year
              programme. Final project: full-stack AI app.
            </div>
          </div>

          <div class="timeline-item">
            <div class="timeline-dot"></div>
            <div class="timeline-date">
              2023 – 2024
            </div>
            <div class="timeline-title">
              Technical Pre-Apprenticeship — ETML
            </div>
            <div class="timeline-sub">
              IT internship (C#, Apache, HTML/CSS) +
              automation internship.
            </div>
          </div>

          <div class="timeline-item">
            <div class="timeline-dot"></div>
            <div class="timeline-date">
              2022 – 2025
            </div>
            <div class="timeline-title">
              CRM Administrator — Salesforce
            </div>
            <div class="timeline-sub">
              Enterprise database setup and maintenance.
              Real professional environment, real responsibility.
            </div>
          </div>

          <div class="timeline-item">
            <div class="timeline-dot"></div>
            <div class="timeline-date">
              Oct 2022
            </div>
            <div class="timeline-title">
              École 42 Renens — Bootcamp
            </div>
            <div class="timeline-sub">
              Built a full website from scratch in one week.
            </div>
          </div>

          <div class="timeline-item">
            <div class="timeline-dot"></div>
            <div class="timeline-date">
              2022
            </div>
            <div class="timeline-title">
              Arrived in Switzerland
            </div>
            <div class="timeline-sub">
              From Ukraine to Vaud — C1 French & English
              in under a year.
            </div>
          </div>

        </div>

        <div>

          <p
            style="
              color: var(--muted);
              font-size: 0.95rem;
              line-height: 1.8;
              margin-bottom: 1.5rem;
            "
          >
            Originally from Ukraine, I moved to Switzerland
            at 16 and threw myself into the local tech scene
            before I even had fluent French. I absorb new
            languages and frameworks the same way.
          </p>

          <p
            style="
              color: var(--muted);
              font-size: 0.95rem;
              line-height: 1.8;
              margin-bottom: 2rem;
            "
          >
            I'm at my best when I have full ownership of a
            project — from first sketch to deployed code.
            I'm also genuinely easy to work with: I explain
            tech clearly, I listen to clients, and I follow through.
          </p>

          <h4
            style="
              font-family: 'Space Grotesk', sans-serif;
              font-size: 0.9rem;
              color: var(--white);
              margin-bottom: 1rem;
              letter-spacing: 0.05em;
              text-transform: uppercase;
            "
          >
            Languages
          </h4>

          <div
            class="lang-grid"
            style="margin-top: 0;"
          >
            <div class="lang-badge">
              <strong>🇺🇦</strong>
              Ukrainian — Native
            </div>

            <div class="lang-badge">
              <strong>🇷🇺</strong>
              Russian — Native
            </div>

            <div class="lang-badge">
              <strong>🇫🇷</strong>
              French — C1
            </div>

            <div class="lang-badge">
              <strong>🇬🇧</strong>
              English — C1
            </div>
          </div>

        </div>

      </div>
    </section>

    <hr class="full-divider">

    <!-- CONTACT -->
    <section id="contact">

      <p class="section-label">
        Let's talk
      </p>

      <h2>Get in touch</h2>

      <p
        class="section-intro"
        style="
          margin: 0 auto 3rem;
          text-align: center;
        "
      >
        Open to freelance work, internships, and full-time
        roles. I respond fast.
      </p>

      <div class="contact-card">

        <p
          style="
            color: var(--muted);
            font-size: 0.9rem;
          "
        >
          Send me an email
        </p>

        <a
          href="mailto:vikavarennik@icloud.com"
          class="contact-email"
        >
          varennikvika@gmail.com
        </a>

        <p class="contact-meta">
          +41 78 621 19 35 &nbsp;·&nbsp;
          Moudon, Switzerland
        </p>

        <p
          class="contact-meta"
          style="margin-top: 0.5rem;"
        >
          Permit S &nbsp;·&nbsp; Available now
        </p>

      </div>

    </section>

    <footer>
      <p>
        Built with intention by Viktoriia Varennyk
        &nbsp;·&nbsp; 2025
      </p>
    </footer>
  </div>
</template>