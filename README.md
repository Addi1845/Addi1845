<picture>
  <source media="(prefers-reduced-motion: reduce) and (max-width: 600px)" srcset="assets/header-mobile-static.svg">
  <source media="(prefers-reduced-motion: reduce)" srcset="assets/header-static.svg">
  <source media="(max-width: 600px)" srcset="assets/header-mobile.svg?v=2">
  <img src="assets/header.svg?v=2" width="100%" alt="Aditya Patil - AI tools, full-stack applications, and data workflows. Build with curiosity. Validate with evidence.">
</picture>

<p align="center">
  <a href="https://www.linkedin.com/in/adityapatil-web/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square" alt="Connect on LinkedIn"></a>
  <img src="https://img.shields.io/badge/Open_to-Internships_%26_software_roles-76E4BC?style=flat-square&amp;labelColor=20262D" alt="Open to internships and software engineering roles">
</p>

I build **AI tools and full-stack applications** with Python, TypeScript, and React. My work focuses on making systems easier to trust: testing agent behavior, explaining rankings, validating data, and reviewing what gets shared with AI.

I learn by taking an idea through the whole workflow: **interface, API, data, and verification**. I'm especially interested in AI tooling, browser privacy, and software that turns complex processes into clear, usable experiences.

<p align="center">
  <a href="#selected-projects"><strong>Projects</strong></a> &nbsp; / &nbsp;
  <a href="#-tech-stack"><strong>Tech stack</strong></a> &nbsp; / &nbsp;
  <a href="#engineering-notes"><strong>Engineering notes</strong></a> &nbsp; / &nbsp;
  <a href="#lets-connect"><strong>Connect</strong></a>
</p>

## Selected projects

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/Addi1845/AgentCrash"><img src="assets/agentcrash.svg" width="100%" alt="AgentCrash workflow: scenarios, sandbox, and findings"></a>
      <h3><a href="https://github.com/Addi1845/AgentCrash">AgentCrash</a></h3>
      <p>A deterministic reliability engine for an e-commerce support agent.</p>
      <ul>
        <li><strong>15 weighted scenarios</strong> spanning normal, edge, failure, and adversarial cases.</li>
        <li>Event evidence, scoring, run history, and re-tests backed by SQLite.</li>
      </ul>
      <p><code>TypeScript</code> <code>React</code> <code>Fastify</code> <code>SQLite</code></p>
      <p><sub>Demo scope: isolated fixtures; no real customer or payment systems.</sub></p>
      <p><a href="https://github.com/Addi1845/AgentCrash#readme"><strong>Code &amp; setup &rarr;</strong></a> &nbsp; <a href="https://github.com/Addi1845/AgentCrash/blob/main/PROJECT_SPEC.md">Specification</a></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/Addi1845/specgraph-ai"><img src="assets/specgraph.svg" width="100%" alt="SpecGraph AI workflow: input, review, and CSV export"></a>
      <h3><a href="https://github.com/Addi1845/specgraph-ai">SpecGraph AI</a></h3>
      <p>A product-data enrichment demo built around an exact delivery contract.</p>
      <ul>
        <li>A six-column input flows through a <strong>12-step mock pipeline</strong>.</li>
        <li>Evidence, confidence, and a review queue lead to a validated <strong>252-column CSV</strong>.</li>
      </ul>
      <p><code>Next.js</code> <code>TypeScript</code> <code>Data contracts</code></p>
      <p><sub>Demo scope: deterministic sample enrichments; runs without API keys.</sub></p>
      <p><a href="https://github.com/Addi1845/specgraph-ai#readme"><strong>Code &amp; setup &rarr;</strong></a> &nbsp; <a href="https://github.com/Addi1845/specgraph-ai/blob/main/ARCHITECTURE.md">Architecture</a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/Addi1845/Recruite.ai"><img src="assets/recruite.svg" width="100%" alt="Recruite.ai workflow: profiles, scores, and ranked results"></a>
      <h3><a href="https://github.com/Addi1845/Recruite.ai">Recruite.ai</a></h3>
      <p>An inspectable candidate-ranking pipeline built for a data and AI challenge.</p>
      <ul>
        <li>Parallel processing, TF-IDF matching, and configurable CPU workers.</li>
        <li><strong>Component-level explanations</strong> and ranked CSV output with reasons.</li>
      </ul>
      <p><code>Python</code> <code>Multiprocessing</code> <code>TF-IDF</code></p>
      <p><sub>Challenge scope: heuristic rankings that require evaluation and human review.</sub></p>
      <p><a href="https://github.com/Addi1845/Recruite.ai#readme"><strong>Code &amp; setup &rarr;</strong></a> &nbsp; <a href="https://github.com/Addi1845/Recruite.ai/blob/main/rank.py">Scoring pipeline</a></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/Addi1845/PrivacyShield_AI"><img src="assets/privacyshield.svg" width="100%" alt="PrivacyShield workflow: select, review, and share"></a>
      <h3><a href="https://github.com/Addi1845/PrivacyShield_AI">PrivacyShield</a></h3>
      <p>A Chrome extension for reviewing AI context and preparing browser tabs for presentations.</p>
      <ul>
        <li><strong>Ask privately:</strong> select, sanitize, and approve the exact context packet.</li>
        <li><strong>Present safely:</strong> blur or hide sensitive content, with local screenshot OCR.</li>
      </ul>
      <p><code>TypeScript</code> <code>React</code> <code>Chrome MV3</code> <code>Tesseract.js</code></p>
      <p><sub>Current scope: browser tabs and snapshots; review remains essential.</sub></p>
      <p><a href="https://github.com/Addi1845/PrivacyShield_AI#readme"><strong>Code &amp; setup &rarr;</strong></a> &nbsp; <a href="https://github.com/Addi1845/PrivacyShield_AI/blob/main/docs/architecture.md">Architecture</a></p>
    </td>
  </tr>
