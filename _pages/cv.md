---
layout: page
permalink: /cv/
title: CV
nav: true
nav_order: 50
toc:
  sidebar: left
---

<style>
  @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;600;700&family=Lato:ital,wght@0,400;0,600;1,400&display=swap');

  :root {
    --primary:      #2e4a7a;
    --primary-light:#3a5c96;
    --accent-soft:  #c8b8f0;
    --accent-warm:  #f0c8b8;
    --text-main:    #333;
    --text-muted:   #666;
  }

  /* ── Section headings ───────────────────────────────── */
  .cv-section-heading {
    font-family: 'Roboto', sans-serif;
    font-size: 1.45rem;
    font-weight: 700;
    color: var(--primary);
    border-bottom: 2px solid var(--primary);
    padding-bottom: 5px;
    margin-top: 2.2rem;
    margin-bottom: 1rem;
    letter-spacing: 0.01em;
  }

  /* ── Entry block ────────────────────────────────────── */
  .cv-entry {
    margin-bottom: 1.2rem;
  }
  .cv-entry-header {
    display: flex;
    justify-content: space-between;
    align-items: baseline;
    flex-wrap: wrap;
    gap: 4px;
  }
  .cv-entry-title {
    font-family: 'Lato', sans-serif;
    font-size: 1rem;
    font-weight: 700;
    color: var(--primary);
  }
  .cv-entry-date {
    font-family: 'Lato', sans-serif;
    font-size: 0.82rem;
    color: var(--text-muted);
    white-space: nowrap;
  }
  .cv-entry-subtitle {
    font-family: 'Lato', sans-serif;
    font-size: 0.92rem;
    font-style: italic;
    color: var(--text-muted);
    margin-top: 1px;
    margin-bottom: 4px;
  }

  /* ── Bullet lists ───────────────────────────────────── */
  .cv-list {
    list-style: none;
    padding-left: 0;
    margin-top: 0.4rem;
  }
  .cv-list li {
    font-family: 'Lato', sans-serif;
    font-size: 0.93rem;
    color: var(--text-main);
    border-left: 3px solid var(--accent-soft);
    padding: 4px 0 4px 10px;
    margin-bottom: 5px;
    line-height: 1.5;
  }
  .cv-list.warm li {
    border-left-color: var(--accent-warm);
  }
  .cv-list.plain li {
    border-left: none;
    padding-left: 0;
  }

  /* ── Course list — Courier New ──────────────────────── */
  .cv-course-list {
    list-style: none;
    padding-left: 0;
    margin-top: 0.3rem;
    columns: 2;
    column-gap: 1.5rem;
  }
  .cv-course-list li {
    font-family: 'Courier New', monospace;
    font-size: 0.88rem;
    color: var(--text-main);
    border-left: 3px solid var(--accent-soft);
    padding: 3px 0 3px 10px;
    margin-bottom: 4px;
    break-inside: avoid;
  }

  /* ── Publication entries ────────────────────────────── */
  .cv-pub {
    font-family: 'Lato', sans-serif;
    font-size: 0.92rem;
    color: var(--text-main);
    border-left: 3px solid var(--accent-soft);
    padding: 5px 0 5px 10px;
    margin-bottom: 10px;
    line-height: 1.55;
  }
  .cv-pub .pub-authors { color: var(--text-main); }
  .cv-pub .pub-title   { font-weight: 700; color: var(--primary); }
  .cv-pub .pub-venue   { font-style: italic; color: var(--text-muted); }
  .cv-pub .pub-doi     { font-size: 0.8rem; color: var(--text-muted); }

  /* ── Sub-section label ──────────────────────────────── */
  .cv-sub-heading {
    font-family: 'Lato', sans-serif;
    font-size: 0.8rem;
    font-weight: 700;
    color: var(--text-muted);
    text-transform: uppercase;
    letter-spacing: 0.1em;
    margin-top: 1rem;
    margin-bottom: 0.4rem;
  }

  /* ── Tag / badge ────────────────────────────────────── */
  .cv-tag {
    display: inline-block;
    font-family: 'Lato', sans-serif;
    font-size: 0.75rem;
    font-weight: 700;
    background: #e0e8f5;
    color: var(--primary);
    border-radius: 4px;
    padding: 2px 8px;
    margin-right: 4px;
    margin-bottom: 4px;
  }
