---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

**Georgia Institute of Technology** | Atlanta, GA  
4.0 GPA _B.S. & M.S. in Computer Science_ (August 2022 – May 2026, August 2024 – May 2026)
Honors Program, Baseball Scholarship Recipient, Create-X I2P Grant, Dean’s List

## Skills

**Languages:** Java, Python, Node.js, SQL, R, C, JavaScript, HTML, CSS, Assembly  
**Technologies:** GitHub, React.js, NumPy, Shiny R, Express.js, Spring Boot, Open Liberty, Redis, JEST, Docker, Kubernetes  
**Courses:** Machine Learning, Data Structures and Algorithms, Computer Networking, Systems, Objects and Design  
**Other Skills:** Agile Methodology, MS Office, Test-Driven Development

## Work Experience

### **Incoming Stripe Software Engineering Intern** | Seattle, WA

**May 2025 – August 2025**

### **IBM Software Engineering Intern** | Armonk, NY

**May 2024 – August 2024**

- Built React.js dashboard with D3.js to track the flow of 4000+ daily invoicing documents across multiple systems, enabling insights into data volume through CloudantDB for optimizing scalability during peak billing cycles.
- Designed user help page for invoicing dashboard for 50+ new users during the team’s migration to SAP S/4 Hana.
- Addressed and resolved security vulnerabilities in 30+ requests by implementing robust session expiration logic in React.js and Express.js stack.

### **IBM Backend Developer Intern** | Research Triangle Park, NC

**May 2023 – August 2023**

- Designed Session ID engine middleware for product usage webhook in Express.js that received events from an aggregated source (Segment), enriched the event with Session IDs, and sent the data to IBM sources such as DB2, Amplitude, Kafka, and Cloud Object Storage.
- Efficiently managed over 900 unique users per minute and stored >30,000 Session IDs in Redis cache instance.
- Provided critical Session ID information that supported executive requests to track user cart abandonment and help convert more users from trial to paid versions.
- Deployed Python cron job to automate the generation of a markdown resource for team developers, consolidating documentation for a comprehensive overview.

### **Georgia Tech Baseball Data Analytics Lead** | Atlanta, GA

**August 2023 – Present**

- Led a team of four students in preparing and delivering weekly scouting reports for coaches.
- Developed and deployed a Shiny R web application with a dashboard summarizing CSV pitching data for player feedback, featuring 10+ visual charts and 15+ tables.
- Created Stuff+ Pitching Metrics using Principal Component Analysis for evaluating pitch effectiveness.

## Peer-Reviewed Publications

- Xiangru Tang, Arjun Nair, Borui Wang, Bingyao Wang, Jai Desai, Aaron Wade, Haoran Li, Asli Celikyilmaz, Yashar Mehdad, and Dragomir Radev. **CONFIT: Toward Faithful Dialogue Summarization with Linguistically-Informed Contrastive Fine-Tuning.** In _Proceedings of NAACL 2022._
- Borui Wang, Chengcheng Feng, Arjun Nair, Madelyn Mao, Jai Desai, Asli Celikyilmaz, Haoran Li, Yashar Mehdad, and Dragomir Radev. **STRUDEL: Structured Dialogue Summarization for Dialogue Comprehension.** In _Proceedings of EMNLP 2022._

## Research

### **Yale University and Facebook AI Research Assistant**

**March 2021 – June 2022** | New Haven, CT

- Developed Python scripts to clean and annotate data for deep learning summarization models.
- Conducted human evaluation of model performance, achieving state-of-the-art results using a taxonomy-based training strategy.

## Projects

### **‘Notator’ Automatic Notetaking Website** | Python, Flask, Django, HTML, JavaScript

[GitHub](https://github.com/jdesai22/notatorWeb)

- Website that scrapes web articles or receives custom text articles, recognizing keywords, quotations, and important phrases for streamlined note-taking.

### **Tic-Tac-Toe AI** | Python

[GitHub](https://github.com/jdesai22/gameAI)

- Tic-tac-toe game and AI featuring different levels, including a MiniMax Algorithm using backtracking and game theory.

### **Punchshot Pickleball** | Node.js, MongoDB, Express.js, React.js

**Jan 2023 – May 2023**

- Collaborated with a startup to build authentication, store player profiles, create teams, enter tournaments, and score pickleball matches.
- Stored data in MongoDB, retrieved via Express.js API, and rendered in React.

### **Momentum Sports Betting** | Python, Pandas, NumPy

[GitHub](https://github.com/jdesai22/sports-betting-analytics)

- Built an NBA player data and odds API pipeline using Pandas and NumPy to collect data, train a regression model, and make predictions based on previous game performance, achieving a 51.7% success rate (0.5% edge on sportsbooks).
- Received a $500 grant through Georgia Tech Create-X Idea to Prototype (I2P) Startup Program.

<!-- ---
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
* Ph.D in Version Control Theory, GitHub University, 2018 (expected)
* M.S. in Jekyll, GitHub University, 2014
* B.S. in GitHub, GitHub University, 2012

Work experience
======
* Spring 2024: Academic Pages Collaborator
  * GitHub University
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users

* Fall 2015: Research Assistant
  * GitHub University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

* Summer 2015: Research Assistant
  * GitHub University
  * Duties included: Tagging issues
  * Supervisor: Professor Git

Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Service and leadership
======
* Currently signed in to 43 different slack teams -->
