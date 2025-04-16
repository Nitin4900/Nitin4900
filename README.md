<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Nitin Kandula - Portfolio</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 20px;
      background-color: #f5f5f5;
      color: #333;
      line-height: 1.6;
    }
    header, section {
      background: #fff;
      margin-bottom: 20px;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    }
    header h1 {
      margin-top: 0;
    }
    .tech-icons img {
      vertical-align: middle;
      margin-right: 12px;
    }
    .badges {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
    }
    .badge-item {
      background: #e9ecef;
      border-radius: 10px;
      padding: 15px;
      flex: 1 1 250px;
      box-shadow: 0 1px 3px rgba(0,0,0,0.1);
      transition: transform 0.2s;
    }
    .badge-item:hover {
      transform: scale(1.02);
    }
    .badge-item h3 {
      margin-top: 0;
      color: #007BFF;
    }
  </style>
</head>
<body>

  <!-- Introduction Section -->
  <header>
    <h1>Hey 👋 What's up?</h1>
    <p>My name is <strong>Your Name</strong> and I'm a <strong>Your Role</strong> from <strong>Your City/Country</strong>.</p>
  </header>

  <!-- About Me Section -->
  <section>
    <h2>About Me</h2>
    <p>
      ✨ Creating bugs since <em>[Your Start Year]</em><br>
      📚 I'm currently learning <em>[Your Learning Path]</em><br>
      🎯 Goals: <em>[Your Goals]</em><br>
      🎲 Fun fact: <em>[Your Fun Fact]</em>
    </p>
  </section>

  <!-- Tech Stack Section -->
  <section>
    <h2>I Code With</h2>
    <div class="tech-icons">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="40" alt="JavaScript Logo">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="40" alt="TypeScript Logo">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="40" alt="React Logo">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" height="40" alt="Next.js Logo">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/storybook/storybook-original.svg" height="40" alt="Storybook Logo">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" height="40" alt="Node.js Logo">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nestjs/nestjs-original.svg" height="40" alt="NestJS Logo">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jest/jest-plain.svg" height="40" alt="Jest Logo">
    </div>
  </section>

  <!-- Badges & Certifications Section -->
  <section>
    <h2>Badges &amp; Certifications</h2>
    <div class="badges">
      <!-- Certification 1 -->
      <div class="badge-item">
        <h3>Databricks Certified Data Engineer Associate</h3>
        <p>Achieved Oct 2024. Demonstrated expertise in data engineering and Azure integrations.</p>
      </div>
      <!-- Certification 2 -->
      <div class="badge-item">
        <h3>Associate Data Engineer</h3>
        <p>DataCamp Certification, Dec 2024. Solid foundation in data manipulation and analytics.</p>
      </div>
      <!-- Certification 3 -->
      <div class="badge-item">
        <h3>Data Analyst in Power BI</h3>
        <p>DataCamp Certification, Feb 2025. Skilled in transforming complex data into clear insights through visualization.</p>
      </div>
      <!-- Additional badges can be added here -->
    </div>
  </section>

</body>
</html>
