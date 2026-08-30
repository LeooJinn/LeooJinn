<h1 align="center">Hey, I'm Jiaxiang (Leo)👋</h1>

<p align="center">
  <a href="https://github.com/LeooJinn">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&duration=2800&pause=900&color=E0584B&center=true&vCenter=true&width=520&lines=CS+student+in+the+Bay+Area;Building+Sonder+%E2%80%94+a+home+for+car+people;Community+builder+before+I+was+a+developer;Every+car+has+a+life+of+its+own." alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/LeooJinn/Sonder"><img src="https://img.shields.io/badge/Sonder-E0584B?style=for-the-badge&logo=github&logoColor=white" alt="Sonder" /></a>
  <a href="https://github.com/LeooJinn?tab=repositories"><img src="https://img.shields.io/badge/All_repos-35566B?style=for-the-badge&logo=github&logoColor=white" alt="Repositories" /></a>
</p>

<p align="center">
  📫 <code>jiaxiangjin213@gmail.com</code>
</p>

---

### 🚗 What I'm building

**[Sonder](https://github.com/LeooJinn/Sonder)** — a community app for car people, built around one idea nobody has shipped well: *every car has a life of its own, and that life should outlive its owners.*

A car gets built, modified, broken, fixed and loved across years and owners. Then it gets sold, and all of that history evaporates. Sonder gives the car its own profile, keyed to its VIN — mods, service, repairs, photos — and **the history transfers when the car sells.**

I started a car club in the Bay Area before I started writing code. This is the app my community needed.

<details>
<summary><b>How it works under the hood</b></summary>

<br />

Entries in a build log don't belong to a user, and they don't belong to a vehicle. They belong to an **ownership period** — a span of time during which one person owned one car.

```
vehicles      one row per physical car in the world, keyed by VIN
   ↓
ownerships    who owned it, and when   ← the hinge
   ↓
entries       what happened during that ownership
   ↓
parts         what went into it
```

That one indirection is what lets a buyer inherit a car's entire documented life without inheriting authorship of it, and lets the previous owner keep credit for their work without keeping control of the car.

A partial unique index enforces the rest: a car may have many past owners, but only ever one current one.

</details>

---

### 🛠 What I build with

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white" />
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white" />
</p>

<details>
<summary><b>What I'm learning right now</b></summary>

<br />

| | |
|---|---|
| **Comfortable** | C++ fundamentals, data structures, git |
| **Building with daily** | TypeScript, React Native, Expo, Postgres |
| **Actively learning** | Row-level security, file storage, auth flows |
| **Next up** | Image pipelines, and shipping to the App Store |

Came from C++, so the things that took rewiring: async/await instead of top-to-bottom execution, and describing what the screen *should be* instead of telling it what to do.

</details>

---

### 📊 Stats

<p align="center">
  <img src="https://streak-stats.demolab.com?user=LeooJinn&hide_border=true&background=00000000&stroke=2C3742&ring=E0584B&fire=E0584B&currStreakLabel=E0584B&sideLabels=8D9BA8&currStreakNum=E6E9EC&sideNums=E6E9EC&dates=5C6B7A" alt="Contribution streak" />
</p>

---

<p align="center">
  <i>Sonder — the realization that each passer-by has a life as vivid and complex as your own.</i>
</p>
