---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Computer Science, University of Oklahoma, 2019
* M.S. in Computer Science, University of Oklahoma, 2017
* B.S. in Computer Science, University of Oklahoma, 2015

Work experience
======
* 2020-Present: Senior Software Engineer  
  * CoreLogic/cotality, Oklahoma City, Remote
  * Responsibilities:  
    - Led multiple teams across both modern and legacy technology stacks.  
    - Delivered multiple enterprise-scale platforms—including payments, appraisals, and analytics—from user-centered design to production, resulting in multi-million-dollar annual revenue.  
    - Coordinated, trained, and mentored full-time employees and contractors through paired programming, paired code reviews, book clubs, and hackathons.  
    - Increased MTBF by over 20% by achieving near-perfect scores (95% or above) for non-functional requirements such as vulnerabilities, code test coverage, and code smells.  
    - Reduced MTTR by over 100% by improving application logging and metrics, setting up alerting rules and dashboards, and enhancing documentation for on-call engineers.  
    - Optimized numerous services and processes, resulting in better response times and lower cost—improvements of over 200% in some cases.  

* 2012-2020: Senior Software Engineer  
  * University of Oklahoma (OU), Norman  
  * Responsibilities: 
    - Managed multiple contracts, teams, and projects throughout the university, including Oklahoms Department of Transportation, the OU Data Science Initiative, and the OU Supercomputing Center for Education and Research.
    - Developed and maintained a large-scale, distributed system for processing and analyzing time-evolving graphs.  
    - Collaborated with researchers and faculty to implement algorithms and techniques for graph compression and analysis.  
    - Published multiple papers in peer-reviewed conferences and journals, contributing to the field of computer science.  
    - Mentored undergraduate and graduate students in research projects, fostering their development in computer science.
  
Proficient Skills
======
* **Programming languages**: Python, Java, C#, JavaScript, TypeScript
* **Frameworks and libraries**: FastAPI, Django, React, LangChain, TensorFlow, PyTorch
* **Cloud platforms**: GCP, AWS, Kubernetes, Docker
* **Databases**: PostgreSQL (incl. AlloyDB), FAISS, Pinecone
* **Infrastructure and DevOps**: Terraform, ArgoCD, CI/CD pipelines, Prometheus, Grafana, Helm
* **AI and machine learning**: Transformer models, LLM-assisted development, API/SDK integration, data analysis
* **Performance optimization**: Profiling, benchmarking, load testing
* **Security**: OAuth, OIDC, JWT
* **Collaboration**: Team leadership, mentoring, pair programming, test-driven development (TDD)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