</style>

---

## Education
{: .cv-section-heading }

<div class="cv-entry">
  <div class="cv-entry-header">
    <span class="cv-entry-title">PhD, Electrical Engineering and Computer Science</span>
    <span class="cv-entry-date">2023</span>
  </div>
  <div class="cv-entry-subtitle">Wichita State University, Wichita, KS</div>
  <ul class="cv-list plain">
    <li>Dissertation: <em>Methods to Achieve t-closeness for Privacy Preserving Data Publishing</em></li>
  </ul>
</div>

<div class="cv-entry">
  <div class="cv-entry-header">
    <span class="cv-entry-title">MS, Electrical Engineering</span>
    <span class="cv-entry-date">2017</span>
  </div>
  <div class="cv-entry-subtitle">Rochester Institute of Technology, Rochester, NY</div>
  <ul class="cv-list plain">
    <li>Graduate Paper: <em>Color Face Recognition using Quaternion based Gabor Filter</em></li>
  </ul>
</div>

<div class="cv-entry">
  <div class="cv-entry-header">
    <span class="cv-entry-title">BE, Electronics and Communication Engineering</span>
    <span class="cv-entry-date">2015</span>
  </div>
  <div class="cv-entry-subtitle">Visvesvaraya Technological University, India</div>
</div>

---

## Certifications
{: .cv-section-heading }

<ul class="cv-list">
  <li>
    <strong>Agentic AI Intensive</strong> — Harvard Data Science Initiative &amp; Harvard Data Science Review
    <em>(In Progress, 2026)</em><br>
    2.5-week executive program on agentic AI workflow design, strategic frameworks, and responsible deployment.
  </li>
</ul>


---

## Professional Experience
{: .cv-section-heading }

<div class="cv-entry">
  <div class="cv-entry-header">
    <span class="cv-entry-title">Assistant Professor of Computer Science</span>
    <span class="cv-entry-date">July 2023 – Present</span>
  </div>
  <div class="cv-entry-subtitle">Champlain College, Burlington, VT</div>
  <ul class="cv-list">
    <li>Teach 10+ courses across Computer Science and Data Analytics, from introductory programming to advanced Machine Learning and AI.</li>
    <li>Designed and developed course materials to stay aligned with emerging technologies and improve student understanding.</li>
    <li>Involve undergraduate students in full research lifecycle resulting in co-authored peer-reviewed publications.</li>
    <li>Advise approximately 20 undergraduate students per academic year..</li>
  </ul>

  <p class="cv-sub-heading">Courses Taught or Currently Teaching</p>
  <ul class="cv-course-list">
    <li>CSI 140: Introduction to Programming</li>
    <li>CSI 160: Python Programming</li>
    <li>CSI 260: Advanced Python</li>
    <li>CSI 300: Database Management Systems</li>
    <li>CSI 380: Emerging Languages</li>
    <li>CSI 480: Topics in Artificial Intelligence</li>
    <li>DAT 210: Data Analytics</li>
    <li>DAT 230: Data Visualization</li>
    <li>DAT 310: Big Data Analytics</li>
    <li>DAT 330: Data Mining</li>
    <li>DAT 410: Machine Learning</li>
  </ul>
</div>

