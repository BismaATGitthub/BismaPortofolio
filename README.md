<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bisma Toriq - Portfolio</title>
  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(135deg, #0f0f0f, #1a1a1a, #2b2b2b);
      color: #fefefe;
      line-height: 1.6;
      overflow-x: hidden;
    }
    header {
      padding: 5rem 2rem;
      text-align: center;
      background: linear-gradient(90deg, #111, #1f1f1f);
      border-bottom: 3px solid #d4af37;
    }
    header h1 {
      font-size: 3.8rem;
      font-weight: 900;
      color: #d4af37;
      margin-bottom: 0.5rem;
      letter-spacing: 2px;
    }
    header p {
      font-size: 1.2rem;
      color: #e5e5e5;
    }
    section {
      max-width: 1100px;
      margin: 3rem auto;
      padding: 0 1.5rem;
      animation: fadeIn 1s ease forwards;
    }
    h2 {
      font-size: 2.2rem;
      margin-bottom: 2rem;
      font-weight: 700;
      color: #d4af37;
      border-left: 6px solid #d4af37;
      padding-left: 0.7rem;
    }
    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
      gap: 2rem;
    }
    .card {
      backdrop-filter: blur(12px);
      background: rgba(255, 255, 255, 0.05);
      padding: 2rem;
      border-radius: 18px;
      border: 1px solid rgba(212, 175, 55, 0.4);
      box-shadow: 0 6px 30px rgba(0,0,0,0.6);
      transition: all 0.4s ease;
    }
    .card:hover {
      transform: translateY(-8px);
      border: 1px solid #d4af37;
      box-shadow: 0 10px 40px rgba(212, 175, 55, 0.3);
    }
    .card h3 {
      font-size: 1.5rem;
      margin-bottom: 1rem;
      color: #d4af37;
    }
    .card p {
      color: #f5f5f5;
    }
    object {
      width: 100%;
      height: 500px;
      border-radius: 10px;
      background: #fff;
    }
    .fallback {
      margin-top: 0.5rem;
      display: block;
      font-size: 0.9rem;
      color: #fefefe;
    }
    footer {
      text-align: center;
      padding: 2rem;
      font-size: 0.9rem;
      color: #ccc;
      background: #0a0a0a;
      border-top: 2px solid #d4af37;
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(30px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>
  <header>
    <h1>Bisma Toriq</h1>
    <p>Pit Geologist | Turangga Resources (Member of Astra)</p>
  </header>

  <section>
    <h2>About Me</h2>
    <p>I am a Pit Geologist who completed the Future Generation Development Program (FGDP) at Turangga Resources in just 1 year, faster than the standard timeline. I transitioned into a full-time role by leading a strategic project from scratch — developing an additional coal product with unique characterization, creating the strategy, and aligning stakeholders to reach full standardization.</p>
  </section>

  <section>
    <h2>Portfolio</h2>
    <div class="cards">
      <div class="card">
        <h3>Coal Product Development</h3>
        <p>Led end-to-end creation of a new coal product with different characterization, from research and design to testing and final standardization.</p>
      </div>
      <div class="card">
        <h3>Stakeholder Strategy & Communication</h3>
        <p>Designed communication and engagement strategies with multiple stakeholders to ensure alignment and project success.</p>
      </div>
      <div class="card">
        <h3>Geology & Operations Support</h3>
        <p>Provided geological analysis and operational support to optimize mining outcomes, ensuring efficiency and sustainability.</p>
      </div>
    </div>
  </section>

  <section>
    <h2>Resume & Documents</h2>
    <div class="cards">
      <div class="card">
        <h3>Resume</h3>
        <object data="resume.pdf" type="application/pdf">
          <p>Your browser does not support PDF preview. 
          <a href="resume.pdf" class="fallback">Download Resume</a></p>
        </object>
      </div>
      <div class="card">
        <h3>Certificate</h3>
        <object data="certificate.pdf" type="application/pdf">
          <p>Your browser does not support PDF preview. 
          <a href="certificate.pdf" class="fallback">Download Certificate</a></p>
        </object>
      </div>
    </div>
  </section>

  <section>
    <h2>Contact</h2>
    <p>Email: <a href="mailto:youremail@example.com">youremail@example.com</a></p>
    <p><a href="https://www.linkedin.com/in/bismatoriq" target="_blank">LinkedIn Profile</a></p>
  </section>

  <footer>
    <p>© 2025 Bisma Toriq. All Rights Reserved.</p>
  </footer>
</body>
</html>
