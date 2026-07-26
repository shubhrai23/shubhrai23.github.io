# [shubhrai23.github.io](https://shubhrai23.github.io)

My personal portfolio website — a single-page site introducing me, my work, my projects, and resume.

?? **Live:** https://shubhrai23.github.io

## About

I'm Shubh Rai, a B.Tech IT student at Delhi Technological University and a Full Stack Developer Intern at Eythor Private Limited, passionate about solving hard problems with code and AI.

## Sections

- **About** — who I am and what I work on
- **Projects** — open-source and personal projects
- **Resume** — viewable and downloadable PDF
- **Contact** — how to reach me

## Tech

- Static HTML / CSS / JavaScript (jQuery), hosted on **GitHub Pages**
- Based on the [MyResume](https://bootstrapmade.com/free-html-bootstrap-template-my-resume/) Bootstrap template
- [AOS](https://michalsnik.github.io/aos/) for scroll animations and [Typed.js](https://github.com/mattboldt/typed.js/) for the hero text
- A [p5.js](https://p5js.org/) flocking-boids animation on the hero canvas

## Local development

It's a static site — no build step. Just open index.html, or serve the folder:

``bash
python -m http.server 8000
# then visit http://localhost:8000
``

## Project structure

``
index.html            # the whole page
assets/
  css/style.css       # site styles
  js/main.js          # nav, smooth scroll, hero typing, AOS init
  canvas/flock.js     # p5.js boids animation
  img/                # images (optimized)
  SR Resume.pdf       # resume
  vendor/             # third-party libraries
``
