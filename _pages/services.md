---
permalink: /services/
title: Services
layout: splash
header:
  overlay_image: /assets/images/blurry-rust.jpg
  overlay_filter: rgba(0, 0, 50, 0.7)
excerpt: >
  _Below is a selection of tasks in which we assist to strengthen and vitalise your software.
  We also aid in starting up new projects and offer general consultancy in software engineering._

feature_row_top:
  - image_path: /assets/images/workflow.jpg
    alt: "placeholder image 2"
    title: "Development Workflow"
    excerpt: >
       We help setting up industry-standard version control systems, such as **Git and GitHub**, to track changes, facilitate collaboration, and ensure a secure and organised development workflow.
       This also entails enabling **continuous integration** pipelines to automate testing, build processes, linting; to ensure the ongoing integrity of your codebase.
  - image_path: /assets/images/unit-test-light.jpg
    alt: "placeholder image 2"
    title: "Lasting Correctness"
    excerpt: >
       Development and implementation of robust **unit tests** is critical to ensure the continued correctness and reliability of your software. Depending of the project, we can enable appropriate **testing and benchmarking frameworks** to automatically trigger reports when code changes are made.
  - image_path: /assets/images/mem-leak.jpg
    alt: "placeholder image 2"
    title: "Security and Performance"
    excerpt: >
       To uncover critical safety and performance issues in your software, we use **static and dynamic code analysis** to find hidden bugs and memory leaks that can lead to resource loss and security risks. We also offer full or partial **migration of critial code** to a high-performance but memory safe language such as **Rust**.

feature_row:
  - image_path: /assets/images/dust-disk-soft.jpeg
    title: "Code Revival"
    alt: "customizable"
    excerpt: >
       Comprehensive analysis and enhancement of legacy code written in C, C++, and Python. Integration of modern practices to extend the lifespan and functionality of existing codebases.
    #url: "/docs/configuration/"
    #btn_class: "btn--primary"
    #btn_label: "Learn more"
  - image_path: /assets/images/apes-to-man.jpeg
    alt: "fully responsive"
    title: "Migration and Translation"
    excerpt: >
       Complete rewriting and translation of code into **Rust** or **modern C++** to enhance performance, reliability, and maintainability.
    #url: "/docs/layouts/"
    #btn_class: "btn--primary"
    #btn_label: "Learn more"
  - image_path: /assets/images/code-refactor.jpg
    alt: "100% free"
    title: "Refactoring"
    excerpt: >
       In-depth code refactoring to improve readability, scalability, and overall code quality. We follow best practices and recommendations for your given language using linting tools and static analysis.
    #url: "/docs/license/"
    #btn_class: "btn--primary"
    #btn_label: "Learn more"


feature_row_services:
  - image_path:
    alt: "placeholder image 2"
    title: "Services"
    excerpt: 'We offer help and consultancy to new or existing projects.'

feature_services_bullets:
  - image_path:
    excerpt: | 
      - **Version Control:** Utilization of industry-standard version control systems, such as Git and GitHub, to track changes, facilitate collaboration, and ensure a secure and organized development workflow.
      - **Continuous Integration**: Setup and configuration of continuous integration pipelines to automate testing, build processes, and ensure the ongoing integrity of your codebase.
  - image_path:
    excerpt: | 
      - Profile existing software using **static and dynamic code analysis**. Profiling is an important tool to find critical safety and and performance issues.
      - **Unit Testing:**
        Development and implementation of robust unit tests to ensure the continued correctness and reliability of your software.
  - image_path:
    excerpt: | 
      - Expose C, C++, or Fortran code with **Python bindings** to significantly lower the threshold to use your application.
      - **Build System Modernization:** Modernization of build systems such as CMake for C/C++ projects or Cargo for Rust projects to streamline development processes and improve project maintainability.

---
{% include feature_row id="feature_row_top" %}
{% include feature_row %}
{% include feature_row id="feature_services_bullets"%}

