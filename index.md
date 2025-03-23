---
layout: default
title: Anubhav Mathur
---

{% include custom-header.html %}

<section id="about">
  <div class="about-content">
    <img src="/assets/img/PXL_20241219_193316216~2.jpg" alt="Anubhav Mathur">
    <h1>Anubhav Mathur</h1>
    <p>Passionate about software engineering, data analytics, and cloud-based solutions, I specialize in building scalable and data-driven applications. I am pursuing an MS in Computer Science at Georgia Tech with a focus on data and computing systems. I bring together expertise in backend engineering, cloud infrastructure, big data, DevOps, and AI/ML to build reliable and high-performance systems.</p><br>
    <a href="https://drive.google.com/file/d/1PMkkQTyEc5LT5mvJfxHdsXmyQPc_V9xI/view" target="_blank" class="resume-link">View Resume</a>
  </div>
</section>

<section id="experience">
  <div class="section-content">
    <h2>Experience</h2>
    <div class="experience-item">
      <h3 class="company-name">Georgia Institute of Technology</h3>
      <div class="position">
        <span class="position-title">Graduate Teaching Assistant, Introduction to Health Informatics</span>
        <span class="duration">January 2024 - Present</span>
        <ul class="bullet-list">
          <li>Assisted course instruction by designing labs, grading assignments/quizzes, and facilitating in-class learning activities.</li>
          <li>Mentored multiple student project groups, provided guidance on project scope, ensured progress through regular check-ins, and evaluated deliverables, similar to a product manager role.</li>
        </ul>
      </div>
    </div><br>
    <div class="experience-item">
      <h3 class="company-name">Fidelity Investments</h3>
      <div class="position">
        <span class="position-title">Lead Software Engineer</span>
        <span class="duration">March 2023 - July 2024</span>
        <ul class="bullet-list">
          <li>Spearheaded the end-to-end development of a Java RESTful API generating personalized spending budgets for 10M retail customers from transaction histories, with results stored in AWS DynamoDB.</li>
          <li>Engineered scalable Spark-Scala big data processes on AWS EMR to aggregate multi-source data to calculate the net worth of 50M customers, improving data processing efficiency by 40%.</li>
          <li>Architected an application for generating financial insights, involving the aggregation of 5 TB of data, the construction of big data processing jobs, APIs, cloud-based storage, and real-time streaming to Snowflake.</li>
        </ul>
      </div>
      <div class="position" style="margin-top: 2rem;">
        <span class="position-title">Software Engineer</span>
        <span class="duration">September 2021 - March 2023</span>
        <ul class="bullet-list">
          <li>Developed a Java API to generate spending insights for 50M customers, a feature integrated into multiple frameworks and now a core component of Fidelity’s Spending experience.</li>
          <li>Orchestrated the migration of an API from a legacy source to an improved one, while live in production and handling high traffic of 300 TPS, developing thorough testing and rollout strategies to minimize disruption.</li>
          <li>Streamlined deployment and scaling with Docker and Kubernetes, reducing manual configuration by 50 hours/month and increasing availability by 60%, supporting 2,000+ concurrent users without performance degradation.</li>
        </ul>
      </div>
      <div class="position" style="margin-top: 2rem;">
        <span class="position-title">Associate Software Engineer</span>
        <span class="duration">August 2020 - September 2021</span>
        <ul class="bullet-list">
          <li>Devised Python ML models utilizing dimensionality reduction and SARIMA to analyze 3 billion+ customer transactions, detecting anomalies and forecasting spending, resulting in a 70k rise in planning customers.</li>
          <li>Created Splunk & Datadog dashboards and alerts, aiding in production support, traffic monitoring, and measuring application performance, saving 20 hours of human intervention per week.</li>
        </ul>
      </div>
    </div>

  </div>
</section>

