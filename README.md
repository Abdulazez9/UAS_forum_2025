<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>UAS Forum 2025 | Chosun University</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap" rel="stylesheet" />
  <style>
    body {
      margin: 0;
      font-family: 'Roboto', sans-serif;
      background: linear-gradient(135deg, #0a1f44, #041029);
      color: #fff;
      line-height: 1.6;
    }

    header {
      text-align: center;
      padding: 100px 20px;
      background: url('https://images.unsplash.com/photo-1508612761958-e931d843bddc?auto=format&fit=crop&w=1950&q=80') no-repeat center center/cover;
      color: white;
      position: relative;
    }

    header::after {
      content: '';
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background-color: rgba(0, 0, 0, 0.55);
    }

    header h1, header h3 {
      position: relative;
      z-index: 2;
    }

    header h1 {
      font-size: 3rem;
      margin-bottom: 1rem;
      letter-spacing: 1px;
    }

    header h3 {
      font-weight: 300;
      font-size: 1.4rem;
      max-width: 800px;
      margin: 0 auto;
    }

    main {
      width: 90%;
      max-width: 1400px;
      margin: 50px auto;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(450px, 1fr));
      gap: 30px;
    }

    section {
      background: rgba(255, 255, 255, 0.05);
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 0 15px rgba(0, 0, 0, 0.3);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    section:hover {
      transform: translateY(-5px);
      box-shadow: 0 0 25px rgba(0, 0, 0, 0.4);
    }

    h2 {
      color: #4cc9f0;
      border-bottom: 2px solid #4cc9f0;
      padding-bottom: 8px;
      margin-bottom: 15px;
    }

    ul {
      list-style-type: square;
      padding-left: 20px;
    }

    .contact {
      text-align: center;
      padding: 60px 0;
      grid-column: 1 / -1;
    }

    .email-btn {
      background: #4cc9f0;
      color: #041029;
      padding: 14px 35px;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
      font-size: 1rem;
      transition: 0.3s;
    }

    .email-btn:hover {
      background: #fff;
      color: #0a1f44;
    }

    footer {
      text-align: center;
      padding: 25px;
      background: rgba(255, 255, 255, 0.05);
      font-size: 0.9rem;
      color: #bbb;
      margin-top: 40px;
    }

    @media (max-width: 768px) {
      header h1 {
        font-size: 2.2rem;
      }

      header h3 {
        font-size: 1.1rem;
      }

      main {
        width: 95%;
        grid-template-columns: 1fr;
      }

      section {
        padding: 20px;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>UAS Forum 2025</h1>
    <h3>Exploring Innovation in Autonomous Systems, Hybrid Propulsion, and Control Technology</h3>
  </header>

  <main>
    <section>
      <h2>About the Forum</h2>
      <p>
        A two-day technical forum focused on sharing research outcomes and exploring advances in autonomy and integration of unmanned systems.
      </p>
      <p>
        <strong>Date:</strong> December 5–6, 2025<br />
        <strong>Venue:</strong> Chosun University, Aerospace Engineering Building, Room 3204, Gwangju, South Korea<br />
        <strong>Organizer:</strong> UAS Laboratory, Chosun University
      </p>
    </section>

    <section>
      <h2>Research Domains</h2>
      <ul>
        <li>Control and Optimization for UAVs</li>
        <li>Hybrid Propulsion Systems</li>
        <li>Energy-Efficient Path Planning</li>
        <li>Multi-Sensor Data Fusion for Unmanned Systems</li>
      </ul>
    </section>

    <section>
      <h2>Global Collaborations</h2>
      <ul>
        <li>IAC JCAS, APISAT, KSAS, SASE, KSME</li>
        <li>Multinational research teams from Poland, Switzerland, Ethiopia, and beyond</li>
      </ul>
    </section>

    <section>
      <h2>Current Projects</h2>
      <ul>
        <li>Test Device for Safe Indoor Flight</li>
        <li>Robot Propulsion Test Unit</li>
        <li>Detachable Inductive Recovery Drone System</li>
        <li>Battery Management System</li>
      </ul>
    </section>

    <section>
      <h2>Program Schedule</h2>
      <p>
        <em>Coming Soon – The detailed program will be updated here. You’ll be able to paste the latest schedule text directly into this section.</em>
      </p>
    </section>

    <div class="contact">
      <a href="mailto:abdulazezjebal@chosun.ac.kr" class="email-btn">Email Us</a>
    </div>
  </main>

  <footer>
    <p>© 2025 UAS Laboratory, Chosun University. All rights reserved.</p>
  </footer>
</body>
</html>
