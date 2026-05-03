# Nuhawebsite

<!DOCTYPE html>

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Nuha Alkhathami | Economic Consultant & Public Policy Analyst</title>
<style>
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

body {
font-family: ‘Book Antiqua’, Palatino, ‘Palatino Linotype’, Georgia, serif;
background: #F3E3D0;
color: #81A6C6;
line-height: 1.8;
font-size: 17px;
}

.container {
max-width: 1100px;
margin: 0 auto;
padding: 0 40px;
}

/* HEADER */
header {
background: #F3E3D0;
padding: 30px 0;
border-bottom: 2px solid #81A6C6;
position: sticky;
top: 0;
z-index: 100;
}

header .container {
display: flex;
justify-content: space-between;
align-items: center;
}

.logo {
font-size: 22px;
font-weight: 600;
color: #1A3263;
text-decoration: none;
letter-spacing: 0.5px;
}

nav ul {
display: flex;
list-style: none;
gap: 35px;
}

nav a {
color: #81A6C6;
text-decoration: none;
font-size: 16px;
transition: color 0.3s;
font-weight: 500;
}

nav a:hover {
color: #1A3263;
}

/* HERO */
.hero {
padding: 100px 0 80px;
text-align: center;
}

.hero h1 {
font-size: 56px;
color: #1A3263;
margin-bottom: 20px;
font-weight: 600;
line-height: 1.2;
}

.hero .subtitle {
font-size: 22px;
color: #AACDDC;
margin-bottom: 15px;
font-weight: 400;
}

.hero .tagline {
font-size: 18px;
color: #81A6C6;
max-width: 750px;
margin: 0 auto 40px;
line-height: 1.7;
}

.hero-stats {
display: flex;
justify-content: center;
gap: 60px;
margin: 50px 0;
}

.stat-box {
text-align: center;
}

.stat-number {
font-size: 42px;
color: #1A3263;
font-weight: 600;
display: block;
margin-bottom: 8px;
}

.stat-label {
font-size: 15px;
color: #81A6C6;
}

.cta-button {
display: inline-block;
background: #1A3263;
color: #F3E3D0;
padding: 15px 40px;
text-decoration: none;
font-size: 16px;
border-radius: 5px;
transition: background 0.3s;
margin-top: 20px;
font-weight: 500;
}

.cta-button:hover {
background: #81A6C6;
}

/* SECTIONS */
section {
padding: 80px 0;
border-top: 1px solid #AACDDC;
}

section h2 {
font-size: 42px;
color: #1A3263;
margin-bottom: 40px;
text-align: center;
font-weight: 600;
}

/* ABOUT */
.about-content {
max-width: 850px;
margin: 0 auto;
text-align: center;
}

.about-intro {
font-size: 20px;
color: #1A3263;
margin-bottom: 30px;
font-weight: 500;
line-height: 1.6;
}

.about-text {
font-size: 17px;
color: #81A6C6;
margin-bottom: 20px;
text-align: left;
line-height: 1.8;
}

.strengths {
display: grid;
grid-template-columns: repeat(3, 1fr);
gap: 30px;
margin-top: 50px;
}

.strength-card {
background: rgba(26, 50, 99, 0.05);
padding: 30px 25px;
border-radius: 8px;
border-left: 4px solid #1A3263;
}

.strength-card h3 {
font-size: 19px;
color: #1A3263;
margin-bottom: 12px;
font-weight: 600;
}

.strength-card p {
font-size: 15px;
color: #81A6C6;
line-height: 1.6;
}

/* PROJECTS */
.projects-grid {
display: grid;
grid-template-columns: 1fr;
gap: 40px;
margin-top: 40px;
}

.project {
background: rgba(255, 255, 255, 0.4);
padding: 40px;
border-radius: 8px;
border-left: 5px solid #1A3263;
transition: transform 0.3s, box-shadow 0.3s;
}

.project:hover {
transform: translateY(-5px);
box-shadow: 0 8px 20px rgba(26, 50, 99, 0.15);
}

.project-header {
display: flex;
justify-content: space-between;
align-items: flex-start;
margin-bottom: 20px;
}

.project h3 {
font-size: 26px;
color: #1A3263;
margin-bottom: 10px;
font-weight: 600;
}

.project-tag {
background: #1A3263;
color: #F3E3D0;
padding: 6px 16px;
border-radius: 4px;
font-size: 13px;
font-weight: 500;
}

