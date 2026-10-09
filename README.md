# swaraj-salesforce
Salesforce project ' Employee Leave Management System '

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Salesforce Developer Portfolio</title>
  <meta name="description" content="Salesforce developer portfolio, projects and resume.">
  <style>
    * { box-sizing: border-box; }
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f4f7fb;
      color: #202b3c;
      line-height: 1.6;
    }
    header {
      background: #102a43;
      color: white;
      padding: 18px 8%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
      gap: 12px;
    }
    header a { color: white; text-decoration: none; margin-left: 16px; }
    .hero {
      background: #e4f1ff;
      text-align: center;
      padding: 65px 20px;
    }
    .hero h1 { font-size: 38px; margin: 0 0 10px; }
    .hero p { max-width: 650px; margin: 10px auto 24px; }
    .button {
      display: inline-block;
      padding: 11px 19px;
      margin: 5px;
      background: #0967b2;
      color: white;
      text-decoration: none;
      border-radius: 7px;
    }
    .button.secondary { background: #102a43; }
    main { max-width: 1000px; margin: auto; padding: 20px; }
    section { padding: 30px 0; }
    h2 { color: #075b9a; }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 18px;
    }
    .card {
      background: white;
      border-radius: 12px;
      padding: 22px;
      box-shadow: 0 3px 12px #102a4310;
    }
    .tag {
      display: inline-block;
      background: #e4f1ff;
      padding: 5px 10px;
      border-radius: 20px;
      margin: 4px;
      font-size: 14px;
    }
    footer {
      text-align: center;
      background: #102a43;
      color: white;
      padding: 24px;
    }
    footer a { color: white; }
    @media (max-width: 600px) {
      .hero h1 { font-size: 30px; }
      header { justify-content: center; }
      header a { margin: 0 7px; }
    }
  </style>
</head>
<body>
  <header>
    <strong>My Salesforce Portfolio</strong>
    <nav>
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#projects">Projects</a>
      <a href="#resume">Resume</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <div class="hero">
    <h1>Hello, I'm Swaraj Wade</h1>
    <p>Aspiring Salesforce Developer | Salesforce CRM | Flow Automation</p>
    <p>I build Salesforce projects focused on CRM configuration,
       business process automation, and reporting.</p>
    <a class="button" href="#projects">Explore My Projects</a>
    <a class="button secondary" href="resume.pdf" target="_blank">View My Resume</a>
  </div>

  <main>
    <section id="about">
      <h2>About Me</h2>
      <div class="card">
        <p>I am an aspiring Salesforce professional developing practical
        skills in Salesforce configuration, declarative automation,
        validation, approval processes, and reports. I use personal
        projects to apply what I learn to realistic business scenarios.</p>
      </div>
    </section>

    <section id="skills">
      <h2>Technical Skills</h2>
      <div class="card">
        <span class="tag">Salesforce CRM</span>
        <span class="tag">Custom Objects & Fields</span>
        <span class="tag">Record-Triggered Flows</span>
        <span class="tag">Validation Rules</span>
        <span class="tag">Approval Processes</span>
        <span class="tag">Reports & Dashboards</span>
        <span class="tag">GitHub</span>
      </div>
    </section>

    <section id="projects">
      <h2>My Projects</h2>
      <div class="grid">
        <article class="card">
          <h3>Lead Management System</h3>
          <p><strong>Goal:</strong> Organize and prioritize sales leads.</p>
          <p><strong>Features:</strong> Automatic lead scoring based on
          lead attributes and automatic follow-up task creation for hot leads.</p>
          <p><strong>Tools:</strong> Salesforce CRM, custom fields,
          Record-Triggered Flows.</p>
          <p><em>Personal project. Screenshots and implementation details
          can be added here.</em></p>
        </article>
        <article class="card">
          <h3>Leave Management System</h3>
          <p><strong>Goal:</strong> Track employee leave requests.</p>
          <p><strong>Features:</strong> Leave-day calculation, date
          validation, approval workflow, and request reporting.</p>
          <p><strong>Tools:</strong> Custom objects, Flow, Validation
          Rules, Approval Processes, Reports.</p>
          <p><em>Personal project. Screenshots and implementation details
          can be added here.</em></p>
        </article>
      </div>
    </section>

    <section id="resume">
      <h2>My Resume</h2>
      <div class="card">
        <p>View or open my latest resume.</p>
        <a class="button" href="resume.pdf" target="_blank">Open Resume PDF</a>
      </div>
    </section>

    <section id="contact">
      <h2>Contact Me</h2>
      <div class="card">
        <p>Email: swarajwade6@gmail.com</p>
        <p>GitHub: <a href="https://github.com/YOUR-USERNAME">My GitHub Profile</a></p>
        <p>LinkedIn: https://www.linkedin.com/in/swaraj-wade/</p>
      </div>
    </section>
  </main>

  <footer>
    <p>Salesforce Developer Portfolio | Personal Projects</p>
  </footer>
</body>
</html>
