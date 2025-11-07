<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Rushikesh D. Sonawane | Resume</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <div class="container">
      <h1>Rushikesh Dilip Sonawane</h1>
      <p class="title">Technical Support Engineer | Linux & Cloud Enthusiast</p>
      <div class="contact">
        <a href="tel:+917796251496">📞 +91 7796251496</a> |
        <a href="mailto:Rushikesh.ds07@gmail.com">✉️ Rushikesh.ds07@gmail.com</a> |
        <a href="https://www.linkedin.com/in/rushikesh-sonawane-372455199" target="_blank">🔗 LinkedIn</a>
      </div>
      <p class="location">📍 Nashik, Maharashtra | Work: Andheri East, Mumbai</p>
    </div>
  </header>

  <main class="container">
    <section id="summary">
      <h2>Summary</h2>
      <p>
        A highly motivated and hardworking individual with strong knowledge of Linux operating systems,
        networking, and cloud technologies.
      </p>
    </section>

    <section id="education">
      <h2>Education</h2>
      <ul>
        <li><strong>MCA</strong> – MET Bhujbal Knowledge City Institute of Engineering, Nashik (Apr 2023) – 64.77%</li>
        <li><strong>BCA</strong> – K J Somaiya College of Engineering, Kopargaon (Jun 2021) – 66.67%</li>
        <li><strong>12th</strong> – K.B. Rohamare Jr. College, Kopargaon (Jun 2018) – 69.38%</li>
      </ul>
    </section>

    <section id="experience">
      <h2>Experience</h2>
      <article>
        <h3>Technical Support Engineer – Manappuram Finance Ltd. <span>(Oct 2024 – Present)</span></h3>
        <ul>
          <li>Provided technical support for internal and external users across hardware and software systems.</li>
          <li>Troubleshot and resolved system and network issues, ensuring minimal downtime.</li>
          <li>Installed, configured, and maintained hardware, software, and peripherals.</li>
          <li>Monitored and maintained IT systems, servers, and databases.</li>
          <li>Collaborated with teams to support financial and loan management systems.</li>
        </ul>
      </article>
      <article>
        <h3>Senior Executive – Bajaj Finserv <span>(Sep 2023 – Jan 2024)</span></h3>
        <p>
          Worked with CRM software, MS Excel, PowerPoint, and financial tools for data analysis, reporting,
          and customer service excellence.
        </p>
      </article>
    </section>

    <section id="skills">
      <h2>Technical Skills</h2>
      <ul>
        <li><strong>Operating Systems:</strong> Linux, Windows Server</li>
        <li><strong>Networking:</strong> TCP/IP, DNS, DHCP, VLAN, VPN, Firewall</li>
        <li><strong>Virtualization:</strong> VMware, RHCSA</li>
        <li>Installation & configuration of Linux, OS upgrades, user management, and server configuration (FTP, WEB, NFS, SAMBA, SMTP).</li>
        <li>Server monitoring, file system management, ACL, backups, and troubleshooting.</li>
      </ul>
    </section>

    <section id="projects">
      <h2>Projects</h2>
      <h3>Online Restaurant Table Reservation</h3>
      <p><strong>Platform:</strong> JavaScript, HTML, CSS, PHP, SQL</p>
      <p>
        Developed and tested an online restaurant table reservation system that allows users to find nearby restaurants,
        view menus, and book tables online through a secure reservation process.
      </p>
    </section>

    <section id="strengths">
      <h2>Strengths</h2>
      <ul>
        <li>Quickly adaptable to new systems</li>
        <li>Problem-solving skills</li>
        <li>Team player</li>
      </ul>
    </section>

    <section id="personal">
      <h2>Personal Details</h2>
      <ul>
        <li><strong>Date of Birth:</strong> 15 Aug 2000</li>
        <li><strong>Nationality:</strong> Indian</li>
        <li><strong>Languages:</strong> English, Hindi, Marathi</li>
        <li><strong>Permanent Address:</strong> Nashik, Maharashtra</li>
      </ul>
    </section>
  </main>

  <footer>
    <p>© 2025 Rushikesh D. Sonawane</p>
  </footer>
</body>
</html>


* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: "Poppins", sans-serif;
  line-height: 1.6;
  background-color: #f7f9fc;
  color: #222;
}

.container {
  width: 90%;
  max-width: 900px;
  margin: auto;
  padding: 20px 0;
}

header {
  background-color: #1f3b73;
  color: white;
  text-align: center;
  padding: 40px 0;
}

header h1 {
  font-size: 2em;
  margin-bottom: 5px;
}

header .title {
  font-size: 1.2em;
  margin-bottom: 10px;
}

header .contact a {
  color: #fff;
  text-decoration: none;
  margin: 0 5px;
}

header .contact a:hover {
  text-decoration: underline;
}

section {
  margin: 30px 0;
}

h2 {
  color: #1f3b73;
  margin-bottom: 10px;
  border-bottom: 2px solid #1f3b73;
  padding-bottom: 5px;
}

h3 {
  color: #333;
  margin-top: 10px;
}

ul {
  list-style-type: square;
  padding-left: 20px;
}

footer {
  background-color: #1f3b73;
  color: #fff;
  text-align: center;
  padding: 15px 0;
  margin-top: 30px;
  font-size: 0.9em;
}

@media (max-width: 600px) {
  header h1 {
    font-size: 1.6em;
  }
  .container {
    width: 95%;
  }
}