.project-context {
font-size: 16px;
color: #81A6C6;
margin-bottom: 20px;
font-style: italic;
}

.project-approach {
font-size: 16px;
color: #81A6C6;
margin-bottom: 20px;
}

.project-impact {
margin-top: 25px;
}

.project-impact h4 {
font-size: 17px;
color: #1A3263;
margin-bottom: 12px;
font-weight: 600;
}

.project-impact ul {
list-style: none;
padding-left: 0;
}

.project-impact li {
font-size: 15px;
color: #81A6C6;
margin-bottom: 8px;
padding-left: 25px;
position: relative;
}

.project-impact li::before {
content: “→”;
position: absolute;
left: 0;
color: #1A3263;
font-weight: 600;
}

.project-tools {
display: flex;
flex-wrap: wrap;
gap: 10px;
margin-top: 20px;
}

.tool-tag {
background: rgba(26, 50, 99, 0.1);
color: #1A3263;
padding: 5px 14px;
border-radius: 4px;
font-size: 13px;
font-weight: 500;
}

/* SKILLS */
.skills-grid {
display: grid;
grid-template-columns: repeat(4, 1fr);
gap: 30px;
margin-top: 40px;
}

.skill-category {
background: rgba(255, 255, 255, 0.4);
padding: 30px 25px;
border-radius: 8px;
border-top: 4px solid #1A3263;
}

.skill-category h3 {
font-size: 18px;
color: #1A3263;
margin-bottom: 20px;
font-weight: 600;
text-align: center;
}

.skill-category ul {
list-style: none;
}

.skill-category li {
font-size: 15px;
color: #81A6C6;
margin-bottom: 10px;
padding-left: 15px;
position: relative;
}

.skill-category li::before {
content: “•”;
position: absolute;
left: 0;
color: #1A3263;
font-weight: 600;
}

/* EDUCATION */
.education-box {
max-width: 700px;
margin: 40px auto;
background: rgba(255, 255, 255, 0.4);
padding: 35px;
border-radius: 8px;
border-left: 5px solid #1A3263;
}

.education-box h3 {
font-size: 22px;
color: #1A3263;
margin-bottom: 10px;
font-weight: 600;
}

.education-box p {
font-size: 16px;
color: #81A6C6;
margin-bottom: 8px;
}

.certifications {
margin-top: 30px;
}

.certifications h4 {
font-size: 18px;
color: #1A3263;
margin-bottom: 15px;
font-weight: 600;
}

.cert-list {
display: grid;
grid-template-columns: 1fr 1fr;
gap: 12px;
}

.cert-item {
font-size: 15px;
color: #81A6C6;
padding-left: 20px;
position: relative;
}

.cert-item::before {
content: “✓”;
position: absolute;
left: 0;
color: #1A3263;
font-weight: 600;
}

/* CONTACT */
.contact-content {
max-width: 700px;
margin: 0 auto;
text-align: center;
}

.contact-intro {
font-size: 19px;
color: #81A6C6;
margin-bottom: 40px;
line-height: 1.7;
}

.contact-details {
display: grid;
grid-template-columns: 1fr 1fr;
gap: 25px;
margin-top: 40px;
}

.contact-item {
background: rgba(255, 255, 255, 0.4);
padding: 25px;
border-radius: 8px;
border-top: 3px solid #1A3263;
}

.contact-item h4 {
font-size: 16px;
color: #1A3263;
margin-bottom: 10px;
font-weight: 600;
text-transform: uppercase;
letter-spacing: 0.5px;
}

.contact-item p {
font-size: 16px;
color: #81A6C6;
}

.contact-item a {
color: #81A6C6;
text-decoration: none;
transition: color 0.3s;
}

.contact-item a:hover {
color: #1A3263;
}

/* FOOTER */
footer {
background: rgba(26, 50, 99, 0.05);
padding: 40px 0;
text-align: center;
margin-top: 80px;
border-top: 2px solid #81A6C6;
}

footer p {
font-size: 15px;
color: #81A6C6;
}

/* RESPONSIVE */
@media (max-width: 768px) {
.container { padding: 0 20px; }
header .container { flex-direction: column; gap: 20px; }
nav ul { gap: 20px; }
.hero h1 { font-size: 38px; }
.hero .subtitle { font-size: 18px; }
.hero-stats { flex-direction: column; gap: 30px; }
.strengths, .skills-grid, .contact-details { grid-template-columns: 1fr; }
.cert-list { grid-template-columns: 1fr; }
section h2 { font-size: 32px; }
}

