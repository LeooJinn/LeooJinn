<h1 align="center">Hey, I'm Jiaxiang (Leo) 👋</h1>

<p align="center">
  <a href="https://github.com/LeooJinn">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&duration=2800&pause=900&color=E0584B&center=true&vCenter=true&width=620&lines=CS+student+in+the+Bay+Area;Building+production+software+and+systems+projects;Building+Sonder+for+car+people;Learning+how+search+systems+work" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/LeooJinn/Sonder"><img src="https://img.shields.io/badge/Sonder-E0584B?style=for-the-badge&logo=github&logoColor=white" alt="Sonder" /></a>
  <a href="https://github.com/LeooJinn/cpp-search-engine"><img src="https://img.shields.io/badge/C%2B%2B%20Search%20Engine-35566B?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++ Search Engine" /></a>
  <a href="https://github.com/LeooJinn?tab=repositories"><img src="https://img.shields.io/badge/All_repos-66734C?style=for-the-badge&logo=github&logoColor=white" alt="Repositories" /></a>
</p>

<p align="center">
  📫 <a href="mailto:Jiaxiangjin213@gmail.com">Jiaxiangjin213@gmail.com</a>
  · <a href="https://www.linkedin.com/in/leoojin/">LinkedIn</a>
</p>

<p align="center">
  <a href="https://imsonder.com"><img src="https://raw.githubusercontent.com/LeooJinn/Sonder/main/docs/assets/sonder-welcome.jpg" alt="Sonder welcome screen" width="48%" /></a>
  <a href="https://github.com/LeooJinn/cpp-search-engine"><img src="https://raw.githubusercontent.com/LeooJinn/cpp-search-engine/main/docs/assets/search-ui-result.jpg" alt="C++ Search Engine browser UI" width="48%" /></a>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/LeooJinn/Sonder/main/docs/architecture/sonder-architecture.svg" alt="Sonder architecture" width="48%" />
  <img src="https://raw.githubusercontent.com/LeooJinn/cpp-search-engine/main/docs/architecture/search-engine-architecture.svg" alt="C++ Search Engine architecture" width="48%" />
</p>

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

On the benchmark corpus, four-worker indexing measured approximately **3.5× faster construction** than sequential indexing, while indexed queries completed in sub-millisecond time on a 2,000-document synthetic corpus.

**Stack:** C++17 · CMake · SQLite · libcurl · multithreading · GitHub Actions

<details>
<summary><b>Optional semantic-search experiment</b></summary>

<br />

The repository also contains an isolated Python sidecar using NumPy and Sentence Transformers. It compares embedding-based retrieval with the deterministic C++ exact, fuzzy, and synonym search modes without making the core build depend on model downloads.

</details>

---

### 🛠 What I build with

<p>
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
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
- Learning when a simple deterministic solution is better than a more complicated one

---

<p align="center">
  <img src="https://streak-stats.demolab.com?user=LeooJinn&hide_border=true&background=00000000&stroke=2C3742&ring=E0584B&fire=E0584B&currStreakLabel=E0584B&sideLabels=8D9BA8&currStreakNum=E6E9EC&sideNums=E6E9EC&dates=5C6B7A" alt="Contribution streak" />
</p>

<p align="center">
  <i>Sonder — the realization that each passer-by has a life as vivid and complex as your own.</i>
</p>
