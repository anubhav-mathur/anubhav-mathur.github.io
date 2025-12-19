---
layout: default
title: Anubhav Mathur
---

{% include custom-header.html %}

<section id="about">
  <div class="about-content">
    <img src="/assets/img/PXL_20241219_193316216~2.jpg" alt="Anubhav Mathur">
    <h1>Anubhav Mathur</h1>
    <p>I am pursuing an MS in Computer Science at Georgia Tech with a focus on distributed systems and scalable computing. I am passionate about software engineering, backend development, and cloud-native architectures. I specialize in building reliable, high-performance services and bring experience in systems design, backend engineering, cloud infrastructure, DevOps, and AI/ML to develop robust, production-ready applications.</p><br>
    <a href="https://drive.google.com/file/d/1PMkkQTyEc5LT5mvJfxHdsXmyQPc_V9xI/view" target="_blank" class="resume-link">View Resume</a>
  </div>
</section>

<section id="experience">
  <div class="section-content">
    <h2>Experience</h2>
    <div class="experience-item">
      <h3 class="company-name">Volvo Group</h3>
      <div class="company-location">Greensboro, NC</div>
      <div class="position">
        <div class="position-header">
          <span class="position-title">Software Engineer Intern</span>
          <span class="experience-duration">May 2025 - Dec 2025</span>
        </div>
        <ul class="bullet-list">
          <li>Developed a full-stack shift bidding and assignment system to replace a slow, error-prone manual process used by HR. Built React pages for bid collection and review, Node.js APIs for workflow orchestration, and Azure Functions for authentication and scheduled processing.</li>
          <li>Automated shift assignment for warehouse workers using greedy algorithms in Python 
          and SQL, reducing 200+ hours of manual effort to under 10 seconds.</li>
          <li>Optimized data pipelines processing 100M+ records using Python, PySpark, SQL, and Databricks on Azure; developed a full-stack workforce hierarchy management platform using React and Node.js.</li>
        </ul>
      </div>
    </div><br>
    <div class="experience-item">
      <h3 class="company-name">Georgia Institute of Technology</h3>
      <div class="company-location">Atlanta, GA</div>
      <div class="position">
        <div class="position-header">
          <span class="position-title">Graduate Teaching Assistant, Introduction to Health Informatics</span>
          <span class="experience-duration">January 2025 - May 2025</span>
        </div>
        <ul class="bullet-list">
          <li>Assisted course instruction by designing labs, grading assignments/quizzes, and facilitating in-class learning activities.</li>
          <li>Mentored multiple student project groups, provided guidance on project scope, ensured progress through regular check-ins, and evaluated deliverables, similar to a product manager role.</li>
        </ul>
      </div>
    </div><br>
    <div class="experience-item">
      <h3 class="company-name">Fidelity Investments</h3>
      <div class="company-location">Bangalore, IN</div>
      <div class="position">
        <div class="position-header">
          <span class="position-title">Lead Software Engineer</span>
          <span class="experience-duration">March 2023 - July 2024</span>
        </div>
        <ul class="bullet-list">
          <li>Spearheaded the end-to-end development of a Java RESTful API generating personalized spending budgets for 10M retail customers from transaction histories, with results stored in AWS DynamoDB.</li>
          <li>Engineered scalable Spark-Scala big data processes on AWS EMR to aggregate multi-source data to calculate the net worth of 50M customers, improving data processing efficiency by 40%.</li>
          <li>Architected an application for generating financial insights, involving the aggregation of 5 TB of data, the construction of big data processing jobs, APIs, cloud-based storage, and real-time streaming to Snowflake.</li>
        </ul>
      </div>
      <div class="position" style="margin-top: 2rem;">
        <div class="position-header">
          <span class="position-title">Software Engineer</span>
          <span class="experience-duration">September 2021 - March 2023</span>
        </div>
        <ul class="bullet-list">
          <li>Developed a Java API to generate spending insights for 50M customers, a feature integrated into multiple frameworks and now a core component of Fidelity’s Spending experience.</li>
          <li>Orchestrated the migration of an API from a legacy source to an improved one, while live in production and handling high traffic of 300 TPS, developing thorough testing and rollout strategies to minimize disruption.</li>
          <li>Streamlined deployment and scaling with Docker and Kubernetes, reducing manual configuration by 50 hours/month and increasing availability by 60%, supporting 2,000+ concurrent users without performance degradation.</li>
        </ul>
      </div>
      <div class="position" style="margin-top: 2rem;">
        <div class="position-header">
          <span class="position-title">Associate Software Engineer</span>
          <span class="experience-duration">August 2020 - September 2021</span>
        </div>
        <ul class="bullet-list">
          <li>Devised Python ML models utilizing dimensionality reduction and SARIMA to analyze 3 billion+ customer transactions, detecting anomalies and forecasting spending, resulting in a 70k rise in planning customers.</li>
          <li>Created Splunk & Datadog dashboards and alerts, aiding in production support, traffic monitoring, and measuring application performance, saving 20 hours of human intervention per week.</li>
        </ul>
      </div>
    </div>

  </div>