/* ANIMATIONS */
.fade-in {
opacity: 0;
animation: fadeIn 0.8s ease forwards;
}

@keyframes fadeIn {
to { opacity: 1; }
}
</style>

</head>
<body>

<!-- HEADER -->

<header>
  <div class="container">
    <a href="#" class="logo">Nuha Alkhathami, CAPM®</a>
    <nav>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#education">Education</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </div>
</header>

<!-- HERO -->

<section class="hero">
  <div class="container">
    <h1 class="fade-in">Nuha Mohammed Alkhathami</h1>
    <p class="subtitle fade-in">Economic Consultant | Public Policy Analyst | Project Management</p>
    <p class="tagline fade-in">
      Strategic analyst with demonstrated expertise in economic analysis, public policy, and data-driven decision-making.
      Transforming complex data into actionable insights that optimize efficiency, reduce costs, and support long-term strategic objectives.
    </p>

```
<div class="hero-stats fade-in">
  <div class="stat-box">
    <span class="stat-number">50%</span>
    <span class="stat-label">Reporting Time Reduced</span>
  </div>
  <div class="stat-box">
    <span class="stat-number">$75M</span>
    <span class="stat-label">Projected Long-term Savings</span>
  </div>
  <div class="stat-box">
    <span class="stat-number">10+</span>
    <span class="stat-label">Predictive Models Developed</span>
  </div>
</div>

<a href="#projects" class="cta-button">View My Work</a>
```

  </div>
</section>

<!-- ABOUT -->

<section id="about">
  <div class="container">
    <h2>About Me</h2>
    <div class="about-content">
      <p class="about-intro">I operate at the intersection of economic analysis, public policy, and execution.</p>

```
  <p class="about-text">
    During my experience within a government environment, I worked on high-impact initiatives where ambiguity
    was the default and decisions carried long-term economic consequences. My role was not just to analyze data,
    but to structure it into clear narratives that decision-makers could act on immediately.
  </p>

  <p class="about-text">
    I have led cross-functional teams, built predictive models assessing trade-offs between growth, inflation,
    and employment, and delivered policy recommendations projected to generate up to $75M in long-term savings.
  </p>

  <div class="strengths">
    <div class="strength-card">
      <h3>Structured Problem Solving</h3>
      <p>Hypothesis-driven analysis frameworks that cut through complexity and deliver clear strategic direction.</p>
    </div>
    <div class="strength-card">
      <h3>Stakeholder Alignment</h3>
      <p>Strong communication across technical and non-technical audiences, ensuring actionable insights.</p>
    </div>
    <div class="strength-card">
      <h3>Measurable Outcomes</h3>
      <p>Focus on implementation-ready recommendations with quantifiable impact and real-world results.</p>
    </div>
  </div>
</div>
```

  </div>
</section>

<!-- PROJECTS -->

<section id="projects">
  <div class="container">
    <h2>Selected Projects</h2>