</table>

**Also exploring:** [FairLens](https://github.com/Addi1845/FairLens), a browser-based prototype for inspecting group-level differences in loan approval data.

[Browse all repositories &rarr;](https://github.com/Addi1845?tab=repositories)

## 💻 Tech Stack

Technologies used across my projects, grouped by where they fit.

### Languages

![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)

### Frontend & interfaces

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/TailwindCSS-38B2AC?style=for-the-badge&logo=tailwindcss&logoColor=white)
![TanStack Start](https://img.shields.io/badge/TanStack_Start-FF4154?style=for-the-badge&logo=tanstack&logoColor=white)

### Backend & data

![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=nodedotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Fastify](https://img.shields.io/badge/Fastify-000000?style=for-the-badge&logo=fastify&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-039BE5?style=for-the-badge&logo=firebase&logoColor=FFCA28)

### Testing & validation

![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge)
![Zod](https://img.shields.io/badge/Zod-3E67B1?style=for-the-badge&logo=zod&logoColor=white)

## Engineering notes

- **Keep behavior inspectable.** [AgentCrash](https://github.com/Addi1845/AgentCrash) records execution evidence and findings. [Recruite.ai](https://github.com/Addi1845/Recruite.ai) exposes scoring components and reasons behind each result.
- **Validate the boundaries.** [SpecGraph AI](https://github.com/Addi1845/specgraph-ai/blob/main/ARCHITECTURE.md) checks input and output contracts and preserves source identifiers through export.
- **Make privacy a workflow.** [PrivacyShield](https://github.com/Addi1845/PrivacyShield_AI/blob/main/docs/user-guide.md) asks users to review context before sharing it and keeps screenshot OCR on device.
- **Verify the full experience.** My TypeScript projects use type checks, linting, and tests; PrivacyShield also includes browser checks and a bundle audit. [View its test evidence](https://github.com/Addi1845/PrivacyShield_AI/blob/main/docs/test-report.md).

## Let's connect

I'm open to **internships and software engineering opportunities**, especially in AI tools and full-stack development.

[Connect on LinkedIn](https://www.linkedin.com/in/adityapatil-web/) &nbsp; &middot; &nbsp; [Explore my work](https://github.com/Addi1845?tab=repositories)
