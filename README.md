<!--
  GitHub Profile README — Hariom Gupta
  Repo name must be exactly: hariomgupta2596-source (your username)
  Paste this whole file as README.md in that repo's root.
-->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1f6feb,100:00f0ff&height=180&section=header&text=Hariom%20Gupta&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Data%20Science%20%E2%80%A2%20Python%20%E2%80%A2%20Full-Stack&descAlignY=58&descSize=18" alt="Hariom Gupta" />

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1200&color=00F0FF&center=true&vCenter=true&width=650&lines=Building+software+that+explains+itself.;Data+science+student+%E2%86%92+analyst+in+the+making.;Turning+coursework+into+shipped+products.;Explainable+AI+%2B+clean+full-stack+engineering." alt="Typing SVG" /></a>

<p>
  <img src="https://komarev.com/ghpvc/?username=hariomgupta2596-source&label=Profile%20views&color=1f6feb&style=flat-square" alt="Profile views" />
  <img src="https://img.shields.io/github/followers/hariomgupta2596-source?label=Followers&style=flat-square&color=1f6feb" alt="Followers" />
  <img src="https://img.shields.io/badge/Location-Mumbai%20Metropolitan%20Region%2C%20India-00f0ff?style=flat-square" alt="Location" />
  <img src="https://img.shields.io/badge/Open%20to-Analyst%20%26%20Data%20Roles-success?style=flat-square" alt="Open to work" />
</p>

</div>

---

## Hi, I'm Hariom 👋

I'm a **Data Science student and developer** from the Mumbai Metropolitan Region who likes building software that solves a real, specific problem — and that can explain *why* it reached an answer.

My work sits in an unusual sweet spot: I'm equally comfortable writing the Python that does the statistical heavy lifting and the interface that makes a non-technical person actually want to use it. So my projects tend to be end-to-end. A phishing detector that returns a **0–100 risk score with the evidence behind it**, not just a probability. A health app that turns raw vitals into readable, downloadable reports. A linear algebra suite that shows the **step-by-step working** instead of only printing the final matrix.

Three things I keep coming back to:

- **Explainability over black boxes.** If a model or a rule says "risky", I want the user to see which signal fired.
- **Shipping beats tutorials.** Every concept I learn gets pushed into a repo that actually runs, usually deployed on Vercel.
- **Data with a human footpath.** My field research on digital payments in semi-urban and rural India shaped how I think about the gap between a product's assumptions and a real user's reality.

---

## 🔭 What I'm working on right now

<table>
<tr>
<td width="50%" valign="top">

**🛡️ SENTINEL — AI Phishing & Impersonation Defense**
A multi-vector cyber-intelligence platform built for the **TechAstra Hackathon**. Combines scikit-learn NLP probabilities, deterministic URL heuristics (typo-squatting, abusive TLDs, `@`-redirect tricks) and brand-registry verification into one explainable 0–100 risk score with an action playbook.

`Python 3.13` · `FastAPI` · `scikit-learn` · `XAI` · `Vercel`

</td>
<td width="50%" valign="top">

**🏥 Health Checkup Program**
Full-stack healthcare monitoring app: Next.js front end, FastAPI REST API, SQLAlchemy 2.0 + SQLite, native bcrypt auth, Plotly trend charts and server-generated PDF health reports.

`Next.js` · `FastAPI` · `SQLAlchemy` · `Plotly` · `ReportLab`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**📐 Linear Algebra Educational Suite**
A production-quality solver covering matrix operations, vectors and systems of equations (`Ax = b`) with Gaussian elimination, Gauss-Jordan, LU decomposition and Cramer's rule — each with step-by-step derivation and a 2D/3D vector visualiser.

`Flask` · `NumPy` · `SciPy` · `SymPy` · `MathJax`

</td>
<td width="50%" valign="top">

**📊 Digital Payments Field Research**
Primary survey across consumer and merchant segments in rural and semi-urban markets — 46 questions, split respondent paths, and analysis of UPI adoption, failure rates and merchant barriers.

`Google Forms` · `Data cleaning` · `Survey design`

</td>
</tr>
</table>

I'm also steadily working through the **Google Cloud Gen AI Academy (APAC, Cohort 3)** — codelabs, Gemini on Cloud Run, and agentic app patterns.

---

## 🚀 Featured projects

### 🛡️ [SENTINEL — AI Phishing & Impersonation Defense](https://github.com/TECHASTRA-2026/AI-Phishing-and-Impersonation-Defense)

> Credential-harvesting attacks don't come through one door. They combine psychological pressure, structural obfuscation in the URL, and brand impersonation — all at once.