```
<div class="projects-grid">

  <div class="project">
    <div class="project-header">
      <h3>National-Level Policy Modeling & Strategic Scenario Design</h3>
      <span class="project-tag">Macroeconomic Policy</span>
    </div>
    <p class="project-context">
      Context: Decision-makers required data-backed insights to evaluate trade-offs between macroeconomic
      variables and support long-term strategic planning.
    </p>
    <p class="project-approach">
      <strong>My Role:</strong> Led the development of predictive economic models and policy analysis frameworks,
      building 10+ econometric and scenario-based models using R and advanced Excel, applying Difference-in-Differences
      methodology to assess regulatory impact.
    </p>
    <div class="project-impact">
      <h4>Impact</h4>
      <ul>
        <li>Informed a 5-year national strategic plan at leadership level</li>
        <li>Delivered policy recommendation projected to reduce market friction by 15%</li>
        <li>Authored health sector strategy projected to achieve $75M in long-term savings by 2050</li>
        <li>Enabled faster, evidence-based decision-making at executive level</li>
      </ul>
    </div>
    <div class="project-tools">
      <span class="tool-tag">R Programming</span>
      <span class="tool-tag">Econometric Modeling</span>
      <span class="tool-tag">Difference-in-Differences</span>
      <span class="tool-tag">Scenario Planning</span>
    </div>
  </div>

  <div class="project">
    <div class="project-header">
      <h3>Data-Driven Reporting Transformation & Dashboard Automation</h3>
      <span class="project-tag">Data Visualization</span>
    </div>
    <p class="project-context">
      Context: Manual reporting processes limited real-time visibility and slowed executive decision-making.
    </p>
    <p class="project-approach">
      <strong>My Role:</strong> Designed and implemented a data visualization and reporting system, developing
      4+ interactive Power BI dashboards for KPI tracking and automating reporting workflows.
    </p>
    <div class="project-impact">
      <h4>Impact</h4>
      <ul>
        <li>Reduced reporting time by 50%</li>
        <li>Improved reporting efficiency by 60%</li>
        <li>Enabled real-time performance tracking for leadership</li>
        <li>Delivered executive-level analytical reports 2 days ahead of schedule</li>
      </ul>
    </div>
    <div class="project-tools">
      <span class="tool-tag">Power BI</span>
      <span class="tool-tag">Dashboard Design</span>
      <span class="tool-tag">Data Automation</span>
      <span class="tool-tag">KPI Tracking</span>
    </div>
  </div>

  <div class="project">
    <div class="project-header">
      <h3>Cross-Functional Leadership & Governance Optimization</h3>
      <span class="project-tag">Project Management</span>
    </div>
    <p class="project-context">
      Context: Large-scale projects faced coordination challenges across multiple stakeholders.
    </p>
    <p class="project-approach">
      <strong>My Role:</strong> Led governance and alignment across a 16-member cross-functional team,
      establishing structured governance model and role clarity, introducing milestone tracking and accountability systems.
    </p>
    <div class="project-impact">
      <h4>Impact</h4>
      <ul>
        <li>Improved delivery timelines and reduced misalignment risks</li>
        <li>Increased team efficiency and execution consistency</li>
        <li>Strengthened decision-making through clear ownership structures</li>
        <li>Completed project evaluations 33% ahead of schedule</li>
      </ul>
    </div>
    <div class="project-tools">
      <span class="tool-tag">Team Leadership</span>
      <span class="tool-tag">CAPM®</span>
      <span class="tool-tag">Risk Mitigation</span>
      <span class="tool-tag">Governance</span>
    </div>
  </div>

  <div class="project">
    <div class="project-header">
      <h3>Financial Operations Optimization (Healthcare Sector)</h3>
      <span class="project-tag">Financial Management</span>
    </div>
    <p class="project-context">
      Context: Urgent financial operations required rapid coordination to prevent delays in critical projects
      at Armed Forces Hospital, Taif.
    </p>
    <p class="project-approach">
      <strong>My Role:</strong> Managed financial operations and process improvements within a high-pressure
      environment, coordinating $300K+ emergency procurement operations and streamlining approval workflows.
    </p>
    <div class="project-impact">
      <h4>Impact</h4>
      <ul>
        <li>Reduced approval timelines by 25%</li>
        <li>Identified 15% budget variance, improving forecasting accuracy</li>
        <li>Maintained 100% audit compliance with zero discrepancies</li>
        <li>Generated 50+ executive financial reports for leadership decision-making</li>
      </ul>
    </div>
    <div class="project-tools">
      <span class="tool-tag">Financial Planning</span>
      <span class="tool-tag">Budget Management</span>
      <span class="tool-tag">Audit Compliance</span>
      <span class="tool-tag">Process Optimization</span>
    </div>
  </div>

</div>
```

  </div>
</section>

<!-- SKILLS -->

<section id="skills">
  <div class="container">
    <h2>Skills & Expertise</h2>

