<!--
  ============================================================
  README upgrade notes (safe to delete before publishing):
  - Palette preserved exactly: #F7CAD0 (pink) · #C9A7EB (lavender) · #E8D5F2 (light lavender) · #FFF9FB (bg)
  - Banner, layout order, and animation style are unchanged.
  - Anchor links in "Quick Navigation" point to the section headers below —
    GitHub auto-generates these anchors from heading text, so don't rename
    headings without updating the links.
  - The Contribution Snake needs a one-time GitHub Actions workflow to
    generate the animated SVG. Instructions + the workflow file are in the
    "GitHub Activity" section comment below — it won't render until that
    workflow runs once.
  - All repo/demo/docs links use TODO placeholders where I don't have your
    actual repo names — swap in real URLs when ready.
  ============================================================
-->

<div align="center">
  <img src="./banner.svg" alt="Nidhi Chougule banner" width="100%"/>
</div>

<div align="center">

<a href="https://www.linkedin.com/in/nidhi-chougule-161764390/">
<img src="https://img.shields.io/badge/LinkedIn-F7CAD0?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=C9A7EB"/>
</a>
<a href="mailto:nidhichougule20@gmail.com">
<img src="https://img.shields.io/badge/Email-F7CAD0?style=for-the-badge&logo=gmail&logoColor=white&labelColor=C9A7EB"/>
</a>
<a href="https://github.com/nidhichougule">
<img src="https://img.shields.io/badge/GitHub-F7CAD0?style=for-the-badge&logo=github&logoColor=white&labelColor=C9A7EB"/>
</a>

</div>

<br/>

<!-- Quick nav: plain markdown links to heading anchors, so no extra tooling needed -->
<div align="center">

