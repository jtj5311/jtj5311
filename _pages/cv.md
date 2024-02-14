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
* Diploma with Highest Honors, Phillips Exeter Academy, 2018
* B.S. in Mathematical Sciences, Carnegie Mellon University, 2022
* M.S. in Mathematical Sciences, Carnegie Mellon University, 2022
* Ph.D in Mathematics, Pennsylvania State University, 2027 (expected)

Work experience
======
* Spring 2024: Graduate Teaching Assistant for Math 231
  * Pennsylvania State University
  * Duties included: Instructor of Record, see Teaching for more info

* Fall 2023: Graduate Teaching Assistant for Math 230
  * Pennsylvania State University
  * Duties included: Instructor of Record, see Teaching for more info

* Summer 2023: Visiting Scholar
  * University of Bonn, Germany
  * Duties included: Implementing and optimizing the MBO (Merriman, Bence, Osher) algorithm to efficiently cluster data. This algorithm is a type
  of spectral clustering algorithm which can create clusters with special
  desirable mathematical properties.

* Summer 2020: Researcher in Fluid Dynamics
  * Carnegie Mellon University
  * Duties included: Helping devise a novel approach to derive the equations governing fluid flow with a layer of surfactants on the outer surface.
  * Supervisor: Ian Tice

* Fall 2019 - Spring 2022: Undergraduate Teaching Assistant
  * Carnegie Mellon University
  * Duties included: 
    * Prepared materials and taught recitation for 15-30 students a semester 
    * Graded homework, exams and quizzes
    * Held bi-weekly office hours
    * Classes taught include: calculus 1, honors vector calculus, and introduction to proofs for math/CS majors
  
Skills
======
* Python: Primary Language of Expertise
  * Have programmed in Python as a researcher since the beginning of grad school
    and as hobbyist for approximately 8 years. 
  * Most of my work has been focused on crafting and optimizing numerical 
    algorithms around machine learning and various mathematical algorithms.
    Techniques have included JIT-compilation and parallel processing with Numba, 
    GPU acceleration with Cupy, and parallel processing with Multiprocessing.
  * Libraries and Tools Commonly Used Include: Numpy, Numba, Cupy, PyTorch, 
    Conda, Faiss, Matplotlib, Plotly, Scipy, JuliaCall, Multiprocessing
* Julia
  * Learned in graduate school to offload differential equation solving
    since Julia's tooling in this area is better developed than Python's.
  * Most of my Julia code is written to be called from Python. This is used
    to build data sets solving differential equations to test/train my Python
    models.
  * Libraries and Tools Commonly Used Include: DifferentialEquations.jl,
    OrdinaryDiffEq.jl, CUDA.jl, KrylovKit.jl, 
* Linux
  * Basic familiarity with interacting with Linux from the terminal.
    All my heavy computational work is currently done through SSH on a 
    cluster running Ubuntu 20.04.
* Git
  * Basic familiarity with Git and Github from the command line.

Honors
======
* University Graduate Fellowship, Spring 2023 - Spring 2024
* Jack and Eleanor Pettit Scholarship in Science, Fall 2023
* Verne M. Willaman Distinguished Graduate Fellowships in Science, Fall 2022
* Jack and Eleanor Pettit Scholarship in Science, Fall 2022
* Science and Humanities Scholar, Carnegie Mellon University Sep 2018–May 2022 
* University Honors, Carnegie Mellon University May 2022
* College Honors, Carnegie Mellon University May 2022
* Department of Mathematical Science’s Mathematics Prize, Carnegie Mellon University May 2022
* Cum Laude Society, Phillips Exeter Academy, Spring 2018

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>