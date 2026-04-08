# jerichojake.github.io
Virtual E-commerce Assistant proficient in managing online stores and engaging with customers.  Capable of posting products, updating inventory status, and completing orders efficiently, all while  extending empathic support via chat, email, and social media platforms
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfolio Jericho Jake Guevara</title>
  <style>
    /* Reset & Base */
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { font-family: 'Segoe UI', Tahoma, sans-serif; line-height: 1.6; color: #333; background: #f9f9f9; }

    /* Navigation */
    nav { background: #222; color: #fff; padding: 1rem; position: sticky; top: 0; }
    nav ul { display: flex; justify-content: center; list-style: none; }
    nav ul li { margin: 0 1rem; }
    nav ul li a { color: #fff; text-decoration: none; transition: color 0.3s; }
    nav ul li a:hover { color: #00bcd4; }

    /* Sections */
    section { padding: 4rem 2rem; max-width: 1000px; margin: auto; }
    section h2 { margin-bottom: 1rem; color: #00bcd4; }
    section p { margin-bottom: 1rem; }

    /* Cards for projects/works */
    .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 1.5rem; }
    .card { background: #fff; padding: 1.5rem; border-radius: 8px; box-shadow: 0 2px 6px rgba(0,0,0,0.1); }
    .card h3 { margin-bottom: 0.5rem; }

    /* Skills & Tools */
    .skills-list, .tools-list { display: flex; flex-wrap: wrap; gap: 1rem; }
    .badge { background: #00bcd4; color: #fff; padding: 0.5rem 1rem; border-radius: 20px; }

    /* Contact */
    form { display: flex; flex-direction: column; gap: 1rem; }
    input, textarea { padding: 0.75rem; border: 1px solid #ccc; border-radius: 5px; }
    button { background: #00bcd4; color: #fff; padding: 0.75rem; border: none; border-radius: 5px; cursor: pointer; }
    button:hover { background: #0097a7; }

    /* Responsive */
    @media (max-width: 768px) {
      nav ul { flex-direction: column; align-items: center; }
    }
  </style>
</head>
<body>

  <!-- Navigation -->
  <nav>
    <ul>
      <li><a href="#about">About Me</a></li>
      <li><a href="#experience">Experience</a></li>
      <li><a href="#skills">Skills</a></li>
      <li><a href="#tools">Tools</a></li>
      <li><a href="#works">Works</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <!-- About Me -->
  <section id="about">
    <h2>About Me</h2>
    <p>Hi, I’m [Your Name], a professional VA and content moderator with expertise in Shopify, admin workflows, and online teaching. I design clean workflows and engaging digital experiences.</p>
  </section>

  <!-- Experience -->
  <section id="experience">
    <h2>Experience</h2>
    <p>Content Moderator, Conversational Workflow Designer, Shopify VA, Admin VA, ESL Teacher (51Talk).</p>
  </section>

  <!-- Skills -->
  <section id="skills">
    <h2>Skills</h2>
    <div class="skills-list">
      <span class="badge">Content Moderation</span>
      <span class="badge">Shopify VA</span>
      <span class="badge">Admin Workflows</span>
      <span class="badge">ESL Teaching</span>
      <span class="badge">Canva Design</span>
    </div>
  </section>

  <!-- Tools -->
  <section id="tools">
    <h2>Tools</h2>
    <div class="tools-list">
      <span class="badge">Asana</span>
      <span class="badge">GitHub</span>
      <span class="badge">Netlify</span>
      <span class="badge">Canva</span>
      <span class="badge">Zoom</span>
    </div>
  </section>

  <!-- Works -->
  <section id="works">
    <h2>Works</h2>
    <div class="grid">
      <div class="card"><h3>Workflow Scripts</h3><p>Designed natural, context-sensitive chat scripts.</p></div>
      <div class="card"><h3>Teaching Materials</h3><p>Created ESL lesson plans and backgrounds.</p></div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact">
    <h2>Contact</h2>
    <form>
      <input type="text" placeholder="Your Name" required>