<<section id="projects">
  <div class="section-content">
    <h2>Projects</h2>
    <div class="project-card">
      <div class="project-header">
        <div>
          <h3 class="project-title">Clinical Text Summarization using Large Language Models</h3>
          <div class="project-location">Georgia Institute of Technology</div>
        </div>
        <span class="project-duration">August 2024 - December 2024</span>
      </div>
      <p class="project-description">Crafted an NLP-driven system utilizing LLMs to automate the extraction and summarization of discharge summaries and patient visit data from clinical notes, optimizing clinician time by 90% and increasing note accuracy by 60%.</p>
      <div class="tech-stack">
        <span class="tech-item">LLMs</span>
        <span class="tech-item">HuggingFace</span>
        <span class="tech-item">Clinical Data Processing</span>
        <span class="tech-item">Text Summarization</span>
      </div>
    </div>
    <div class="project-card">
      <div class="project-header">
        <div>
          <h3 class="project-title">Predictive Modeling for IMDb Ratings</h3>
        </div>
        <span class="project-duration">November 2023 - January 2024</span>
      </div>
      <p class="project-description">Innovated a machine learning framework using Random Forest and LGBM regressors to predict IMDb scores based on features like genre, ratings, and budget. Improved accuracy by 25% through PCA and label encoding.</p>
      <div class="tech-stack">
        <span class="tech-item">Prinicpal Component Analysis</span>
        <span class="tech-item">Random Forest</span>
        <span class="tech-item">One-hot Encoding, Label Encoding</span>
        <span class="tech-item">Text Summarization</span>
      </div>
      <div class="project-links">
        <a href="#" class="project-link">
          <img src="https://cdn-icons-png.flaticon.com/512/25/25231.png" alt="Research Paper">
          Published Research Paper
        </a>
      </div>
    </div>
    <div class="project-card">
      <div class="project-header">
        <div>
          <h3 class="project-title">Load Forecasting and Energy Scheduling in a Smart Grid</h3>
          <div class="project-location">National Institute of Technology Kurukshetra</div>
        </div>
        <span class="project-duration">August 2019 - June 2020</span>
      </div>
      <p class="project-description">Implemented SVR and LSTM models to forecast power demand in a smart grid, achieving 92% prediction accuracy. Applied grid scheduling techniques, akin to CPU scheduling, to efficiently allocate electric power among 500 households and monitor appliance usage, reducing energy wastage by 20%.</p>
      <div class="tech-stack">
        <span class="tech-item">Grid Scheduling</span>
        <span class="tech-item">Support Vector Regression</span>
        <span class="tech-item">Long-Short Term Memory (LSTMs)</span>
        <span class="tech-item">Recurrent Neural Networks</span>
      </div>
      <div class="project-links">
        <a href="#" class="project-link">
          <img src="/assets/img/research-paper.png" class="research-paper-icon" alt="Research Paper">
          Published Research Paper
        </a>
      </div>
    </div>

  </div>
</section>

<section id="education">
  <div class="section-content">
    <h2>Education</h2>
    <div class="education-item">
      <h3 class="institution">Georgia Institute of Technology</h3>
      <p class="degree">Master of Science in Computer Science</p>
      <p class="education-duration">August 2024 - Present</p>
      <ul class="education-details">
        <li>GPA: 4.0/4.0</li>
        <li>Specializing in Computing Systems</li>
        <li>Relevant Courses: Graduate Algorithms, Database Systems, Computer Networks, Machine Learning</li>
      </ul>
    </div>
    <div class="education-item" style="margin-top: 2rem;">
      <h3 class="institution">National Institute of Technology Kurukshetra</h3>
      <p class="degree">Bachelor of Technology in Computer Engineering</p>
      <p class="education-duration">July 2016 - June 2020</p>
      <ul class="education-details">
        <li>GPA: 9.59/10.00</li>
        <li>Relevant Courses: Software Engineering, Operating Systems, Distributed Systems, Data Structures</li>
      </ul>
    </div>

  </div>
</section>

<section id="contact">
  <div class="section-content">
    <h2>Get in Touch</h2>
    <div class="social-links">
      <a href="https://linkedin.com/in/anubhav-m-44892210b" target="_blank">
        <img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" alt="LinkedIn">
      </a>
      <a href="https://github.com/anubhav-mathur" target="_blank">
        <img src="https://cdn-icons-png.flaticon.com/512/25/25231.png" alt="GitHub">
      </a>
      <a href="mailto:amathur310@gatech.edu">
        <img src="https://cdn-icons-png.flaticon.com/512/281/281769.png" alt="Email">
      </a>
    </div>
  </div>
</section>