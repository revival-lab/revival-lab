---
layout: splash
header:
  overlay_color: "#000"
  overlay_filter: "0.7"
  overlay_image: /assets/images/blurry-rust.jpg
  #actions:
  #  - label: "<i class='fas fa-download'></i> Install now"
  #    url: "/docs/quick-start-guide/"
excerpt: >
  _We vitalise and strengthen software._
intro: 
  - excerpt: "Our mission is to breathe life into legacy code, ensuring longevity in the ever-evolving landscape of technology.
We specialize in crafting maintainable, mission-critical, and secure software solutions.
We don't just refactor; we _revive_, ensuring that your software stands the test of time."

feature_row:
  - image_path: /assets/images/dust-disk.jpeg
    title: "Code Revival"
    alt: "customizable"
    excerpt: "Comprehensive analysis and enhancement of legacy code written in C, C++, and Python. Integration of modern practices to extend the lifespan and functionality of existing codebases."
    #url: "/docs/configuration/"
    #btn_class: "btn--primary"
    #btn_label: "Learn more"
  - image_path: /assets/images/apes-to-man.jpeg
    alt: "fully responsive"
    title: "Migration and Translation"
    excerpt: "Complete rewriting and translation of code into **Rust** or **modern C++** to enhance performance, reliability, and maintainability."
    #url: "/docs/layouts/"
    #btn_class: "btn--primary"
    #btn_label: "Learn more"
  - image_path: /assets/images/code-refactor.jpg
    alt: "100% free"
    title: "Refactoring"
    excerpt: "In-depth code refactoring to improve readability, scalability, and overall code quality"
    #url: "/docs/license/"
    #btn_class: "btn--primary"
    #btn_label: "Learn more"

feature_row_expertise:
  - image_path: /assets/images/wordcloud.jpg
    alt: "placeholder image 2"
    title: "Expertise"
    excerpt: 'At Code Revival Lab, our expertise extends into the realms of **scientific and technical software**, with a specialized focus on **high-performance** applications. We thrive in crafting solutions for **restricted and embedded systems**, ensuring efficiency even in resource-constrained environments.
We excel in languages crucial to modern software development, including **Rust**, **C/C++**, and **Python**.'

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
{% include feature_row id="intro" type="center" %}
{% include feature_row id="feature_row_expertise" type="left" %}
{% include feature_row id="feature_row_services" type="center" %}
{% include feature_row %}
{% include feature_row id="feature_services_bullets"%}