<div class="cv-entry">
  <div class="cv-entry-header">
    <span class="cv-entry-title">Graduate Assistant: Direct Instructor</span>
    <span class="cv-entry-date">Aug 2021 – May 2023</span>
  </div>
  <div class="cv-entry-subtitle">Wichita State University</div>
  <ul class="cv-list warm">
    <li>Independently developed and delivered lectures covering core Computer Science concepts as instructor on record.</li>
    <li>Designed course materials, including assignments, exams, and lab exercises, to align with learning objectives.</li>
    <li>Supervised hands-on lab sessions and practical exercises to reinforce theory.</li>
    <li>Provided student support through office hours and detailed feedback.</li>
    <li>Managed all course administration using the institutional learning management system.</li>
  </ul>

  <p class="cv-sub-heading">Courses / Labs Instructed</p>
  <ul class="cv-course-list">
    <li>CS 540: Operating Systems (Spring 2023)</li>
    <li>CS 211: Introduction to Programming (Fall 2021, Spring 2022, Summer 2022, Fall 2022, Spring 2023)</li>
    <li>CS 211L: Problem Solving &amp; Programming Lab (Fall 2021, Spring 2022, Summer 2022, Fall 2022, Spring 2023)</li>
  </ul>
</div>

<div class="cv-entry">
  <div class="cv-entry-header">
    <span class="cv-entry-title">Graduate Teaching Assistant</span>
    <span class="cv-entry-date">Jan 2019 – May 2021</span>
  </div>
  <div class="cv-entry-subtitle">Wichita State University</div>
  <ul class="cv-list warm">
    <li>Assisted faculty in teaching computer science courses by leading lab sessions, grading assignments and exams, and managing classroom technology.</li>
    <li>Mentored students during lab sessions and office hours, providing guidance on projects and reinforcing complex concepts.</li>
  </ul>

  <p class="cv-sub-heading">Supported Courses / Labs</p>
  <ul class="cv-course-list">
    <li>CS 410: Program Paradigms</li>
    <li>CS 464: Computer Networks</li>
    <li>CS 194: Introduction to Digital Design</li>
    <li>CS 211L: Problem Solving &amp; Programming Lab</li>
    <li>CS 594L: Microprocessor System Design Lab</li>
  </ul>
</div>

---

## Course & Curriculum Development
{: .cv-section-heading }

<ul class="cv-list">
  <li><strong>Program Innovation:</strong> Collaborating on re-designing the <em>Data Analytics</em> minor.</li>
  <li><strong>Curriculum Leadership:</strong> Led comprehensive revisions for the Data Analytics major, updating course descriptions, learning outcomes, assessment methods, and curriculum mapping in collaboration with the Program Director.</li>
  <li><strong>Instructional Design:</strong> Designed and implemented revised syllabi and instructional materials for Data Analytics (DAT 210), Data Visualization (DAT 230), and Big Data Analytics (DAT 310).
    <ul style="margin-top:6px; padding-left:16px; list-style:disc;">
      <li style="font-family:'Lato',sans-serif; font-size:0.9rem; color:#444; margin-bottom:4px;"><strong>DAT 210:</strong> Following curriculum modifications, student enrollment increased by 50% and evaluations improved from 4.2 to 4.43/5.0.</li>
      <li style="font-family:'Lato',sans-serif; font-size:0.9rem; color:#444; margin-bottom:4px;"><strong>DAT 310:</strong> Restructured to emphasize applied machine learning; student evaluation scores increased from 3.6 to 4.72/5.0.</li>
    </ul>
  </li>
  <li><strong>Governance &amp; Alignment:</strong> Successfully guided all curricular updates through internal institutional review and approval processes, ensuring alignment with program-level learning objectives.</li>
</ul>


---

## Research Interests
{: .cv-section-heading }

<span class="cv-tag">Privacy-Preserving Data Publishing</span>
<span class="cv-tag">Data Anonymization Algorithms</span>
<span class="cv-tag">Trustworthy AI</span>
<span class="cv-tag">Machine Learning and Computer Vision</span>
<span class="cv-tag">Fairness and Bias in AI Systems</span>

---

## Publications
{: .cv-section-heading }

<p class="cv-sub-heading">Journal</p>

