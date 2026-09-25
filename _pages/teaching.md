---
layout: page
permalink: /teaching/
title: Teaching
description: A list of my online and undergraduate courses.
nav: true
nav_order: 6
---

## 📚 Course Pages

Detailed pages (schedule, grading, and student projects) for current courses.

{% include courses.liquid %}

<br>

## 💻 Online Courses (KOCW)

---

- **Python Programming**
  Covers the fundamentals of Python programming for data analysis, including Python installation, variables, operators, conditionals, loops, functions, and libraries like Numpy and Pandas. (KOCW)
  **Lecture Link:** [http://kocw.net/home/cview.do?cid=3aeee0aa8ad8e840](http://kocw.net/home/cview.do?cid=3aeee0aa8ad8e840)

- **Python Programming 2**
  Focused on object-oriented programming and fundamental Python concepts, this lecture is tailored for learners seeking a deeper understanding of Python programming essentials. (KOCW)
  **Lecture Link:** [http://www.kocw.net/home/search/kemView.do?kemId=1368521](http://www.kocw.net/home/search/kemView.do?kemId=1368521)

- **R Programming (Big Data Analysis)**
  Focuses on the basics of data analysis using R programming, covering R installation, data preprocessing, visualization, descriptive statistics, regression analysis, and more. (KOCW)
  **Lecture Link:** [http://www.kocw.net/home/search/kemView.do?kemId=1335286](http://www.kocw.net/home/search/kemView.do?kemId=1335286)

- **JAVA Programming (Fundamentals of Programming)**
  This lecture uses Java to teach the fundamental concepts and principles of programming. It covers core programming elements such as variables, operators, conditionals, and loops, as well as an introduction to object-oriented programming fundamentals. (KOCW)
  **Lecture Link:** [http://www.kocw.net/home/search/kemView.do?kemId=1351017](httpS://www.kocw.net/home/search/kemView.do?kemId=1351017)

<br>

## 🏫 University Courses

---

### Hankuk University of Foreign Studies, Seoul, South Korea (2025 - )

#### 2026 Fall

- **[M04103201] Fundamentals of Social Data Programming**
  An introduction to Python for students with no programming background. Beyond syntax, the course trains students to read, question, and repair AI-generated code — the literacy that matters most once a model writes the first draft.

{% details Course Details %}

**Course Focus**

- Step-by-step coverage of numbers and strings, lists and tuples, dictionaries and sets, operators, conditionals, loops, functions, file I/O, classes, modules, and packages
- Every concept practiced as a cycle: run it, modify it, diagnose the error, explain the fix
- Google Colab for the first half; VS Code from week 12 onward for multi-file programs

**Learning Objectives**

- Represent social data with appropriate types and structures, and implement processing logic with conditionals, loops, and functions
- Read execution flow and error messages to diagnose boundary, type, index, file path, and exception problems
- Write small programs that load, classify, aggregate, and save anonymized CSV and text data
- Record where AI assistance was used and how it was verified, and explain results with data ethics and reproducibility in mind

{% enddetails %}

- **[M04112201] Technology Development Research Project**
  A studio course in which each student defines a problem, builds a working service with a coding agent (Claude Code), verifies it, and deploys it. There are no exams: the semester produces a personal homepage and one deployed project, and every student is assessed on whether they can read, run, and explain the changes the agent proposes.
  **Course Page:** [donghyunlee-lab.github.io/teaching/tech-development-project](/teaching/tech-development-project/)

{% details Course Details %}

**Semester Structure**

- Weeks 2–5: build and deploy a personal homepage — information structure, HTML and CSS, Git, README, and a public URL
- Weeks 4–8: choose one user and one problem, fix the core flows and the definition of done, and reach a working mid-term MVP
- Weeks 9–15: user testing, quality and security review, deployment, documentation, and a final demo with a retrospective
- Each 150-minute session spends 85 minutes on development with rotating coaching, and closes with a three-line record: what was done, what was verified, what comes next

**Project Tracks**

- Public and social data explorers — youth employment, population change, commuting time and cost
- Campus and community information services — scholarships, exchange-student life, campus facilities and events
- Research support tools — survey CSV checkers, interview tagging boards, literature evidence cards
- Comparison and simulation tools — commuting alternatives, event budgets, time-use scenarios

**Learning Objectives**

- Fix the user, the problem, the core flows, and a definition of done before writing code
- Write requests that carry the goal, the context, and the completion criteria, then read and run the agent's changes instead of accepting them
- Diagnose failures through reproduction, boundary conditions, and logs, and confirm each fix under the conditions that exposed it
- Handle data sources, personal information, and secrets responsibly, and gather feedback from at least three real users
- Deploy a reproducible service with a README and explain the design decisions, the verification evidence, and the remaining limits

{% enddetails %}

- **[M04111101] Industrial Data Visualization**
  Select the chart that fits the analytical goal — comparison, trend, distribution, or relationship — and turn an AI-generated draft into a defensible visualization. Students build static charts with Matplotlib and Seaborn, interactive charts with Plotly, and integrate them into a deployed Streamlit dashboard.

{% details Course Details %}

**Chart Literacy**

- Diagnose how truncated axes, selective ranges, wrong aggregation, and misleading color or labels distort a message
- Control Figure and Axes explicitly rather than accepting library defaults
- Critique and redesign AI-drafted charts on the basis of evidence rather than decoration
- Apply accessibility rules: never encode a category by color alone, keep sufficient contrast, and keep labels readable

**Learning Objectives**

- Choose chart types that match both the data and the intended claim
- Build static charts with Matplotlib and Seaborn, controlling color, axes, annotation, and legends
- Design interactive charts in Plotly and combine multiple charts and widgets into a Streamlit dashboard
- Deliver a one-sentence claim supported by data evidence and a visual narrative, published to the web

{% enddetails %}

---

#### 2026 Spring

- **[M04107101] Object-Oriented Programming**
  Learn the principles and practical applications of Object-Oriented Programming (OOP) — a core paradigm of modern software engineering — through Python. This course cultivates object-oriented design skills for social science data modeling.

{% details Course Details %}

**What is OOP?**

- A methodology that models programs as interactions among meaningful _objects_, rather than a simple sequence of commands
- Bundles data (state) and functionality (methods) together to solve complex problems intuitively
- A core paradigm that improves code reusability and maintainability

**Learning Objectives**

- Master core Python syntax and develop computational thinking skills
- Understand the four pillars of OOP: Abstraction, Encapsulation, Inheritance, and Polymorphism
- Systematically structure data through classes and objects
- Cultivate design skills for solving social science problems using OOP

{% enddetails %}

- **[M04114101] Deep Learning and Applications**
  Study the theory and practice of artificial neural networks — from individual neurons to modern deep learning architectures (CNN, LSTM, etc.). Implement core mechanisms from scratch with NumPy to understand the mathematical principles, then build practical models with PyTorch for data analysis.

{% details Course Details %}

**Core Mechanisms**

- Implement deep learning algorithms from scratch with NumPy to understand mathematical foundations
- Hands-on practice with modern neural network architectures using PyTorch
- Applied analysis of image and time-series social science data

**Learning Objectives**

- Clearly understand the mathematical foundations of neural networks and Backpropagation
- Implement a Multi-Layer Perceptron (MLP) from scratch using only NumPy
- Design and train CNN and LSTM models using the PyTorch framework
- Develop practical deep learning skills for image and time-series data

{% enddetails %}

---

#### 2025 Fall

- **[M04103201] Fundamentals of Social Data Programming**
  This course covers the fundamental concepts of programming using Python. Students will learn to use Python data types, operators, conditionals, loops, functions, and classes, and understand Pythonic code, modules, packages, and exception handling.

- **[M04112101] Understanding Technology Development Research**
  Understand technology management and the high-tech industry. Learn methodologies for technology development based on consumer preference and market analysis. Study factors to consider in the commercialization process of new technologies.

- **[M04111101] Industrial Data Visualization**
  Learn data preprocessing using Python, focusing on Numpy and Pandas libraries. Learn how to appropriately visualize various data using libraries like Matplotlib.

---

### Tech University of Korea, Siheung-si, South Korea (2017 - 2024)

#### 2024 Spring

- **[AEB43017] Big Data Analysis**
  R programming and statistics. Covers fundamental concepts of data, regression analysis, basic programming, data preprocessing, and visualization using R.
- **[AEB13018] Fundamentals of Programming**
  Basic programming with JAVA, focusing on fundamental programming concepts and techniques.
- **[AEB44011] Management Capstone Design 1**
  Performing graduate research using research methodologies.

---

#### 2023 Fall

- **[AEB21022] Programming and Data Analysis**
  Basic programming with Python, covering object-oriented concepts such as classes, modules, and packages and introduction to data preprocessing.

---

#### 2023 Spring

- **[AEB43017] Big Data Analysis**
  R programming and statistics. Covers fundamental concepts of data, regression analysis, basic programming, data preprocessing, and visualization using R.
- **[AEB13018] Fundamentals of Programming**
  Basic programming with JAVA, focusing on fundamental programming concepts and techniques.
- **[AEB44011] Management Capstone Design 1**
  Performing graduate research using research methodologies.

---

#### 2022 Fall

- **[AEB21022] Programming and Data Analysis**
  Basic programming with Python, covering object-oriented concepts such as classes, modules, and packages and introduction to data preprocessing.
- **[AEB34013] Management Capstone Design 2**
  Graduate research using advanced research methodologies.
- **[AEB34002] Management Capstone Design Planning**
  Exploration of graduation research topics and foundational research methodologies.

---

#### 2022 Spring

- **[AEB43017] Big Data Analysis**
  R programming and statistics. Covers fundamental concepts of data, regression analysis, basic programming, data preprocessing, and visualization using R.
- **[AEB13018] Fundamentals of Programming**
  Basic programming with JAVA, focusing on fundamental programming concepts and techniques.
- **[AEB44011] Management Capstone Design 1**
  Performing graduate research using research methodologies.

---

#### 2021 Fall

- **[AEB21022] Programming and Data Analysis**
  Basic programming with Python, covering object-oriented concepts such as classes, modules, and packages and introduction to data preprocessing.
- **[AEB33017] Advanced IT Service Techniques**
  Deep learning and machine learning concepts with practical Python applications.
- **[AEB34013] Management Capstone Design 2**
  Graduate research using advanced research methodologies.
- **[AEB34002] Management Capstone Design Planning**
  Exploration of graduation research topics and foundational research methodologies.

---

#### 2021 Spring

- **[AEB43017] Big Data Analysis**
  R programming and statistics. Covers fundamental concepts of data, regression analysis, basic programming, data preprocessing, and visualization using R.
- **[AEB13018] Fundamentals of Programming**
  Basic programming with JAVA, focusing on fundamental programming concepts and techniques.
- **[AEB44011] Management Capstone Design 1**
  Performing graduate research using research methodologies.

---

#### 2020 Fall

- **[AEB33017] Advanced IT Service Techniques**
  Deep learning and machine learning concepts with practical Python applications.
- **[AEB34013] Management Capstone Design 2**
  Graduate research using advanced research methodologies.
- **[AEB34002] Management Capstone Design Planning**
  Exploration of graduation research topics and foundational research methodologies.

---

#### 2020 Spring

- **[AEB43017] Big Data Analysis**
  R programming and statistics. Covers fundamental concepts of data, regression analysis, basic programming, data preprocessing, and visualization using R.
- **[AEB13018] Fundamentals of Programming**
  Basic programming with JAVA, focusing on fundamental programming concepts and techniques.
- **[AEB44011] Management Capstone Design 1**
  Performing graduate research using research methodologies.

---

#### 2019 Fall

- **[AEB33017] Advanced IT Service Techniques**
  Deep learning and machine learning concepts with practical Python applications.
- **[AEB23017] Understanding Programming**
  Basics of programming and data analysis using R.
- **[AEB34013] Management Capstone Design 2**
  Graduate research using advanced research methodologies.
- **[AEB34002] Management Capstone Design Planning**
  Exploration of graduation research topics and foundational research methodologies.
- **[BIM61019] Graduate Course: Information Strategy and Management Innovation**
  Theories of MIS, focusing on big data, AI, and other emerging technologies.

---

#### 2019 Spring

- **[AEB43017] Big Data Analysis**
  R programming and statistics. Covers fundamental concepts of data, regression analysis, basic programming, data preprocessing, and visualization using R.
- **[AEB13018] Fundamentals of Programming**
  Basic programming with JAVA, focusing on fundamental programming concepts and techniques.
- **[AEB44011] Management Capstone Design 1**
  Performing graduate research using research methodologies.

---

#### 2018 Fall

- **[AEB33017] Advanced IT Service Techniques**
  Deep learning and machine learning concepts with practical Python applications.
- **[AEB23017] Understanding Programming**
  Basics of programming and data analysis using R.
- **[AEB34013] Management Capstone Design 2**
  Graduate research using advanced research methodologies.
- **[AEB34002] Management Capstone Design Planning**
  Exploration of graduation research topics and foundational research methodologies.
- **[BIM60001] Graduate Course: New Technology Management**
  Core concepts of technology management and innovation theories.

---

#### 2018 Spring

- **[AEB43017] Big Data Analysis**
  R programming and statistics. Covers fundamental concepts of data, regression analysis, basic programming, data preprocessing, and visualization using R.
- **[AEB13018] Fundamentals of Programming**
  Basic programming with JAVA, focusing on fundamental programming concepts and techniques.
- **[AEB44011] Management Capstone Design 1**
  Performing graduate research using research methodologies.

---

#### 2017 Fall

- **[AEB33017] Advanced IT Service Techniques**
  Deep learning and machine learning concepts with practical Python applications.
- **[AEB23017] Understanding Programming**
  Basics of programming and data analysis using R.
- **[AEB34013] Management Capstone Design 2**
  Graduate research using advanced research methodologies.
- **[AEB34002] Management Capstone Design Planning**
  Exploration of graduation research topics and foundational research methodologies.
- **[BIM61019] Graduate Course: Information Strategy and Management Innovation**
  Theories of MIS, focusing on big data, AI, and other emerging technologies.

---

#### 2017 Spring

- **[AEB13018] Fundamentals of Programming**
  Basic programming with JAVA, focusing on fundamental programming concepts and techniques.
- **[AEB33013] Corporate Data Analysis**
  Empirical analysis of corporate data using R and statistical methods.