SENTINEL scores all three vectors together and returns a **normalised 0–100 risk score** with the exact diagnostic evidence behind it, plus a countermeasure playbook. Built on a Python 3.13 / FastAPI backend with a scikit-learn classifier (~94% accuracy) layered against deterministic URL heuristics and an authoritative brand registry, so the model never gets the final word alone.

<p>
  <a href="https://ai-phishing-and-impersonation-defen.vercel.app"><img src="https://img.shields.io/badge/Live%20Demo-00f0ff?style=flat-square&logo=vercel&logoColor=black" alt="Live demo" /></a>
  <a href="https://ai-phishing-and-impersonation-defen.vercel.app/docs"><img src="https://img.shields.io/badge/Swagger%20API-009688?style=flat-square&logo=fastapi&logoColor=white" alt="API docs" /></a>
</p>

**What I'd point to:** architecture decisions that keep a probabilistic model auditable, and the choice to make the *reasoning* the product's headline feature.

---

### 🏥 [Health Checkup Program](https://github.com/hariomgupta2596-source/Health_checkup_Program)

A healthcare monitoring web app built around a clean separation of concerns: a Next.js + CSS Modules front end deployed on Vercel, talking to a FastAPI service with SQLAlchemy 2.0 persistence and bcrypt password hashing.

- **Vitals + lifestyle intake** with live sliders for sleep, exercise and hydration
- **Instant derived metrics** — BMI category, vitals status, trend charts
- **Rule-based personalised recommendations** that stay auditable
- **Server-side PDF reports** via ReportLab, so results leave the app in a usable form
- **Five evidence-based guideline categories**: nutrition, exercise, sleep, stress, disease prevention

`Next.js` `FastAPI` `SQLite` `SQLAlchemy` `bcrypt` `Plotly` `ReportLab`

---

### 📐 [Linear Algebra Educational Suite](https://github.com/hariomgupta2596-source/linear-algebra-website-1)

Built because a calculator that only gives you the answer doesn't teach you anything. Every operation validates its preconditions (dimension matching, square-matrix requirements, singularity) and then shows the working.

- **Matrix module** — add, subtract, multiply, scalar, transpose, trace, rank, determinant, inverse (with cofactor expansion and LU reduction)
- **Vector module** — dot, cross, magnitude, unit vector, projection, angle in degrees *and* radians, distance, plus a Plotly 2D/3D visualiser
- **Systems of equations** — Gaussian elimination with partial pivoting, Gauss-Jordan to RREF, LU, and Cramer's rule
- Rendered maths throughout with **MathJax**, styled with **Bootstrap 5**

`Flask` `NumPy` `SciPy` `SymPy` `Bootstrap` `MathJax`

---

### 🪄 [The Vanishing Student of Hogwarts](https://github.com/hariomgupta2596-source/Hogwarts-Vanishing-Student)

A web-based logic mystery game built around **computational thinking and data reasoning** — the puzzle *is* the data problem. Full TypeScript stack: React/Vite client, Drizzle ORM, Tailwind, deployed with a Vercel config.

`TypeScript` `React` `Vite` `Drizzle ORM` `Tailwind`

---

### 🐺 [Wolf Territory](https://github.com/hariomgupta2596-source/Wolf-Territory)

An animated, scrollable open-world wolf adventure — vanilla JavaScript and Three.js, no framework, no build step. A deliberate exercise in hand-rolled animation timing, scroll orchestration and keeping a large vanilla codebase readable without a bundler.

`JavaScript` `Three.js` `CSS`

---

### 🧭 [Algorithm Trace](https://github.com/hariomgupta2596-source/Algorithm_Trace)

A single-file interactive HTML visualiser for stepping through algorithms one operation at a time — zero dependencies, opens straight in a browser, useful in a classroom.

`HTML` `JavaScript`

---

<details>
<summary><b>Other repositories</b></summary>