<div class="cv-pub">
  <span class="pub-authors">V. Thammanna Gowda, L. Humphrey, A. Kadoch, Y. Chen, O. Roberts.</span>
  "<span class="pub-title">Multi Attribute Stratified Sampling: An Automated Framework for Privacy-Preserving Healthcare Data Publishing with Multiple Sensitive Attributes.</span>"
  <span class="pub-venue">Advances in Science, Technology and Engineering Systems Journal (ASTESJ)</span>, Volume 11, Issue 1, pp. 51–68, 2026.
  <br><span class="pub-doi">DOI: 10.25046/aj110106</span>
</div>

<div class="cv-pub">
  <span class="pub-authors">R. Bagai, E. Weber, V. Thammanna Gowda.</span>
  "<span class="pub-title">Data Sanitization for t-Closeness over Multiple Numerical Sensitive Attributes.</span>"
  <span class="pub-venue">Transactions on Data Privacy</span>, vol. 16, no. 3, pp. 191–210, 2023.
</div>

<p class="cv-sub-heading">Conference</p>

<div class="cv-pub">
  <span class="pub-authors">V. Thammanna Gowda, M. Lee, V. Campagna.</span>
  "<span class="pub-title">Enhanced Stratified Sampling: A Method for Privacy-Preserving Big Data Publishing.</span>"
  <span class="pub-venue">IEEE Conference on Future Machine Learning and Data Science (FMLDS)</span>, Sydney, Australia, 2024, pp. 265–269.
  <br><span class="pub-doi">DOI: 10.1109/FMLDS63805.2024.00056</span>
</div>

<div class="cv-pub">
  <span class="pub-authors">V. Thammanna Gowda, R. Bagai.</span>
  "<span class="pub-title">Generating t-closed partitions of datasets with multiple sensitive attributes.</span>"
  <span class="pub-venue">Proceedings of the 2023 7th International Conference on Cryptography, Security and Privacy (CSP)</span>, Tianjin, China, 2023, pp. 107–111.
  <br><span class="pub-doi">DOI: 10.1109/CSP58884.2023.00024</span>
</div>

<div class="cv-pub">
  <span class="pub-authors">V. Thammanna Gowda, R. Bagai, G. Spilinek, S. Vitalapura.</span>
  "<span class="pub-title">Efficient Near-Optimal t-Closeness With Low Information Loss.</span>"
  <span class="pub-venue">Proceedings of the 11th IEEE International Conference on Intelligent Data Acquisition and Advanced Computing Systems: Technology and Applications (IDAACS)</span>, Cracow, Poland, 2021, pp. 494–498.
  <br><span class="pub-doi">DOI: 10.1109/IDAACS53288.2021.9661004</span>
</div>

---

## Research in Progress
{: .cv-section-heading }

<div class="cv-pub">
  <span class="pub-authors">V. Thammanna Gowda, R. Gouda Kulkarni.</span>
  "<span class="pub-title">Imaging Conditions and Demographic Bias in Face Recognition: A Systematic Multi-Source Investigation.</span>"
  <span class="pub-venue">Target: IEEE Transactions on Image Processing.</span>
</div>

<div class="cv-pub">
  <span class="pub-authors">V. Thammanna Gowda, C. Hill, A. Zeng.</span>
  "<span class="pub-title">v-Difference Privacy: Theoretical Foundations and Polynomial-Time Approximation Algorithms.</span>"
  <span class="pub-venue">Target: IEEE Transactions on Knowledge and Data Engineering.</span>
</div>

---

## Paper Presentations
{: .cv-section-heading }

<ul class="cv-list">
  <li>"Enhanced Stratified Sampling: A Method for Privacy-Preserving Big Data Publishing." <em>FMLDS 2024</em></li>
  <li>"Generating t-closed partitions of datasets with multiple sensitive attributes." <em>CSP 2023</em></li>
  <li>"Efficient Near-Optimal t-Closeness With Low Information Loss." <em>IDAACS 2021</em></li>
</ul>

---

## Grants and Funding
{: .cv-section-heading }

