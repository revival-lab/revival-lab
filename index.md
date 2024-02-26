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
  - image_path:
    title: Revive and Survive
    excerpt: >
       Our mission is to breathe life into legacy code, ensuring longevity in the ever-evolving landscape of technology. We specialise in crafting maintainable, mission-critical, and secure software solutions. We don't just refactor; we _revive_, ensuring that your software stands the test of time.

expertise:
  - image_path: /assets/images/wordcloud.jpg
    alt: "placeholder image 2"
    title: "Expertise"
    excerpt: >
       At Code Revival Lab, our expertise extends into the realms of **scientific and technical software**, with a specialized focus on **high-performance** applications. We thrive in crafting solutions for **restricted and embedded systems**, ensuring efficiency even in resource-constrained environments.
       We excel in languages crucial to modern software development, including **Rust**, **C/C++**, and **Python**.
    url: "/portfolio"
    btn_class: "btn--primary"
    btn_label: "See Portfolio"

feature_row_services:
  - image_path:
    alt: "placeholder image 2"
    title: "Services"
    excerpt: >
       We assist to strengthen and vitalise your software. We also aid in starting up small to mid-sized projects and offer general consultancy in software engineering
    url: "/services"
    btn_class: "btn--primary"
    btn_label: "Learn more"

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
    excerpt: "Complete rewriting and translation of code into **Rust** or **modern C++** to enhance performance, reliability, and maintainability."
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
    excerpt: >
      We assist to strengthen and vitalise your software. We also aid in starting up small to mid-sized projects and offer general consultancy in software engineering.
    url: "/services"
    btn_class: "btn--primary"
    btn_label: "Learn more"
---
{% include feature_row id="intro" type="center" %}
{% include feature_row id="expertise" type="center" %}
{% include feature_row id="feature_row_services" type="center" %}
{% include feature_row %}