[About](#about-me) · [Projects](#featured-projects) · [Tech Stack](#tech-stack) · [GitHub Stats](#github-activity) · [Achievements](#achievements) · [Contact](#lets-connect)

</div>

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="100%" height="3px">

<br/>

### Hey, I'm Nidhi 👋

I'm an Electronics & Computer Engineering student who ended up loving the space where logic meets design — I like my code clean and my interfaces a little pretty. Most days you'll find me somewhere between a half-finished full-stack app and a Jupyter notebook full of experiments I probably won't finish this week.

<br/>

## About Me

I got into engineering because I liked understanding how things work underneath — circuits, systems, logic. Somewhere along the way, building software became the thing I actually wanted to do all day, and AI became the thing I couldn't stop reading about at 1am.

I care about **craft** — not just making something work, but making it feel intentional, whether that's a well-structured API or a UI that doesn't look like everyone else's. I'm the person who will refactor a component twice because the spacing felt off, and also the person who'll happily spend an afternoon debugging a model that won't converge.

Right now, I'm building toward an **SDE or AI Engineer internship**, sharpening my full-stack fundamentals while going deeper into applied machine learning. I like projects that sit at the intersection of the two — smart systems with interfaces people actually enjoy using.

<br/>

## Featured Projects

<!--
  Card format per project: badges for Repo / Live Demo / Docs (Demo & Docs
  only shown when you actually have one — remove the badge line entirely
  for projects without a live version rather than linking a dead page),
  a one-line summary, 2-3 feature highlights, tech badges, and a status tag.
-->

### 🧠 AI Study Companion
`Status: In Progress`

An AI-powered study assistant that turns raw notes and material into structured explanations and summaries in real time — built for the version of me who used to lose an hour just organizing before actually studying.

- 📚 Converts raw notes into structured summaries on demand
- 💬 Conversational Q&A over your own study material
- 🔄 Syncs progress across sessions

`React` `Node.js` `Express` `MongoDB` `AI Integration`

[![Repo](https://img.shields.io/badge/Repository-F7CAD0?style=flat-square&logo=github&logoColor=white&labelColor=C9A7EB)](https://github.com/nidhichougule/ai-study-companion) [![Demo](https://img.shields.io/badge/Live%20Demo-TODO-F7CAD0?style=flat-square&logo=vercel&logoColor=white&labelColor=C9A7EB)](#)

<br/>

### 📧 Smart Email Classifier
`Status: In Progress`

A machine learning classifier wrapped in a serverless Firebase backend that automatically sorts and prioritizes incoming email — started as a fix for a cluttered inbox, turned into a real look at applied classification.

- 🧠 ML model trained to rank email by priority
- ⚡ Runs serverless via Firebase Cloud Functions
- 🔔 Configurable priority rules

`Firebase` `Python` `Machine Learning` `Cloud Functions`

[![Repo](https://img.shields.io/badge/Repository-F7CAD0?style=flat-square&logo=github&logoColor=white&labelColor=C9A7EB)](https://github.com/nidhichougule/smart-email-classifier)

<br/>

### 🍦 Ice Cream Ordering Web App
`Status: Completed`

A complete full-stack ordering platform — flavor selection, order tracking, database integration, and receipt generation. The project where I really understood what "full-stack" means in practice, not just in theory.

- 🍨 End-to-end flavor selection & order flow
- 🧾 Automated receipt generation
- 🗄️ PostgreSQL-backed order history

`HTML` `CSS` `JavaScript` `Node.js` `Express.js` `PostgreSQL`

[![Repo](https://img.shields.io/badge/Repository-F7CAD0?style=flat-square&logo=github&logoColor=white&labelColor=C9A7EB)](https://github.com/nidhichougule/ice-cream-ordering-app) [![Demo](https://img.shields.io/badge/Live%20Demo-F7CAD0?style=flat-square&logo=vercel&logoColor=white&labelColor=C9A7EB)](#)

<br/>

### 🤖 MATLAB + Robotics Projects
`Status: Ongoing`

A set of simulation and control-systems projects where the ECE side of my degree meets the software side — signal processing, robotics logic, and automation, all worked out in MATLAB.

- 📡 Signal processing simulations
- 🦾 Control-systems & robotics logic
- 📈 Visualized results per experiment

`MATLAB` `Robotics` `Signal Processing`

[![Repo](https://img.shields.io/badge/Repository-F7CAD0?style=flat-square&logo=github&logoColor=white&labelColor=C9A7EB)](https://github.com/nidhichougule/matlab-robotics-projects)

<br/>

### 🤟 Text/Voice to Sign Language Translator
`Status: Completed`

Converts spoken or typed language into Indian Sign Language gestures through a 3D avatar, with fingerspelling as a fallback for unfamiliar words — built around making information more accessible.

- 🗣️ Text & speech input support
- 🧍 3D avatar gesture rendering via Three.js
- 🔤 Fingerspelling fallback for unknown words

`NLP` `Speech Recognition` `Three.js` `Blender`

[![Repo](https://img.shields.io/badge/Repository-F7CAD0?style=flat-square&logo=github&logoColor=white&labelColor=C9A7EB)](https://github.com/nidhichougule/sign-language-translator) [![Docs](https://img.shields.io/badge/Documentation-F7CAD0?style=flat-square&logo=readthedocs&logoColor=white&labelColor=C9A7EB)](#)

<br/>

### 🔐 Federated Learning for Credit Risk
`Status: Completed`

Explores how you predict credit risk *without* compromising user privacy, combining Differential Privacy with Explainable AI (SHAP) so the model's decisions stay interpretable, not a black box.

- 🔒 Differential Privacy-preserving training
- 🧩 Federated setup across simulated clients
- 📊 SHAP-based explainability layer

`Python` `Federated Learning` `SHAP`

[![Repo](https://img.shields.io/badge/Repository-F7CAD0?style=flat-square&logo=github&logoColor=white&labelColor=C9A7EB)](https://github.com/nidhichougule/federated-credit-risk)

<br/>

### 🎵 Emotion-Based Music Recommender
`Status: Completed`

Detects emotions through facial expressions using CNNs and OpenCV, then maps them to personalized music recommendations.

- 📷 Real-time facial emotion detection
- 🎶 Emotion-to-playlist mapping
- 🧠 CNN model trained on labeled expression data

`Python` `OpenCV` `CNN`

[![Repo](https://img.shields.io/badge/Repository-F7CAD0?style=flat-square&logo=github&logoColor=white&labelColor=C9A7EB)](https://github.com/nidhichougule/emotion-music-recommender)

<br/>

### 📊 Process Scheduling Simulator
`Status: Completed`

Simulates FCFS, SJF, Priority, and Round Robin scheduling algorithms with interactive Gantt chart visualizations.

- ⏱️ Four scheduling algorithms implemented
- 📊 Interactive Gantt chart output
- 🧮 Configurable process sets

`HTML` `CSS` `JavaScript`

[![Repo](https://img.shields.io/badge/Repository-F7CAD0?style=flat-square&logo=github&logoColor=white&labelColor=C9A7EB)](https://github.com/nidhichougule/process-scheduling-simulator) [![Demo](https://img.shields.io/badge/Live%20Demo-F7CAD0?style=flat-square&logo=vercel&logoColor=white&labelColor=C9A7EB)](#)

<br/>

## Tech Stack

<div align="center">

**Languages**
<br/>
<img src="https://img.shields.io/badge/C-F7CAD0?style=for-the-badge&logo=c&logoColor=white&labelColor=C9A7EB"/>
<img src="https://img.shields.io/badge/C++-F7CAD0?style=for-the-badge&logo=c%2B%2B&logoColor=white&labelColor=C9A7EB"/>
<img src="https://img.shields.io/badge/Python-F7CAD0?style=for-the-badge&logo=python&logoColor=white&labelColor=C9A7EB"/>
<img src="https://img.shields.io/badge/JavaScript-F7CAD0?style=for-the-badge&logo=javascript&logoColor=white&labelColor=C9A7EB"/>
<img src="https://img.shields.io/badge/SQL-F7CAD0?style=for-the-badge&logo=postgresql&logoColor=white&labelColor=C9A7EB"/>

**Full-Stack**
<br/>
<img src="https://img.shields.io/badge/React-E8D5F2?style=for-the-badge&logo=react&logoColor=white&labelColor=C9A7EB"/>
<img src="https://img.shields.io/badge/Node.js-E8D5F2?style=for-the-badge&logo=node.js&logoColor=white&labelColor=C9A7EB"/>
<img src="https://img.shields.io/badge/Express.js-E8D5F2?style=for-the-badge&logo=express&logoColor=white&labelColor=C9A7EB"/>
<img src="https://img.shields.io/badge/MongoDB-E8D5F2?style=for-the-badge&logo=mongodb&logoColor=white&labelColor=C9A7EB"/>
<img src="https://img.shields.io/badge/PostgreSQL-E8D5F2?style=for-the-badge&logo=postgresql&logoColor=white&labelColor=C9A7EB"/>
<img src="https://img.shields.io/badge/Firebase-E8D5F2?style=for-the-badge&logo=firebase&logoColor=white&labelColor=C9A7EB"/>

**AI / ML**
<br/>
<img src="https://img.shields.io/badge/Machine%20Learning-D8BFD8?style=for-the-badge&logo=scikit-learn&logoColor=white&labelColor=C9A7EB"/>
<img src="https://img.shields.io/badge/OpenCV-D8BFD8?style=for-the-badge&logo=opencv&logoColor=white&labelColor=C9A7EB"/>
<img src="https://img.shields.io/badge/TensorFlow-D8BFD8?style=for-the-badge&logo=tensorflow&logoColor=white&labelColor=C9A7EB"/>
<img src="https://img.shields.io/badge/NLP-D8BFD8?style=for-the-badge&logo=googlecloud&logoColor=white&labelColor=C9A7EB"/>

**Cloud & Tools**
<br/>
<img src="https://img.shields.io/badge/Google%20Cloud-F0E6FA?style=for-the-badge&logo=googlecloud&logoColor=white&labelColor=C9A7EB"/>
<img src="https://img.shields.io/badge/Git-F0E6FA?style=for-the-badge&logo=git&logoColor=white&labelColor=C9A7EB"/>
<img src="https://img.shields.io/badge/GitHub-F0E6FA?style=for-the-badge&logo=github&logoColor=white&labelColor=C9A7EB"/>
<img src="https://img.shields.io/badge/MATLAB-F0E6FA?style=for-the-badge&logo=mathworks&logoColor=white&labelColor=C9A7EB"/>

</div>

<br/>

## Currently Learning

<div align="center">

<img src="https://img.shields.io/badge/System%20Design-FFF0F5?style=for-the-badge&labelColor=C9A7EB&color=F7CAD0"/>
<img src="https://img.shields.io/badge/Cloud%20Architecture-FFF0F5?style=for-the-badge&labelColor=C9A7EB&color=F7CAD0"/>
<img src="https://img.shields.io/badge/Advanced%20ML-FFF0F5?style=for-the-badge&labelColor=C9A7EB&color=F7CAD0"/>
<img src="https://img.shields.io/badge/DSA-FFF0F5?style=for-the-badge&labelColor=C9A7EB&color=F7CAD0"/>

</div>

<br/>

## GitHub Activity

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=nidhichougule&show_icons=true&count_private=true&hide_border=true&title_color=C9A7EB&icon_color=F7CAD0&text_color=6b6b6b&bg_color=FFF9FB"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=nidhichougule&layout=compact&hide_border=true&title_color=C9A7EB&text_color=6b6b6b&bg_color=FFF9FB"/>

<br/>

<img src="https://streak-stats.demolab.com/?user=nidhichougule&hide_border=true&background=FFF9FB&ring=C9A7EB&fire=F7CAD0&currStreakLabel=C9A7EB"/>

<br/><br/>

<!-- Activity graph, same pastel palette as the rest of the profile -->
<img width="90%" src="https://github-readme-activity-graph.vercel.app/graph?username=nidhichougule&bg_color=FFF9FB&color=6b6b6b&line=C9A7EB&point=F7CAD0&area=true&area_color=F7CAD0&title_color=C9A7EB&hide_border=true"/>

<br/><br/>

<!--
  Contribution snake: requires a one-time GitHub Actions workflow to
  generate contribution-snake.svg on your account. Steps:
  1. Create .github/workflows/snake.yml in this repo with the content below.
  2. Push it — the action runs on a schedule and on push, and commits the
     generated SVG to an "output" branch.
  3. Once it's run once, this <img> tag will render automatically.

  ---- .github/workflows/snake.yml ----
  name: Generate Snake
  on:
    schedule:
      - cron: "0 0 * * *"
    workflow_dispatch:
    push:
      branches: [ main ]
  jobs:
    generate:
      runs-on: ubuntu-latest
      steps:
        - uses: Platane/snk@v3
          with:
            github_user_name: nidhichougule
            outputs: |
              dist/snake-pink.svg?palette=github-light
              dist/snake-pink.gif?color_snake=%23C9A7EB&color_dots=%23FFE1EC,%23F6C9DE,%23F7CAD0,%23C9A7EB,%23A47DC0
        - uses: crazy-max/ghaction-github-pages@v4
          with:
            target_branch: output
            build_dir: dist
          env:
            GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
  --------------------------------------
-->
<img src="https://raw.githubusercontent.com/nidhichougule/nidhichougule/output/snake-pink.svg" alt="Contribution snake" width="90%"/>

</div>

<br/>

## Achievements

<!--
  Structured so each line is a one-item update — add a row, no need to
  restructure the section as things come in.
-->

**🎓 Certifications**
- TODO — e.g. *Google Cloud Associate Engineer*, *Coursera Machine Learning Specialization*

**🏆 Hackathons**
- TODO — e.g. *[Hackathon Name] — [Result/Track], [Month Year]*

**🌱 Open Source**
- TODO — e.g. *Contributed to [Project Name] — [brief contribution]*

**🥇 Awards**
- TODO — e.g. *[Award/Recognition] — [Issuing Organization]*

**💻 Coding Profiles**
<br/>
<img src="https://img.shields.io/badge/LeetCode-TODO-F7CAD0?style=flat-square&logo=leetcode&logoColor=white&labelColor=C9A7EB"/>
<img src="https://img.shields.io/badge/Codeforces-TODO-F7CAD0?style=flat-square&logo=codeforces&logoColor=white&labelColor=C9A7EB"/>
<img src="https://img.shields.io/badge/GeeksforGeeks-TODO-F7CAD0?style=flat-square&logo=geeksforgeeks&logoColor=white&labelColor=C9A7EB"/>

<br/>

## Let's Connect

Whether you're a **recruiter** scanning for your next intern, a **collaborator** with an idea worth building, or part of an **open-source project** looking for an extra pair of hands — I'd genuinely love to hear from you.

I'm currently open to **SDE / Full-Stack / AI Engineer internship** opportunities.

<div align="center">

<a href="https://www.linkedin.com/in/nidhi-chougule-161764390/">
<img src="https://img.shields.io/badge/LinkedIn-F7CAD0?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=C9A7EB"/>
</a>
<a href="mailto:nidhichougule20@gmail.com">
<img src="https://img.shields.io/badge/Gmail-F7CAD0?style=for-the-badge&logo=gmail&logoColor=white&labelColor=C9A7EB"/>
</a>
<a href="https://github.com/nidhichougule">
<img src="https://img.shields.io/badge/GitHub-F7CAD0?style=for-the-badge&logo=github&logoColor=white&labelColor=C9A7EB"/>
</a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=nidhichougule&label=Profile%20Views&color=C9A7EB&style=for-the-badge" alt="Profile Views" />

</div>
