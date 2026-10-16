<h1 align="center">Hey, I'm Jiaxiang (Leo) 👋</h1>

<p align="center">
  <a href="https://github.com/LeooJinn">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&duration=2800&pause=900&color=E0584B&center=true&vCenter=true&width=620&lines=CS+student+in+the+Bay+Area;Building+production+software+and+systems+projects;Building+Sonder+for+car+people;Training+RL+agents+to+land+rockets;Learning+how+search+systems+work" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://jiaxiangjin.com"><img src="https://img.shields.io/badge/Portfolio-jiaxiangjin.com-2F4B8F?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio website" /></a>
  <a href="https://github.com/LeooJinn/Sonder"><img src="https://img.shields.io/badge/Sonder-E0584B?style=for-the-badge&logo=github&logoColor=white" alt="Sonder" /></a>
  <a href="https://github.com/LeooJinn/cpp-search-engine"><img src="https://img.shields.io/badge/C%2B%2B%20Search%20Engine-35566B?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++ Search Engine" /></a>
  <a href="https://github.com/LeooJinn/rocket-landing-rl"><img src="https://img.shields.io/badge/Rocket%20Landing%20RL-5FE3D0?style=for-the-badge&logo=pytorch&logoColor=black" alt="Rocket Landing RL" /></a>
  <a href="https://github.com/LeooJinn?tab=repositories"><img src="https://img.shields.io/badge/All_repos-66734C?style=for-the-badge&logo=github&logoColor=white" alt="Repositories" /></a>
</p>

<p align="center">
  📫 <a href="mailto:Jiaxiangjin213@gmail.com">Jiaxiangjin213@gmail.com</a>
  · <a href="https://www.linkedin.com/in/leoojin/">LinkedIn</a>
</p>

<p align="center">
  <a href="https://jiaxiangjin.com"><img src="https://raw.githubusercontent.com/LeooJinn/LeooJinn.github.io/main/docs/assets/portfolio-hero.jpg?v=2" alt="Portfolio website home page" width="48%" /></a>
  <a href="https://jiaxiangjin.com/#work"><img src="https://raw.githubusercontent.com/LeooJinn/LeooJinn.github.io/main/docs/assets/portfolio-work.jpg?v=2" alt="Portfolio website work section" width="48%" /></a>
</p>

<p align="center">
  <a href="https://imsonder.com"><img src="https://raw.githubusercontent.com/LeooJinn/Sonder/main/docs/assets/sonder-welcome.jpg?v=2" alt="Sonder welcome screen" width="48%" /></a>
  <a href="https://github.com/LeooJinn/cpp-search-engine"><img src="https://raw.githubusercontent.com/LeooJinn/cpp-search-engine/main/docs/assets/search-ui-result.jpg" alt="C++ Search Engine browser UI" width="48%" /></a>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/LeooJinn/Sonder/main/docs/architecture/sonder-architecture.svg" alt="Sonder architecture" width="48%" />
  <img src="https://raw.githubusercontent.com/LeooJinn/cpp-search-engine/main/docs/architecture/search-engine-architecture.svg" alt="C++ Search Engine architecture" width="48%" />
</p>

---

### 🌐 Portfolio Website

