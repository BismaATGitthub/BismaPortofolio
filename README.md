<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Bisma Toriq | Portfolio</title>
  <style>
    /* Fonts & Base */
    body {
      margin: 0;
      font-family: "Helvetica Neue", Arial, sans-serif;
      background: linear-gradient(135deg, #0d0d2b, #1f1f5c, #3a0ca3);
      color: #fff;
    }
    h1, h2, h3 {
      font-family: "Georgia", serif;
      margin: 0 0 15px;
    }
    a {
      color: #ffd700;
      text-decoration: none;
    }

    /* Header */
    header {
      text-align: center;
      padding: 60px 20px;
      background: rgba(0,0,0,0.5);
    }
    header h1 {
      font-size: 3rem;
      color: #ffd700;
      letter-spacing: 2px;
    }
    header p {
      font-size: 1.2rem;
      opacity: 0.9;
    }

    /* Container */
    .container {
      max-width: 1100px;
      margin: 0 auto;
      padding: 40px 20px;
    }

    /* Section Titles */
    .section-title {
      font-size: 2rem;
      margin-bottom: 30px;
      color: #ffd700;
      text-align: center;
      position: relative;
    }
    .section-title::after {
      content: "";
      display: block;
      width: 60px;
      height: 3px;
      background: #ffd700;
      margin: 10px auto 0;
      border-radius: 2px;
    }

    /* Card Grid */
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 25px;
    }
    .card {
      background: rgba(255, 255, 255, 0.05);
      border: 1px solid rgba(255, 215, 0, 0.4);
      border-radius: 15px;
      padding: 20px;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .card:hover {
      transform: translateY(-8px);
      box-shadow: 0 10px 25px rgba(0,0,0,0.6);
    }
    .card h3 {
      color: #ffd700;
      margin-bottom: 15px;
    }

    /* PDF Preview */
    .pdf-frame {
      width: 100%;
      height: 400px;
      border: none;
      border-radius: 10px;
      background: #fff;
    }

    /* Footer */
    footer {
      text-align: center;
      padding: 25px;
      font-size: 0.9rem;
      background: rgba(0,0,0,0.5);
      margin-top: 50px;
    }
  </style>
</head>
<body>
  <!-- HEADER -->
  <header>
    <h1>Bisma Toriq</h1>
    <p>Pit Geologist | Turangga Resources (Member of Astra)</p>
  </header>

  <!-- ABOUT -->
  <div class="container">
    <section>
      <h2 class="section-title">About Me</h2>
      <p>
        I am a Pit Geologist with proven experience in driving innovation and
        strategy. I successfully completed the FGDP program in just one year,
        accelerating my career into a full-time position. My key achievement:
        leading a project to develop a new coal product — from concept to
        standardization — while managing strategy and communication with
        multiple stakeholders.
      </p>
    </section>

    <!-- PORTFOLIO -->
    <section>
      <h2 class="section-title">Portfolio</h2>
      <div class="grid">
        <div class="card">
          <h3>Coal Product Innovation Project</h3>
          <p>
            Spearheaded development of an additional coal product with unique
            characterization. Drove project from scratch to full standardization
            within 1 year.
          </p>
        </div>
        <div class="card">
          <h3>Stakeholder Strategy & Communication</h3>
          <p>
            Designed and executed communication strategies with diverse
            stakeholders to ensure project success and alignment with company
            goals.
          </p>
        </div>
      </div>
    </section>

    <!-- DOCUMENTS -->
    <section>
      <h2 class="section-title">Documents</h2>
      <div class="grid">
        <div class="card">
          <h3>Resume</h3>
          <iframe src="resume.pdf" class="pdf-frame"></iframe>
        </div>
        <div class="card">
          <h3>Certificate</h3>
          <iframe src="certificate.pdf" class="pdf-frame"></iframe>
        </div>
      </div>
    </section>
  </div>

  <!-- FOOTER -->
  <footer>
    © 2025 Bisma Toriq. All rights reserved.
  </footer>
</body>
</html>