</section>

<section id="education">
  <div class="section-content">
    <h2>Education</h2>
    <div class="education-item">
      <div class="education-header">
        <div>
          <h3 class="institution">Georgia Institute of Technology</h3>
          <div class="degree">Master of Science in Computer Science</div>
        </div>
        <span class="education-duration">August 2024 - Present</span>
      </div>
      <ul class="education-details">
        <li>GPA: 4.0/4.0</li>
        <li>Specializing in Computing Systems</li>
        <li>Relevant Courses: Graduate Algorithms, Database Systems, Computer Networks, Machine Learning</li>
      </ul>
    </div>
    <div class="education-item" style="margin-top: 2rem;">
      <div class="education-header">
        <div>
          <h3 class="institution">National Institute of Technology Kurukshetra</h3>
          <div class="degree">Bachelor of Technology in Computer Engineering</div>
        </div>
        <span class="education-duration">July 2016 - June 2020</span>
      </div>
      <ul class="education-details">
        <li>GPA: 9.59/10.00</li>
        <li>Relevant Courses: Software Engineering, Operating Systems, Distributed Systems, Data Structures</li>
      </ul>
    </div>

  </div>
</section>

<section id="projects">
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
          <h3 class="project-title">Dsitributed Rate Limiter</h3>
        </div>
        <span class="project-duration">April 2025 - May 2025</span>
      </div>
      <p class="project-description">Designed and implemented a distributed rate limiter in Go using gRPC and Redis, enforcing global request limits across multiple horizontally scaled instances using a token bucket algorithm coordinated via Lua scripting. Exposed real-time metrics via Prometheus and Grafana and validated system behavior under concurrent multi-node load.</p>
      <div class="tech-stack">
        <span class="tech-item">Go</span>
        <span class="tech-item">gRPC</span>
        <span class="tech-item">Distributed Systems</span>
        <span class="tech-item">Redis</span>
        <span class="tech-item">Grafana</span>
      </div>
      <div class="project-links">
        <a href="https://github.com/anubhav-mathur/distributed-rate-limiter" class="project-link">
          <img src="https://cdn-icons-png.flaticon.com/512/25/25231.png" alt="GitHub">
          GitHub
        </a>
      </div>
    </div>
    <div class="project-card">
      <div class="project-header">
        <div>
          <h3 class="project-title">Mini-Internet: Designing an Autonomous System with OSPF & BGP</h3>
          <div class="project-location">Georgia Institute of Technology</div>
        </div>
        <span class="project-duration">January 2025 - March 2025</span>
      </div>
      <p class="project-description">Built and managed a fully-functional virtual Autonomous System (AS) using OSPF and BGP, ensuring robust intra- and inter-domain routing. Implemented dynamic traffic engineering, load balancing, policy-driven peerings, and secured the network against BGP hijacking using RPKI.</p>
      <div class="tech-stack">
        <span class="tech-item">OSPF</span>
        <span class="tech-item">BGP</span>
        <span class="tech-item">RPKI Security</span>
        <span class="tech-item">Layer 2/3 Networking</span>
        <span class="tech-item">Traffic Engineering</span>
      </div>
    </div>
    <div class="project-card">
      <div class="project-header">
        <div>
          <h3 class="project-title">Graph Database-Powered Soccer Analytics with Neo4j</h3>
          <div class="project-location">Georgia Institute of Technology</div>
        </div>
        <span class="project-duration">August 2024 - December 2024</span>
      </div>
      <p class="project-description">Developed a scalable analytics platform using a Neo4j graph database, Flask API, and Streamlit frontend to efficiently rank European soccer teams via PageRank. Enhanced query performance through dynamic, in-memory graph projections, supporting fast CRUD operations and real-time analytics across 25,000+ matches.</p>
      <div class="tech-stack">
        <span class="tech-item">Neo4j Graph Database</span>
        <span class="tech-item">Flask REST API</span>
        <span class="tech-item">Streamlit</span>
        <span class="tech-item">Cypher Queries</span>
      </div>
      <div class="project-links">
        <a href="https://github.com/anubhav-mathur/cs6400-neo4j-soccer" class="project-link">
          <img src="https://cdn-icons-png.flaticon.com/512/25/25231.png" alt="GitHub">
          GitHub
        </a>
      </div>
    </div>
    <div class="project-card">
      <div class="project-header">
        <div>
          <h3 class="project-title">Detecting Domain Shadowing through DNS Analytics</h3>
          <div class="project-location">Georgia Institute of Technology</div>
        </div>
        <span class="project-duration">August 2024 - December 2024</span>
      </div>
      <p class="project-description">Built a DNS-based detection system to identify domain shadowing attacks by analyzing subdomain activity patterns, IP geolocations, and DNS traffic anomalies. Leveraged passive DNS datasets and clustering techniques to proactively flag suspicious network behavior, enhancing infrastructure security against sophisticated cyber threats.</p>
      <div class="tech-stack">
        <span class="tech-item">DNS Security</span>
        <span class="tech-item">Network Anomaly Detection</span>
        <span class="tech-item">IP Geolocation</span>
        <span class="tech-item">Passive DNS</span>
      </div>
      <div class="project-links">
        <a href="https://drive.google.com/file/d/16gPD6SglfsgwlAdD9NT9SNUeMSYWvryJ/view?usp=sharing" class="project-link">
          <img src="/assets/img/research-paper.png" alt="Paper">
          Technical Paper (Preprint)
        </a>
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
        <a href="https://www.ijariit.com/manuscript/a-comparison-of-machine-learning-techniques-for-predicting-imdb-score-of-movies/" class="project-link">
          <img src="/assets/img/research-paper.png" alt="Research Paper">
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
    </div>
    <div class="project-card">
      <div class="project-header">
        <div>
          <h3 class="project-title">SuspectRecon: AI-Powered Investigation Assistant</h3>
        </div>
        <span class="project-duration">January 2024 - March 2024</span>
      </div>
      <p class="project-description">Built an AI-driven application using Amazon PartyRock to help law enforcement visualize and analyze suspect data efficiently. Implemented prompt engineering and AI widgets for text and image generation, enabling quick insights from complex datasets.</p>
      <div class="tech-stack">
        <span class="tech-item">Amazon PartyRock</span>
        <span class="tech-item">Generative AI</span>
        <span class="tech-item">Prompt Engineering</span>
      </div>
      <div class="project-links">
        <a href="https://partyrock.aws/u/anubhavmathur/OWYjx_kRi/SuspectRecon" class="project-link">
          <img src="/assets/img/research-paper.png" alt="Try Out">
          Try Out
        </a>
        <a href="https://www.youtube.com/watch?v=M-WRxTai5MU" class="project-link">
          <img src="https://cdn-icons-png.flaticon.com/512/1384/1384060.png" alt="YouTube">
          YouTube
        </a>
      </div>
    </div>

  </div>
