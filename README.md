<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Hi%20%F0%9F%91%8B%2C%20I'm%20Sakthivel%20V&fontSize=38&fontColor=fff&animation=twinkling&fontAlignY=32&desc=ECE%20Student%20%7C%20Flutter%20%26%20Android%20Developer%20%7C%20IoT%20Tinkerer&descAlignY=55&descSize=17"/>

<p align="center">
  <a href="https://readme-typing-svg.demolab.com">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=70A5FD&center=true&vCenter=true&width=600&lines=Flutter+%26+Android+Developer;IoT+%26+Embedded+Systems+Enthusiast;Front-End+Web+Developer;Eager+to+Build+Scalable+Solutions" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=sakthivelV05&label=Profile%20Views&color=70a5fd&style=flat-square" alt="Profile Views"/>
  <a href="https://linkedin.com/in/sakthivel05/">
    <img src="https://img.shields.io/badge/LinkedIn-sakthivel05-0077B5?style=flat-square&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:sakthivelvelmurugan7815@gmail.com">
    <img src="https://img.shields.io/badge/Email-sakthivelvelmurugan7815%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://github.com/sakthivelV05">
    <img src="https://img.shields.io/badge/GitHub-sakthivelV05-181717?style=flat-square&logo=github&logoColor=white"/>
  </a>
  <img src="https://img.shields.io/badge/Open%20to-Internships%20%26%20Collabs-2ea44f?style=flat-square&logo=handshake&logoColor=white"/>
</p>

<p align="center">
  <i>📍 Srivilliputhur, Tamil Nadu, India &nbsp;•&nbsp; 🎓 B.E. ECE @ Kongu Engineering College</i>
</p>

---

### 👨‍💻 About Me

<img align="right" width="380" src="https://raw.githubusercontent.com/abhisheknaiidu/abhisheknaiidu/master/code.gif"/>

```dart
class SakthivelV {
  final String name     = "Sakthivel V";
  final String location = "Srivilliputhur, Tamil Nadu, India";
  final String degree   = "B.E – Electronics & Communication Engineering";
  final String college  = "Kongu Engineering College (2023 – Present)";
  final double cgpa     = 6.85;

  final List<String> stack = [
    "Flutter / Dart",
    "Android Development",
    "HTML", "CSS", "JavaScript",
    "Embedded Systems",
    "Git & GitHub",
  ];

  final List<String> currentlyLearning = [
    "Advanced Flutter & State Management",
    "Full Stack Web Development",
    "IoT & Sensor Integration",
  ];

  final List<String> interests = [
    "Software Development",
    "Mobile App Development",
    "Web Development",
    "IoT & Smart Systems",
  ];

  final bool openToOpportunities = true;

  final String funFact =
    "I built a smart home system at a hackathon with sensors!";

  String motto() =>
    "Build things that are practical, useful & user-friendly.";
}
```

<br clear="right"/>

---

### 🎯 What I'm Focused On Right Now

```
🦋  Flutter        →  Advanced State Management, Animations, Firebase
🌐  Web Dev        →  JavaScript (ES6+), Responsive Design, React Basics
☁️  Cloud & IoT    →  MQTT, Firebase Realtime DB, Arduino Cloud
🤖  AI / ML Basics →  Python, Sensor Data Analytics
```

---

### 🛠️ Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=dart,flutter,android,html,css,js,git,github,arduino,vscode,androidstudio,figma&theme=dark" />
</p>

---

### 📊 GitHub Analytics

<p align="center">
  <img height="165em" src="https://github-readme-stats.vercel.app/api?username=sakthivelV05&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&bg_color=0d1117&title_color=70a5fd&icon_color=bf91f3&text_color=c9d1d9&border_radius=10"/>
  <img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sakthivelV05&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=70a5fd&text_color=c9d1d9&langs_count=8&border_radius=10"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=sakthivelV05&theme=tokyonight-duo&hide_border=true&background=0D1117&ring=70A5FD&fire=BF91F3&currStreakLabel=70A5FD&sideLabels=38BDAE&dates=8B949E&currStreakNum=C9D1D9&sideNums=C9D1D9&stroke=0D1117&border_radius=10"/>
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=sakthivelV05&theme=tokyo-night&bg_color=0d1117&color=70a5fd&line=bf91f3&point=38bdae&area=true&hide_border=true"/>
</p>