**[jiaxiangjin.com](https://jiaxiangjin.com)** is my portfolio website: the best place to see my selected projects, experience, and resume in one place.

It's a dependency-free static site (plain HTML, CSS, and JavaScript) hosted on GitHub Pages, with sections for selected work, an interactive lab, experience, and a one-page resume. The source is in [LeooJinn.github.io](https://github.com/LeooJinn/LeooJinn.github.io).

**Stack:** HTML · CSS · JavaScript · GitHub Pages

---

### 🚗 Sonder

**[Sonder](https://github.com/LeooJinn/Sonder)** is a community app for car people, built around one idea: *every car has a life of its own, and that life should outlive its owners.*

A car gets built, modified, broken, fixed, and loved across years and owners. Then it gets sold, and that history can disappear. [Sonder](https://imsonder.com) gives the car its own profile, keyed to its VIN, so mods, service, repairs, photos, and ownership history can travel with it.

The data model centers on **ownership periods**:

```text
vehicles      one row per physical car in the world, keyed by VIN
   ↓
ownerships    who owned it, and when   ← the hinge
   ↓
entries       what happened during that ownership
   ↓
parts         what went into it
```

That structure lets a buyer inherit a car's documented life without inheriting authorship of it, while previous owners keep credit for their work without retaining control of the car.

**Stack:** React Native · Expo · TypeScript · Supabase · PostgreSQL · Vercel

---

### 🔎 C++ Search Engine

**[C++ Search Engine](https://github.com/LeooJinn/cpp-search-engine)** is a portfolio-grade C++17 search system built to make data structures, concurrency, and performance measurable.

It includes:

- A linear-scan baseline and an inverted-index implementation
- Parallel index construction across worker threads
- Versioned persistent indexes
- PDF, web, and SQLite ingestion adapters
- Exact search, fuzzy spelling tolerance, and configured synonym expansion
- A localhost browser UI with clickable document details
- GitHub Actions CI on Ubuntu and macOS
- Reproducible multi-size benchmark reports

On a real-corpus run over **5,950 English Wikipedia articles (74.5 MB)**, worker-local indexing reduced peak RSS from **1.04 GB to 892 MB (14.6% lower)**. Parallel build improved from **496 ms to 434 ms**, while indexed query latency measured **0.005 ms p50 / 0.026 ms p95**. The persistent index remained about 141 MB; the next systems target is separating document bodies from index metadata for lazy detail loading.

**Stack:** C++17 · CMake · SQLite · libcurl · multithreading · GitHub Actions

<details>
<summary><b>Optional semantic-search experiment</b></summary>

<br />

The repository also contains an isolated Python sidecar using NumPy and Sentence Transformers. It compares embedding-based retrieval with the deterministic C++ exact, fuzzy, and synonym search modes without making the core build depend on model downloads.

</details>

---

### 🚀 Rocket Landing RL

**[Rocket Landing RL](https://github.com/LeooJinn/rocket-landing-rl)** is a from-scratch PyTorch PPO agent that learns to land a simulated 2D rocket on a pad. It sees seven numbers (position, velocity, tilt, spin, fuel), picks one of four thrusters each step, and learns from a shaped reward alone.

<p align="center">
  <a href="https://jiaxiangjin.com/rocket-landing-rl/"><img src="https://raw.githubusercontent.com/LeooJinn/rocket-landing-rl/main/docs/demo.gif" alt="The same start flown by an early, a middle and the final checkpoint of one training run: the early one crashes after running out of fuel, the middle one lands slowly, the final one lands in about half the time with more fuel left" width="96%" /></a>
</p>

**[Watch the trained agent →](https://jiaxiangjin.com/rocket-landing-rl/)** (recorded runs, no server needed)

It includes:

- A deterministic NumPy simulator behind the Gymnasium API, and PPO written from scratch (no RL library)
- A held-out evaluation protocol that checks test seeds never overlap training, with 95% confidence intervals
- A hand-written heuristic controller as a baseline (99.6% of held-out landings), and a fuel-aware reward tested on two independent sets of ten seeds
- A diagnosis of why training is unstable: late collapses traced to policies running out of fuel
- A browser replay viewer, with a live mode and a recorded mode on GitHub Pages
- Over 120 tests and GitHub Actions CI

With a fuel-aware reward, **19 of 20 training seeds land at least 90% of 500 unseen starts** (mean **98.8%**), against 12 of 20 (70.5%) with the original reward. Fixed observation scaling had already raised mean held-out success from **27.6% to 95.0%** on six seeds, and a diagnosis traced the remaining failures to policies running out of fuel. A couple of seeds are still imperfect, and the repository keeps the failed seeds in the results instead of hiding them.

**Stack:** Python · PyTorch · NumPy · Gymnasium · GitHub Actions · GitHub Pages

---

### 🛠 What I build with

<p>
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React Native" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite" />
  <img src="https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white" alt="CMake" />
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white" alt="Supabase" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
</p>

### 🧰 Systems experience

I also work as a contract IT Support Technician with **Five Star Networking**, supporting client environments with Windows and macOS administration, Active Directory permissions, VPN and network troubleshooting, system updates, and end-user support.

---

### 📚 What I'm focused on

- Building stronger foundations in data structures, algorithms, and systems programming
- Preparing for software engineering internships
- Turning projects into measurable, testable systems rather than demos
- Learning reinforcement learning by building agents from scratch and evaluating them honestly, failed runs included
- Learning when a simple deterministic solution is better than a more complicated one

---

<p align="center">
  <img src="https://streak-stats.demolab.com?user=LeooJinn&hide_border=true&background=00000000&stroke=2C3742&ring=E0584B&fire=E0584B&currStreakLabel=E0584B&sideLabels=8D9BA8&currStreakNum=E6E9EC&sideNums=E6E9EC&dates=5C6B7A" alt="Contribution streak" />
</p>

<p align="center">
  <i>Sonder — the realization that each passer-by has a life as vivid and complex as your own.</i>
</p>