</section>

<section id="skills">
  <div class="section-content">
    <h2>Skills</h2>
    <div class="skills-category">
      <h3>Languages & Databases</h3>
      <div class="skills-grid">
        <div class="skill-item">
          <i class="fab fa-java"></i>
          <span>Java</span>
        </div>
        <div class="skill-item">
          <i class="fab fa-python"></i>
          <span>Python</span>
        </div>
        <div class="skill-item">
          <i class="fas fa-database"></i>
          <span>Scala</span>
        </div>
        <div class="skill-item">
          <i class="fa-brands fa-golang"></i>
          <span>Go</span>
        </div>
        <div class="skill-item">
          <i class="fas fa-database"></i>
          <span>SQL</span>
        </div>
        <div class="skill-item">
          <i class="fas fa-code"></i>
          <span>C++</span>
        </div>
        <div class="skill-item">
          <i class="fas fa-terminal"></i>
          <span>Shell</span>
        </div>
        <div class="skill-item">
          <i class="fab fa-html5"></i>
          <span>HTML</span>
        </div>
        <div class="skill-item">
          <i class="fab fa-js"></i>
          <span>JavaScript</span>
        </div>
        <div class="skill-item">
          <i class="fas fa-database"></i>
          <span>Oracle</span>
        </div>
        <div class="skill-item">
          <i class="fas fa-snowflake"></i>
          <span>Snowflake</span>
        </div>
        <div class="skill-item">
          <i class="fas fa-database"></i>
          <span>PostgreSQL</span>
        </div>
        <div class="skill-item">
          <i class="fas fa-project-diagram"></i>
          <span>Neo4j</span>
        </div>
      </div>
    </div>
    <div class="skills-category">
      <h3>Frameworks</h3>
      <div class="skills-grid">
        <div class="skill-item">
          <i class="fab fa-git-alt"></i>
          <span>Git</span>
        </div>
        <div class="skill-item">
          <i class="fas fa-leaf"></i>
          <span>SpringBoot</span>
        </div>
        <div class="skill-item">
          <i class="fas fa-cloud"></i>
          <span>REST</span>
        </div>
        <div class="skill-item">
          <i class="fas fa-box"></i>
          <span>Maven</span>
        </div>
        <div class="skill-item">
          <i class="fa-solid fa-hexagon-nodes"></i>
          <span>Hadoop</span>
        </div>
        <div class="skill-item">
          <i class="fas fa-bolt"></i>
          <span>Spark</span>
        </div>
        <div class="skill-item">
          <i class="fab fa-node"></i>
          <span>NodeJS</span>
        </div>
        <div class="skill-item">
          <i class="fab fa-python"></i>
          <span>Django</span>
        </div>
        <div class="skill-item">
          <i class="fas fa-flask"></i>
          <span>Flask</span>
        </div>
        <div class="skill-item">
          <i class="fas fa-brain"></i>
          <span>sklearn</span>
        </div>
        <div class="skill-item">
          <i class="fas fa-network-wired"></i>
          <span>TensorFlow</span>
        </div>
      </div>
    </div>

    <div class="skills-category">
      <h3>Tools & Platforms</h3>
      <div class="skills-grid">
        <div class="skill-item">
          <i class="fab fa-aws"></i>
          <span>AWS</span>
        </div>
        <div class="skill-item">
          <i class="fas fa-ship"></i>
          <span>Kubernetes</span>
        </div>
        <div class="skill-item">
          <i class="fab fa-docker"></i>
          <span>Docker</span>
        </div>
        <div class="skill-item">
          <i class="fab fa-microsoft"></i>
          <span>Azure</span>
        </div>
        <div class="skill-item">
          <i class="fas fa-chart-line"></i>
          <span>SonarQube</span>
        </div>
        <div class="skill-item">
          <i class="fas fa-database"></i>
          <span>Informatica</span>
        </div>
        <div class="skill-item">
          <i class="fas fa-chart-bar"></i>
          <span>Splunk</span>
        </div>
        <div class="skill-item">
          <i class="fas fa-tools"></i>
          <span>Jenkins</span>
        </div>
        <div class="skill-item">
          <i class="fas fa-chart-pie"></i>
          <span>Datadog</span>
        </div>
      </div>
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