---

### 🐍 Contribution Snake

<p align="center">
  <img src="https://raw.githubusercontent.com/sakthivelV05/sakthivelV05/output/github-contribution-grid-snake.svg" alt="Contribution Snake animation"/>
</p>

> **Setup note:** to make this animate, create a repo named exactly `sakthivelV05` (your special GitHub "profile" repo), then add the file below as `.github/workflows/snake.yml` inside it and push once.

<details>
<summary>📄 Click to expand <code>snake.yml</code> workflow</summary>

```yaml
name: Generate Snake Animation

on:
  schedule:
    - cron: "0 0 * * *"   # runs once a day
  push:
    branches:
      - main              # change to 'master' if that's your default branch
  workflow_dispatch:        # lets you trigger it manually from the Actions tab

jobs:
  generate:
    permissions:
      contents: write
    runs-on: ubuntu-latest
    steps:
      - name: Generate snake animation SVG
        uses: Platane/snk@v3
        with:
          github_user_name: sakthivelV05
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - name: Push to output branch
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

</details>

---

### 🏆 Trophy Wall

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=sakthivelV05&theme=tokyonight&no-frame=true&no-bg=true&row=1&column=7&margin-w=4"/>
</p>

---

### 🚀 Featured Projects

<div align="center">

| 🗂️ Project | 🛠️ Stack | ✨ Highlights |
|:-----------|:---------|:-------------|
| **AI-Based Smart Home Control System** | IoT, Sensors, Dashboard UI | Built at Dr. Mahalingam College of Engineering Hackathon. Automated home appliance control using sensor-based decision logic with a real-time monitoring dashboard. |
| **Health Monitoring System** | IoT, Sensors, Dashboard UI | Built at Kongu Engineering College Hackathon. Tracks health parameters in real time with a live data visualization dashboard. |
| **School Website Development** | HTML, CSS, JavaScript | Designed and developed a responsive, clean school website with a structured layout and user-friendly interface. |

</div>

> 💡 *Tip: link each project name to its GitHub repo (`[AI-Based Smart Home Control System](https://github.com/sakthivelV05/your-repo)`) once they're pushed — that turns this table into clickable proof of work for recruiters.*

---

### 🏅 Achievements

<div align="center">

| 🏆 | Achievement | Details |
|:--:|:-----------|:--------|
| 🤖 | **Hackathon Participant** | AI-Based Smart Home Control System — Dr. Mahalingam College of Engineering |
| 💡 | **Hackathon Participant** | Health Monitoring System — Kongu Engineering College |
| 🌐 | **Web Development** | Designed and deployed a complete school website using HTML, CSS & JS |

</div>

---

### 🎓 Education

<div align="center">

| 📚 Degree | 🏫 Institution | 📅 Year | 🎯 Score |
|:---------|:-------------|:-------|:--------|
| B.E – Electronics & Communication Engineering | Kongu Engineering College | 2023 – Present | CGPA: 6.85 |
| HSC & SSLC | Valluvar Vidhyalaya | 2017 – 2023 | 71% |

</div>

---

### ⚡ Fun Facts

- 🏠 Built an IoT Smart Home System at a hackathon — controlled appliances with just sensors!
- 💊 Created a real-time health monitor that visualizes live body data on a dashboard.
- 🌏 From Srivilliputhur, Tamil Nadu — a small town with big tech dreams.
- 📱 Passionate about making apps that solve real problems for real people.
- 🔧 Equally comfortable writing Flutter code and tinkering with embedded hardware.

---

<p align="center">
  <i>"Build things that are practical, useful & user-friendly."</i>
</p>

<p align="center">
  <a href="https://linkedin.com/in/sakthivel05/"><img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=flat-square&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:sakthivelvelmurugan7815@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=flat-square&logo=gmail&logoColor=white"/></a>
  <a href="https://github.com/sakthivelV05"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white"/></a>
</p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer&animation=twinkling"/>
