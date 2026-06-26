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

* Ph.D. in Computer Science and Engineering, Wright State University — in progress
  * Current research under Professor Junjie Zhang.
  * Early Ph.D. research under Professor Fathi Amsaad.
  * Research interests: AI security, agentic AI security, software/security analysis, adversarial machine learning, and secure financial systems.
  * Graduate coursework includes Distributed Computing, Advanced Software Engineering, Algorithm Design and Analysis, Machine Learning, Cloud Computing, Fundamentals of Data Science, independent study, and residency research.
  * Graduate GPA: 4.00 through Spring 2026, based on graded coursework available in the transcript record.

* M.S. in Cyber Security, Cyberdefense Concentration, Wright State University — awarded December 14, 2024
  * Research under Professor Fathi Amsaad.
  * Graduate GPA: 4.00.
  * Thesis/research focus: adversarial machine learning and machine-learning-based hardware Trojan detection.

* B.S. in Computer Science, Birzeit University — awarded June 21, 2018
  * WES U.S. GPA equivalency: 3.22.
  * Broad CS foundation including programming, data structures, algorithms, operating systems, databases, artificial intelligence, image processing, networks, software engineering, web applications, digital systems, and computer security.

Research Interests
======

* Agentic AI and web-agent security
* AI-assisted software and malware security
* Software and network security
* Adversarial machine learning
* Hardware Trojan detection and trusted systems
* Trusted microelectronics and embedded systems security
* Financial/payment-system security
* Compliance-aware QA and regulated-system testing

Research Experience
======

* Current Ph.D. research under Professor Junjie Zhang: security analysis of agentic AI and web/browser-based AI agents.
* M.S. and early Ph.D. research under Professor Fathi Amsaad: adversarial machine learning, hardware Trojan detection, side-channel data, and ML-assisted hardware-security evaluation.
* Experience with experimental research workflows, literature review, research writing, and graduate-level independent study.

Professional Experience
======

* QA/UAT Analyst — Bank of Palestine, Cards / Payment Systems context
  * Performed business-side QA/UAT for card and payment systems.
  * Tested ATM, POS, mobile POS, online payment gateway, card issuance, instant issuance, and PowerCARD-Switch integrations.
  * Validated transaction routing, authorization behavior, reversals, settlement-related outputs, audit trails, card/payment workflows, and post-deployment behavior.
  * Supported compliance-aware and fraud-sensitive testing scenarios involving EMV-related validation, receipt/data masking, transaction limits, blacklisted cards, suspicious activity flags, and audit evidence.
  * Collaborated with business teams, IT support, vendors, accounting, compliance/audit stakeholders, and project managers.
  * Supported pilot rollouts, go-live readiness, defect retesting, post-deployment validation, and incident/complaint investigation.

Technical Skills
======

* Programming and scripting: Python, Java, shell scripting, JavaScript, SQL basics
* Cybersecurity: host security, information security, network security, reverse engineering, malware/security analysis concepts, applied cryptography, access control, vulnerability assessment concepts
* AI/ML: machine learning, adversarial machine learning, experimental evaluation, data analysis, Jupyter/Python workflows
* Systems: Linux, distributed computing, cloud computing concepts, computer networks, operating systems
* QA/UAT: manual testing, test case design, regression testing, integration testing, UAT, defect tracking, test evidence, payment transaction validation
* Tools and workflows: Git/GitHub, Jupyter, Overleaf/LaTeX, PowerCARD-Switch monitoring interfaces, Excel-based test documentation

Publications
======

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Projects
======

  <ul>{% for post in site.portfolio reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
