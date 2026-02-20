<!DOCTYPE html>

<html lang="en">

<head>

  <meta charset="UTF-8" />

  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>

  <title>TOMIWA RAPHAEL - Personal / Virtual / Executive Assistant</title>

  <link rel="preconnect" href="https://fonts.googleapis.com">

  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">

  <style>

    * { margin: 0; padding: 0; box-sizing: border-box; }

    body {

      font-family: 'Inter', sans-serif;

      line-height: 1.6;

      color: #ffffff;

      background: #21049e; /* Deep navy blue background */

      min-height: 100vh;

    }

    .container {

      max-width: 1000px;

      margin: 0 auto;

      padding: 40px 20px;

    }

    header {

      text-align: center;

      padding: 80px 20px 60px;

    }

    .profile-container {

      width: 180px;

      height: 180px;

      margin: 0 auto 25px;

      position: relative;

    }

    .profile-pic {

      width: 100%;

      height: 100%;

      border-radius: 50%;

      object-fit: cover;

      border: 4px solid rgba(102, 204, 255, 0.3);

      box-shadow: 0 8px 25px rgba(0, 0, 0, 0.6);

      mix-blend-mode: multiply;           /* Helps blend lighter parts into dark background */

      background-color: #001f3f;          /* Matches the body background */

      filter: brightness(0.92) contrast(1.08); /* Subtle adjustment for better blending */

    }

    h1 {

      font-size: 3.5rem;

      font-weight: 700;

      color: #ffffff;

      margin-bottom: 8px;

    }

    .subtitle {

      font-size: 1.5rem;

      font-weight: 500;

      color: #dddddd;

      margin-bottom: 20px;

    }

    .tagline {

      font-size: 1.3rem;

      color: #66ccff;

      margin-bottom: 30px;

    }

    .contact-info {

      font-size: 1.1rem;

      margin-bottom: 20px;

      color: #dddddd;

    }

    .email-btn {

      display: inline-block;

      background: #0066cc;

      color: white;

      padding: 12px 28px;

      border-radius: 30px;

      text-decoration: none;

      font-weight: 500;

      margin: 10px;

    }

    .email-btn:hover { background: #0055aa; }

    nav {

      text-align: center;

      margin: 40px 0;

      padding: 15px 0;

      border-top: 1px solid #444444;

      border-bottom: 1px solid #444444;

    }

    nav a {

      margin: 0 20px;

      color: #ffffff;

      text-decoration: none;

      font-weight: 500;

      font-size: 1.1rem;

    }

    nav a:hover { color: #66ccff; }

    section {

      padding: 60px 0;

      border-bottom: 1px solid #444444;

    }

    h2 {

      font-size: 2.2rem;

      color: #66ccff;

      margin-bottom: 30px;

      text-align: center;

    }

    p {

      max-width: 800px;

      margin: 0 auto 20px;

      font-size: 1.05rem;

      color: #dddddd;

    }

    ul {

      list-style: none;

      padding: 0;

      max-width: 800px;

      margin: 0 auto 30px;

    }

    ul li {

      margin-bottom: 12px;

      font-size: 1.05rem;

      position: relative;

      padding-left: 25px;

      color: #dddddd;

    }

    ul li::before {

      content: "•";

      position: absolute;

      left: 0;

      color: #66ccff;

      font-size: 1.6rem;

    }

    .job {

      max-width: 800px;

      margin: 0 auto 40px;

    }

    .job-title {

      font-size: 1.4rem;

      font-weight: 600;

      margin-bottom: 8px;

      color: #ffffff;

    }

    .job-period {

      font-style: italic;

      color: #aaaaaa;

      margin-bottom: 12px;

    }

    .achievements {

      font-weight: 500;

      margin: 15px 0 8px;

      color: #dddddd;

    }

    .tools-grid {

      display: grid;

      grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));

      gap: 25px;

      max-width: 900px;

      margin: 0 auto;

      text-align: center;

    }

    .tool-item img {

      width: 60px;

      height: 60px;

      object-fit: contain;

      margin-bottom: 10px;

    }

    .tool-name {

      font-size: 0.95rem;

      color: #dddddd;

    }

    .testimonial {

      max-width: 800px;

      margin: 0 auto 30px;

      background: #002b5b;

      padding: 20px;

      border-radius: 8px;

      border-left: 5px solid #66ccff;

    }

    .quote {

      font-style: italic;

      margin-bottom: 10px;

      font-size: 1.1rem;

    }

    .author {

      text-align: right;

      font-weight: 500;

      color: #66ccff;

    }

    .screenshots {

      display: grid;

      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));

      gap: 20px;

      max-width: 900px;

      margin: 0 auto;

    }

    .screenshot-item img {

      width: 100%;

      border-radius: 8px;

      border: 1px solid #444444;

    }

    .screenshot-item p {

      text-align: center;

      font-size: 0.95rem;

      color: #aaaaaa;

      margin-top: 8px;

    }

    footer {

      text-align: center;

      padding: 40px 20px;

      color: #aaaaaa;

      font-size: 0.95rem;

      border-top: 1px solid #444444;

    }

    @media (max-width: 768px) {

      h1 { font-size: 2.8rem; }

      nav a { margin: 0 10px; font-size: 0.95rem; }

      .profile-container { width: 140px; height: 140px; }

    }

  </style>