| Repo | What it is | Stack |
| --- | --- | --- |
| [LinearlyIndependent](https://github.com/hariomgupta2596-source/LinearlyIndependent) | Streamlit app exploring linear independence | Python, Streamlit |
| [Student-Result-Management-App](https://github.com/hariomgupta2596-source/Student-Result-Management-App) | Marks storage and result calculation | Python |
| [invisible-student](https://github.com/hariomgupta2596-source/invisible-student) | Earlier prototype of the Hogwarts mystery game | TypeScript, React |
| [eve-slack-agent](https://github.com/hariomgupta2596-source/eve-slack-agent) | Slack agent starter on the Eve framework, deployed on Vercel | TypeScript |

</details>

---

## 🧰 Tech stack

<table>
<tr>
<td valign="top" width="33%">

**Languages**
<br/>
<img src="https://skillicons.dev/icons?i=python,js,ts,java,cpp,html,css" alt="Languages" />
<br/><sub>+ SQL, Excel, Markdown</sub>

</td>
<td valign="top" width="33%">

**Data & ML**
<br/>
<img src="https://skillicons.dev/icons?i=sklearn,numpy,scipy,plotly" alt="Data and ML" />
<br/><sub>+ SymPy, Jupyter, data mining</sub>

</td>
<td valign="top" width="33%">

**Web & APIs**
<br/>
<img src="https://skillicons.dev/icons?i=react,nextjs,nodejs,fastapi,flask,express,tailwind" alt="Web" />

</td>
</tr>
<tr>
<td valign="top">

**Data & storage**
<br/>
<img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,sqlite,supabase" alt="Databases" />

</td>
<td valign="top">

**Cloud & DevOps**
<br/>
<img src="https://skillicons.dev/icons?i=vercel,gcp,docker,git,github" alt="Cloud and DevOps" />
<br/><sub>+ Neon Postgres, Replit, Cloud Run</sub>

</td>
<td valign="top">

**Currently learning**
<br/>
<img src="https://skillicons.dev/icons?i=gcp,postgres,linux" alt="Learning" />
<br/><sub>+ data engineering, system design</sub>

</td>
</tr>
</table>

---

## 📊 GitHub activity

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=hariomgupta2596-source&show_icons=true&hide_border=true&rank_icon=github&include_all_commits=true&count_private=true&title_color=1f6feb&icon_color=00f0ff&bg_color=00000000" alt="GitHub stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=hariomgupta2596-source&layout=compact&hide_border=true&langs_count=8&title_color=1f6feb&bg_color=00000000" alt="Top languages" />

<img src="https://streak-stats.demolab.com?user=hariomgupta2596-source&hide_border=true&ring=00f0ff&fire=1f6feb&currStreakLabel=00f0ff&background=00000000" alt="Streak" />

<img src="https://github-profile-trophy.vercel.app/?username=hariomgupta2596-source&theme=nord&no-frame=true&no-bg=true&column=7&margin-w=8&margin-h=8" alt="Trophies" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=hariomgupta2596-source&hide_border=true&area=true&custom_title=Contribution%20Activity&color=00f0ff&line=1f6feb&point=ffffff&bg_color=00000000" alt="Activity graph" />

</div>

---

## 🎯 How I work

```python
class Hariom:
    def __init__(self):
        self.role        = "Data science student → analyst"
        self.focus       = ["explainable ML", "data products", "full-stack delivery"]
        self.approach    = "ship it, measure it, then explain it"

    def on_new_problem(self, problem):
        return [
            "understand who actually suffers from this",
            "build the smallest end-to-end version that runs",
            "make the output legible to a non-expert",
            "deploy it, then improve it",
        ]
```

A few principles I've picked up the hard way:

- **A model nobody can interrogate is a model nobody will trust.** XAI isn't a bonus feature.
- **Preconditions are part of the product.** Dimension checks, singularity checks, validation — they're what make a tool usable by someone who isn't you.
- **Deploy early.** A Vercel URL changes how seriously you treat your own code.
- **Field data humbles you.** 60% of surveyed consumers had a failed payment, and top barrier was still network signal, not trust. Real constraints are rarely the ones in the spec.

---

## 🌱 Currently learning

| Area | What specifically |
| --- | --- |
| **Cloud & Gen AI** | Google Cloud Gen AI Academy (APAC, Cohort 3) — codelabs, Gemini on Cloud Run, agentic app patterns |
| **Data engineering** | AWS Glue pipelines, Postgres with Neon and Supabase, warehouse concepts |
| **Data science core** | Data mining, design & analysis of algorithms, linear algebra for data science |
| **ML practice** | Kaggle datasets and notebooks, model evaluation beyond accuracy |
| **Career track** | Data analyst / data science roles across Mumbai, Thane and remote |

---

## 🤝 Let's connect

I'm open to **data analyst / data science roles, internships, and collaborations** on projects where the analysis has to reach an actual user.

<p align="left">
  <a href="https://www.linkedin.com/in/ds-hariom-gupta"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:hariomgupta2596@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/hariomgupta2596-source?tab=repositories"><img src="https://img.shields.io/badge/All%20Repositories-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repositories" /></a>
</p>

If you're hiring for analyst work or want a second pair of hands on a Python/ML build, my inbox is open. The fastest way to judge me is to open [SENTINEL](https://ai-phishing-and-impersonation-defen.vercel.app) and try to fool it.

<div align="center">

<br/>

*"Build the thing. Then make it explain itself."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00f0ff,100:1f6feb&height=110&section=footer" alt="footer" />

</div>