```
<div class="skills-grid">
  <div class="skill-category">
    <h3>Strategy & Economic Analysis</h3>
    <ul>
      <li>Policy Impact Assessment</li>
      <li>Macroeconomic Modeling</li>
      <li>Econometric Analysis</li>
      <li>Cost-Benefit Analysis</li>
      <li>Scenario Planning</li>
      <li>Regulatory Evaluation</li>
    </ul>
  </div>

  <div class="skill-category">
    <h3>Data & Tools</h3>
    <ul>
      <li>Power BI Dashboards</li>
      <li>R Programming</li>
      <li>Advanced Excel</li>
      <li>SQL Database Management</li>
      <li>Predictive Analytics</li>
      <li>Data Visualization</li>
    </ul>
  </div>

  <div class="skill-category">
    <h3>Leadership & Execution</h3>
    <ul>
      <li>Cross-Functional Leadership</li>
      <li>Stakeholder Management</li>
      <li>Project Governance</li>
      <li>Risk Mitigation</li>
      <li>Strategic Planning</li>
      <li>Team Coordination</li>
    </ul>
  </div>

  <div class="skill-category">
    <h3>Compliance & Domain</h3>
    <ul>
      <li>Regulatory Risk Assessment</li>
      <li>Compliance Framework Design</li>
      <li>Audit & Reporting</li>
      <li>Policy Development</li>
      <li>Financial Forecasting</li>
      <li>Business Optimization</li>
    </ul>
  </div>
</div>
```

  </div>
</section>

<!-- EDUCATION -->

<section id="education">
  <div class="container">
    <h2>Education & Certifications</h2>

```
<div class="education-box">
  <h3>Bachelor's Degree in Business Administration</h3>
  <p><strong>University of Bisha</strong> | Saudi Arabia</p>
  <p>GPA: 4.92/5 | August 2019 – July 2023</p>

  <div class="certifications">
    <h4>Professional Certifications</h4>
    <div class="cert-list">
      <div class="cert-item">CAPM® Certification (2026)</div>
      <div class="cert-item">Power BI Advanced Course (2025)</div>
      <div class="cert-item">Google Project Management Certificate (2024)</div>
      <div class="cert-item">Microsoft Office Specialist (2024)</div>
      <div class="cert-item">Financial Management for Companies (2024)</div>
      <div class="cert-item">Foundations: Data Everywhere - Google (2024)</div>
    </div>
  </div>
</div>

<div class="education-box" style="margin-top: 30px;">
  <h3>Languages</h3>
  <p>Arabic (Native) | English (Professional - IELTS 6.5) | Chinese (Professional)</p>
</div>
```

  </div>
</section>

<!-- CONTACT -->

<section id="contact">
  <div class="container">
    <h2>Get In Touch</h2>

```
<div class="contact-content">
  <p class="contact-intro">
    I am interested in opportunities where analytical rigor meets real-world impact.
    If you are looking for someone who can transform complex data into strategic direction
    and measurable outcomes, I would welcome the opportunity to connect.
  </p>

  <div class="contact-details">
    <div class="contact-item">
      <h4>Email</h4>
      <p><a href="mailto:nuhabusinessn@gmail.com">nuhabusinessn@gmail.com</a></p>
    </div>
    <div class="contact-item">
      <h4>Phone</h4>
      <p><a href="tel:+966533495226">+966 533 495 226</a></p>
    </div>
    <div class="contact-item">
      <h4>LinkedIn</h4>
      <p><a href="https://linkedin.com/in/nuha-al-khathami" target="_blank">linkedin.com/in/nuha-al-khathami</a></p>
    </div>
    <div class="contact-item">
      <h4>Location</h4>
      <p>Saudi Arabia</p>
    </div>
  </div>

  <a href="mailto:nuhabusinessn@gmail.com" class="cta-button" style="margin-top: 40px;">Send Me a Message</a>
</div>
```

  </div>
</section>

<!-- FOOTER -->

<footer>
  <div class="container">
    <p>&copy; 2026 Nuha Mohammed Alkhathami, CAPM® | Economic Consultant & Public Policy Analyst</p>
    <p style="margin-top: 10px; font-size: 14px;">Available for consulting opportunities and graduate studies</p>
  </div>
</footer>

<script>
  // Smooth scroll
  document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
      e.preventDefault();
      const target = document.querySelector(this.getAttribute('href'));
      if (target) target.scrollIntoView({ behavior: 'smooth', block: 'start' });
    });
  });

  // Fade-in on scroll
  const observer = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
      if (entry.isIntersecting) {
        entry.target.style.opacity = '1';
        entry.target.style.transform = 'translateY(0)';
      }
    });
  }, { threshold: 0.1, rootMargin: '0px 0px -50px 0px' });

  document.querySelectorAll('.project, .skill-category, .strength-card, .education-box, .contact-item').forEach(el => {
    el.style.opacity = '0';
    el.style.transform = 'translateY(20px)';
    el.style.transition = 'opacity 0.6s ease, transform 0.6s ease';
    observer.observe(el);
  });
</script>

</body>
</html>