<div class="cv-entry">
  <div class="cv-entry-header">
    <span class="cv-entry-title">Subject Matter Expert: Full Stack Web Development</span>
    <span class="cv-entry-date">Sept 2024 – Dec 2025</span>
  </div>
  <div class="cv-entry-subtitle">Davis Educational Foundation Grant, Champlain College</div>
  <ul class="cv-list">
    <li>Serve as subject matter expert for a grant-funded initiative to develop full-stack web applications that visualize college curriculum competency data for institutional assessment.</li>
    <li>Lead and supervise a multidisciplinary undergraduate student team, including hiring, mentoring, and performance oversight.</li>
    <li>Coordinate project milestones, technical documentation, and deliverables in collaboration with grant administrators and institutional stakeholders.</li>
    <li>Produce data-driven visualizations that support curriculum evaluation and evidence-based teaching improvements.</li>
  </ul>
</div>

<div class="cv-entry">
  <div class="cv-entry-header">
    <span class="cv-entry-title">Student Experience Grant</span>
    <span class="cv-entry-date">Fall 2025</span>
  </div>
  <div class="cv-entry-subtitle">John W. Heisse, Jr., M.D. Endowment Fund, Champlain College</div>
  <ul class="cv-list">
    <li>Project: Undergraduate Co-authoring Extension of IEEE FMLDS Conference Paper to ASTES Journal Special Issue.</li>
    <li>Role: Principal Investigator. Involved 4 undergraduate students.</li>
  </ul>
</div>

<div class="cv-entry">
  <div class="cv-entry-header">
    <span class="cv-entry-title">Undergraduate Research Grant</span>
    <span class="cv-entry-date">Fall 2024</span>
  </div>
  <div class="cv-entry-subtitle">ITS Program Budget, Champlain College</div>
  <ul class="cv-list">
    <li>Project: Undergraduate Co-authored IEEE FMLDS 2025 Conference Paper.</li>
    <li>Role: Principal Investigator. Involved 2 undergraduate students.</li>
  </ul>
</div>

<div class="cv-entry">
  <div class="cv-entry-header">
    <span class="cv-entry-title">Graduate School Mill Levy Funds</span>
    <span class="cv-entry-date">Spring 2022</span>
  </div>
  <div class="cv-entry-subtitle">Wichita State University</div>
</div>

---

## Professional Development
{: .cv-section-heading }

<ul class="cv-list">
  <li>Maryland LEAD: Ethical Leadership Course, Leadership Community Service-Learning — <em>February 2026</em></li>
  <li>AI and Career Empowerment, University of Maryland Robert H. Smith School of Business — <em>February 2026</em></li>
</ul>

---

## Service
{: .cv-section-heading }

<p class="cv-sub-heading">Institutional Service</p>
<ul class="cv-list">
  <li>Member, Academic Affairs Committee, Champlain College — <em>Fall 2024–Present</em></li>
  <li>Academic Advisor for undergraduate students, Champlain College — <em>Fall 2023–Present</em></li>
</ul>

<p class="cv-sub-heading">Professional Service</p>
<ul class="cv-list">
  <li>Reviewer, <em>Advances in Science, Technology and Engineering Systems Journal</em></li>
  <li>Reviewer, <em>Journal of Circuits, Systems, and Computers</em></li>
  <li>Steering Committee Member &amp; Publicity Co-Chair, ALLDATA — <em>2025, 2026</em></li>
  <li>Technical Program Committee Member, CCSC Northeast — <em>2025, 2026</em></li>
  <li>Technical Program Committee Member, CSP — <em>2025, 2026</em></li>
  <li>Technical Program Committee Member, IEEE FMLDS — <em>2024, 2025</em></li>
</ul>

---

## Scholarships and Awards
{: .cv-section-heading }

<ul class="cv-list">
  <li>Graduate Assistant Scholarship — <em>Fall 2021–Spring 2023</em></li>
  <li>Indian Student Association Scholarship — <em>Spring 2019</em></li>
  <li>Graduate Teaching Assistant Scholarship — <em>Spring 2019–Spring 2021</em></li>
  <li>Graduate Scholarship — <em>Fall 2015–Spring 2017</em></li>
</ul>