</head>

<body>



  <header>

    <div class="profile-container">

      <img 

        src="https://i.postimg.cc/htvSR6BM/30a0ebf9ef6549d6af539cb8f410c9a6(1).jpg" 

        alt="Tomiwa Raphael" 

        class="profile-pic"

      >

    </div>



    <h1>TOMIWA RAPHAEL</h1>

    <div class="subtitle">PROFESSIONAL PERSONAL ASSISTANT / VIRTUAL ASSISTANT / EXECUTIVE ASSISTANT</div>

    <div class="tagline">Reliable, tech-savvy individual specialised in support for administration, social media & executive tasks</div>



    <div class="contact-info">

      No 3, Oluwasuyi street, Akure, Ondo State.<br>

      (+234) 8141970557 • (+234) 9067846423<br>

      tomiwaraphael1@gmail.com

    </div>

    <a href="mailto:tomiwaraphael1@gmail.com" class="email-btn">Email Me</a>

  </header>



  <nav>

    <a href="#about">About Me</a>

    <a href="#skills">Key Skills</a>

    <a href="#tools">Tools & Software</a>

    <a href="#experience">Experience</a>

    <a href="#testimonials">Testimonials</a>

    <a href="#education">Education</a>

    <a href="#examples">Work Examples</a>

  </nav>



  <div class="container">



    <section id="about">

      <h2>Personal statement</h2>

      <p>A conscientious, tech savvy and professional personal assistant with extensive experience in administration, executive assistance and Social media management, currently seeking a position in relevant field of experience. A highly organised and efficient individual, whose thorough and precise approach to projects has yielded excellent results.</p>

    </section>



    <section id="skills">

      <h2>Key Skills</h2>

      <ul>

        <li>50 words per minute typing</li>

        <li>Proficiency in all areas of Microsoft Office, including Access, Excel, Word, PowerPoint and google sheets</li>

        <li>Web Development (frontend)</li>

        <li>Excellent communication skills, both written and verbal</li>

        <li>Record keeping proficiency</li>

        <li>Travel Planning</li>

        <li>Data Management</li>

        <li>Time Management</li>

        <li>Report Preparation</li>

        <li>Discretion</li>

        <li>AI Automation</li>

        <li>Calender Management</li>

        <li>Social media management</li>

        <li>Customer service</li>

        <li>Video Editing</li>

        <li>Content writing</li>

      </ul>

    </section>



    <section id="tools">

      <h2>Tools & Software</h2>

      <div class="tools-grid">

        <div class="tool-item">

          <img src="https://upload.wikimedia.org/wikipedia/commons/0/0c/Capcut-icon.png" alt="CapCut">

          <div class="tool-name">CapCut</div>

        </div>

        <div class="tool-item">

          <img src="https://upload.wikimedia.org/wikipedia/commons/4/44/Microsoft_logo.svg" alt="Microsoft">

          <div class="tool-name">Microsoft Office</div>

        </div>

        <div class="tool-item">

          <img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png" alt="Instagram">

          <div class="tool-name">Instagram</div>

        </div>

        <div class="tool-item">

          <img src="https://upload.wikimedia.org/wikipedia/commons/5/51/Facebook_f_logo_%282019%29.svg" alt="Facebook">

          <div class="tool-name">Facebook</div>

        </div>

        <div class="tool-item">

          <img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Google_Calendar_icon_%282020%29.svg" alt="Calendly" style="background:white; padding:5px; border-radius:8px;">

          <div class="tool-name">Calender</div>

        </div>

        <div class="tool-item">

          <img src="https://upload.wikimedia.org/wikipedia/commons/f/fd/Zapier_logo.svg" alt="Zapier">

          <div class="tool-name">Zapier</div>

        </div>

      </div>

    </section>



    <section id="experience">

      <h2>Experience</h2>

      <div class="job">

        <div class="job-title">Administrative officer, Our God Reign’s Gas, Akure, Nigeria</div>

        <div class="job-period">(March 2021 – August 2022)</div>

        <div class="achievements">Achievements and responsibilities:</div>

        <ul>

          <li>Handled daily office activities, including data entry and database auditing, maintaining smooth operations.</li>

          <li>Created employee attendance reports, verifying compliance</li>

          <li>Devised and implemented a new filing and indexing system for files, resulting in greater ease of access and a more time-efficient process for annual auditing</li>

        </ul>

      </div>



      <div class="job">

        <div class="job-title">Office Assistant Intern, Federal University Of Technology, Akure, Nigeria</div>

        <div class="job-period">(May 2024 – July 2024)</div>

        <div class="achievements">Achievements and responsibilities:</div>

        <ul>

          <li>Presenting a professional and friendly first impression of the department to all visitors and clients</li>

          <li>Managing incoming phone calls and mail</li>

          <li>Maintained confidentiality of sensitive information, adhering to data protection policies and legal requirements</li>

          <li>Organised files, faxed reports and scanned documents into document management system</li>

        </ul>

      </div>



      <div class="job">

        <div class="job-title">Laboratory Assistant Intern, Federal University Of Technology, Akure, Nigeria</div>

        <div class="job-period">(August 2024 – October 2024)</div>

        <div class="achievements">Achievements and responsibilities:</div>

        <ul>

          <li>Managed Laboratory databases, inputting data and ensuring up-to-date records</li>

          <li>Kept research findings and data safely in-line with the Institution policies and data protection laws</li>

          <li>Assisted in the publications of research findings, contributing to data collection and analysis sections</li>

        </ul>

      </div>



      <div class="job">

        <div class="job-title">Virtual Assistant, Delphi Education, United Kingdom</div>

        <div class="job-period">(January 2025 - April 2025)</div>

        <div class="achievements">Achievements and responsibilities:</div>

        <ul>

          <li>Managed company data and spreadsheets</li>

          <li>Scheduled meetings for the MD</li>

          <li>End of the day updates</li>

          <li>Monthly reports on spreadsheet</li>

          <li>Sent applications for students seeking to study abroad</li>

          <li>Cold mailing</li>

          <li>Managed social media account</li>

          <li>Created and scheduled contents on Instagram and Facebook</li>

          <li>Managed social media campaigns for webinars that increased registrations by 65%</li>

        </ul>

      </div>



      <div class="job">

        <div class="job-title">Executive Assistant (Confidential Role) Top UK Official (NDA-protected)</div>

        <div class="job-period">(May 2025 - November 2025)</div>

        <div class="achievements">Achievements and responsibilities:</div>

        <ul>

          <li>Provided high-level administrative support to a senior official, managing calendars, correspondence, and meetings</li>

          <li>Coordinated travel arrangements, logistics, and communications with government officials and external stakeholders</li>

          <li>Prepared briefing materials, reports, and speeches, ensuring accuracy and confidentiality</li>

          <li>Demonstrated discretion and professionalism in handling sensitive information and high-pressure situations</li>

          <li>Implemented an AI automation tool that read, sorted, and summarized emails, increasing email processing efficiency by 40%</li>

        </ul>

      </div>

    </section>



    <section id="testimonials">

      <h2>Testimonials</h2>

      <div class="testimonial">

        <p class="quote">"Tomiwa was reliable and efficient in managing office operations and implementing new systems that improved our auditing process significantly."</p>

        <p class="author">- Manager, Our God Reign’s Gas</p>

      </div>

      <div class="testimonial">

        <p class="quote">"Excellent discretion and organizational skills during internship; handled sensitive data and communications professionally."</p>

        <p class="author">- Supervisor, Federal University of Technology</p>

      </div>

      <div class="testimonial">

        <p class="quote">"Boosted our webinar registrations by 65% through effective social media campaigns and data management. Highly recommended."</p>

        <p class="author">- Managing Director, Delphi Education</p>

      </div>

      <div class="testimonial">

        <p class="quote">"Implemented AI tools that increased email efficiency by 40%. Demonstrated exceptional professionalism in a confidential high-level role."</p>

        <p class="author">- Senior Official (Confidential Role)</p>

      </div>

    </section>

    <section id="education">

        <h2>Education</h2>

  

        <div class="job">

          <div class="job-title">Adekunle Ajasin University, Akungba Akoko, Nigeria</div>

          <div class="job-period">(August 2021 – Ongoing)</div>

          <p>BSc Physics and Electronics</p>

        </div>

  

        <div class="job">

          <div class="job-title">Mother’s Pride Model School</div>

          <div class="job-period">(September 2014 – June 2020)</div>

          <p>10 GCSEs, grade A-C, including Maths and English</p>

        </div>

      </section>

  

    



    <section id="examples">

      <h2>Work Examples</h2>

      <div class="screenshots">

        <div class="screenshot-item">

          <img src="https://i.postimg.cc/rF7zwqFZ/2c743ef5.png" alt="Well Arranged Google Sheets">

          <p>Well-Organized Google Calender</p>

        </div>

        <div class="screenshot-item">

          <img src="https://i.postimg.cc/jqZ7tVfS/Screenshot-(34).png" alt="CapCut Editing Interface">

          <p>CapCut Open for Video Editing</p>

        </div>

        <div class="screenshot-item">

          <img src="https://img.officetimeline.com/uploads/assets/graphical_itinerary_template_acac16f9ea.png" alt="Travel Itinerary">

          <p>Travel Itinerary & Planning Example</p>

        </div>

        

      </div>

    </section>



  </div>



  <footer>

    Portfolio of Tomiwa Raphael 

  </footer>



</body>

</html>
