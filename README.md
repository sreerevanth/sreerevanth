<h1 align="center">⚡ revanth</h1>

<p align="center">
  <b>builds things that probably shouldn’t work — but do.</b>
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?lines=building+ai+systems;breaking+things;fixing+them;shipping+fast&center=true&color=FFD700&size=22">
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=sreerevanth&color=yellow&style=flat-square"/>
</p>

---

## 🧠 what i actually do

```diff
+ build autonomous systems
+ make AI take actions, not just respond
+ break systems → fix them better

i build things like:

🤖 agents that fix code by themselves
📊 trading systems that generate signals + track profit
🧠 multi-model AI orchestration systems
🚀 current focus
agentic systems:    evolving
real-time engines:  building
ideas:              too many
sleep:              optional
💻 featured builds
⚡ TRADEX → real-time trading dashboard (signals + P&L + charts)
🤖 RepoPilot → self-correcting AI coding agent
🧠 RMM → multi-model AI orchestration system
⚙️ tech stack
<p align="center"> <img src="https://skillicons.dev/icons?i=python,ts,js,fastapi,react,nodejs,docker,linux,git" /> </p>
🧪 ai / data
<p align="center"> <img src="https://skillicons.dev/icons?i=pytorch,tensorflow" /> </p> <p align="center"> <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/> <img src="https://img.shields.io/badge/APIs-000000?style=for-the-badge&logo=fastapi&logoColor=white"/> </p>
📊 stats
<p align="center"> <img src="https://github-readme-stats.vercel.app/api?username=sreerevanth&show_icons=true&theme=tokyonight"/> <br/> <img src="https://github-readme-streak-stats.herokuapp.com/?user=sreerevanth&theme=tokyonight"/> </p>
🐍 contribution snake
<p align="center"> <img src="https://github.com/sreerevanth/sreerevanth/blob/output/github-contribution-grid-snake.svg"/> </p>
⚡ philosophy

build → break → understand → rebuild better

🧩

still figuring things out
just shipping anyway


---

# 🐍 IMPORTANT (snake animation setup)

👉 This doesn’t work automatically  
You must set it up once:

---

## 🚀 Steps

### 1. Go to your profile repo:
👉 `sreerevanth`

---

### 2. Create folder:
```text
.github/workflows
3. Create file:
snake.yml
4. Paste this:
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest

    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: sreerevanth
          outputs: |
            dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
